# Smart Construct — Build from an Android phone

1. Create a GitHub account or sign in.
2. Create a new repository named `SmartConstruct`.
3. Upload the contents of this project ZIP to the repository (not the ZIP file itself).
4. Open the repository's **Actions** tab.
5. Select **Build Smart Construct APK**.
6. Tap **Run workflow**.
7. Wait for the workflow to finish successfully.
8. Open the completed workflow run and download the **SmartConstruct-APK** artifact.
9. Extract the downloaded artifact and install `app-debug.apk` on your Android phone.

The workflow uses a GitHub-hosted runner to install Java/Gradle, compile the Android project, and upload the APK as a workflow artifact.
