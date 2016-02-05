# Galvanize Group Project Proposal

## Group Members
Jon Casey, Ben Allred, Elana Kopelevich (“Designated Drinkers”) 

## Project Description
Stumblr is a social barhopping app for competitive drinkers. Designed for mobile use, Stumblr maps a route of nearby bars for an optimal barhopping circuit. 


## Who uses it?
Anybody over the age of 21 who enjoys social drinking and adventures. 


## What outputs do they need?
* As an anonymous user, I should be able to:
	* View the home page
	* Sign up or Login with Uber
* As a logged-in user, I should be able to:
	* Create a route based on my location
	* View my previous routes (incomplete and complete)
	* Be able to mark a route completed
	* Comment and rate my routes


## What inputs are needed to generate those outputs?
* To create a bar hopping circuit we need: 
	* user login	
	* location
* To complete a route: 
	* mark route complete (T/F)


## What technologies will you use that weren't covered in class?

* React.js
* Redux.js
* Taigo.io (project management)
* OpenShift (for deployment)
* Uber OAuth
* Google Maps Web Services
* MySQL


## What technologies do you plan to use?
In addition to those listed above: 

* Node.js
* Express.js
* Passport.js
* Knex.js


## Feature list

* (MVP) As a user, I can: 
	* Create a bar hopping circuit based on my location 
	* See a map with pins and a list of sorted bars
	* Save my circuit and return to it later
	* Add notes to a circuit
	* Rate a circuit (1-5)
	
* (Stretch) As a user, I can: 
	* Setup a route...
		* Choose my level (“Fun Run” (3 bars), “5k” (5 bars), “Half Marathon” (10 bars), “Marathon” (20 bars)
		* Choose a circular route or a route with different start and end points
	* Find friends... 
		* Find friends by username or email
		* Add friends
		* Remove friends
		* View my friends list 
		* View my friends’ routes
		* Comment on my friends’ routes
	* Receive notifications when my friends:
		* Complete a route
		* Visit a bar
		* Share info…
	* Automatically tweet or check-in when I check-in via Stumblr
	* Timer…
		* Time between bar check-ins
	* Earn Badges..
		* Based on number of bars?
		* Based on number of bars in specific bar category?
		* Based on number of drinks?
		* Based on number of completed routes?
	* Track Drinks… (pretty stretchy)
		* Earn badges or points based on type of drink (beer, shot, cocktail)



