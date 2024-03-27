# Super-Square-Man
This is a video game I made for one of my classes. To play it, simply download [the BasicGraphics.jar file](https://github.com/Gr8Potato/Super-Square-Man/blob/master/BasicGraphics.jar).

### Developer's Note: Bug
This game consists of three levels. Levels 2 and 3 do not load properly without manually calling the `load()` method for each object that controls how the sprites are displayed. This is because of the way the graphical library that was provided 'kills' sprites rather than temporarily deactivates them. This can be fixed by creating each level as needed, however, that's easier said than done due to the nature of the graphical library as well as some coupling issues introduced when I had initially made the project a year ago (at the time I am writing this). Until I decide to look into it, only level 1 is playable. You're welcome to compile a version of this program with levels 2 and 3 initialized (independently).

> [!CAUTION]
> I do not support people plagiarizing my code. I do not take responsibility for the unlawful actions of others.