# Jquery-navScrollFX
 A simple jquery plugin to retract or show your navbar when scrolling

## Usage

Simply import it on your project, per default, the navbar height is 50px so please edit the `navbar_height` variable to adjust it to your navbar. 

If you need to lock the navbar and not retract you can do it by simple adding a class you can set a class name in `navbar_lockclass` which will be added when needed, this class is here so you can give it to your navbar to lock it.

The script can also make the navbar togglable by hovering an element on your page, if you wish to use that please give its class / id name in `navbar_hovertrigger` like `#elt` or `.elt`.

## Note

Obviously the script target per default a class called `navbar` but if you wish to change the target (it must be the parent of your entire navbar) you can change `navbar_target`.
