# Get your app to the store faster...use this seed...

Steps :

1. Clone 
2. Create a new Error Tracking project : https://sentry.io/
3. Find/Replace com.simpleproductionsinc.ion2seed with your app identifier
4. Find/Replace ion2Seed with your app name
5. Update remote & push changes
6. Fastlane

  * Update the Fastfile under ~/Fastlane & ~/Appfile to match your config
  * Run the below script to create a new app in the Apple App Store
  
  ```
  fastlane produce
  ```
  * Generate Provisioning Profiles
    * Ad-Hoc
 
    ```
    sigh --adhoc
    ```
    
    * App Store
    
    ```
    sigh
    ```
   
    
7. Add platforms (ionic platform add ios && ionic platform add android)
8. Splash Screen & App Icon

  * Update app icon (1024x1024) under ~/resources & run npm run resources
  * Update splash screen (2208x2208) under ~/resources & run npm run resources
  * Make sure you have padding around the image to allow for cropping 
