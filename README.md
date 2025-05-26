*This is a submission for the [Bright Data AI Web Access Hackathon](https://dev.to/challenges/brightdata-2025-05-07)*

## What I Built
I created **Pantry Chef**, an AI-powered assistant that helps people cook based on ingredients they already have at home.

The user enters a few ingredients, and Pantry Chef fetches real-time recipes from across the web using Bright Data. These are then ranked based on similarity to the user’s pantry, cooking preferences, and time constraints. Pantry Chef can also generate new recipe ideas using an LLM and enrich them with cuisine classification and matching scores.

This solves the “What can I cook right now?” problem in a personalized, intelligent way.

## Demo

The Pantry Chef Repo is Located : [Here](https://github.com/Mogboella/pantrychef)
Here are some screenshots : 

[]("/Screenshot 2025-05-26 at 6.13.44 AM.png")
[]("/Screenshot 2025-05-26 at 6.13.52 AM.png")
[]("/Screenshot 2025-05-26 at 6.13.58 AM.png")
[]("Screenshot 2025-05-26 at 6.14.06 AM.png")
[]("Screenshot 2025-05-26 at 6.16.42 AM.png")
[]("Screenshot 2025-05-26 at 6.16.49 AM.png")
[]("Screenshot 2025-05-26 at 6.16.53 AM.png")

you can try out the backend on postman with : 

## How I Used Bright Data's Infrastructure
I utilized Bright Data's MCP server to:

Discover relevant recipes across the web.
Access complex recipe sites to gather diverse content.
Extract structured data at scale for processing.
Interact with dynamically rendered pages, ensuring up-to-date information.


## Performance Improvements
