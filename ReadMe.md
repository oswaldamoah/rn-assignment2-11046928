# rn-assignment2-ID-YourStudentID

## Description

This is the second assignment for the DCIT202 Mobile Application Development course. The task involved creating a new React Native project using Expo CLI and making specific changes to the `App.js` file. The modifications included changing the background color of the `View` component, editing the `Text` component to display "My name is Oswald Amoah" with the name "Oswald Amoah" in bold, and increasing the font size of the text to 24.

## Task Requirements

- Create a new React Native blank template project using Expo CLI.
- In the `App.js` file:
  - Change the background color of the `View` component.
  - Edit the `Text` component to display "My name is Oswald Amoah".
  - Increase the font size of the text to 24.
  - Make the name "Oswald Amoah" bold.
- Create a repository named `rn-assignment2-ID` (e.g., `rn-assignment2-ID-1129884`).
- Commit frequently.
- Add a README file with a screenshot of your application, a description of the task, and your student ID.

## Screenshot

![Screenshot of the Application](screenshot.png)

## Student ID

YourStudentID

## App.js

```javascript
import React from 'react';
import { StyleSheet, Text, View } from 'react-native';

export default function App() {
  return (
    <View style={styles.container}>
      <Text style={styles.text}>
        My name is <Text style={styles.boldText}>Oswald Amoah</Text>
      </Text>
    </View>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: '#ADD8E6',  // Change to your desired background color
    alignItems: 'center',
    justifyContent: 'center',
  },
  text: {
    fontSize: 24,
  },
  boldText: {
    fontWeight: 'bold',
  },
});
