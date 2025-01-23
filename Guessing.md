
## Guessing Flow chart

```mermaid
flowchart TD
  Start([Start]) --> B[Generate Random Number 1 to 100]
  B --> C[Asks for guess from player]
  C --> D[Validate player Input]
  D --> |Invalid Value| E[Prompts player to enter valid guess]
  D --> |Valid Value| F[Compare guess with random number generated ]
  F --> G[Is the guess too high?]
  G --> |Yes| H[Prompt player to lower their guess]--> C 
  G --> |No| I[Is guess too low?]
  I --> |Yes| J[Prompt player to guess a higher number] --> C 
  I --> |No| K[Correct guess!]
  K --> L[End]
```
## Textual Descriptions: 
1. Game generates a random number from 1 to 100. 
2. Game asks for guess from player. 
3. Game checks player input, is it a valid guess? 
4. If a valid integer, game will check if guess is too high or low. 
5. If guess is incorrect, game will prompt another guess from the player.
6. If guess is correct, game displays that the player wins. 
7. Game ends. 
