# SmartDrivingTrainer (SDT)
## A real time driving tutor

Making India ready for the decade of autonomy


## Features

- Check if a person is following the traffic rules.
- Observe how the user reacts to the road signs while driving.
- Provides real-time lane line detection.
- Provides real-time drowsiness detection.
- Detect road signs and obstacles and guide appropriately.
- Make sure the user’s vehicle maintains safe distance from others.
- Log the scores.

![Workflow](https://github.com/DevilAeron/SmartDrivingTrainer/blob/main/Themes/workflow.jpeg?raw=true)


## Tech
- [React Native](https://reactnative.dev/)
- [Flask](https://flask.palletsprojects.com/en/2.0.x/)
- [Firebase](https://firebase.google.com/)
- [OpenCV](https://opencv.org/)
- [Python](https://www.python.org/)
- [JavaScript](https://www.javascript.com/)


## Installation

Create an react native CLI application named SDT
```sh
npx react-native init SDT
```

Modify the files in Android folder of your application with the given files, rest of the code can be copied without any modifications.

Install the dependencies and node_modules mentioned in requirements.txt.
Setup a firebase project and replace the configuration keys.

Navigate to your node_modules/react-native/Libraries/Core/Timers/JSTimers.js file.
Look for the variable MAX_TIMER_DURATION_MS
Change its value to 10000 * 1000
Save the changes (with auto format turned off) and re-build your app.

Finally -
```sh
npx react-native run-android
```

## Working and UI


## License

MIT
