# StageHand
A python project to enhance the workflow of theatre production teams. 

## The Aim
I want to create a piece of software that has the following features
 - User interface for the stage manager to see what is going on at lighting console, sound desk, TheatreControl and in QLab
 - User interface for operators to view a syncronised clock and stopwatch.
 - Connection to lighting console, sound desk, TheatreControl and Qlab via OSC over websockets
 - Webserver to serve user interfaces on a local network

## Early Design Mockup (Stage Manager View)
![StageHand UI V1](https://github.com/user-attachments/assets/69c91ee3-bbfe-4684-814a-ae7812f114ac)

## Features to implement
 - OSC connection to QLab (partially completed)
 - Websocket-based web page for stage manager to view what is going on
 - OSC connection for X32/M32 (to view mic mute status)
 - OSC connection to TheatreControl (to view cue info)
 - OSC connection to EOS (for lighting cues)
 - Add stopwatch functionality
 - Add webpage for operators to view stopwatch.
 - Add other sound/lighting consoles
