# Commit Invaders 👾

[![status: experimental](https://github.com/GIScience/badges/raw/master/status/experimental.svg)](https://github.com/GIScience/badges#experimental) <img src="https://img.shields.io/github/repo-size/carloswunsche/commit-invaders" alt="Repo size"> <img src="https://img.shields.io/github/languages/top/carloswunsche/commit-invaders" alt="Prominent language">

_A.K.A. commit-grafitti_

## What's this?

Ever had to stop coding for a long time and after going back to your Github page there's a huge blank space of nothingness that's screaming right in your face?

## Wait a minute... there are aliens on your commit history section!

That's right. This program allows you to render some sprites over unused blank space of your Github commit history.

## Features

- Select up to 3 different graphics: Squid, Crab and Octopus
- Select level of graphic brightness/intensity.
- More features to come (maybe...?). Like being able to render text.

## Requirements

- Node.js
- Bash or Git bash

## Usage

1. Go to your Github profile and choose the date _that will match with the top-left corner of the graphic._
2. Clone this repo into your computer and connect it with a new remote Github repo.
3. Open `config.js` and fill in the values with the date you chose, type of alien, and brightness following the instructions included in the comments.
4. Run `node index.js`. This will create a bash script with all the commits one after the other.
5. Open a Bash terminal or Git Bash and run `./script.sh`. Wait for the script to finish.
6. Sync changes to your remote Github repo.
7. Go to your Github profile again and enjoy your new alien! 👾

## Preview

![Screenshot 1](/screenshot.png)

## Credits

Made by [Carlos Wunsche](https://carloswunsche.github.io)

## License

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
