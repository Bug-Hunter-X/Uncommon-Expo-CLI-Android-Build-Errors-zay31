# Uncommon Expo CLI Android Build Errors

This repository demonstrates troubleshooting for uncommon errors encountered during the Android build process using the Expo CLI. These errors are often difficult to diagnose because they stem from subtle issues within the automatically managed `android` folder.  The `bug.js` file contains code that might trigger the error while `bugSolution.js` shows a solution. The focus is on issues that go beyond basic dependency resolution, configuration problems, and Gradle conflicts.   

## Error Scenarios

- Missing or Corrupted `android/gradlew` file.
- Conflicts between Expo CLI version and Android build tools.
- Unclear or cryptic error messages from the Gradle build system. 

## Setup

1. Clone the repo.
2. Navigate to the project directory.
3. Install dependencies (if necessary). 
4.  Follow instructions within the file to reproduce and fix the issue. 

## Disclaimer

Expo's build system is intricate. This repo focuses on specific, unusual cases.  Standard debugging practices should be attempted first (check logs, ensure correct configurations, etc.).