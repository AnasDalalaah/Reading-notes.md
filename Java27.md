 #Java27: - Intents, Activities, and SharedPreferences

## [Android Tasks and the Back Stack](https://developer.android.com/guide/components/activities/tasks-and-back-stack)

- **A task** is a collection of activities that users interact with when performing a certain job. 

- The activities are arranged in a stack—the back stack—in the order in which each activity is opened.

- For example,
 an email app might have one activity to show a list of new messages.
  When the user selects a message, a new activity opens to view that message.
   This new activity is added to the back stack.
    If the user presses the Back button, that new activity is finished and popped off the stack.


When apps are running simultaneously in a multi-windowed environment, supported in Android 7.0 (API level 24) and higher,
 the system manages tasks separately for each window; each window may have multiple tasks.


When the current activity starts another, the new activity is pushed on the top of the stack and takes focus.

When apps are running simultaneously in a multi-windowed environment, supported in Android 7.0 (API level 24) and higher,
 the system manages tasks separately for each window; each window may have multiple tasks.


When the current activity starts another, the new activity is pushed on the top of the stack and takes focus.
 The previous activity remains in the stack, but is stopped. When an activity stops, the system retains the current state of its user interface.
  When the user presses the Back button, the current activity is popped from the top of the stack ( destroyed) and the previous activity resumes (the previous state of its UI is restored).
   


### `<activity>` attributes you can use are:
 - `taskAffinity` - `launchMode` - `allowTaskReparenting` - `clearTaskOnLaunch` - `alwaysRetainTaskState` - `finishOnTaskLaunch`
 #### And the principal intent flags you can use are:
 - `FLAG_ACTIVITY_NEW_TASK` - `FLAG_ACTIVITY_CLEAR_TOP` - `FLAG_ACTIVITY_SINGLE_TOP` 


### Defining launch modes,ways :

1. **Using the manifest file**
When you declare an activity in your manifest file, you can specify how the activity should associate with tasks when it starts.

2. **Using Intent flags**
When you call startActivity(), you can include a flag in the Intent that declares how (or whether) the new activity should associate with the current task.

## [Android SharedPreferences](https://developer.android.com/training/data-storage/shared-preferences) 
- **Shared Preferences:** Is to Save data as key-value pairs.
 ### You can create a new shared preference file or access an existing one by calling one of these methods: 
- **getSharedPreferences()** — Use this if you need multiple shared preference files identified by name, which you specify with the first parameter.
 You can call this from any Context in your app.

