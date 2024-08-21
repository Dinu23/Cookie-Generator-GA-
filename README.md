# Cookies Recipe Generator - Genetic Algorithm

## Project Overview

This project implements a genetic algorithm to generate creative and unique cookie recipes. By leveraging a database of ingredient pairings and classifications, the algorithm optimizes recipes based on taste, creativity, and novelty. The approach not only generates cookie recipes but can also be adapted to create other types of recipes by modifying ingredient classes.

## Features

- **Ingredient Knowledgebase**: Utilizes CSV files containing ingredient pairings and classifications to create initial populations of recipes.
- **Taste Function**: Evaluates the quality of a recipe based on Food Pairing Theory, focusing on ingredient compatibility and optimal ingredient ratios.
- **Genetic Algorithm**: Includes parent selection, crossover, mutation, and environment selection processes to evolve and improve recipes over time.
- **Creativity and Novelty**: Generates unique and creative recipes, ensuring a high degree of variation with each run of the algorithm.

## Genetic Algorithm Components

### 1. Representation
- Recipes are represented as lists of ingredients, categorized into classes such as binding, core, fat, flavor, flour, fruit, nut, rising, spirits, and sugars.

### 2. Parent Selection
- Uses a roulette algorithm, where recipes with higher taste function values have a greater probability of being selected as parents.

### 3. Crossover
- Applies a uniform crossover technique to combine ingredients from two parent recipes, ensuring diverse and novel offspring.

### 4. Mutation
- Mutates offspring recipes by adding, removing, or modifying ingredients within their respective classes.

### 5. Environment Selection
- Selects the best recipes from the combined population of parents and offspring to proceed to the next generation.

## Knowledgebase

- **pairings.csv**: Contains data on which ingredients pair well together.
- **ingredients.csv**: Lists ingredients along with their class and quantity ranges.

## Full Report

A detailed report on the methodology, algorithms, and the results of this project can be found in the PDF file included in this repository: `Cookies_Recipe_Generator_Report.pdf`.

## Requirements

- Python 3.x
- Libraries: numpy, pandas


## Contact

For any inquiries, please contact:
- **Name**: Dinu Catalin-Viorel
- **Email**: viorel.dinu00@gmail.com
