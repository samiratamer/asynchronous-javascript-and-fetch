For this assignment, students will use fetch() and the Poke API (https://pokeapi.coLinks to an external site.) to request data and dynamically display it on the page, using basic HTML and JavaScript.  NOTE: the Poke API is a 3rd-party resource that we are using for educational purposes.  Please cache server responses to minimize the number of API calls (see final slides from Feb. 17, for more information).

Create a simple "Pokemon Team Builder" page that displays data according to the user's choices.  There is no CSS requirement, but you are encouraged to choose an appropriate design.  You cannot use any framework to complete this assignment; just use HTML, CSS, and JavaScript.

Requirements:

The user must be able to enter in the ID or name of a Pokemon
When the user clicks the submit button, a fetch() should be executed to collect the JSON corresponding to that Pokemon from the API.
The data should be parsed, and the page should be dynamically updated as follows:
The image of the pokemon should be displayed
The sound of the pokemon should be loaded, and playable
The moves of the pokemon should be loaded into 4 dropdown menus
The user should be able to select the moves from four dropdown menus
When the user presses a button for "Add to Team", their choices should be saved and displayed appropriately (see below).
Your solution will be tested against a variety of pokemon.  If you do not know any pokemon names, you can use numbers between 1 and 151 instead of names.
