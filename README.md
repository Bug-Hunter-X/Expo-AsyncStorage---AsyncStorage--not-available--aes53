# Expo AsyncStorage - "AsyncStorage: not available" Error

This repository demonstrates a common issue encountered when using AsyncStorage in Expo: the `AsyncStorage: not available` error.  This error typically arises from inconsistencies between the AsyncStorage implementation and the environment (simulator vs. device).  The solution involves careful setup and potentially using a different storage mechanism.

## Bug Description

The `bug.js` file shows the code causing the error.  Even with seemingly correct AsyncStorage usage, the error persists in certain environments.

## Solution

The `bugSolution.js` file offers potential solutions. This includes double-checking AsyncStorage setup, using alternative storage solutions like MMKV or AsyncStorage alternative for specific platforms if needed.

## How to Reproduce

1. Clone this repository.
2. Run `npm install`
3. Try to run the `bug.js` file in different Expo environments(simulators and physical devices) and observe the error. 
4. Then run `bugSolution.js` to see the fix.

