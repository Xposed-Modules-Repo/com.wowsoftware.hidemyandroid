# HideMyAndroid

![HideMyAndroid Thumbnail](images/thumbnail.png)

English | [简体中文](README.zh-CN.md)

## Support/Discussion

[XDA Thread](https://xdaforums.com/t/app-xposed-9-15-hidemyandroid-advanced-privacy-masking.4781780/)

HideMyAndroid is a privacy-focused Android module built to reduce app tracking and device fingerprinting through profile-based masking/spoofing.

Official Website: https://www.hidemyandroid.com  
Web App / Dashboard: https://app.hidemyandroid.com

## Requirements

- Android 9.0+ (Pie or newer)
- Rooted Android device
- Properly working Xposed/LSPosed environment
- If you are not familiar with Xposed modules, this project may not be suitable for your setup.

## How It Works

When a target app requests identifiers or environment signals, HideMyAndroid intercepts the request and returns configured spoofed values based on your selected profile.

## Feature List

- Hide Device Identifiers (Android ID, GAID, GSF ID, Widevine DRM ID, IMEI, Serial, ...)
- Hide VPN Connection
- Hide Wi-Fi Information (NAME/MAC)
- Spoof Nearby Wi-Fi Networks
- Block LAN Scan
- Hide Developer Mode
- Spoof Play Store Installation
- Spoof Timezone Based on IP
- Spoof Region Based on IP
- Spoof GPS Location Based on IP
- Spoof App Identity
- Isolated Account Environment
- Virtual Gmail Accounts Per Profile
- Hide Installed Applications
- Realistic Sensor Data
- Profile-Based System
- Backup & Restore app's data
- Per-Profile Proxy (each profile can use its own independent proxy configuration)
- Hide Suspicious Keyboards
- Virtual Default Keyboard Value
- Many More Features

## Free vs Premium

| Features                                          | Freemium | Premium (Subscription) |
| ------------------------------------------------- | :------: | :--------------------: |
| Hide device identifiers (partial/full by plan)    |    ✅    |           ✅           |
| Backup & restore app data                         |    ✅    |           ✅           |
| Hide active VPN from apps                         |    ✅    |           ✅           |
| Spoof Wi-Fi SSID/BSSID                            |    ✅    |           ✅           |
| Hide Developer Options state                      |    ✅    |           ✅           |
| Spoof installer as Google Play                    |    ✅    |           ✅           |
| Hide installed apps list                          |    ✅    |           ✅           |
| Hide suspicious keyboards from enabled keyboard lists |    ✅    |           ✅           |
| Virtual default keyboard value spoofing           |    ✅    |           ✅           |
| Spoof nearby Wi-Fi networks                       |          |           ✅           |
| Block private LAN scan behavior                   |          |           ✅           |
| Spoof timezone by geo                             |          |           ✅           |
| Spoof locale/region by geo                        |          |           ✅           |
| Spoof GPS by geo                                  |          |           ✅           |
| Spoof app identity                                |          |           ✅           |
| Virtual Gmail accounts per profile                |          |           ✅           |
| Virtual account isolation per profile             |          |           ✅           |
| Realistic sensor behavior                         |          |           ✅           |

## Important Notice

System-level modification always carries risk.  
Please back up your ROM and important data before use.

## Disclaimer

Use at your own risk.  
By installing or using HideMyAndroid, you are solely responsible for how you use it.  
The developers are not responsible for misuse, violations of laws/platform policies, account penalties, data loss, instability, or bootloops.

## Ongoing Updates

HideMyAndroid is actively maintained with continuous feature and stability updates.

## Feature Requests

Feature requests are welcome.  
If you need a specific capability, share your use case and we will prioritize based on community demand.

