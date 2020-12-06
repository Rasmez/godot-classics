# Contributing

## 📋 Pull Request Checklist

Before sending your pull requests, make sure you followed this list.

- Read [contributing guidelines (this file)](CONTRIBUTING.md).
- Read [Code of Conduct](CODE_OF_CONDUCT.md).
- Check if your changes are consistent with the [guidelines](https://github.com/Rasmez/godot-classics/master/CONTRIBUTING.md#general-guidelines-and-philosophy-for-contribution).
- Changes are consistent with the [Coding Style](https://github.com/Rasmez/godot-classics/master/CONTRIBUTING.md#gdscritpt-coding-style).
- Changes in the graphics/audio must be consistent with the [Art Style](https://github.com/Rasmez/godot-classics/master/CONTRIBUTING.md#art-style).
- Follow the [Pull Request Process](https://github.com/Rasmez/godot-classics/master/CONTRIBUTING.md#pull-request-process).

## General guidelines and philosophy for contribution

*   Include tests when you contribute new features, as they help to a)
    prove that your code works correctly, and b) guard against future breaking
    changes.
    
*   Bug fixes also generally require a lot of tests, because the presence of bugs
    usually indicates insufficient test coverage, so please, test your code.
    
*   When you contribute a new feature to this project, the maintenance burden is
    (by default) transferred to me. This means that the benefit
    of the contribution must be compared against the cost of maintaining the
    feature.

## How to become a contributor and submit your changes

### Contributing code 🖥

If you have improvements to this project, send your pull requests! For those
just getting started, Github has a
[how to](https://help.github.com/articles/using-pull-requests/).

I'll review your pull requests. Once the pull requests are approved and pass 
some checks, I'll will apply the `ready to pull` label to your changes. 
This means that i'm working on getting your pull request submitted to my internal/local repository. 
After the change has been submitted and tested internally, your pull request will be merged
automatically on GitHub.

If you want to contribute, start working through the project codebase,
navigate to the
[Github "issues" tab](https://github.com/Rasmez/godot-classics/issues) and start
looking through interesting issues. If you are not sure of where to start, then
start by trying one of the smaller/easier issues here i.e.
[issues with the "good first issue" label](https://github.com/Rasmez/godot-classics/labels/good%20first%20issue)
and then take a look at the
[issues with the "help wanted" label](https://github.com/Rasmez/godot-classics/labels/help%20wanted).
These are issues that we believe are particularly well suited for outside
contributions, often because we probably won't get to them right now. If you
decide to start on an issue, leave a comment so that other people know that
you're working on it. If you want to help out, but not alone, use the issue
comment thread to coordinate.

### Contributing 🖼graphical or 🎶audio assets 

If you want to submit or help with graphics or audio material for this project, send your pull requests! 
with more or less the same guidelines for the code contribution, with some caviats:
 
Your issue/pull request must have the label "audio/graphic" on it, if the pull request it's a about an open
issue, it must have the "help wanted" label applied too.

## GDScript Coding Style

You can read the full GDscript coding style guide [here](https://docs.godotengine.org/en/stable/getting_started/scripting/gdscript/gdscript_styleguide.html)

## Art Style

Stick to a minimalistic aesthethic, more or less following the game art style guidelines from GDQuest, you can read the full guide [here](https://www.gdquest.com/docs/guidelines/style-guides/game-art/), you can also try to emulate the art already present in the project to the best of your ability.

In the audio section, I'm trying to somewhat follow a modernized version of chiptunes, I'll post a guideline here when the sound direction is fully fledged.

### Formats for art contributions:

🖼 .PNG with Alpha Channel or .SVG format is used for: Sprites, Sprite sheets, Concept Art, Tiles, Tilesets, Backgrounds, Textures (for shaders), Particle effecs, and varius other components, specifications of size, color depth and pallets are not determined yet.

🎶 .OGG Stereo @192 kpbs format is used for: Sound Effects, loops, background tracks or any other audio-related asset.

## ⬆️ Pull Request Process

1. Ensure that your code/asset works with the most recent version of the project, run at least 2 test.
2. Update the README.md and CHANGELOG.md files with details of changes you made, this includes new environment 
   variables, change to the interface, fixed bugs, new features added, etc.
3. Increase the version numbers in any examples files and the README.md to the new version that this
   Pull Request would represent. The versioning scheme we use is [SemVer](http://semver.org/).
4. Wait for your pull request to be merge, this can take a while because I'm only one person and i'm only work on the project in my spare time (wich is not unlimited by no strech of the imagination).

## 🐞 Bug Report Process

1. Check if really the issue that you having is indeed a bug, tell tell signs are: is reproduceable, it's crearly not intentional, and can be or is, gamebreaker/crasher.
2. Gather as much information as possible about the issue (Specs of your device and O.S, how to reproduce the bug, etc)
3. Proceed to the "Issues" tab on this repository, check if your problem it's not listed there, then click on "create an issue" or the "New Issue" botton
4. Choose "Bug Report" and fill the form with the corresponding data (needs to be in understandable English, Spanish, French or Italian, don't know anymore languages, sorry).
5. Press "Submit the issue".
6. Have patience and wait, the process of bugfixing can be very hard and I'm alone in this basically.

## 💡 Feature request Process

1. Check the README, Project boards and the other documentation to see if your feature is planned or already implemented.
2. Analyze the cost (in man/hours) or the skill required to implement your idea/feature.
3. Gather as much information as possible about the request (essays, notes, pictures, diagrams, doodles, videos, code, etc)
4. Proceed to the "Issues" tab and create a new issue
5. Pock the "Feature request" option there.
6. Fill the form with your idea/request (needs to be in understandable English, Spanish, French or Italian, don't know anymore languages, sorry).
7. Press "Submit the issue".
8. Have patience, with a little bit of luck, I'll add your idea to the project board and tag your feature request with the corresponding labels, eventually your feature will be implemented.
