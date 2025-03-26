# NoSQL Challenge: UK Food Hygiene Ratings

## Overview

This project analyzes food hygiene rating data from the UK Food Standards Agency using MongoDB and PyMongo. The goal is to help a food magazine, *Eat Safe, Love*, identify restaurants of interest based on cleanliness scores, rating values, and locations.

---

## Contents

- `NoSQL_setup_starter.ipynb`: Sets up the MongoDB database, imports and cleans the data, and updates documents as requested.
- `NoSQL_analysis_starter.ipynb`: Performs exploratory data analysis to answer specific business questions using MongoDB queries and Pandas.

---

## Data Source

The dataset comes from the UK Food Standards Agency and includes hygiene scores, business types, addresses, and food safety ratings for various UK establishments.

File:
- `Resources/establishments.json`

---

## Tools Used

- Python
- PyMongo
- Pandas
- MongoDB
- Jupyter Notebook

---

## Key Tasks

### Part 1: Database Setup
- Imported JSON data using `mongoimport`
- Connected to MongoDB and confirmed collection was created

### Part 2: Database Updates
- Added a new restaurant manually
- Updated document fields
- Removed entries from Dover
- Converted coordinates and rating values to numeric types

### Part 3: Exploratory Analysis
- Identified establishments with hygiene score of 20
- Found highly rated restaurants in London
- Located the top 5 restaurants near "Penang Flavours"
- Aggregated hygiene score 0 counts by Local Authority
