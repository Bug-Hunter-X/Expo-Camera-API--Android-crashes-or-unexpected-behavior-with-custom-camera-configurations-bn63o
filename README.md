# Expo Camera Bug: Android Crashes with Custom Configurations

This repository demonstrates a bug encountered when using the Expo Camera API with custom camera configurations on Android.  The issue manifests as unexpected crashes or erratic behavior when specific camera options are set (especially focus and zoom).  The problem is exacerbated by a lack of informative error messages from Expo, making debugging challenging.

The `bug.js` file contains code that reproduces the problem. `bugSolution.js` offers a potential workaround, although a complete fix requires more investigation into the root cause within the Expo Camera API or underlying Android Camera implementation.

**To reproduce:**
1. Clone this repository.
2. Run `npm install`.
3. Run the app on an Android emulator or device.
4. Observe the camera behavior (it may crash or display unexpected results).

**Note:**  This bug is primarily observed on Android.  iOS may exhibit different behaviors.

Feel free to contribute with improved solutions or further insights!