# Synthesis Fork of Colyseus-Unity-SDK

**When updating this fork, in order to make your changes bubble up to games consuming this package, you must do the following in each:**

1. In the `manifest.json` file, remove the line for this package `"com.gosynthschool.io.colyseus.sdk": "https://github.com/gosynthschool/colyseus-unity-sdk.git#synthesis-changes",`.
2. Give unity editor focus and let it refresh packages.
3. In the `manifest.json` file, add the line you removed for this package in step 1 back.
4. Give unity editor focus and let it refresh packages.
5. You should see the `client` `packages-lock.json` file has updated with a new commit hash for this package.