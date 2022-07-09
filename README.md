# konane-fe

## Values

- Respects Konane as a game and it's history
- Respects user's time and privacy
- Playing the game just works
- Playing is fun and challenging
- This shouldn't cost much money

## Plan

### Tech Basics

- Served via the cloud
- NextJS Serving
- Staging and Prod Sites
- Testing Framework of Logic and Components
- Build a database of moves (or utilized an existing one)
- PWA
- Anonymized tracking

### Implementation

#### Computerized Opponent

- MinMax with alpha-beta pruning
  - https://www.geeksforgeeks.org/minimax-algorithm-in-game-theory-set-4-alpha-beta-pruning/
- Support a range of player skill
- Implemented in JS first, then compare performance with Rust
  - Web Assembly
    - https://webassembly.org/
  - Rust
    - https://www.rust-lang.org/what/wasm

#### Human Opponents

- Email / password sign in
- Social login if necessary
- Minimum data kept (only what we need to function)
- Allow folks to not log in if they don't want
  - Not sure if this is possible
- Matching against folks of like-skill

#### ML-driven Computer Opponents

- Support multiple computer algos
