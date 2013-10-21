Demo app of Growth Push iOS SDK
===================

Blank view app integrated Growth Push iOS SDK. [GrowthPush](https://growthpush.com/) is push notification and anaylysis platform.

## Notes

1. You cannot get device token for push notification in simulator. You need a real device to test push notification.
2. To get the device token for push notification in device, provisioning profile that does not use the wild card is required.
3. The push notification configuration of provisioning profile must be enabled.

## Customize application ID

You can change AppDelegate's following statement to your application id and secret.

```objc
[EasyGrowthPush setApplicationId:xxxxxxxx secret:@"xxxxxxxx" environment:kGrowthPushEnvironment debug:YES];
```

## License

- Demo app itself is under MIT License.
- [Growth Push iOS SDK](https://github.com/SIROK/growthpush-ios): Apache License
- [AFNetworking](https://github.com/AFNetworking/AFNetworking): MIT license
