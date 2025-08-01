H3KZ Roulette Strategy Simulator
An advanced simulator for testing a dynamic, Fibonacci-based betting strategy for European Roulette.

This tool allows users to set various risk management parameters and visualize the outcomes of long-term simulations. It is intended for educational and entertainment purposes to explore the mathematics of betting progressions and the impact of different risk management rules.

Features
Customizable Simulation: Set your own Starting Balance, Target Balance, and the Dozen/Column you wish to bet on.

Dynamic Fibonacci Progression: The betting sequence starts with a standard Fibonacci-style progression and dynamically scales to any bankroll size if a long losing streak occurs.

Advanced Risk Management:

Profit Cashout: Automatically secure profits by setting a percentage of growth (5% - 50%) that triggers a cashout.

Percentage-Based Stop-Loss: Set a percentage of your current baseline (5% - 50%) as a stop-loss for any single losing streak.

Strategic "Free Spin" Mode:

After a user-defined number of consecutive losses, the simulation pauses betting.

Double Confirmation Logic: If free spins continue for too long, the system requires two consecutive favorable outcomes before resuming bets.

Automatic Table Changes: The simulation mimics changing tables after a successful cashout or repeated high-risk events.

Data Visualization: A dynamic line chart visualizes your Total Worth (Current Balance + Cashed Out) over every spin.

Detailed Logging: A real-time log provides a spin-by-spin breakdown of bets, outcomes, and strategic decisions.

How to Use
Download: Save the roulette_strategy_sim.html file to your computer.

Open: Open the file in any modern web browser (like Chrome, Firefox, or Edge).

Configure: Adjust the settings at the top of the page to define your starting conditions and risk management rules.

Simulate: Click the "Start Simulation" button to run the test.

Strategy Rules Explained
1. Betting Progression
The core of the strategy is a Fibonacci-style progression. Bets start at ₹50. After a loss, the bet increases. After a win, the bet resets to ₹50.

2. Cashout Logic
The "baseline" is initially your starting balance. After any win, the simulator checks if Current Balance > Baseline * (1 + Cashout %). If true, the profit is moved to the "Cashed Out" wallet, the Current Balance becomes the new baseline, and a table change is scheduled for the next win.

3. Stop-Loss Logic
During a losing streak, the simulator tracks the Current Streak Loss. If this loss exceeds Baseline * Stop-Loss %, the streak is abandoned, and the current balance becomes the new, lower baseline.

4. Free Spin & Table Change Logic
If a losing streak hits the trigger amount, the simulation enters "Free Spin Mode." If this happens twice on one table, a table change is scheduled for the next win. The simulation waits for a favorable outcome (or two, if "Double Confirmation" is needed) before resuming bets.

Disclaimer
This is a simulation tool, not a guaranteed winning strategy. Roulette is a game of chance with a built-in house edge. No betting system can overcome this mathematical advantage in the long run. This project is intended to demonstrate the complexities and risks of progressive betting systems for educational purposes. Please gamble responsibly.