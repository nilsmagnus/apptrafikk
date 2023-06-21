## Celebrus

```
GET https://dnb.celebrus.tech-03.net/0934/v4/appConfigRequest.xml?aE=L&ap=MM&au=app%3A%2F%2FMobilbank.app&sj=dnbcsa&aD=1686465142108&cf=DNB&bb=iOS%2016.5%3B%20iPhone&di=null_8ff592d0b63d4bafa9a7edf6881ba42a15133c565479425f962aef285c9c623d&ut=apple&az=dnbcsapersisted%3D_8ff592d0b63d4bafa9a7edf6881ba42a15133c565479425f962aef285c9c623d_cad9e7ef842248e29f3f23d673cc5fe2_1686464944417_18014398703008251_1686464944417_1%3B%20dnbcsaP3P%3DoptedIn&vb=3 HTTP/1.1

Host: dnb.celebrus.tech-03.net

Accept: */*

Cookie: AWSALB=FBx3c2o8p+AINsOcWCclMFy1vsAvWDwrZ01exK5yjeGYJeUKLT/sSJ4li03S7Rc5epXnIa8IQXzbRuKFEIUvxdfKEnjjSX2gXCJa7NbKFhIsnkjsQopbU8s3ubmA; AWSALBCORS=FBx3c2o8p+AINsOcWCclMFy1vsAvWDwrZ01exK5yjeGYJeUKLT/sSJ4li03S7Rc5epXnIa8IQXzbRuKFEIUvxdfKEnjjSX2gXCJa7NbKFhIsnkjsQopbU8s3ubmA

User-Agent: DNB/1 CFNetwork/1408.0.4 Darwin/22.5.0

Accept-Language: en-GB,en;q=0.9

Accept-Encoding: gzip, deflate, br

Connection: keep-alive
```

```
aE: L

ap: MM

au: app://Mobilbank.app

sj: dnbcsa

aD: 1686465142108

cf: DNB

bb: iOS 16.5; iPhone

di: null_8ff592d0b63d4bafa9a7edf6881ba42a15133c565479425f962aef285c9c623d

ut: apple

az: dnbcsapersisted=_8ff592d0b63d4bafa9a7edf6881ba42a15133c565479425f962aef285c9c623d_cad9e7ef842248e29f3f23d673cc5fe2_1686464944417_18014398703008251_1686464944417_1; dnbcsaP3P=optedIn

vb: 3
```

## Adobe DC

```
POST https://dnbbankasa.data.adobedc.net/ee/irl1/v1/interact?configId=8f4fa919-154b-4aa0-9ec3-edc40dcf7aa2&requestId=FD1C7DA1-70B7-489F-B833-1F70F02005B8 HTTP/2.0

accept: application/json

content-type: application/json

accept-encoding: gzip, deflate, br

user-agent: Mozilla/5.0 (iPhone; CPU OS 16_5 like Mac OS X; en_NO)

accept-language: en-NO

content-length: 1702
```

```
{

    "events": [

        {

            "xdm": {

                "_id": "C1963F19-4FCC-46AB-9F3C-BB994E3B3F5C",

                "dnb": {

                    "domain": "mobilbank.dnb.bank",

                    "event_type": "PageLoaded",

                    "page_name": "Payment Overview",

                    "party_id": "FX070118051670081A",

                    "party_id_hashed": "b939ff4b1ef9332cc1bbeb3dbfe40f337aa335a63870def1446d1df053899044",

                    "path": "payment_overview"

                },

                "timestamp": "2023-06-13T19:24:38.086Z"

            }

        }

    ],

    "meta": {

        "konductorConfig": {

            "streaming": {

                "enabled": true,

                "lineFeed": "\n",

                "recordSeparator": "\u0000"

            }

        },

        "state": {

            "entries": [

                {

                    "key": "kndctr_2B764D045BDC6C450A495D90_AdobeOrg_cluster",

                    "maxAge": 1800,

                    "value": "irl1"

                },

                {

                    "key": "kndctr_2B764D045BDC6C450A495D90_AdobeOrg_identity",

                    "maxAge": 34128000,

                    "value": "CiYwNzYxNTQxNjk0MTcxNzI3NDIzNjA4MjU5NjkzMzE5OTY3MTUzNFIPCLXb3bGLMRgBKgRJUkwx8AG1292xizE="

                }

            ]

        }

    },

    "xdm": {

        "identityMap": {

            "ECID": [

                {

                    "authenticatedState": "ambiguous",

                    "id": "07615416941717274236082596933199671534",

                    "primary": false

                }

            ],

            "partyID": [

                {

                    "authenticatedState": "authenticated",

                    "id": "b939ff4b1ef9332cc1bbeb3dbfe40f337aa335a63870def1446d1df053899044",

                    "primary": false

                }

            ]

        },

        "implementationDetails": {

            "environment": "app",

            "name": "https://ns.adobe.com/experience/mobilesdk/ios",

            "version": "3.8.2+1.6.0"

        }

    }

}

*:8080mitmproxy 9.0.1
```