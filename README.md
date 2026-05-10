# REH DOGG: SUDS OF FURY

**Interactive Arcade Movie** by **Reh Dogg Games Plus**.

REH DOGG: SUDS OF FURY is a browser-based FMV arcade game where players react to fast on-screen prompts to survive each scene. Choose the right action, keep your Soap Stock alive, build your score, and reach the cliffhanger ending.

## How To Play

Press **Tap To Start**, choose a difficulty, then react when the arcade prompts appear.

Controls:

- **Left Arrow** = LEFT
- **Right Arrow** = RIGHT
- **Up Arrow** = UP
- **Down Arrow** = DOWN
- **Space / Enter** = ATTACK
- **P** = Pause / Resume
- **Escape** = Pause Menu

Mobile:

- Tap the on-screen LEFT, RIGHT, UP, DOWN, and ATTACK buttons.
- Best played in landscape mode.

## Features

- Interactive arcade movie gameplay
- Multiple video-based stages
- Difficulty modes: Normal, Hard, Arcade
- Score system with fast-reaction bonuses
- Scene ranks
- Soap Stock lives system
- Game Over screen
- Pause menu
- Fullscreen button
- Mobile-friendly controls
- VHS arcade visual style
- To Be Continued ending

## Required Structure

```text
SUDS_OF_FURY/
  index.html
  README.md
  assets/
    images/
      sudsy_title.png
    video/
      scene_intro.mp4
      scene_left_success.mp4
      scene_attack_success.mp4
      scene_right_fail.mp4
      scene2_intro.mp4
      scene2_left_success.mp4
      scene2_attack_setup.mp4
      scene2_attack_success.mp4
      scene2_fail.mp4
      scene3_intro.mp4
      scene3_jump_success.mp4
      scene3_right_success.mp4
      scene3_duck_success.mp4
      scene3_attack_success.mp4
      scene4_intro.mp4
      scene4_left_success.mp4
      scene4_down_success.mp4
      scene4_attack_success.mp4
      scene4_fail.mp4
      scene5_intro.mp4
      scene5_right_success.mp4
      scene5_down_success.mp4
      scene5_jump_success.mp4
      scene5_attack_success.mp4
      scene5_fail.mp4
      scene6_intro.mp4
      scene6_right_success.mp4
      scene6_jump_success.mp4
      scene6_down_success.mp4
      scene6_left_success.mp4
      scene6_attack_success.mp4
      scene6_cliffhanger.mp4
```

Optional audio files can be placed in:

```text
assets/audio/
  menu_theme.mp3
  button_click.wav
  prompt_flash.wav
  success.wav
  fail.wav
```

If optional audio files are missing, the game still runs silently.

## GitHub Pages

Upload the full `SUDS_OF_FURY` folder to your repository.

The game runs from:

```text
index.html
```

For GitHub Pages, make sure all file names match exactly, including capitalization. Video paths are case-sensitive on GitHub Pages.

## Release Notes

Public release mode has debug tools disabled. The game is built with plain HTML, CSS, and JavaScript. No external libraries or build tools are required.
