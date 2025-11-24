OV N-Land Network - Android project prepared for GitHub Actions CI build

This package contains a minimal Android app module and a GitHub Actions workflow that
installs Gradle on the runner (no local Gradle required) and builds a debug APK.
Upload the entire folder to a new GitHub repository (use Upload files in the web UI),
then open Actions → run the workflow. The APK artifact will be available after the run.
