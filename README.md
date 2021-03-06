# pokemon_go_egg_hatching
This app helps a user determine when to place their Pokemon Go eggs in incubators in order to hatch them all at the same time. Doing so can help increase the player's XP gain by timing all the hatching with a lucky egg XP bonus or special event bonus. The three main options include: displaying a reference table of all egg and incubator types, calculating an individual egg's hatch time and calculating an egg-placement plan based on the user's current inventory.

Currently, this project is meant for personal use and is serving as a demonstration of my coding.

## UML & 70 Second Demo Video
### UML (Lucid Charts): 
https://lucid.app/lucidchart/invitations/accept/eb355742-50ba-4669-96c2-bd05b83e711f

### 70 second demo video (YouTube):
https://youtu.be/N5VraCcRUu4

## Status
First iteration complete. Basic functionality.

### Future expansion:
Expand the Create Plan feature to include the choice of incubators, eggs that are already incubating and a range for how much the user is willing to walk.

* add functionality to choose incubator (regular or super) and calculate the fastest hatching with only the highest distances being in super incubators
* add functionality to recognize eggs already incubating and how that affects the plan. Any eggs with more distance than those already incubating AND outside the maximum range cannot be walked 
* add range to consider (within 1-2 KM -- no greater than 5KM, since the fastest you can go during hatching is 10.5 KM/hr)
* decide where in the code to require at least 2 eggs for creating a plan
* update instructions once new functionality is in place

## Getting Started
These options will help you set up the program in your local environment. Currently, this only runs in an IDE.

### Prerequisites
No prerequisites other than having an IDE set for Java

### Installing
1. Create a project called aw.pokemon_go_egg_hatching
2. Import the src/pokemongoeggs file 

## Running Tests
No incorporated testing at this time (other than print statements).
Most data validation handled by pre-determined choices in menus (no user input)

## Contributing
No outside contributing at this time.

## Versioning
1.0 - IDE System print out with user input  
2.0 - GUI-based application

## Authors 
@Audra

## Acknowledgments
The Sort class was created by Nikita Tiwari on the Geeks for Geeks website (Java version) https://www.geeksforgeeks.org/bubble-sort/. Adaptations for my program are noted in comments
