# Expo CLI Android Build Failure: Gradle Plugin Version Conflicts

This repository demonstrates a common, yet difficult-to-diagnose, error encountered when building Android apps with the Expo CLI.  The problem stems from inconsistencies or misconfigurations within the Gradle build system, specifically related to the Android Gradle Plugin version.

The `bug.js` file shows a (simulated) Expo project structure and a build process that triggers the Gradle conflict. The `bugSolution.js` file offers a solution by specifying a compatible Gradle plugin version or resolving dependency conflicts. 

This issue often presents as cryptic error messages, lacking clear guidance on the root cause. The goal is to aid developers in swiftly identifying and rectifying such build failures.

## Reproduction Steps
1. Clone the repository.
2. Navigate to the `android` directory.
3. Attempt to build the Android application (e.g., `./gradlew assembleRelease`).
4. Observe the Gradle build failure. 
5. Review the solution in `bugSolution.js` to understand how to resolve the conflict.