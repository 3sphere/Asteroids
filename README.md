# Asteroids

### About

This is my attempt at recreating the game [*Asteroids*](https://www.youtube.com/watch?v=WYSupJ5r2zo) using C++.  

With this project, I wanted to begin to learn how code for games more complex than [Pong](https://github.com/3sphere/Pong) or [Snake](https://github.com/3sphere/Snake) should be structured in a way that is scalable. To this end, I learned about *game object models*, where a game object refers to anything in the game that updates, draws, or does both. Specifically, I learned how to implement a game object model that is similar to the one used by *Unreal Engine 4*, whereby all game objects inherit from a base *Actor* class, and each game object contains a selection of *components* to incorporate any particular functionality that it needs (e.g. movement, collision detection, animation, etc).  

![Screenshot](https://github.com/3sphere/Asteroids/blob/master/screenshot.png)  

Video: https://www.youtube.com/watch?v=iX6WroFH7rA&feature=youtu.be  

### Libraries used
**SDL 2.0** for windowing and rendering of simple graphics  
**SDL_mixer 2.0** for sounds  

### Controls  
W: Move forward  
A: Rotate left  
D: Rotate right  
Space: Fire