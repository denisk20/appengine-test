# Test case for https://github.com/gradle/gradle/issues/5468

1. Run `./gradlew appengineRun`
2. Wait for `INFO: Dev App Server is now running` line to appear
3. Click `CTRL+C`
4. Wait a 4-5 seconds for the "Java" task to disappear
5. Run `./gradlew appengineRun` again. Notice `Starting Daemon` line briefly appearing
