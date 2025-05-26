*This is a submission for the [Bright Data AI Web Access Hackathon](https://dev.to/challenges/brightdata-2025-05-07)*

## What I Built

You know that feeling when you're staring into your fridge at 6 PM, holding a random bell pepper, some leftover rice, and maybe half a can of coconut milk, wondering if delivery is really *that* expensive? Yeah, me too. Sometimes shopping is literally the last thing I want to do, especially when I have 2-3 random ingredients sitting around and absolutely no clue what magic I can create with them.

Enter **PantryChef**, my AI-powered kitchen companion, just tell it what's lurking in your pantry, and it'll hook you up with recipe recommendations based on your taste preferences, budget constraints, and most importantly, what you actually have on hand right now.

Here's the cool part: PantryChef doesn't just pull from some dusty static database. It uses Bright Data to scrape real-time recipes from across the web, then gets smart about ranking them based on how well they match your pantry situation, cooking style, and time constraints. Plus, it can generate completely new recipe ideas using AI and even classify cuisines with matching scores.

This literally solves my "What the heck can I cook right now without leaving my apartment?" crisis in the most personalized way possible.

## Demo

The PantryChef repository is available [here](https://github.com/Mogboella/pantrychef).

Here are some screenshots showcasing the frontend in action:

![Screenshot 1](https://github.com/Mogboella/pantrychef/blob/main/Screenshot%202025-05-26%20at%206.13.44%E2%80%AFAM.png)  
![Screenshot 2](https://github.com/Mogboella/pantrychef/blob/main/Screenshot%202025-05-26%20at%206.13.52%E2%80%AFAM.png)  
![Screenshot 3](https://github.com/Mogboella/pantrychef/blob/main/Screenshot%202025-05-26%20at%206.13.58%E2%80%AFAM.png)
![Screenshot 4](https://github.com/Mogboella/pantrychef/blob/main/Screenshot%202025-05-26%20at%206.14.06%E2%80%AFAM.png)

It's also deployed and almost ready to rescue your dinner plans at: [the-pantry-chef.netlify.app](the-pantry-chef.netlify.app) – though fair warning, I haven't connected the frontend and backend yet, so right now it's mostly a UI scaffold/demo to show off the vision!

Backend In Action:
![Screenshot 5](https://github.com/Mogboella/pantrychef/blob/main/Screenshot%202025-05-26%20at%206.16.42%E2%80%AFAM.png)
![Screenshot 6](https://github.com/Mogboella/pantrychef/blob/main/Screenshot%202025-05-26%20at%206.16.49%E2%80%AFAM.png)
![Screenshot 7](https://github.com/Mogboella/pantrychef/blob/main/Screenshot%202025-05-26%20at%206.16.53%E2%80%AFAM.png)

Want to peek under the hood? You can test out the backend endpoints via Postman or any HTTP client. Here's a sample Postman collection with all the necessary endpoints: [Postman Sample Requests](https://github.com/Mogboella/pantrychef/blob/main/pantrychefBackendDemo.json)

## How I Used Bright Data's Infrastructure

Bright Data's MCP server became my secret weapon for turning random pantry ingredients into culinary inspiration:

- **Discover** relevant recipes from across the entire web 
- **Access** even the most complex recipe websites that usually hide behind paywalls or annoying pop-ups
- **Extract** clean, structured data including ingredients, step-by-step instructions, and mouth-watering images
- **Interact** with dynamically rendered pages to ensure I'm getting the freshest, most up-to-date recipes (no more "this recipe was last updated in 2019" situations)

## Performance Improvements

Here's where things get exciting: real-time web data completely transforms PantryChef's game. Instead of being stuck with some stale recipe database that probably thinks "fusion cuisine" means putting pineapple on pizza, my solution serves up fresh, relevant recipes that actually match what's in your kitchen right now.

The AI component acts as the perfect wingman, creating innovative recipe combinations I never would have thought of and learning my preferences over time for increasingly smart recommendations. It's like having a personal chef who actually gets your weird dietary quirks and budget constraints.

---

Building PantryChef has been one of those projects that scratches a very personal itch. As someone who genuinely loves cooking but absolutely despises the "what should I make for dinner" decision fatigue, creating an AI assistant that can look at my random collection of ingredients and suggest something actually delicious feels like pure magic.

It's not just about convenience – it's about reducing food waste, saving money, and rediscovering the joy of cooking with what you have instead of always feeling like you need to buy more stuff.

Plus, there's something deeply satisfying about building a tool that makes the everyday task of feeding yourself feel less like a chore and more like a creative adventure.