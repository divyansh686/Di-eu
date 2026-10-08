# Liquid Glass Dock — GitHub Actions Android Project

## GitHub build

1. Create a new GitHub repository.
2. Upload the complete contents of this folder.
3. GitHub → **Actions** → **Build Android APK**.
4. Click **Run workflow**.
5. Open the completed workflow run.
6. Under **Artifacts**, download `liquid-glass-dock-debug-apk`.

## Important

This is a standalone sample app. To use it in your existing app:
- copy `liquid_glass_dock.xml`
- copy the two liquid-glass drawables
- copy `LiquidGlassDock.kt`
- replace the four sample icon drawables with your app's actual dock icons
- connect your existing click/navigation logic

GitHub Actions installs/uses Gradle for the workflow build.

The generated debug APK is signed with the standard debug key and is suitable for testing. For Play Store release builds, configure a release signing key and a release GitHub Actions workflow.
