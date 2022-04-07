# Planets & Pickups

## Description

This is a small open source game prototype made with Unity/C#. The player moves around on small planets and can jump between them, influenced by the gravity field generated by the planets. Pickups will spawn which the player can collect to score points. Increasingly more enemies will spawn which the player has to evade. The goal of the game is to score as many points as possible before eventually touching an enemy.

Unless otherwise noted (e.g. in the "Used libraries and assets" section).


## Play the game

You can play the game without building it [in your browser](https://dragonlab.de/projects/PlanetsAndPickups/). (You can see whether your browser is compatible [here](https://docs.unity3d.com/Manual/webgl-browsercompatibility.html).)

<img src="https://dragonlab.de/projects/PlanetsAndPickups/gameplay_small.gif"/>

## Building the project

1. Get the project by cloning it with your favourite git client or download it as a ZIP archive.
2. Install Unity 2018.3.9f1 from the [download archive](https://unity3d.com/get-unity/download/archive) or the Unity Hub. Newer versions might also work.
3. Open either the Unity Hub or Unity 2018.3.9f1 directly.
4. Open the project by selecting the folder you got from step 1 as the project.
5. Go to "File->Build Settings".
6. Select your target platform and click "Switch Platform".
7. Click on `Build And Run" and select a target folder.
8. The project should now build and run once completely built.

## Used libraries and assets

For this project I used the following libraries:
- [Zenject](https://github.com/modesttree/Zenject), an incredibly easy to use dependency injection framework.
- Unity's [Post Processing Stack V1](https://assetstore.unity.com/packages/essentials/post-processing-stack-83912) for the bloom and vignette effects.

The assets used are:
- [Acme](https://fonts.google.com/specimen/Acme?selection.family=Acme), a great google font.
- The swinging tune "Experimental Gameplay ID 953" by [Lobo Loco](http://freemusicarchive.org/music/Lobo_Loco).
- A few sound effects from the ever-fabulous [Universal Sound FX](https://www.imphenzia.com/universal-sound-fx) by Imphenzia.

## License

Treat it as public domain for all intents and purposes, and then do with it whatever you want.

Libraries in the AddOn folder and other assets besides my own code in Asset/Scripts may be subject to other licenses.

## Possible next steps?

Assuming I ever continue working on this, I'd mostly be concerned with smoothing out the player controls. While I still like the concept of jumping in a world full of different gravity, in its current iteration it often feels too unpredictable for the player. Maybe it's possible to tune the gravity fields so that the jumps behave more predictably without feeling too stifling. Maybe the way forward would be to properly visualize the gravity fields to the player so that they can make more informed decisions (or at least aren't surprised by the strange paths their avatar is taking).
