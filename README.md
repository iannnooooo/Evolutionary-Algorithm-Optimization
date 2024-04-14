# Genetic Algorithm Text Generator

This Python script implements a simple genetic algorithm to generate a target string. It uses a population of candidate strings and evolves them over generations to match the target string through mutation and natural selection.

## How it works

- **Population Initialization**: The algorithm starts with a population of randomly generated candidate strings.
  
- **Fitness Calculation**: Each candidate's fitness is calculated based on how many characters match the corresponding characters in the target string.

- **Selection**: Candidates are sorted based on fitness, and less fit candidates are removed from the population.

- **Breeding**: More fit candidates are selected to produce offspring through crossover and mutation.

- **Display**: The current population is displayed after each generation, showing the candidate strings with color highlighting to indicate matching and mismatching characters.

- **Iterative Evolution**: The process continues iteratively until a candidate string perfectly matches the target string.

## Features

- Customizable target string: You can specify the target string that the algorithm aims to generate.

- Adjustable parameters: You can tweak parameters such as population size, mutation probability, and the number of fittest candidates to keep in each generation.

- Real-time visualization: The algorithm displays the population after each generation, allowing you to observe the evolution process visually.

## Usage

1. Clone this repository or download the `genetic_text_generator.py` file.

2. Run the script using Python:

3. Observe the algorithm's progress as it evolves the population to generate the target string.

## Requirements

- Python 3.x

## Disclaimer

This script is provided for fun purposes and as a demonstration of genetic algorithms. It should be used responsibly and might be addictive to watch it run. 

## HAVE FUN!!!!!!!!!!!!!!!!!!!!!!!!!!

