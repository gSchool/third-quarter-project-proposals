# Galvanize Q3 Group Project Proposal

1. Fork/clone this repo
2. Update this readme with proposal
  * Use valid markdown formatting!
3. Pull request

## Group Members

* Justin Hart
* Devin Gray
* Derek Kramer
* Tristan Gilfoyle
* Devin Hanaway
* Izabela louw

## Project Description

MicroLens is consumer facing food tracker, that allows users to track the food they eat, based upon Micro/Macro Nutrients <> compared to the DRI (Daily Recommended Intake). We will allow users to input food, take a photo of a foods bar code, and as a stretch take a photo of a food and return the nutritional data for it.

We will give the users a daily graph of their micro and macro nutrients compared to the DRI values.


## Who uses it?

People who currently track their food intake, but would like to have a more in depth breakdown of their nutrients.

People who have a chronic or acute condition, and would like a recommended nutritional plan that helps their disposition.

## What outputs do they need?

 * Micro Nutrients from the food they eat.

 * Macro Nutrients from the food they eat.

 * Comparison between a users micro nutrient intake with Daily Recommended Intake.

## What inputs are needed to generate those outputs?

 * USDA OPEN FOOD API
 * Barcode Scanning of food
 * User inputed foods
 * Photo image processing ( from DSI neural net)

## What technologies will you use that weren't covered in class?
MAIN
 * D3
 * REACT
 * HTML5 File API ( 3rd party bar code scanning library)
 * AWS (production EC2 hosting) Heroku if all fails

STRETCH
 * Neural Net API (DSI)
 * PWA (Progressive Web APP)
 * oAuth

## What technologies do you plan to use?

### MAIN
 * D3
 * REACT
 * HTML5 File API ( 3rd party bar code scanning library)
 * AWS (production EC2 hosting)---- Heroku if all fails
 * USDA open food API
 * PSQL
 * Node.JS ( Knex + Express)

### STRETCH
 * Neural Net API (DSI)
 * PWA (Progressive Web APP)
 * Auth (oAuth)


## Feature list
### MAIN
 * User Profile
 * Food Input Nutrient tracker
 * User Nutrient Graphical Comparison of Micro & Macro nutrient to RDI (Recommended Daily Intake)
 * User Nutrient Graphical Comparison of Macro nutrient to RDI (Recommended Daily Intake)
 * BarCode Scanning Nutrient tracker

### STRETCH
 * Image recognition nutrient tracker
 * Drilled down D3 graphical breakdown of individual micro nutrients
