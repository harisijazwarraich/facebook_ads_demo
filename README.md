### Initialization:

For testing purposes you need to obtain the hashed ID of your testing device. To obtain the hashed ID: 

1. Call `FacebookAudienceNetwork.init()` during app initialization.
2. Place the `FacebookBannerAd` widget in your app.
3. Run the app.

The hased id will be in printed to the logcat. Paste that onto the `testingId` parameter.

```dart
FacebookAudienceNetwork.init(
  testingId: "37b1da9d-b48c-4103-a393-2e095e734bd6", //optional
  iOSAdvertiserTrackingEnabled: true //default false
);
