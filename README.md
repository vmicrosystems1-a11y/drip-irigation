# Drip Irrigation 2 Flutter app

Upload all files to GitHub repository root, preserving folders. Workflow builds package `com.vmicrosystems.drip_irrigation2`. Verify this package is registered in Firebase Console Android app settings and regenerate firebase_options.dart if necessary. No google-services.json is required for explicit Flutter Firebase.initializeApp(options:...).

The dashboard uses Firebase `.info/serverTimeOffset` to render a clock every second; the database does NOT store a ticking HH:MM:SS value. Device online is calculated from a recent `lastSeen` heartbeat.
