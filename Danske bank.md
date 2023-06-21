## eum.danskebank.com

```
POST https://eum.danskebank.com/eumcollector/mobileMetrics?version=2 HTTP/1.1

Host: eum.danskebank.com

an: com.danskebank.mobilebank3no

Cookie: NSC_JObbjvshdyjtki1dvdjvekdkhzfrhdQ=14b5a3d9603f38afcba7f9189c071d99757e0bde07528e1ead7b83e2dd3f1ea58c0fd209

User-Agent: MobileBank%20NO/3812372 CFNetwork/1408.0.4 Darwin/22.5.0

Content-Encoding: gzip

adrum_request_config: 11

ADRUM_1: isMobile:true

mat: 1685646000000

di: D3757545-B048-4A77-BA4D-5C0D99B007A7

Content-Length: 325

Connection: keep-alive

osn: iOS

Accept-Language: en-GB,en;q=0.9

ky: EUM-AAB-KPU

ADRUM: isAjax:true

Accept: */*

Content-Type: application/json

Accept-Encoding: gzip, deflate, br

cap: s:1,f:1

gzip: false

bid: d34e4acff6ea37119abee463b447a68d
```

```
[

    {

        "ab": "bf250adfb9221a665083d4790da0f64d4183a0a0",

        "agv": "2022.3.0",

        "av": "2023.6",

        "ca": "Telia N",

        "cc": "6",

        "cct": "wifi",

        "cf": "825",

        "ct": "wifi",

        "ctt": "dct",

        "dmo": "iPhone14,4",

        "ds": "121943",

        "eid": "1a423e4a-4645-448f-8fa9-1955778f3fed",

        "et": 1686594098932,

        "eut": 922072259,

        "event": "Connection Transition",

        "hat": "React Native",

        "hav": "22.5.0",

        "mv": "3812372",

        "osv": "16.5",

        "pct": "cell",

        "sessionCounter": -1,

        "st": 1686594098932,

        "sut": 922072259,

        "tm": "435",

        "type": "system-event"

    }

]
```

## sentry
```
POST https://o1113344.ingest.sentry.io/api/6182271/envelope/ HTTP/2.0

accept: */*

content-type: application/x-sentry-envelope

content-length: 303

accept-language: en-GB,en;q=0.9

content-encoding: gzip

user-agent: sentry.cocoa

x-sentry-auth: Sentry sentry_version=7,sentry_client=sentry.cocoa/8.2.0,sentry_timestamp=1686334055,sentry_key=08fb79779ea24b2993110b85fee2369d

accept-encoding: gzip, deflate, br
```

```
{"sdk":{"name":"sentry.cocoa","version":"8.2.0"}}

{"type":"session","length":321}

{"errors":0,"status":"exited","started":"2023-06-09T18:06:30.389Z","did":"5F5D8E8E-7E8F-4DDF-8AFE-BE897985A7A4","duration":60.833364009857178,"sid":"17649B94-B41B-4BE8-AD08-6493B0B77732","attrs":{"release":"com.danskebank.mobilebank3no@2023.6+3812372","environment":"PROD"},"timestamp":"2023-06-09T18:07:31.222Z","seq":2}

```

## in.appcenter.ms

```
POST https://in.appcenter.ms/logs?api-version=1.0.0 HTTP/1.1

Host: in.appcenter.ms

ADRUM_1: isMobile:true

Accept: */*

App-Secret: 6d1ee742-7a1a-414b-8e1d-3dbc6f295d14

Accept-Language: en-GB,en;q=0.9

Accept-Encoding: gzip, deflate, br

Content-Type: application/json

Install-ID: 5B944379-3BCD-4E2F-81A5-E6E81FC767E4

User-Agent: MobileBank%20NO/3812372 CFNetwork/1408.0.4 Darwin/22.5.0

Connection: keep-alive

ADRUM: isAjax:true

Content-Length: 968
```

```
{

    "logs": [

        {

            "device": {

                "appBuild": "3812372",

                "appNamespace": "com.danskebank.mobilebank3no",

                "appVersion": "2023.6",

                "locale": "en_NO",

                "model": "iPhone14,4",

                "oemName": "Apple",

                "osBuild": "20F66",

                "osName": "iOS",

                "osVersion": "16.5",

                "screenSize": "2436x1125",

                "sdkName": "appcenter.ios",

                "sdkVersion": "4.4.3",

                "timeZoneOffset": 120,

                "wrapperSdkName": "appcenter.react-native",

                "wrapperSdkVersion": "4.4.5"

            },

            "sid": "6A95C718-5B8D-4AFD-938F-167EBA448B91",

            "timestamp": "2023-06-09T18:23:42.252Z",

            "type": "startSession"

        },

        {

            "device": {

                "appBuild": "3812372",

                "appNamespace": "com.danskebank.mobilebank3no",

                "appVersion": "2023.6",

                "locale": "en_NO",

                "model": "iPhone14,4",

                "oemName": "Apple",

                "osBuild": "20F66",

                "osName": "iOS",

                "osVersion": "16.5",

                "screenSize": "2436x1125",

                "sdkName": "appcenter.ios",

                "sdkVersion": "4.4.3",

                "timeZoneOffset": 120,

                "wrapperSdkName": "appcenter.react-native",

                "wrapperSdkVersion": "4.4.5"

            },

            "sid": "F7CE0946-0784-44DB-A761-3E0C8C00741F",

            "timestamp": "2023-06-12T18:16:19.490Z",

            "type": "startSession"

        }

    ]

}

```