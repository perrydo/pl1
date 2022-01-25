# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json?origin=place_id:ChIJ-3t2CzPN1IkRGW2nncyZuNs&destination=place_id:ChIJmzrzi9Y0K4gRgXUc3sTY7RU&waypoints=place_id:ChIJoYAZDTQyK4gRuR4PYg_YSJk|place_id:ChIJvUYHUcs0K4gRN8i7jHsUiYs|place_id:ChIJWyfdtDHL1IkR_bal8ay1Cso&departure_time=1653743133&traffic_model=pessimistic&mode=driving&avoid=highways&units=metric&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
```

## Next paste the full JSON response to this query here:

```
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ-3t2CzPN1IkRGW2nncyZuNs",
         "types" : [ "establishment", "point_of_interest", "university" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJoYAZDTQyK4gRuR4PYg_YSJk",
         "types" : [ "establishment", "point_of_interest", "shopping_mall" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJvUYHUcs0K4gRN8i7jHsUiYs",
         "types" : [ "establishment", "point_of_interest", "shopping_mall" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJWyfdtDHL1IkR_bal8ay1Cso",
         "types" : [ "establishment", "point_of_interest", "tourist_attraction" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJmzrzi9Y0K4gRgXUc3sTY7RU",
         "types" : [ "establishment", "point_of_interest", "tourist_attraction" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 43.7719568,
               "lng" : -79.3699055
            },
            "southwest" : {
               "lat" : 43.6406072,
               "lng" : -79.4933685
            }
         },
         "copyrights" : "Map data ©2022 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "8.4 km",
                  "value" : 8386
               },
               "duration" : {
                  "text" : "16 mins",
                  "value" : 965
               },
               "end_address" : "3401 Dufferin St, Toronto, ON M6A 2T9, Canada",
               "end_location" : {
                  "lat" : 43.7230944,
                  "lng" : -79.45670799999999
               },
               "start_address" : "4700 Keele St, Toronto, ON M3J 1P3, Canada",
               "start_location" : {
                  "lat" : 43.7719453,
                  "lng" : -79.4933685
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "5 m",
                        "value" : 5
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 1
                     },
                     "end_location" : {
                        "lat" : 43.7719568,
                        "lng" : -79.4933125
                     },
                     "html_instructions" : "Head \u003cb\u003eeast\u003c/b\u003e on \u003cb\u003eThe Pond Rd\u003c/b\u003e toward \u003cb\u003eKeele St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "uedjGp`edNAK"
                     },
                     "start_location" : {
                        "lat" : 43.7719453,
                        "lng" : -79.4933685
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 521
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 47
                     },
                     "end_location" : {
                        "lat" : 43.7673497,
                        "lng" : -79.4921308
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eKeele St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wedjGd`edNhASp@Kf@KpASb@IzCi@JCZGB?JCPC`@IHAPC@?HARE^GXEl@KHCZCx@OTERCTEJAf@G"
                     },
                     "start_location" : {
                        "lat" : 43.7719568,
                        "lng" : -79.4933125
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 606
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 120
                     },
                     "end_location" : {
                        "lat" : 43.7641091,
                        "lng" : -79.4882648
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eTangiers Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}hcjGxxddNTCEi@Gy@Eg@CUCQACACISEUE]CQCOI{@EY?GAK?E?G@A?CBEBCBE@?BCDA?A|@YJCBAJCNG\\MVIVIRGRG@AHCvAe@`A[b@OLEJCZKDANGVSFGFINMPMBAJEvAe@"
                     },
                     "start_location" : {
                        "lat" : 43.7673497,
                        "lng" : -79.4921308
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 907
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 100
                     },
                     "end_location" : {
                        "lat" : 43.7664518,
                        "lng" : -79.4774632
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eFinch Ave W\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "utbjGr`ddNYqBAQGk@G]e@eDIu@EUU_B_@sCOaACSCUGc@@O?I?EAE?GAIGg@EYWmBIm@Iq@CQKw@]eCQoAOeAM}@Ks@WqBCQKo@SwAIm@CQIi@ESGYCOIk@Ek@"
                     },
                     "start_location" : {
                        "lat" : 43.7641091,
                        "lng" : -79.4882648
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1418
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 172
                     },
                     "end_location" : {
                        "lat" : 43.75552880000001,
                        "lng" : -79.4742644
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eChesswood Dr\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "iccjGb}adN`@K^Mv@Wj@QXKf@OHCn@Un@QNElA_@^MDA^KTIVG@?JC@AF?DAB?JAF?@?F?J?H?J@F@L@J@D@NBHBJDXJRJFDFDFD@@DDHFTRb@b@BBHHHHRPLLf@h@B@rApA`@`@PRB@JJJJFDBBBBB@@@B@BBD@FBB?D@F@H?F?HAB?DABADAJEDATIHC^Mb@Oh@OFChA_@LEJCJCHE@AB?DCBCDALKNMJMBEDG@EDG@EBE@E@E@C@CBKFYBKHg@Lm@Lk@Nq@BOBIDONa@LWLUJMNQVW\\[|@w@BCPMFCLIPMBANIDAPGJEBAJCJCREb@GVCt@A"
                     },
                     "start_location" : {
                        "lat" : 43.7664518,
                        "lng" : -79.4774632
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1117
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 130
                     },
                     "end_location" : {
                        "lat" : 43.7501644,
                        "lng" : -79.46343949999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eSheppard Ave W\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "a_ajGbiadN?E@k@@_@Ba@Dm@De@D[DWHe@DW@IFUPk@dAqDLe@~@aDPm@HSFSJSVo@Rc@R]Ze@DIDGJORWLQNM~@cAh@i@HInAsALADAXUn@s@vBwBnAuADGNOVYRYNYN]N]H[DOBIHa@Fa@D[BU?U@Y?U?WAUC_@KmA"
                     },
                     "start_location" : {
                        "lat" : 43.75552880000001,
                        "lng" : -79.4742644
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1212
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 86
                     },
                     "end_location" : {
                        "lat" : 43.7417938,
                        "lng" : -79.45440409999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAllen Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "o}_jGne_dNfC[\\Gb@GREb@KHEFA^O`@Qf@[VQ^[TUNQNQRYTYFKHONYP_@n@{ARg@~@wBZ{@^{@Pa@R_@FMLWXg@T[FMBCRYT[FInA{Ax@aALOr@y@j@o@jC{C`CoCxBeCtA}A"
                     },
                     "start_location" : {
                        "lat" : 43.7501644,
                        "lng" : -79.46343949999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1061
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 96
                     },
                     "end_location" : {
                        "lat" : 43.733428,
                        "lng" : -79.4527887
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eTransit Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ei~iG~l}cNd@bAHLHNBBVNHDB@VFB?@?TCRCLCTIHELKJINOBCFGV]tAyBx@sAZc@vAwBFKRY@?LQLMJINMVO?AVMPGDCPEBALCRCJALAb@Ab@AD?\\An@Ez@Ev@Cr@CP?P?D@R@PDPDn@TB?JDr@TlAd@d@N@@PHFBDBJH`@^LJJHLDJBD@PB@?B?B?B?DAVITI"
                     },
                     "start_location" : {
                        "lat" : 43.7417938,
                        "lng" : -79.45440409999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 507
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 70
                     },
                     "end_location" : {
                        "lat" : 43.7321488,
                        "lng" : -79.4588364
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWilson Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}t|iG|b}cNXbCBXNdABTDX@HNfAFd@TjBJt@BTHb@BZDPHp@Jr@BX?@Hl@FZTfBBPBVBL@JHh@DR?JBR@HF^Db@"
                     },
                     "start_location" : {
                        "lat" : 43.733428,
                        "lng" : -79.4527887
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 1032
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 143
                     },
                     "end_location" : {
                        "lat" : 43.7230944,
                        "lng" : -79.45670799999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eDufferin St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}l|iGvh~cN@TTCp@Kf@Id@I\\E~@Qr@KLA`C[hDm@NA^Gx@K\\EJAJCRCVEB?XGJARCPCJCLCz@MRCpAOb@GxB]dAKdAUlASPCDALCTUZEr@Ox@MTETENCNClAO"
                     },
                     "start_location" : {
                        "lat" : 43.7321488,
                        "lng" : -79.4588364
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "13.2 km",
                  "value" : 13169
               },
               "duration" : {
                  "text" : "32 mins",
                  "value" : 1947
               },
               "end_address" : "220 Yonge St, Toronto, ON M5B 2H1, Canada",
               "end_location" : {
                  "lat" : 43.6539873,
                  "lng" : -79.37992079999999
               },
               "start_address" : "3401 Dufferin St, Toronto, ON M6A 2T9, Canada",
               "start_location" : {
                  "lat" : 43.7230944,
                  "lng" : -79.45670799999999
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 148
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 24
                     },
                     "end_location" : {
                        "lat" : 43.7217839,
                        "lng" : -79.4564785
                     },
                     "html_instructions" : "Head \u003cb\u003esouth\u003c/b\u003e on \u003cb\u003eDufferin St\u003c/b\u003e toward \u003cb\u003eMcAdam Ave\u003c/b\u003e",
                     "polyline" : {
                        "points" : "itziGl{}cNPENCNATDXEh@Ib@EtAQ"
                     },
                     "start_location" : {
                        "lat" : 43.7230944,
                        "lng" : -79.45670799999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 916
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 128
                     },
                     "end_location" : {
                        "lat" : 43.7239401,
                        "lng" : -79.4456156
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRanee Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "clziG~y}cNNC?U?[AO@AAG?OAKAKAKCWIg@AMGa@AK[cCIg@]sC]iCsAgKmAkJIk@Iu@EUIk@SaBGe@M{@CUKo@Io@QuAIi@OgAEW"
                     },
                     "start_location" : {
                        "lat" : 43.7217839,
                        "lng" : -79.4564785
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "93 m",
                        "value" : 93
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 14
                     },
                     "end_location" : {
                        "lat" : 43.723135,
                        "lng" : -79.44528769999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eVarna Dr\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "syziGbv{cNVIv@UHAPGLERGPI"
                     },
                     "start_location" : {
                        "lat" : 43.7239401,
                        "lng" : -79.4456156
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 381
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 46
                     },
                     "end_location" : {
                        "lat" : 43.7222315,
                        "lng" : -79.4414158
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003eTurtle Island Rd\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "stziG`t{cNrA[r@SJEFEBE@E?G?I?KAOCi@?S?K?M@O@ULoB@WL{D@k@Bk@?]?SAE?GCQGc@"
                     },
                     "start_location" : {
                        "lat" : 43.723135,
                        "lng" : -79.44528769999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 242
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 31
                     },
                     "end_location" : {
                        "lat" : 43.7201217,
                        "lng" : -79.44099779999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eVarna Dr\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}nziGz{zcNFEFEFCHCFAXKNEl@Sr@SBAZITGHAHARAHAN?J?P@J@H@L@JBNBJBLB"
                     },
                     "start_location" : {
                        "lat" : 43.7222315,
                        "lng" : -79.4414158
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 416
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 61
                     },
                     "end_location" : {
                        "lat" : 43.7175081,
                        "lng" : -79.4376206
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eVarna Dr\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "waziGfyzcNHm@BQDYBMBKBMDMBG?ADKBIDKDKHODKPYr@kALQn@eAxAaCFKBEFGBCBCJKFEHEHENE\\M`@Mn@SVI"
                     },
                     "start_location" : {
                        "lat" : 43.7201217,
                        "lng" : -79.44099779999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.8 km",
                        "value" : 1846
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 232
                     },
                     "end_location" : {
                        "lat" : 43.7221912,
                        "lng" : -79.41565319999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLawrence Ave W\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mqyiGbdzcN[cCQoACOBM?ASgBSyAE[Ik@WsBa@wC_@{CGk@SoAKo@E]SkA[mBGc@k@gEEYGa@G]AK?ICC?AIIAGMy@YyBCQ[_CAS]kCKaAWkBGi@Ky@i@cEQoAi@gEUiBk@mEs@wFIo@}@_HE[Q{AKu@OkAS}AK{@DWEc@UgB"
                     },
                     "start_location" : {
                        "lat" : 43.7175081,
                        "lng" : -79.4376206
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.2 km",
                        "value" : 3199
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 418
                     },
                     "end_location" : {
                        "lat" : 43.6950308,
                        "lng" : -79.40464
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAvenue Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "unziGxzucNz@W\\KTGPEXIRC^Ij@ILAXGt@If@GdAQbAMRE^GVO~@Mb@Gl@IFAHCf@Gt@MFABCBAFEFEDGFGBELQh@q@pAaBxAkBJMX_@n@w@NQHGFGBABABABA@AFAFCHCHCDAFCBAD?BABAB?B?FAbBMTAdAGXA~@IlBKlAEhAEnBGb@ARAPAB?HAHCLENE\\IVIr@Ub@MtAc@lBk@bAYvAe@r@S`@Mv@UNEDAVGPCr@M`Dg@|AUdAQp@MFA@AHCDCBAHGFKFKFKFMBI?APg@JODGFIJKHGLKTKJG\\MXKv@UTGhBg@bD}@DAhBg@p@Sj@O^MbA]r@UnDkAhC{@\\KZMx@W`@Ov@SFCLCn@Sb@KTIRGPENCRGVGjAa@dAYxBm@nDeARG"
                     },
                     "start_location" : {
                        "lat" : 43.7221912,
                        "lng" : -79.41565319999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 204
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 32
                     },
                     "end_location" : {
                        "lat" : 43.6949936,
                        "lng" : -79.4023299
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eKilbarry Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}duiG~uscNIo@S_BIm@?AIg@MaADg@DQ@KBIBIDKFMHOX_@"
                     },
                     "start_location" : {
                        "lat" : 43.6950308,
                        "lng" : -79.40464
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 426
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 41
                     },
                     "end_location" : {
                        "lat" : 43.6913083,
                        "lng" : -79.40137249999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eOriole Pkwy\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "uduiGpgscNNCVGLEZK`Cq@f@Mz@Wf@M`@K\\KfCq@ZAXIDCFADAJCH?H?L@NBD@DBHDJDLL"
                     },
                     "start_location" : {
                        "lat" : 43.6949936,
                        "lng" : -79.4023299
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 144
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 18
                     },
                     "end_location" : {
                        "lat" : 43.6908194,
                        "lng" : -79.4029932
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eLonsdale Rd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "umtiGpascNDDDFBBBFHLDJDLBH@F@FBLDRBZJz@NjAD`@"
                     },
                     "start_location" : {
                        "lat" : 43.6913083,
                        "lng" : -79.40137249999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.6 km",
                        "value" : 2567
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 372
                     },
                     "end_location" : {
                        "lat" : 43.6687059,
                        "lng" : -79.39413209999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eAvenue Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "sjtiGtkscNDFDBD@ZDHABANCHCRGHC?AHKDCDAZKJCNELC^MLE^KXKFA`@MLEr@Qt@UFC\\KLEDAb@M\\KZKB?DCHC\\KVGd@MFCJCbA[HCDALE|@YxAe@JC|@[RGv@Y~@WFCf@OVIJC`A]dA]TIPEf@QjCw@fBk@jDeAjA]|@YfBi@hA]jBk@zBo@x@Wx@Wl@SjA_@LEd@Mp@S`A[VIx@WTIj@QLEv@UZIPG`@M`@Mv@Wh@Qf@OnA_@t@UFCr@UdA[LEl@Q`Bg@r@U`@KJAZIDALEFAXILERGj@Qn@Ul@Sf@OdA]XKb@MpBm@"
                     },
                     "start_location" : {
                        "lat" : 43.6908194,
                        "lng" : -79.4029932
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 330
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 53
                     },
                     "end_location" : {
                        "lat" : 43.6658866,
                        "lng" : -79.3933335
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eQueens Park\u003c/b\u003e",
                     "polyline" : {
                        "points" : "m`piGhtqcNd@Mp@Ux@UPG\\Kx@W\\MDADAPGBC\\IPGt@URGd@O@ANHJCD?F?B@F@B@BBB@BBDBBB@BBB"
                     },
                     "start_location" : {
                        "lat" : 43.6687059,
                        "lng" : -79.39413209999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 665
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 81
                     },
                     "end_location" : {
                        "lat" : 43.66062669999999,
                        "lng" : -79.3911387
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eQueen's Park Cres W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ynoiGhoqcN`@l@HJJLXNVLTHJ@T@H?F?HAFAHC^KNELEBAZIJCXITG\\KTGt@Sp@S`@K@Ad@Mp@SLEJEPKJIpA}@PKBCJGJGHEJCTINEHCLGLGHEDEJIBAHIJOLSJUJUFODKBIPu@"
                     },
                     "start_location" : {
                        "lat" : 43.6658866,
                        "lng" : -79.3933335
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 101
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 16
                     },
                     "end_location" : {
                        "lat" : 43.6598335,
                        "lng" : -79.3906016
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eQueens Park\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "}mniGraqcNBGDIBEBEBEDEHIFEDCFCd@O|@Y"
                     },
                     "start_location" : {
                        "lat" : 43.66062669999999,
                        "lng" : -79.3911387
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 268
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 46
                     },
                     "end_location" : {
                        "lat" : 43.65753,
                        "lng" : -79.38962599999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eUniversity Ave\u003c/b\u003e",
                     "polyline" : {
                        "points" : "}hniGf~pcN`@M`@OJCHCd@O\\KBANGr@U`@MNEn@S@ABAB?XKNEl@S`@M"
                     },
                     "start_location" : {
                        "lat" : 43.6598335,
                        "lng" : -79.3906016
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 630
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 166
                     },
                     "end_location" : {
                        "lat" : 43.6590871,
                        "lng" : -79.3820928
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eGerrard St W\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "qzmiGdxpcNE]C[OeAGi@Io@Io@EWGg@YoCMqASaBGa@AMUyAIo@UsB_@mCE]G_@Ku@AGS}AM_AIu@OiA"
                     },
                     "start_location" : {
                        "lat" : 43.65753,
                        "lng" : -79.38962599999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 593
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 168
                     },
                     "end_location" : {
                        "lat" : 43.6539873,
                        "lng" : -79.37992079999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eYonge St\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "idniG`iocNpAc@~Ag@|@[`A[^MjA_@bBi@f@Q|@YJCHCb@OLEb@MbA]`@MPGNE`@M`@M`@Mh@QNG"
                     },
                     "start_location" : {
                        "lat" : 43.6590871,
                        "lng" : -79.3820928
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "1.2 km",
                  "value" : 1207
               },
               "duration" : {
                  "text" : "6 mins",
                  "value" : 356
               },
               "end_address" : "93 Front St E, Toronto, ON M5E 1C3, Canada",
               "end_location" : {
                  "lat" : 43.649217,
                  "lng" : -79.37181269999999
               },
               "start_address" : "220 Yonge St, Toronto, ON M5B 2H1, Canada",
               "start_location" : {
                  "lat" : 43.6539873,
                  "lng" : -79.37992079999999
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 415
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 134
                     },
                     "end_location" : {
                        "lat" : 43.6504197,
                        "lng" : -79.37840969999999
                     },
                     "html_instructions" : "Head \u003cb\u003esouth\u003c/b\u003e on \u003cb\u003eYonge St\u003c/b\u003e toward \u003cb\u003eQueen St E\u003c/b\u003e",
                     "polyline" : {
                        "points" : "mdmiGn{ncN`A[`AY`@OfBi@`@OJCLEt@WjA]lAa@p@SFEfA]BAh@Q"
                     },
                     "start_location" : {
                        "lat" : 43.6539873,
                        "lng" : -79.37992079999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 293
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 62
                     },
                     "end_location" : {
                        "lat" : 43.651172,
                        "lng" : -79.374922
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eAdelaide St E\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "cnliG`rncNM{@?AGa@K{@OiAAG_@wCWmBS}AUgB"
                     },
                     "start_location" : {
                        "lat" : 43.6504197,
                        "lng" : -79.37840969999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 297
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 95
                     },
                     "end_location" : {
                        "lat" : 43.6486135,
                        "lng" : -79.3738487
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eChurch St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "yrliGf|mcNxAe@r@ULElAa@NEhA[z@Y~Bu@"
                     },
                     "start_location" : {
                        "lat" : 43.651172,
                        "lng" : -79.374922
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 202
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 65
                     },
                     "end_location" : {
                        "lat" : 43.649217,
                        "lng" : -79.37181269999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eFront St E\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ybliGpumcNb@MQk@Us@[iAIYKa@Qk@GWEKEQSi@IW"
                     },
                     "start_location" : {
                        "lat" : 43.6486135,
                        "lng" : -79.3738487
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "2.1 km",
                  "value" : 2125
               },
               "duration" : {
                  "text" : "7 mins",
                  "value" : 449
               },
               "end_address" : "290 Bremner Blvd, Toronto, ON M5V 3L9, Canada",
               "end_location" : {
                  "lat" : 43.641677,
                  "lng" : -79.38665709999999
               },
               "start_address" : "93 Front St E, Toronto, ON M5E 1C3, Canada",
               "start_location" : {
                  "lat" : 43.649217,
                  "lng" : -79.37181269999999
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "37 m",
                        "value" : 37
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 14
                     },
                     "end_location" : {
                        "lat" : 43.6493692,
                        "lng" : -79.3714018
                     },
                     "html_instructions" : "Head \u003cb\u003enortheast\u003c/b\u003e on \u003cb\u003eFront St E\u003c/b\u003e toward \u003cb\u003eLower Jarvis St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "sfliGxhmcNCIYgA"
                     },
                     "start_location" : {
                        "lat" : 43.649217,
                        "lng" : -79.37181269999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 417
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 116
                     },
                     "end_location" : {
                        "lat" : 43.6457783,
                        "lng" : -79.3699055
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eLower Jarvis St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qgliGffmcNr@W`AYp@W~@UhA[~Bu@HC`A[l@Sb@M`@Mr@S@ADARIJE"
                     },
                     "start_location" : {
                        "lat" : 43.6493692,
                        "lng" : -79.3714018
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "13 m",
                        "value" : 13
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 3
                     },
                     "end_location" : {
                        "lat" : 43.6457503,
                        "lng" : -79.37006649999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eLake Shore Blvd W\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cqkiG||lcND^"
                     },
                     "start_location" : {
                        "lat" : 43.6457783,
                        "lng" : -79.3699055
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 859
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 150
                     },
                     "end_location" : {
                        "lat" : 43.6423392,
                        "lng" : -79.37949549999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eLake Shore Blvd W\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "}pkiG|}lcNb@dDRxAHn@p@lF|@|GHh@J`@Jf@Rr@Lb@HTN\\Xx@HTTf@h@nAz@zBRf@|@zBRf@Tf@~@vB^x@DJBDHPHR"
                     },
                     "start_location" : {
                        "lat" : 43.6457503,
                        "lng" : -79.37006649999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 142
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 27
                     },
                     "end_location" : {
                        "lat" : 43.6416118,
                        "lng" : -79.3809522
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003eLake Shore Blvd W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eThe PATH - One York St\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "s{jiGzxncNfAlChArC"
                     },
                     "start_location" : {
                        "lat" : 43.6423392,
                        "lng" : -79.37949549999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 221
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 33
                     },
                     "end_location" : {
                        "lat" : 43.6406072,
                        "lng" : -79.3833164
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to continue on \u003cb\u003eLake Shore Blvd W\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "awjiG|aocNJb@BHbAfCLZt@tBDJFX`@jB"
                     },
                     "start_location" : {
                        "lat" : 43.6416118,
                        "lng" : -79.3809522
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 207
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 54
                     },
                     "end_location" : {
                        "lat" : 43.64239449999999,
                        "lng" : -79.3840129
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eLower Simcoe St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ypjiGvpocN[LMFa@HaARSDa@J_AX_Bh@"
                     },
                     "start_location" : {
                        "lat" : 43.6406072,
                        "lng" : -79.3833164
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 229
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 52
                     },
                     "end_location" : {
                        "lat" : 43.641677,
                        "lng" : -79.38665709999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBremner Blvd\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}{jiG`uocND^BPDX@NF`@Ht@Jz@Jx@D^BPBL@D?B@D?B@B@B?D@D@B?BBF@B?DBFBH@D@B@@?@@D@DBFJRDLDFBF"
                     },
                     "start_location" : {
                        "lat" : 43.64239449999999,
                        "lng" : -79.3840129
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "uedjGp`edNAKhASxAW|GkA|B_@jDi@xB_@r@ITCEi@MaBGg@Sq@_@oDDSLMlC}@|FkBxAe@TI^[l@g@bBk@[cC_AeHkAkIGi@Es@AU_AsHaCiQeA_HM{@Ek@`@KvAe@dA]pC{@bCu@jBe@bA?f@F~@Xj@\\f@b@hCfCnDjDb@RVBTA`Bi@nEwANIn@i@Zs@x@{D\\{A\\y@Xc@bC}Bj@_@j@[l@SzAUt@A?EBkATqCV_BlByGbBwFb@cAf@aAr@gApB{Br@s@nAsALADAhAiA|EeFj@s@^w@b@sAZuB@}AEu@KmAfC[`AOv@QrAi@~@m@t@q@hAwAr@uAdFuLdAiBt@gAlOmQnEcFn@pALR`@T`@Hh@Gb@Mb@[r@y@bGiJj@w@`Au@n@[v@O`BGnCMnCGXBb@JrBp@fC`ALFl@h@XTXH\\Dd@KTIXbCR~AZ`Cl@|Ev@`Gz@dGLhAFx@fAOjDk@`AMjHiAfC[bAOdDg@bGy@dAKdAU~AWRETUZElB]j@K~B]^ETDXElAOdBU?cAEo@OkAaEm[{CsUk@kEYqBEWVI`AW^Md@QrA[~@YJK@c@EyAPcDTkHA_AKu@NKr@UtBo@dAUx@Ct@Ft@NVgB`@sAf@aAjEeHV]`@[xAg@fA]m@sE?_@w@iGaBsMy@iFuAsJQuAOWgAeIsCeU_G_e@{@{GDWEc@UgBz@Wr@Sj@OlBY|Dk@vAS^GVObBUt@KnB[VQ^g@`FmGbBqBh@Wr@ShHe@tJ_@lAE~DiA|NmEbB[vJ}AXK\\a@Re@\\w@LQTSb@WzBw@pOiEfQ}F|EsAjOkEg@_EWiBJy@H_@LYb@o@pA]lGeB~@WfCq@ZA^MLCl@Ad@NXRJLVd@Lf@XxBTlBJJ`@FLCv@SHMJEdAYfBk@tEsAtC{@rDeAtJ}CbH{BfYuIfW{HdJsCnC{@dF{A~Bm@pDkAtFeB~GuBzDmAPFPCVDPLj@x@TXp@\\`@J^@b@G`AYrF{AzBo@XK\\UrBuA`@Q|@[h@]X[l@oA^sAP[\\YlC{@bEsAtC}@nAa@Iy@k@oEu@aHs@kFoBkOWuBOiApAc@|CcA`Bi@tGuBfA]pGqBtJ}C|E}AdCy@h@QM{@Gc@}@eHk@kEUgBxAe@`A[|Ag@hHyBmAcEoAeE]qAtBq@zH_CtFeBXKJED^v@~Fz@|GfAfIVhAz@jCdGnOzE~KtAvDfApCpAvD`@jB[Lo@PuAXaBd@_Bh@D^Hj@^bD\\lCLf@Nj@`@~@"
         },
         "summary" : "Chesswood Dr",
         "warnings" : [],
         "waypoint_order" : [ 0, 1, 2 ]
      }
   ],
   "status" : "OK"
}
```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
