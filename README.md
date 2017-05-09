# APerspectiveOnTechnology
A collection of the thoughts of people like Bret Victor, Ted Nelson, Alan Kay and other programming luminaries of our generation.

# Representation

The Foundation of the representation will be a 3D cube. There will be three Views. We will be using six markdown files as input for each plane. 

# Legend

Each plane has its own color theme. Relations should have a special color.

# One: 2D - single 

The Single view simply displays the data from a markdown file as a "normal" HTML page (can be embedded into SVG). Text color should be white or black, but there should be a transition.

# Two: 2D - all planes

Same as "One" but each file is now a seperrated, colored "tile" and you can scroll 2D wise across all planes without interception.

# Three : 3D - rotating

Starting from a edge view. Inside the cube is all the data from the markdown files as "word clouds". There need to be a balance between readability of words and the visual size of relations. This view should make _better_ sense of the relations.

# Transitions

Transitions between views should be _smoothly_ animated (see bret victor: stop drawing dead fish)

# Implementation

- use JavaScript or ClojureScript to load the data from the mardown files. 
- the relationship informations needs to be put into "data"
- use SVG and *Script* to create a pseudo 3D View and to transform between views

## Can you make a chatbot out of it

## Youtube ML
