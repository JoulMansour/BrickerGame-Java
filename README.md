# BrickerGame-Java

A Brick Breaker / Breakout-style game written in Java using the **danogl** framework.
The game is managed by `BrickerGameManager` and uses a **strategy pattern** to assign different collision behaviors to bricks. :contentReference[oaicite:3]{index=3}

## Features
- Classic gameplay: ball + paddle + brick grid. :contentReference[oaicite:4]{index=4}
- Lives system (UI hearts + colored life counter) + win/lose dialogs. :contentReference[oaicite:5]{index=5}
- Random brick behaviors (selected per brick):
  - **Extra pucks (extra balls)** 
  - **Extra paddle**
  - **Exploding bricks (affects neighbors)**
  - **Falling heart (gain a life if caught)** 
  - **Double strategy** (combines 2 strategies, sometimes 3)

 ## How to Run
1. Clone this repository.
2. Open the project in your preferred Java IDE (e.g., IntelliJ IDEA, Eclipse).
3. Ensure the **DanoGameLab (danogl)** library is correctly linked in your project dependencies.
4. Run the `main` method located in `bricker.main.BrickerGameManager`.


