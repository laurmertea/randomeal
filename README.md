# randomeal
A random meal generator for when you are feeling hungry

## About the Project
This is a project meant to test working with a public API.

Using [TheMealDB](https://www.themealdb.com/ 'TheMealDB: An open, crowd-sourced database of Recipes from around the world')'s public API we'll be able to get a random meal and display it on our web page.

## Version 1.0
In version 1.0, based on the data that we can get through a [Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API 'Fetch API provides an interface for fetching resources (including across the network)') API request, we'll show the following meal details:
- meal name
- meal category
- meal image
- a Youtube video with the meal recipe
- the meal ingredients

## Randomeal Screenshots
![Randomeal fetches a random meal from TheMealDB, including ingredients, recipe steps and a video link](/screenshots/screenshot_1.png "Randomeal's random meal area")
> **Randomeal** fetches a random meal from **TheMealDB**, including: the ingredients & their measures, the recipe steps, different details about the meal, like its category and the area where it comes from, and a video link (if available).

![Randomeal returns each time a complete meal recipe by pressing the random meal button](/screenshots/screenshot_2.png "Randomeal's random meal button")
> **Randomeal** returns each time a random complete meal from **TheMealDB** by pressing the _random meal button_.

![If a Youtube video recipe is available Randomeal will show it in an iFrame](/screenshots/screenshot_3.png "Randomeal's random meal Youtube video area")
> **Randomeal** shows the random meal's Youtube if it's available from **TheMealDB**.

![Randomeal works with only one page - a modal component is available with different informations](/screenshots/screenshot_4.png "Randomeal's modal component")
> **Randomeal** shows different information in modal components. The information is passed through data attributes.

## Future versions

### Features
You should be able to select a few things about yourself and the meal you're interested in, in case you want to reduce the random factor and/or have intolerances / allergies.

### Improvements
- improve modals and data passing;
- cleanup JavaScript code;
- cleanup CSS.
