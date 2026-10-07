# Scale Worker Capture

Native Android recreation of the public worker capture workflow from the shaikali-c/worker project.

## Build on GitHub
The repository includes `.github/workflows/build-apk.yml`. After uploading this project to GitHub, open **Actions → Build APK → Run workflow**. When the job finishes, download the **ScaleWorker-debug-apk** artifact and extract `app-debug.apk`.

The workflow builds with Java 17 and Gradle 8.9 on a GitHub-hosted runner; no Android Studio is required for the cloud build.
