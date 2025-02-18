# Expo Go Unsupported Module Error

This repository demonstrates an uncommon error encountered in Expo CLI when using modules or functionalities not supported by the Expo Go runtime environment.  The example showcases a scenario where attempting to use a non-Expo compatible native module leads to an error in Expo Go, while the same code functions correctly when built as a standalone app.

## How to Reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Try to run the app using `expo start` and test it on Expo Go.  You'll encounter the error.
4. To see the solution, refer to `expoGoBugSolution.js` and follow the instructions to adapt the code for Expo Go compatibility.

## Solution

The solution involves replacing non-Expo Go compatible modules or approaches with their Expo counterparts (if available) or modifying the code to work within Expo Go's limitations.  The solution file shows the adapted code with proper Expo module integration.