# Halcyon
*TouchDesigner control system for lighting and visuals at the Halcyon nightclub in San Francisco*

![GUI](https://i.imgur.com/70JIRyY.png "The GUI")

## Description
This project contains the code used to map and control 20 universes of addressable LED lights at the Halcyon Nightclub as well as nine output video channels.

For the LEDs, textures are mapped onto the ceiling and the wall behind the stage at the venue.

This project features a very simple GUI split into three sections: controls for the video content, controls for the LED content and controls for the venue lighting and previsualizion.

There are several examples of the final result on [YouTube](https://www.youtube.com/watch?v=5YREMmuiGhc).

NOTE: This project has beens simplified to make it less specific to the venue and easier to look at.  This comes at the cost of functionality. The project installed in
the venue is considerably more complicated (including elements to control the venue's Hog4PC server and DMX lights).

Some components also have `privacy` enabled. Hit me up if you are curious about elements that can't be shared online.

A more full write up of this project is available [here](https://willynolan.com/halcyon).

## Tested On
- Windows

## To Use
- Clone this repo and open `TouchDesigner/project.toe`

## Project Structure
NOTE: This is definitely not how a normal project should be structured.
Here, nothing is externalized because the simplest possible choices (at every opportunity)
were taken with the end user (operator) in mind.

- `Blender` contains a simple 3D scene of the venue
- `TouchDesigner` contains the code to control the mapped LEDs and video output

## Venue Hardware
At install time the venue contained the following hardware:
  - One server with nine HD outputs (projectors) and one 4K output (control monitor)
  - 20 Universes of individually addressable LEDs
  - 18 DMX fixtures controlled by Hog4PC

## Extra Notes
- This project requires [TouchDesigner 099](http://derivative.ca/) and a commerical license

### License

:copyright: Willy Nolan 2017

[MIT License](http://en.wikipedia.org/wiki/MIT_License)
