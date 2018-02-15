# Open Exercise

Create and workout to exercise routines!

## Disclaimer

This application is currently very ugly, under development, insecure, and barely usable. In other words, if you're looking for a stable exercise management app, check back later. Sorry!

Right now, the creation of this application is a way for [me](https://github.com/jeffmaher) and some friends to practice our visual design and coding skills. This is also why some parts of the design and code may be rough...we're doing some learning as we go. Maybe someday this will be awesome, but maybe not. We'll remove this disclaimer if things change and this is _actually_ a production worthy app.

## Purpose

Open Exercise is an application designed to manage and workout to exercise routines. Basically, an admin can login to the app, add exercises (pictures and instructions), and group exercises into routines. A non-admin user can choose from routines and then step through the exercises during their workout.

## Structure

Stuff is divided across three repositories:

- [**open_exercise**](https://github.com/jeffmaher/open_exercise) (this): Application design documents and other high-level materials.
- [**open_exercise_api**](https://github.com/jeffmaher/open_exercise_api): Source code for the REST API and data layer. 
- [**open_exercise_ui**](https://github.com/jeffmaher/open_exercise_ui): Source code for the user interface.

### This Repo

Currently, the only file of note is a Sketch design file, `open_exercise.sketch`. Within this file, there are several Sketch Pages:

- **Application**: Visual designs for the application.
- **Common**: Sketch templates specific to Open Exercise components for mockups.
- **Sketch Wireframing Kit - \***: Symbol library. (I'm gonna remove this now that I know how to actually import Sketch Symbol Libraries)