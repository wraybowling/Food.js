![Image Food.js](food.js.png)

# Food.js
raw cooking data, and tools to read it

Start here: http://wraybowling.github.io/Food.js/

## How It Works

### Example Scenario 1: You want to use up ingredient X

 1. Put X on a food scale
 2. Adjust the amount in the recipe
 5. All other values are updated!

### Example Scenario 2: You want to serve Y people

 1. Think about how much you want to serve per person (Z)
  - 500 grams is a typical amount for a plate of food
  - 250 for half a plate
  - and so on...
 2. Multiply by Y number of people.
 2. Put that value in the Total field
 5. All other values are updated!

### Example Scenario 3: You want to make a perfect cocktail ([How this all got started!](https://vine.co/v/eZaqYpDBW1j/))

 1. Write a piece of software to balance proportions (Food.js)
 2. Create a JavaScript object with
  - all the ingredients as attributes
  - all the values as mass
 3. Measure the volume of the glass
  - put it on the scale
  - press tare
  - fill with water
 4. Put the glass's volume in the Total field
 5. All other values are updated!

## Philosophies

### You Need A Food Scale
In most kitchens, many ingredients are added to taste after a recipe has been followed. The reason for this is because we don't actually pay attention to a few extra teaspoons when we cook. But with metric, you can. With a scale you can. Because the metric system on a food scale has a much higher resolution, you don't have to think of it as "european." Think of it, rather, as Digital HD Ingredient Measuring.

### Mass Measurements
In countries where the metric system is employed, cooking involves fewer headaches and more accurate outcomes. Many cite baking, since flour by weight is more accurate. But there are other reasons why metric is better. Namely, recipes involve less guessing and arithmetic. All of the recipes are in grams, but so long as you're going by weight, you can really use any unit you like. Grams are just the easiest to read.

### It's Still Just A Guideline
Once you get used to following recipes with Food.js, you can feel free to drift away from the values and experiment with replacing ingredients with alternatives. Perhaps an experience you've never had: the balance and proportions will remain the same.

### No Prescribed Feelings
This cookbook aims to do away with anything that isn't raw cooking data. No one will tell you how delicious the recipe is. There are no stories to read. No one will tell you about their wonderful time in Venice when they had this dish with their aunt Jenn. There are no photographs to show you what it will look. There are no guidelines on how you should cut things. Instead, just be creative! This cookbook has none of those things because you don't need my feelings. You have your own.

## Put The Code On Your Fork
Food.js is written in JavaScript, and is open source. The reader and the recipes live in just one file. The format is simple to edit. The viewer is streamlined for offline viewing, and looks great on a phone or tablet.

Fork this repository to add your own recipes. Please feel free to send in your recipes as pull requests, and do not be surprised when they are forked and adjusted. That is actually the most delightful thing about cookbooks—how they mutate. What better way to facilitate such a thing than through Github?

## Recipe Conversion Process
There are two ways you can convert your recipe to grams.

### Make your recipe using normal means, measuring in grams with a food scale with each step.
- set bowl on scale, press tare
- deposit first pre-measured ingredient, write down the value, press tare
- deposite second pre-measured ingredient, write down the value, press tare
- and so on...

### Enter ingredient amounts as arbitrary units into Wolfram Alpha.
For example, search [1 lb of brussel sprouts](https://www.wolframalpha.com/input/?i=1+lb+of+brussel+sprouts)
observe the serving size in the generated nutritional information card (454g), and write this down.

![1 lb of brussel sprouts](https://www4d.wolframalpha.com/Calculate/MSP/MSP4770223gdegd70cg388500002eaae38h4ff0g954?MSPStoreType=image/gif&s=31)

Enjoy your meals,


Wray Bowling | programmer, cook, & interaction designer
