# MLB Players Database Queries

## Overview

This repository contains SQL queries designed to extract and analyze information from a Major League Baseball (MLB) players database. The database, `players.db`, includes data on MLB players from 1871 to 2023, encompassing details such as player names, birthplaces, physical attributes, and career timelines.

## Problem Statement

The dataset provided in `players.db` presents several challenges, including:

- Extracting specific player details based on various criteria.
- Analyzing players' attributes such as batting and throwing sides.
- Identifying players with missing or specific data points.

## Solution Approach

I developed a series of SQL queries to efficiently address these challenges and answer various questions about the players in the database. Below is a summary of the problems tackled and the solutions provided:

1. **Jackie Robinson's Hometown**:
   - **Query**: Retrieve Jackie Robinson's hometown, including city, state, and country.

2. **Babe Ruth's Batting Side**:
   - **Query**: Find the side on which Babe Ruth batted (right or left).

3. **Missing Debut Dates**:
   - **Query**: Identify player records with missing debut dates.

4. **Non-U.S. Born Players**:
   - **Query**: List and sort the names of players born outside the United States.

5. **Right-Handed Batters**:
   - **Query**: List all right-handed batters and sort their names alphabetically.

6. **Players Born in Pittsburgh**:
   - **Query**: Extract details of players born in Pittsburgh, PA, including debut dates, and sort by debut date.

7. **Mixed Batting and Throwing Hands**:
   - **Query**: Count players who bat right-handed and throw left-handed, or vice versa.

8. **Average Height and Weight of Recent Players**:
   - **Query**: Calculate the average height and weight of players who debuted on or after January 1, 2000, rounded to two decimal places.

9. **Final Games in 2022**:
   - **Query**: Find players who played their final MLB game in 2022, sorted alphabetically.

10. **Custom Query**:
    - **Query**: A custom query answering a unique question, utilizing column renaming, conditions, and sorting.

## Files

- `1.sql` - Query to find Jackie Robinson's hometown.
- `2.sql` - Query to determine Babe Ruth's batting side.
- `3.sql` - Query to find player records with missing debut dates.
- `4.sql` - Query to list players not born in the U.S.
- `5.sql` - Query to list right-handed batters.
- `6.sql` - Query to extract details of players from Pittsburgh.
- `7.sql` - Query to count players with mixed batting and throwing hands.
- `8.sql` - Query to calculate the average height and weight of recent players.
- `9.sql` - Query to find players with final games in 2022.
- `10.sql` - Custom query of your choice.

## Usage

To test the queries, run the following commands in your terminal:

```sh
.read FILENAME
