# Get your app to the store faster...use this seed...

Steps :

1. Clone 
2. Create a new Error Tracking project : https://sentry.io/
3. Update Raven.config in app.module.ts to point to the new dsn
4. Find/Replace ion2Seed with your app name
5. Add platforms (ionic platform add ios && ionic platform add android)
6. Update app icon (1024x1024) under ~/resources & run npm run resources
7. Update splash screen (2208x2208) under ~/resources & run npm run resources
- Make sure you have padding around the image to allow for cropping
8. Update remote & push changes
