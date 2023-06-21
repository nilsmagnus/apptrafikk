urbanairship

```
PUT https://device-api.urbanairship.com/api/channels/d5e11afc-5ccd-4c6a-b696-f4bf57dcd72c HTTP/2.0

x-ua-app-key: W5ZnNFGdTbOZ0SM_V2sY4Q

accept: application/vnd.urbanairship+json; version=3;

content-type: application/json

accept-encoding: gzip;q=1.0, compress;q=0.5

content-length: 434

accept-language: en-GB,en;q=0.9

user-agent: (UALib 16.11.3; W5ZnNFGdTbOZ0SM_V2sY4Q)

authorization: Basic VzVabk5GR2RUYk9aMFNNX1Yyc1k0UTp1ZVBfQVNTMVFSMm1INGREbEdJS3Rn
```

```
{

    "channel": {

        "app_version": "4.9.0",

        "background": true,

        "carrier": "Telia N",

        "contact_id": "71a53839-64b6-4e64-b5be-df145fd78a72",

        "device_model": "iPhone14,4",

        "device_os": "16.5",

        "device_type": "ios",

        "ios": {},

        "is_activity": true,

        "locale_country": "NO",

        "locale_language": "en",

        "opt_in": false,

        "push_address": "6cd368677dbf8e1f37c23cd1f98c37abc93726e938837f9d9e9b3a57e981a764",

        "sdk_version": "16.11.3",

        "set_tags": false,

        "timezone": "Europe/Stockholm"

    }

}
```


## firebase logging

```
POST https://firebaselogging-pa.googleapis.com/v1/firelog/legacy/batchlog HTTP/2.0

accept: */*

content-type: application/x-protobuf

accept-encoding: gzip

content-length: 375

content-encoding: gzip

accept-language: en-GB,en;q=0.9

user-agent: datatransport/0.0.1 fllsupport/0.0.1 apple/

x-goog-api-key: AIzaSyB4G40IhwotnuD26vAV-0PAxOVr5zn1BCc
```

```
1 {

  1 {

    1: 15

    4 {

      3: 16

      4: 16.5

      5: 2407

      6: NO

      7 {

        13: 3185225148172036176

        }

      }

      8 {

        12: 1330523502

      }

      11: com.nordea.mobilebank.no

    }

  }

  2: 137

  3 {

    1: 1686685361937

    6 {

      1: 1

      7 {

        2 {

      }

      9 {

        13: 3185225148172036176

        }

      }

      10: 1:571393288604:ios:31b13383003ba0e0950059

      12: com.nordea.mobilebank.no

      16: 2

      18: 90500000

      21: 1

      22: 16.5

      24: 15.0

      25: 1

      26: 1

      28: 14C18-20C52

      29: 0

      30: 4

      31: apple-platform/ios apple-sdk/20C52 appstore/true deploy/swiftpm device/iPhone14,4 fire-abt/9.5.0 fire-install/9.5.0 fire-ios/9.5.0 fire-rc/9.5.0 firebase-crashlytics/9.5.0 os-version/16.5 xcode/14C18

      33: 1

      36: 1

    }

    15: 14400

    17: 1990292015

  }

  4: 1686685362099

  8: 1990292178

}
```