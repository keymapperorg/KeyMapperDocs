--8<-- "preamble.md"

In this tutorial we will make a simple key map to make the volume down key toggle the flashlight on the lockscreen.

## Add a trigger

Tap the :octicons-plus-16: icon on the home screen to create a new key map.

We will use the volume down key as the trigger for the key map.

Tap 'Record trigger' and then press the volume down key. It will appear in the list.

Tap the 'Long press' radio button. This will make sure that only long presses of the volume button will toggle the flashlight.

## Add an action

Tap the actions tab. Now we need to make the volume button turn on the flashlight.

Tap 'Add action' to bring up the list of possible actions. Choose 'Toggle flashlight' in the list.

If you're happy with the default settings, press 'Done'.

## Add a constraint

Tap the constraints tab. Now we need to make sure that the key map only runs when we are on the lockscreen.

Tap 'Add constraint' to bring up the list of possible constraints. Choose 'Lockscreen is showing' in the list.

## Now let's test...

Now we can see if the key map is running. Tap 'Done' to complete the key map and return to the home screen.

Make sure that the status indicator at the top of the home screen is green and says 'Running'.

You should also see your key map in the list.

Now, lock your device, and with the screen on, long press volume down. Now you can toggle the flashlight on the lockscreen!

You can't use this key map while the screen is off. To make it work with the screen off, you need to use [an experimental feature]().

!!! discord "Want to ask for help?"
    If you've already tried troubleshooting and the tutorials aren't enough, come and ask for help in our [support server.](http://keymapper.club)