This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

Below you will find some information on how to perform common tasks.<br>
You can find the most recent version of this guide [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).

## Table of Contents

- [Available Scripts](#available-scripts)
  - [npm start](#npm-start)
  - [npm test](#npm-test)
  - [npm run build](#npm-run-build)
  - [npm run eject](#npm-run-eject)


## Updating to New Releases

Create React App is divided into two packages:

* `create-react-app` is a global command-line utility that you use to create new projects.
* `react-scripts` is a development dependency in the generated projects (including this one).

You almost never need to update `create-react-app` itself: it delegates all the setup to `react-scripts`.

When you run `create-react-app`, it always creates the project with the latest version of `react-scripts` so you’ll get all the new features and improvements in newly created apps automatically.

To update an existing project to a new version of `react-scripts`, [open the changelog](https://github.com/facebookincubator/create-react-app/blob/master/CHANGELOG.md), find the version you’re currently on (check `package.json` in this folder if you’re not sure), and apply the migration instructions for the newer versions.

In most cases bumping the `react-scripts` version in `package.json` and running `npm install` in this folder should be enough, but it’s good to consult the [changelog](https://github.com/facebookincubator/create-react-app/blob/master/CHANGELOG.md) for potential breaking changes.

We commit to keeping the breaking changes minimal so you can upgrade `react-scripts` painlessly.

## About

This app was created as an interview demo for Quick Base. The app is an admin control of a product that allows builders to set up their own input form (e.g. how Google Forms, Survey Monkey, or Quick Base allow you to build a survey with a multiple choice field.) The app creates a control to modify the properties of a multiple choice field. 

# How to install
1. Clone or download repo interview-app.
2. Download and save file to local folder.
3. On Command line, locate folder and run git npm start.


# How to use

## Label
In the "Label" field, type in the label you want for the builder. Clicking "Save Changes" at the bottom of the app will save the inputted label. 

## Type
Check the box if a value is required to be added to "Choices".

## Default value
A value in the "Default Value" field will show after clicking "Save Changes", which will save the value inputted into "Add Choice" to "Default Value".

## Add Choice
An input into "Add Choice" will be saved into the dropdown menu after clicking "Add Choice" button. The input field will clear when clicking "Add Choice" button. 

## Choices
This is a chronologically-ordered dropdown menu of choices saved from "Add choice" field, from which users can choose.

## Save Changes
The "Save Changes" button saves the input in "Add choice" field both to "Default value" field and "Choices" dropdown.

## Cancel
The "Cancel" button erases all inputs in fields. 

