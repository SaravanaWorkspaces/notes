# Android

  Android is an linux-based operating system for devices like smartphones, tablets and tv etc.

### App components

  App components are basic building blocks of android app. 

  - Activity
  - Service
  - Broadcast receiver
  - Content provider

  Any app can have at least any one of the app components. App components are the entry points of an app.
  Each component is a distinct in operational and life cycle.

#### Activity

  It's a single screen, And is an entry point for interacting with user. (I.e: Email app - Single screen to display list of mails)
  The activities work together to give cohesive experience. Different apps can start any one of the activities. 

##### Activity lifecycle

  Activity class has different callbacks to be invoked to denote the state change of an activity

    - onCreate 
      - Activity enters into created state, Called only once in complete life cycle
      - onCreate(savedInstanceState: Bundle?) 

    - onStart
      - Callback will be invoked, when activity enters into started state
      - State makes activity visible to the user, And prepares activity to be interactive

    - onResume
      - Once activity enters into resumed state, Activity comes to foreground, User can able to interact with the activity,
        activity stays in this state until, any other interruption happens to take away the focus of the activity
      
    - onPause
      - It means user leaving the activity to background,
        - Some interruption like call, moving to next activity and turn-off screen
        - Multi-window mobile apps, while focusing other apps
        - While display dialog on the activity
      - It can be used to pause certain operations, that don't want to continue when activity not in foreground
      - Releasing resources like cancelling network call, or managing gps fetching to save battery usage

    - onStop
        - When activity no longer visible to the user, It enters into stopped state
        
    - onDestroy
        - Method will be called before activity destroyed
        - This method will be called either 
          - calling finish() 
          - System destroying activity for temporary for config change




