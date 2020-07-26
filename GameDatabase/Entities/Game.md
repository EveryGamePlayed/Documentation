# Game

The Game Entity is the main entity of the system. It contains all information needed to completely describe a game in it's entirety.

## Properties

The following properties are defined for the Game Entity:

__Id__ - The primary key and unique identifier for a particular game

__Title__ - The title of a particular game - Is not unique as there can be ports to different systems that are treated as unique games (This is to allow for the launcher to create different information based upon the port)

__SortTitle__ - Used to define a better title when sorting games (Usually to get rid of initial "The" or to change roman numerals to numbers)

__Description__ - A text description that describes the game such as the game's plot, links to game footage, review excerpts, etc.

__Release Date__ - The release date of the game

__Community Rating__ - The Aggregate score based upon the communities review score

__Images__ - A List of Images that show different aspects of the game such as the box art, title screen and other screenshots

__Platform__ - The game console / PC that the game plays on

__Series__ - The series that the game belongs to

__Developer__ - the Developer of the game

__Publisher__ - The Publisher of the game
