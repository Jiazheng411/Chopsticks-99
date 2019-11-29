# Chopsticks·99
an electronic game inspired by childhood hand game Chopsticks implemented using Mojo FPGA

## UI and Instructions
![image](https://user-images.githubusercontent.com/37904339/69853658-67a45600-12c2-11ea-8e26-50a36c6e2b9a.png)

## Rules:
1. Each player has a yellow and a white number with same shape starting from 1.
2. Players take turns to choose one of the opponent’s numbers to add to one of his or her own
numbers as stated in the instruction example above.
3. A player must make exactly one move during his/her turn.
4. When one’s number surpasses 10, we take its remainder.
5. Four numbers are always available to be chosen during the game.
6. One whoever gets his/her both numbers reach value 9 will be the winner.

## Datapath Diagram
![DataPath](https://user-images.githubusercontent.com/37904339/69853556-31ff6d00-12c2-11ea-8843-81d62351cdae.jpg)

## General State Transition Diagram
![GeneralStateDiagram](https://user-images.githubusercontent.com/37904339/69853517-172cf880-12c2-11ea-91a6-660d169c69fa.jpg)

## Detailed State Transition Diagram
![DetailedStateDiagram](https://user-images.githubusercontent.com/37904339/69853549-2e6be600-12c2-11ea-83c1-a4a4a670c65f.jpg)
