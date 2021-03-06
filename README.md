# Keyboard On, Keyboard Off
A simple Alfred workflow to turn the built-in Mac laptop keyboard on or off.

## But why?
I prefer mechanical keyboards over the scissor-switch design of Mac laptops, but when using a 60% keyboard and placing it over the built-in keyboard, it would activate keys on the laptop as I would type. This workflow allows me to easily switch the built-in keyboard on or off if I'm placing a keyboard on top of my laptop.

## Requirements
Keyboard On, Keyboard Off requires Alfred v2 with PowerPack. Download Alfred at http://www.alfredapp.com/

It has not been tested with Alfred v1.

## Installation:
Double click the .alfredworkflow file or drag it to the Workflows screen in Alfred Preferences.

## Usage:
1. Run the command "kb"
2. Give it an "on" or "off" argument.
3. When running "kb off" make sure your external keyboard is **unplugged** or it could cause a system crash as OSX will try to turn off BOTH keyboards!
3. You may be prompted to enter your administrator password because this runs a sudo command.

## Tweaking
By default, Keyboard On, Keyboard Off runs a Terminal "say" command to inform you of the state of your built-in keyboard. If this bothers you, simply double click the "Run Script" command in the workflow and delete the "say" lines.

## In action...
![Keyboard On, Keyboard Off in action](https://cloud.githubusercontent.com/assets/89553/11122851/9ad7f866-8922-11e5-8153-e6f35f9e44ac.jpg)
