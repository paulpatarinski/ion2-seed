# Get your app to the store faster...use this seed...

Steps :

1. Clone 
2. Create a new Error Tracking project : https://sentry.io/
3. Update Raven.config in app.module.ts to point to the new dsn
4. Find/Replace ion2Seed with your app name
5. Add platforms (ionic platform add ios && ionic platform add android)
5. Update app icon (1024x1024) under ~/resources & run npm run resources6
6. Update remote & push changes
