
# VALORANT Analysis Dashboard

## Overview

This project provides an interactive dashboard for analyzing VALORANT game data, focusing on agents' abilities and weapon statistics. The dashboard is built using two primary datasets:

1.  **Agent Abilities:** Contains detailed information about each VALORANT agent, including their roles, biographies, images, and abilities with descriptions and video examples.
2.  **Weapon Statistics:** Includes data on weapon names, types, prices, fire rates, wall penetration, and damage values for head, body, and leg shots at different ranges.

## Methodology
- Data Collection and Preprocessing
- Exploratory Data Analysis (EDA)
- Dashboard Development

## Tools Used
- Power BI

## Key Components

*   **Agent Selection:**
    *   Allows users to select an agent and their role, dynamically updating the displayed image and information.
*   **Treemap:**
    *   Visualizes the roles and abilities of each agent.
    *   Selecting a box in the treemap changes the agent image and updates a text box with the agent's role and name.
*   **Weapon Slicer:**
    *   Filters the data based on weapon name, affecting the charts below.
*   **Weapon Damage Chart:**
    *   Displays the damage caused by each weapon to the body, head, and legs.
    *   Highlights that the "Operator" causes the highest damage across all three body parts, while the "Shorty" causes the least.
*   **Weapon Price Chart:**
    *   Shows the price of each weapon relative to its type (Sniper, Heavy, Rifle, SMG).
    *   Examples:
        *   "Operator" (Sniper): 4500 credits
        *   "Odin" (Heavy): 3200 credits
        *   "Phantom" and "Vandal" (Rifle): 2900 credits
        *   "Spectre" (SMG): 1600 credits
*   **Weapon Fire Rate Chart:**
    *   Illustrates the fire rate (rounds per second) of each weapon.
    *   "Stinger" has the highest fire rate at 18, while "Operator" has the lowest at 0.75.


  
