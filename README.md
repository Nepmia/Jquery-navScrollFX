# N4 ScrollFX
 A simple jquery plugin to retract or show your navbar when scrolling

## Usage

Simply import it on your project, per default, the navbar height is 50px so please edit the `navbar_height` variable to adjust it to your navbar's height. 

If you need to lock the navbar from retracting you can do it by simply adding a class to it. This class can be set in `navbar_lockclass`.

The script can also make the navbar togglable by hovering an element on your page, if you wish to use that please give its class / id name in `navbar_hovertrigger` like `#elt` or `.elt`.

## Note

Obviously the script target per default a class called `navbar` but if you wish to change the target (it must be the parent of your entire navbar) you can change `navbar_target`.


## More specs about parameters

* `navbar_height` must be an INT
* `navbar_lockclass` must be a str, it can only be a str and will be a class, it cannot be changed to id by adding `#` and it doesn't need a `.` before the classname
* `navbar_hoverTrigger` and `navbar_target` must be a str, can be a class or an id using the proper selector (`#` or `.`)

