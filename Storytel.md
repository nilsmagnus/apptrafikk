## facebook

```
POST https://graph.facebook.com/v16.0/156162597852941/activities HTTP/2.0

accept: */*

content-type: application/json

accept-encoding: gzip, deflate, br

content-encoding: gzip

user-agent: FBiOSSDK.16.1.0

content-length: 627

accept-language: en-GB,en;q=0.9
```


```
{

    "access_token": "156162597852941|969397c2a85a503f4c098dc7792b9e24",

    "advertiser_id_collection_enabled": "0",

    "advertiser_tracking_enabled": "1",

    "anon_id": "XZ6A214109-D58E-4ECC-8BD6-B64E27F9BF42",

    "application_tracking_enabled": "1",

    "custom_events": "[{\"_eventName\":\"fb_mobile_aem_auto_setup_opt_in\",\"_logTime\":1686380413,\"source\":\"scenedelegate_coldstart\",\"_inBackground\":\"1\",\"_ui\":\"STRootViewController\"}]",

    "event": "CUSTOM_APP_EVENTS",

    "extinfo": "[\"i2\",\"com.storytel.iphone\",\"215753\",\"23.20.0\",\"16.5\",\"iPhone14,4\",\"en_NO\",\"CEST\",\"--\",375,812,\"3.00\",6,119,30,\"Europe\\/Stockholm\"]",

    "format": "json",

    "include_headers": "false",

    "sdk": "ios",

    "ud": "{}",

    "url_schemes": "[\"fb156162597852941\",\"storytel\",\"com.storytel.iphone\",\"com.googleusercontent.apps.195597693343-docc0raksjeg7i8fa574rsj0u7iuku9v\",\"com.googleusercontent.apps.195597693343-fsm4q2jhsrcqmirnk3uk69gdp0pacuhu\",\"com.googleusercontent.apps.381837560703-ta3e5vc1fne81k6c6i66jrne1dm01q64\",\"com.googleusercontent.apps.381837560703-rvuj3k00chdlejiudleu2omrp4s2hepe\"]"

}
```

## google app-measurement

```
POST https://region1.app-measurement.com/a HTTP/2.0

accept: */*

content-type: application/x-www-form-urlencoded

user-agent: Storytel/215753 CFNetwork/1408.0.4 Darwin/22.5.0

content-encoding: gzip

accept-language: en-GB,en;q=0.9

content-length: 1168

accept-encoding: gzip, deflate, br

---
```


```
[message]  1           

[uint32]   1.1         1                                                                

[message]  1.2         

[message]  1.2.1       

[string]   1.2.1.1     _si                                                              

[uint64]   1.2.1.3     4452565542090510204                                              

[message]  1.2.1       

[string]   1.2.1.1     _pc                                                              

[string]   1.2.1.2     LoginViewController                                              

[message]  1.2.1       

[string]   1.2.1.1     _sc                                                              

[string]   1.2.1.2     SFAuthenticationViewController                                   

[message]  1.2.1       

[string]   1.2.1.1     _o                                                               

[string]   1.2.1.2     auto                                                             

[message]  1.2.1       

[string]   1.2.1.1     _pi                                                              

[uint64]   1.2.1.3     4452565542090510203                                              

[string]   1.2.2       _vs                                                              

[uint64]   1.2.3       1686380774324                                                    

[uint64]   1.2.4       1686380769545                                                    

[message]  1.2         

[message]  1.2.1       

[string]   1.2.1.1     _o                                                               

[string]   1.2.1.2     app                                                              

[message]  1.2.1       

[string]   1.2.1.1     details                                                          

[string]   1.2.1.2     The operation couldn’t be completed. (STHPErrorDomain error 0.)  

[message]  1.2.1       

[string]   1.2.1.1     auth_provider                                                    

[string]   1.2.1.2     google                                                           

[message]  1.2.1       

[string]   1.2.1.1     _sc                                                              

[string]   1.2.1.2     SFAuthenticationViewController                                   

[message]  1.2.1       

[string]   1.2.1.1     _si                                                              

[uint64]   1.2.1.3     4452565542090510204                                              

[message]  1.2.1       

[string]   1.2.1.1     failure                                                          

[string]   1.2.1.2     server_error                                                     

[message]  1.2.1       

[message]  1.2.1.1     

[fixed64]  1.2.1.1.12  7309475735946163317                                              

[string]   1.2.1.2     login                                                            

[string]   1.2.2       auth_error_happened                                              

[uint64]   1.2.3       1686380779855                                                    

[uint64]   1.2.4       1686380752755                                                    

[message]  1.2         

[message]  1.2.1       

[string]   1.2.1.1     _si                                                              

[uint64]   1.2.1.3     4452565542090510204                                              

[message]  1.2.1       

[string]   1.2.1.1     _et                                                              

[uint32]   1.2.1.3     5850                                                             

[message]  1.2.1       

[string]   1.2.1.1     _sc                                                              

[string]   1.2.1.2     SFAuthenticationViewController                                   

[message]  1.2.1       

[string]   1.2.1.1     _o                                                               

[string]   1.2.1.2     auto                                                             

[string]   1.2.2       _e                                                               

[uint64]   1.2.3       1686380780072                                                    

[uint64]   1.2.4       1686380772839                                                    

[message]  1.2         

[message]  1.2.1       

[string]   1.2.1.1     _si                                                              

[uint64]   1.2.1.3     4452565542090510203                                              

[message]  1.2.1       

[string]   1.2.1.1     _pc                                                              

[string]   1.2.1.2     SFAuthenticationViewController                                   

[message]  1.2.1       

[string]   1.2.1.1     _sc                                                              

[string]   1.2.1.2     LoginViewController                                              

[message]  1.2.1       

[string]   1.2.1.1     _o                                                               

[string]   1.2.1.2     auto                                                             

[message]  1.2.1       

[string]   1.2.1.1     _pi                                                              

[uint64]   1.2.1.3     4452565542090510204                                              

[string]   1.2.2       _vs                                                              

[uint64]   1.2.3       1686380780074                                                    

[uint64]   1.2.4       1686380774324                                                    

[message]  1.2         

[message]  1.2.1       

[string]   1.2.1.1     _si                                                              

[uint64]   1.2.1.3     4452565542090510205                                              

[message]  1.2.1       

[string]   1.2.1.1     _pc                                                              

[string]   1.2.1.2     LoginViewController                                              

[message]  1.2.1       

[string]   1.2.1.1     _sc                                                              

[string]   1.2.1.2     UIAlertController                                                

[message]  1.2.1       

[string]   1.2.1.1     _o                                                               

[string]   1.2.1.2     auto                                                             

[message]  1.2.1       

[string]   1.2.1.1     _pi                                                              

[uint64]   1.2.1.3     4452565542090510203                                              

[string]   1.2.2       _vs                                                              

[uint64]   1.2.3       1686380780531                                                    

[uint64]   1.2.4       1686380780074                                                    

[message]  1.2         

[message]  1.2.1       

[string]   1.2.1.1     _si                                                              

[uint64]   1.2.1.3     4452565542090510205                                              

[message]  1.2.1       

[string]   1.2.1.1     _et                                                              

[uint32]   1.2.1.3     5923                                                             

[message]  1.2.1       

[string]   1.2.1.1     _sc                                                              

[string]   1.2.1.2     UIAlertController                                                

[message]  1.2.1       

[string]   1.2.1.1     _o                                                               

[string]   1.2.1.2     auto                                                             

[string]   1.2.2       _e                                                               

[uint64]   1.2.3       1686380785995                                                    

[uint64]   1.2.4       1686380780072                                                    

[message]  1.2         

[message]  1.2.1       

[string]   1.2.1.1     _si                                                              

[uint64]   1.2.1.3     4452565542090510203                                              

[message]  1.2.1       

[string]   1.2.1.1     _pc                                                              

[string]   1.2.1.2     UIAlertController                                                

[message]  1.2.1       

[string]   1.2.1.1     _sc                                                              

[string]   1.2.1.2     LoginViewController                                              

[message]  1.2.1       

[string]   1.2.1.1     _o                                                               

[string]   1.2.1.2     auto                                                             

[message]  1.2.1       

[string]   1.2.1.1     _pi                                                              

[uint64]   1.2.1.3     4452565542090510205                                              

[string]   1.2.2       _vs                                                              

[uint64]   1.2.3       1686380785996                                                    

[uint64]   1.2.4       1686380780531                                                    

[message]  1.2         

[message]  1.2.1       

[string]   1.2.1.1     _si                                                              

[uint64]   1.2.1.3     4452565542090510193                                              

[message]  1.2.1       

[string]   1.2.1.1     _pc                                                              

[string]   1.2.1.2     LoginViewController                                              

[message]  1.2.1       

[string]   1.2.1.1     _sc                                                              

[string]   1.2.1.2     OnboardingViewController                                         

[message]  1.2.1       

[string]   1.2.1.1     _o                                                               

[string]   1.2.1.2     auto                                                             

[message]  1.2.1       

[string]   1.2.1.1     _pi                                                              

[uint64]   1.2.1.3     4452565542090510203                                              

[string]   1.2.2       _vs                                                              

[uint64]   1.2.3       1686380786680                                                    

[uint64]   1.2.4       1686380785996                                                    

[message]  1.2         

[message]  1.2.1       

[string]   1.2.1.1     _si                                                              

[uint64]   1.2.1.3     4452565542090510193                                              

[message]  1.2.1       

[string]   1.2.1.1     _et                                                              

[uint32]   1.2.1.3     4546                                                             

[message]  1.2.1       

[string]   1.2.1.1     _sc                                                              

[string]   1.2.1.2     OnboardingViewController                                         

[message]  1.2.1       

[string]   1.2.1.1     _o                                                               

[string]   1.2.1.2     auto                                                             

[string]   1.2.2       _e                                                               

[uint64]   1.2.3       1686380790542                                                    

[uint64]   1.2.4       1686380785995                                                    

[message]  1.3         

[uint64]   1.3.1       1609308272097                                                    

[string]   1.3.2       _fi                                                              

[uint32]   1.3.4       0                                                                

[message]  1.3         

[uint64]   1.3.1       1668789232015                                                    

[string]   1.3.2       _fot                                                             

[uint64]   1.3.4       1668790800000                                                    

[message]  1.3         

[uint64]   1.3.1       1686380398112                                                    

[string]   1.3.2       _sid                                                             

[uint32]   1.3.4       1686380398                                                       

[message]  1.3         

[uint64]   1.3.1       1686380398406                                                    

[string]   1.3.2       _sno                                                             

[uint32]   1.3.4       732                                                              

[message]  1.3         

[uint64]   1.3.1       1686380413745                                                    

[string]   1.3.2       language_filter                                                  

[string]   1.3.3       nn,en                                                            

[message]  1.3         

[uint64]   1.3.1       1686380413745                                                    

[string]   1.3.2       was_ever_logged_in                                               

[string]   1.3.3       1                                                                

[message]  1.3         

[uint64]   1.3.1       1686380413745                                                    

[string]   1.3.2       device                                                           

[string]   1.3.3       iPhone                                                           

[message]  1.3         

[uint64]   1.3.1       1686380413745                                                    

[string]   1.3.2       subscriptionStatus                                               

[string]   1.3.3       0                                                                

[message]  1.3         

[uint64]   1.3.1       1686380413745                                                    

[string]   1.3.2       preferred_font_size                                              

[string]   1.3.3       L                                                                

[message]  1.3         

[uint64]   1.3.1       1686380413745                                                    

[string]   1.3.2       reader_version                                                   

[string]   1.3.3       2                                                                

[message]  1.3         

[uint64]   1.3.1       1686380413745                                                    

[string]   1.3.2       platform                                                         

[string]   1.3.3       16.5                                                             

[message]  1.3         

[uint64]   1.3.1       1686380413745                                                    

[string]   1.3.2       book_format_filter                                               

[string]   1.3.3       A                                                                

[message]  1.3         

[uint64]   1.3.1       1686380413745                                                    

[string]   1.3.2       preferred_localization                                           

[string]   1.3.3       en                                                               

[message]  1.3         

[uint64]   1.3.1       1686380413745                                                    

[string]   1.3.2       is_voiceover_on                                                  

[string]   1.3.3       0                                                                

[message]  1.3         

[uint64]   1.3.1       1686380413745                                                    

[message]  1.3.2       

[fixed64]  1.3.2.12    7308609269595598960                                              

[string]   1.3.3       light                                                            

[message]  1.3         

[uint64]   1.3.1       1686380413745                                                    

[string]   1.3.2       is_kids_mode_on                                                  

[string]   1.3.3       0                                                                

[message]  1.3         

[uint64]   1.3.1       1686380413745                                                    

[string]   1.3.2       profileprivacy_is                                                

[string]   1.3.3       0                                                                

[message]  1.3         

[uint64]   1.3.1       1686380413745                                                    

[string]   1.3.2       player_version                                                   

[string]   1.3.3       3                                                                

[message]  1.3         

[uint64]   1.3.1       1686380583607                                                    

[string]   1.3.2       _id                                                              

[string]   1.3.3       guest                                                            

[message]  1.3         

[uint64]   1.3.1       1686380790556                                                    

[string]   1.3.2       _lte                                                             

[uint32]   1.3.4       10967065                                                         

[message]  1.3         

[uint64]   1.3.1       1686380790558                                                    

[string]   1.3.2       _se                                                              

[uint32]   1.3.4       370419                                                           

[uint64]   1.4         1686380790564                                                    

[uint64]   1.5         1686380774324                                                    

[uint64]   1.6         1686380790542                                                    

[uint64]   1.7         1686380772839                                                    

[string]   1.8         ios                                                              

[string]   1.9         16.5                                                             

[string]   1.10        iPhone14,4                                                       

[message]  1.11        

[fixed32]  1.11.12     1869491566                                                       

[uint32]   1.12        120                                                              

[string]   1.14        com.storytel.iphone                                              

[string]   1.16        23.20.0                                                          

[uint32]   1.17        100900                                                           

[uint32]   1.18        100900                                                           

[uint32]   1.20        1                                                                

[string]   1.21        ADF1C98E9B8843E8B0EF24A5B7E40969                                 

[uint32]   1.23        1387                                                             

[string]   1.25        1:529138207293:ios:3789a8e46f5f0f39                              

[uint64]   1.26        1686380746640                                                    

[string]   1.27        CF983E2F-1263-475D-918E-774E9864C0C4                             

[message]  1.29        

[uint32]   1.29.1      94                                                               

[message]  1.29.2      

[uint32]   1.29.2.1    4                                                                

[uint32]   1.29.2.2    4                                                                

[message]  1.29.2.3    

[uint32]   1.29.2.3.1  2                                                                

[uint32]   1.29.2.3.2  1668789232                                                       

[uint32]   1.29.4      0                                                                

[message]  1.29        

[uint32]   1.29.1      22                                                               

[message]  1.29.2      

[uint32]   1.29.2.1    1                                                                

[uint32]   1.29.2.2    1                                                                

[uint32]   1.29.4      0                                                                

[message]  1.29        

[uint32]   1.29.1      92                                                               

[message]  1.29.2      

[uint32]   1.29.2.1    4                                                                

[uint32]   1.29.2.2    4                                                                

[message]  1.29.2.3    

[uint32]   1.29.2.3.1  2                                                                

[uint32]   1.29.2.3.2  1668789232                                                       

[uint32]   1.29.4      0                                                                

[message]  1.29        

[uint32]   1.29.1      49                                                               

[message]  1.29.2      

[uint32]   1.29.2.1    1                                                                

[uint32]   1.29.2.2    1                                                                

[message]  1.29.2.3    

[uint32]   1.29.2.3.1  0                                                                

[uint32]   1.29.2.3.2  1668789232                                                       

[uint32]   1.29.4      0                                                                

[message]  1.29        

[uint32]   1.29.1      50                                                               

[message]  1.29.2      

[uint32]   1.29.2.1    4                                                                

[uint32]   1.29.2.2    4                                                                

[message]  1.29.2.3    

[uint32]   1.29.2.3.1  2                                                                

[uint32]   1.29.2.3.2  1677128566                                                       

[uint32]   1.29.4      0                                                                

[message]  1.29        

[uint32]   1.29.1      46                                                               

[message]  1.29.2      

[uint32]   1.29.2.1    1                                                                

[uint32]   1.29.2.2    1                                                                

[message]  1.29.2.3    

[uint32]   1.29.2.3.1  0                                                                

[uint32]   1.29.2.3.2  1668789232                                                       

[uint32]   1.29.4      0                                                                

[message]  1.29        

[uint32]   1.29.1      89                                                               

[message]  1.29.2      

[uint32]   1.29.2.1    2                                                                

[uint32]   1.29.2.2    0                                                                

[uint32]   1.29.4      0                                                                

[message]  1.29        

[uint32]   1.29.1      51                                                               

[message]  1.29.2      

[uint32]   1.29.2.1    1                                                                

[uint32]   1.29.2.2    1                                                                

[message]  1.29.2.3    

[uint32]   1.29.2.3.1  0                                                                

[uint32]   1.29.2.3.2  1677506470                                                       

[uint32]   1.29.4      0                                                                

[message]  1.29        

[uint32]   1.29.1      47                                                               

[message]  1.29.2      

[uint32]   1.29.2.1    1                                                                

[uint32]   1.29.2.2    1                                                                

[message]  1.29.2.3    

[uint32]   1.29.2.3.1  0                                                                

[uint32]   1.29.2.3.2  1668789232                                                       

[uint32]   1.29.4      0                                                                

[message]  1.29        

[uint32]   1.29.1      90                                                               

[message]  1.29.2      

[uint32]   1.29.2.1    2                                                                

[uint32]   1.29.2.2    0                                                                

[uint32]   1.29.4      0                                                                

[string]   1.30        ftkblkEVBkMXtINBei7RnK                                           

[uint32]   1.31        215753                                                           

[uint64]   1.35        1685345707883676                                                 

[string]   1.52        G1--                                                             

[uint32]   1.53        1
```


## Adjust.com

```
POST https://app.adjust.com/event HTTP/1.1

Host: app.adjust.com

Content-Type: application/x-www-form-urlencoded

User-Agent: Storytel/215753 CFNetwork/1408.0.4 Darwin/22.5.0

Client-Sdk: ios4.33.4

Connection: keep-alive

Accept: */*

Accept-Language: en-GB,en;q=0.9

Authorization: Signature signature="4E7FDF2F0B1C90F1F0FE543E2CEB53E0E5E6285DB4E38D80C66F1EF4FE13E12C8D301E821AC223CE010BFAC5DBA48A7C6596A99DF99357155C7074CC8277E34F43E9059F0BF8A8D18A892E9F578410EEE867C45E867EE01D518329DA3077E3B1",secret_id="9",algorithm="adj3",headers_id="4",native_version="2.8.0"

Content-Length: 1213

Accept-Encoding: gzip, deflate, br
```

```
os_version:              16.5

attribution_deeplink:    1

installed_at:            2022-10-23T21:48:40.000Z+0200

event_buffering_enabled: 0

primary_dedupe_token:    6adde278-0a1c-4719-b04c-2ba8eb9544c4

created_at:              2023-06-10T09:09:06.512Z+0200

bundle_id:               com.storytel.iphone

needs_response_details:  1

fb_anon_id:              XZ6A214109-D58E-4ECC-8BD6-B64E27F9BF42

app_version_short:       23.20.0

subsession_count:        10

environment:             production

session_count:           237

started_at:              2023-05-21T20:51:09.000Z+0200

callback_params:         {"author":"Alexander Fallo","reader":"Alexander Fallo","referrer":"personal-recommendations____2b5b6047-6c6c-4571-b464-d2fba588e618","origin":"0","userId":"44984714","title":"du fucker med hjertet mitt nå","referrer_page":"frontpage-sthp-no","consumable_id":"1549569","wasReading":"false"}

os_name:                 ios

idfv:                    CF983E2F-1263-475D-918E-774E9864C0C4

device_type:             iPhone

time_spent:              514

event_count:             74

event_token:             nmva9n

session_length:          548

skadn_registered_at:     2023-06-10T09:06:36.898Z+0200

att_status:              1

app_version:             215753

app_token:               z9k8dvf0nuv4

device_name:             iPhone14,4

sent_at:                 2023-06-10T09:09:06.832Z+0200
```