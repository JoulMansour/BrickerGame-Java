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
