# DriveRage



## **Description**
This is a racing game built in Unity with C#. The game tracks the lap times of players, displaying the time in minutes, seconds, and milliseconds format. When a player completes a lap, the timer resets for the next lap.

## **Features**
1. Lap completion and half lap triggers.
2. Dynamic display of lap time (in minutes, seconds, and milliseconds).
3. Automatic resetting of lap time on lap completion.

## **Script Details**
The provided script, `LapComplete`, is responsible for tracking the player's progress throughout the race and updating the lap time display.

### **Script Variables:**
- `LapCompleteTrig`: A trigger for lap completion.
- `HalfLapTrig`: A trigger for halfway point of the lap.
- `MinuteDisplay`, `SecondDisplay`, `MilliDisplay`: UI elements to display lap time.
- `LapTimeBox`: Box to display the overall lap time.

### **Method Details:**
- `OnTriggerEnter()`: This method is invoked when the player's vehicle enters the lap completion trigger. It updates the lap time display and resets the lap timer.

## **How to Setup**
1. Ensure you have Unity installed.
2. Clone or download this game repository.
3. Open Unity and import the project.
4. Drag the `LapComplete` script onto the desired game object, usually the player's vehicle.
5. Assign the appropriate game objects to the script's public variables in the Unity Editor.

## **Usage**
1. Start the game in Unity.
2. Drive the vehicle around the track.
3. On crossing the `LapCompleteTrig`, your lap time will be displayed.
4. The timer will reset for the next lap.

## **Dependencies**
- Unity 3D
- UnityEngine.UI for UI components.

## **Contribution**
To contribute to this project, please fork the repository and submit a pull request with your changes.

## **License**
This project is open-sourced under the MIT license.



---

