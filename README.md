# Rotman MMA Summer Datathon: NWHL Player Selection
This repository contains the project submission for the Rotman MMA Summer Datathon 2023, where we applied a genetic algorithm to select five optimal players from the National Women’s Hockey League (NWHL) for the 2021-2022 season. The project focuses on assembling a well-rounded team that excels in various key areas of hockey performance.

## Project Overview
The NWHL dataset includes detailed hockey events for players across the league. Our task was to help the Toronto Six build their roster for the new season, considering a combination of goal-scoring, passing, faceoff, and takeaway skills.

We applied a genetic algorithm to analyze the performance of players and select five that best meet the following criteria:

At least three excellent goal scorers.
At least two excellent passers.
At least two faceoff specialists.
At least one takeaway specialist.
Strong synergies between passers and shooters.

## Dataset
The dataset used in this project is titled 'Rotman MMA Summer Datathon NWHL.csv'. It includes the following types of data:

Player names and teams.
Detailed event information, such as shots, passes, faceoffs, takeaways, puck recoveries, and zone entries.
Coordinates for where events occurred on the ice.
For more detailed information on the data structure and types of events, refer to the Data Descriptions and Context document.

## Methodology
### Genetic Algorithm
A genetic algorithm was employed to iteratively optimize the selection of players based on the defined criteria. The steps involved were:

Population Initialization: We started by generating a random population of player selections.
Fitness Evaluation: Each set of players was evaluated based on their performance in goals, passes, faceoffs, and takeaways.
Selection: The top-performing groups of players were selected to reproduce.
Crossover and Mutation: We introduced variations to form new player combinations and explored better solutions.
Termination: The algorithm terminated when an optimal set of five players was found that met all the criteria.
