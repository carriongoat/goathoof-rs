# goathoof-rs
## safe rust game engine for the 3DS
i really want to make a game for the 3ds. cant make a game without an engine (untrue, but the game'd be a mess or very basic). so here i am, booboo the fool, sitting above the homebrew slop dunk tank. All contributors must throw one apple at my dunk target, and if you successfully land your apple on my target i will fall in the tank and you will own this repository. Its like highlander for homebrew jank slop. 

## goals
- render good
- decent but basic physics
- dont require the user to touch citro3d or libctru themselves
- ECS, because everyone says its performant and i only have 128mb of ram here
- basic positional audio system, the 3ds isnt fancy enough to go too crazy though

## potential goals
- pica shader language that's got easier syntax than picasso
  - actually picasso is really nice, i think i mean "shader syntax that integrates better with rust and my camera system and asset systems"
   - i dont want users to have to learn super low level stuff about the 3ds to get hardware rendering working 
   - but i also want to allow the flexibility picasso's assembler provides
- asset system. glTF parser, scripts to batch compress/convert textures, .ogg audio pipeline, video player maybe? for fmvs?
