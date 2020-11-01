# agenda
A daily agenda app using React Native.

![](agenda.gif)

# Development Progress

## **Current/Planned Features**

* 7 day agenda
* Customizable events (name, location, colour, start/end time)
* To Do list per event (e.g. class homework to complete)
* Notes per event (e.g. notes from class)


## **Working Features**

* Scrolling 7 day week and 24 hours per day
* Events display nicely and show their detail when clicked on
* Horizontal line to display current time is functional


## **Features in Development**

* Custom events cannot yet be added by user - need to create a menu where details can be entered
* Event details are currently hard coded and shared by all events - need to include details in event state
* To Do list exists visually but functionality hasn't been programmed yet
* List of notes is displayed in event detail but functionality hasn't been programmed yet


## **Known Issues**

* Small graphical error in top left/right corner when scrolling between dates, this is caused by the drop shadow effect on the View that contains the day of the week - possibly an issue only on Android due to the use of the elevation property


## **Code Clean-up**

* There are a few sections of code that I believe can be rewritten to use fewer lines or that can simply be done better. 
* I've learnt more JavaScript since starting this project and now feel more capable about improving these sections.
