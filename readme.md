# Modifier Classes Example Project

This is an example site meant to explore how if we modify Willow components with a single class with a modifier appended, or if we want to use multiple classes.

## Setup

1. `git pull` the latest from the [Unum Theme](https://github.com/unumux/theme-unum-default)
1. From the theme's directory in terminal run `npm link`
1. `git pull` the latest from the [Willow Repo](https://github.com/unumux/willow)
1. `git checkout modifier-rework` - this is the branch in Willow where this scratch work was done.
    - _It is important that you do not switch to another branch on Willow while running UX in this project (step 8) or else it will not pull the correct styling._
1. `npm link` after you are on the correct branch
1. In a new terminal window, `git clone` this repo [modifier-classes]()
1. From this repo's directory in terminal run the following:
   1. `npm link @unumux/theme-unum-default`
   1. `cd node_modules/@unumux/theme-unum-default`
   1. `npm link @unumux/willow`
1. `cd ../../../` and run `ux` from the modifier-classes project

## Examples to Review

Check out the HTML in this repo's code to see the components in action, and then check out the code on the default-visibility branch in Willow to see how it works behind the scenes.

- Button
- Primary Nav
- Global Alert