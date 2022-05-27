# Template HTML Dice Game Match 

*NOTE: do not contain JS code for interaction*

## [DEMO](https://domenicomonaco.github.io/dice-game-webpack/)

### Sponsored by

[<img align="left" style="margin:5px; "src="http://cdn.tecnologieperpersone.it/img/dmonaco_happy_hacking.png" height="64" />](https://blog.domenicomonaco.it)
 [<img style="margin:5px;" src="http://cdn.tecnologieperpersone.it/img/tecnologie-per-persone-logo.png" height="64" />](https://tecnologieperpersone.it)

 ## Requirements

* node > 14
* npm > 6
* *cazzimma* > ∞

### Advanced Usage

Clone the source files of the theme and navigate into the theme's root directory. Run `npm install` and then run `npm dev` which will open up a preview of the project in your default browser, watch for changes to core project files, and live reload the browser when changes are saved. You can view the `package.json` file to see which scripts are included.

#### npm Scripts
- `npm run build` builds the project - this builds assets, HTML, JS, and CSS into `dist`
	- `npm run build-prod` as previous build but in production mode
- `npm run clean` deletes the `dist` directory to prepare for rebuilding the project
- `npm run clean-inst` delete the `dist` and `node_modules` directories and `package-lock.json` file to prepare for reinstall from scratch the entire projects
- `npm run dev` runs the project in developing mode
- `npm watch` not launches a live preview but runs compiling and watches for changes made to files in `src`
- `npm pages` deletes the `dist` and files into `docs` and then build project and move in to `docs` folder to be displayer as *[DEMO](https://domenicomonaco.github.io/dice-game-webpack/) GitHub Pages* 

You must have npm installed in order to use this build environment.

## Preview HTML

![Dice Match HTML preview](preview.png)

## Game Rules

### Game of Dice (Dice Match)
#### Match

A game consists of several consecutive hands (rounds). The participant who wins a hand receives 2 points, 0 the participant who loses. If the round is tied, both participants receive 1 point. During the game the results of the hands are added up and at the end whoever has scored the most points wins the game.

#### Round (hands)
The "round" (hands) is the actual game, it simply consists of throwing a die for each participant. The participant with the highest die number wins the hand. If the dice show the same number then the hand is even. As mentioned before, the participant who wins a hand receives 2 points, 0 the participant who loses. If the round is tied, both participants receive 1 point. Note Attention: during the game do not add up the dice results but only the result of the rounds, that is 2, 1 or 0 for each hand.

## Copyright and License

Copyright
Domenico Monaco [https://domenicomonaco.it](https://domenicomonaco.it) Code released under MIT License
