---
title: Grandstand Gauntlet
type: game
authors: ["Morgan", "Olf"]
---

[Return to safe place](https://wabtey.github.io)

Thanks for passing by !

<p style="text-align: center;"><b>WARNING:</b> This is a post submission version.</p>

<p style="text-align: center;">For the submission vote, vote only on the basis of the <a href="https://fabinistere.itch.io/grandstand-gauntlet">Itch.io Version</a></p>

## Note

Please click the ***fullscreen button*** to play

We wanted to create a BossFight game, where you, as a small and weak creature, are sent into the pit (the arena is not built yet but the spectators are there anyway). But when the crowd laughs at your death, your soul shifts towards a normie in the grandstand (bushes), like a parasite you will control their body now.

The boss will have to fight hundreds of clone parasites.

The Boss being static it breaks the fight concept :)

## Quick Controls

`E` : So Long (*spamming e = the most fun part of this 'game'*)

`Left Mouse Click`: Light Attack

`Long Pressed Left Mouse Click`: Charged Attack (slap return)

`A D` or `Q D` or `Left Right`: Move

## Current Release

- Player
  - Can light slap with, light press on `Left Click Mouse` or `Return`
  - Can heavy slap with, long press on `Left Click Mouse` or `Return`
  - Can move left or right with, `A D` or `Q D` or `Left Right`
  - Can so long with, `E`
- Boss
  - Can stare the player
  - Can attack with a 'light' smash the player if too close
  - Can wonder about all the abilities they have been given without any chance to triggering them
- After Two hits, the player dies and soul shift towards a nearby spectator
  - The spectator comes at the first plan
  - The Dead Body lays above the scene
  - The new player is fully functional

## Future Updates ?

- [x] The boss has other phase and attack but no time :D <3
- [ ] The nice battle music we found earlier
- [ ] A Lore screen explaining that the Grandstand is not yet build
  - [ ] a long/medium corridor where we can put dummies to try attack and explicitly say (on the wall) the controls
  - [ ] build some tension
- [ ] A Ending

## Credit

2 person game, created for the game jam Brackeys 2023 (1week limit)

### Developement

- [Morgan aka Elzapat](https://github.com/Elzapat)

- [Olf aka Wabtey](https://github.com/Wabtey)

### Assets

- [***Eder Munizz***](https://edermunizz.itch.io/) - Parallax
  - [Free Pixel Art Hill](https://edermunizz.itch.io/free-pixel-art-hill)

    ![Free Pixel Art Hill](https://img.itch.zone/aW1hZ2UvMTc4ODM2LzgzNzU3Mi5wbmc=/original/t0jyLw.png)

- [***Penusbmic***](https://penusbmic.itch.io/) - Scifi Character Pack
  - [Character Pack 10 - Ball and Chain Bot](https://penusbmic.itch.io/sci-fi-character-pack-10)

      ![Ball and Chain Bot](https://img.itch.zone/aW1nLzQ4NzY4NzUucG5n/180x143%23c/fWIjAB.png "pack ten")
  
  - [Character Pack 11 - Toaster Bot](https://penusbmic.itch.io/sci-fi-character-pack-11)

      ![Toaster Bot](https://img.itch.zone/aW1nLzUyNzk4MzkucG5n/180x143%23c/RzE1WI.png "pack eleven")

<!-- []() -->

<style>
    body {
        margin: 0;
        background: linear-gradient(-45deg, #a6a6a6, #5ac05a, #262626, #a6a6a6);
        background-size: 400% 400%;
        animation: gradient 15s ease infinite;
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    canvas {
        margin: 0;
        background-color: white;
        height: 100%;
        width: 100%;
    }

    @keyframes gradient {
        0% {
            background-position: 0% 50%;
        }
        50% {
            background-position: 100% 50%;
        }
        100% {
            background-position: 0% 50%;
        }
    }
</style>

<script type="module">
    import init from '../grandstand-gauntlet.js'
    init()
</script>
