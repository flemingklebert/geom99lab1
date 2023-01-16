# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json
?departure_time=1697457600
&destination=place_id%3AChIJOwg_06VPwokRYv534QaPC8g
&origin=place_id%3AChIJdR3LEAHKJIgR0sS5NU6Gdlc
&waypoints=via%3A40.53260%2C-80.24417%7Cvia%3A38.99572%2C-77.08011%7Cvia%3A40.02597%2C-75.29790
&trafficmodel=pessimistic
&units=imperial
&avoid=tolls
&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
```

## Next paste the full JSON response to this query here:

```JSON
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJdR3LEAHKJIgR0sS5NU6Gdlc",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJOUbSOm5dNIgR6xDju0Zvtz4",
         "types" : [ "premise" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJaUJXfUDJt4kRG5ZZNsFzT04",
         "types" : [ "premise" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJp97sJoO_xokRWlVmcZlEe0c",
         "types" : [ "premise" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJOwg_06VPwokRYv534QaPC8g",
         "types" : [ "locality", "political" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 42.3332583,
               "lng" : -74.00625260000001
            },
            "southwest" : {
               "lat" : 38.9954086,
               "lng" : -83.5135093
            }
         },
         "copyrights" : "Map data ©2023 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "836 mi",
                  "value" : 1345361
               },
               "duration" : {
                  "text" : "14 hours 50 mins",
                  "value" : 53407
               },
               "end_address" : "New York, NY, USA",
               "end_location" : {
                  "lat" : 40.7124882,
                  "lng" : -74.00625260000001
               },
               "start_address" : "Detroit, MI, USA",
               "start_location" : {
                  "lat" : 42.331381,
                  "lng" : -83.045754
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 193
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 70
                     },
                     "end_location" : {
                        "lat" : 42.3314372,
                        "lng" : -83.04340929999999
                     },
                     "html_instructions" : "Head \u003cb\u003eeast\u003c/b\u003e on \u003cb\u003eCadillac Square\u003c/b\u003e toward \u003cb\u003eBates St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "czjaG|zzyN?C?q@?o@?o@?q@?AC]EW?O?e@?{@?e@A{@"
                     },
                     "start_location" : {
                        "lat" : 42.331381,
                        "lng" : -83.045754
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 203
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 56
                     },
                     "end_location" : {
                        "lat" : 42.3298617,
                        "lng" : -83.0421594
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eRandolph Street\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ozjaGhlzyNNKNMZYb@[x@m@\\U\\U@?d@]?A@??ABAv@k@"
                     },
                     "start_location" : {
                        "lat" : 42.3314372,
                        "lng" : -83.04340929999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 263
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 48
                     },
                     "end_location" : {
                        "lat" : 42.3286662,
                        "lng" : -83.04491519999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eE Jefferson\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "spjaGndzyNj@bBDLRn@DJ~A`FBFX~@JXJZJX"
                     },
                     "start_location" : {
                        "lat" : 42.3298617,
                        "lng" : -83.0421594
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 mi",
                        "value" : 506
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 37
                     },
                     "end_location" : {
                        "lat" : 42.3264479,
                        "lng" : -83.0502513
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to continue on \u003cb\u003eW Jefferson Ave\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "eijaGvuzyNPXn@vAt@|BL`@z@hCdA`DPh@FNv@zBHVJZn@|BDTLh@@F@DB^?T"
                     },
                     "start_location" : {
                        "lat" : 42.3286662,
                        "lng" : -83.04491519999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 mi",
                        "value" : 1258
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 54
                     },
                     "end_location" : {
                        "lat" : 42.3325871,
                        "lng" : -83.06207979999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eM-10 N\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eJohn C. Lodge Fwy\u003c/b\u003e",
                     "polyline" : {
                        "points" : "i{iaG`w{yN@pB@N?^@`B?JC~@?BAd@CnAAJEzACb@?HCXAPANG\\Ib@EZI^EVCLEREPGTKZo@pBUj@ELIPIPQ^QZq@jAGLU^Wd@EDYd@g@x@GHaAxAQXUXSXKPQXEFUVQVi@p@g@n@i@n@]`@Y^YZWVUVWZgBjByCrCk@f@OJOL"
                     },
                     "start_location" : {
                        "lat" : 42.3264479,
                        "lng" : -83.0502513
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.4 mi",
                        "value" : 5538
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 225
                     },
                     "end_location" : {
                        "lat" : 42.310902,
                        "lng" : -83.098253
                     },
                     "html_instructions" : "Take exit \u003cb\u003e2A\u003c/b\u003e to merge onto \u003cb\u003eI-75 S\u003c/b\u003e toward \u003cb\u003eToledo\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "uakaG~`~yNQCA?cAj@IDEBKFKFSJA@GBIBOFMHK@I@E@C?E@I?K?I?C?OCQC]EsC_@QCQCGAE?I?EAE@G?E?G@ODEBIBIDMHEDCBEDEDCDCDEDEHEHCFIZCHCLALAJA@?LAP?J?D?F?H@F?B?D@D@H@J@JBJBFDLDPHTDNFNTp@Pj@Nb@`@nALZFVJ^BJFVDVF`@Hh@PxAJt@Hp@Ff@D`@Fd@@JDb@?@ANBZHnAB^Bb@LnB?@FbABd@B`@BJBXHh@FZH\\J`@L`@L^DRDJL^J`@J^L^J`@H^^zAFZJf@Pt@Jf@HZFXBLFZJf@FXFZDZDZD\\Ff@Fj@BZBV@RB\\@Z@X@^@N@|A?b@?d@Ab@Ad@Cb@Cd@APARAPCPCXa@nEADSvBAJE^?BGl@C^Cb@Cp@At@?j@?d@@TBr@@N@T@F?@BZ@NDTHj@BJFVLb@FRFLFTJRHPJPLRLRJNRTHJZXZZ\\\\ZXFDTNXTb@ZVPJF\\PPH@@JDRHB@PFRFVDRDXDVBN@^BX@l@AFA`@CRCTENCREXIPGNELGl@YJEh@[fAm@b@UJExBmAtAu@fAm@hBaA~@g@b@WbCoAJG^Sd@ShAe@VK\\Mb@MNEbA]PG`@IZINCVCPCHAVEVC^CZCRCL?LAX?XAf@Af@AZ?dAB`AB^Dh@FLB\\F`@HTH\\Jl@TXLb@Rj@\\TPNJTNh@`@l@h@`AfANRDFZf@T^FHXf@Xj@\\p@Xv@Tn@Xv@^nA?@Lb@HX^nAPn@Pj@J^b@~ADLZhANh@@??@Nf@Nd@r@dCPj@`@rA?@DL?@@DHV?@@BJ\\?@Rl@Jh@DPFRZbAj@lB\\hAZdAFT@FVx@FVf@bBDPDNDLBFFPFRNj@HX?BDLPp@H\\Tx@X~@ZjAJ\\Rl@jApE"
                     },
                     "start_location" : {
                        "lat" : 42.3325871,
                        "lng" : -83.06207979999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "50.3 mi",
                        "value" : 80977
                     },
                     "duration" : {
                        "text" : "44 mins",
                        "value" : 2647
                     },
                     "end_location" : {
                        "lat" : 41.6914307,
                        "lng" : -83.5117465
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eI-75 S\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Ohio\u003c/div\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "czfaG`cezN|@lCd@pAx@tBf@jA^z@DH@DBFBDDH|FhM?@Xl@h@lATf@^x@@@^v@tA~Cj@|Af@zAx@tC@?Nf@?@bAjDp@xBX|@FVzAhFdAfD@B@HZfA|@vCf@dBDNL`@FTb@xAFPLh@?BL^Vz@Pn@JZV|@d@`BHZBBBBBHHX\\hAn@rBBJl@rBHX`BrFRp@HXBHNh@Vz@HRPj@\\bARj@h@dA`@r@f@|@X`@NT|BnCzAhB`AfA~@fAFH@?fApAtBzBTTDF@?HHHHFFJJJJDBHJHFHF@@XV@?RPRLHHNJHFVPnBjAbE~Br@`@~@l@j@Z~Av@?@@?bBr@j@Vr@h@l@b@PNf@d@VVpAbBX^R\\T`@\\p@Vj@Tj@L\\LZ~AjFT|@T|@DLNf@\\hANh@Pj@Xz@HZJXL`@ZfAL`@Vx@Pf@|@rCTr@Pf@^jAn@dBHTNd@`@pAb@xANf@`@rAVx@Tx@l@nB\\fA?@Tr@@B@D^jAPh@@D^lAd@|AVz@@?BJ@DNb@@BHXTv@p@tBr@~BHXJXj@hBLb@L^Ph@Rh@N`@N\\Xn@Td@BDVh@HN\\l@NVPVPXT^LPPTPTRTp@v@NPPPj@j@\\ZZV\\Vj@b@^ZdCnBbBrARNDFb@`@RRBBFHv@|@PVd@r@JPPZTd@NZ@@N\\LZXt@Ph@DPLb@Nj@?@Pt@T`AH\\hA`FPt@Nl@H^`@fBb@jBPr@Nn@Pj@Rn@Nd@FNPf@JTTj@b@|@@@Vf@Xf@HJPZRXT\\l@r@LNJLHJRPFHNNVT@@j@d@n@f@jA~@r@l@FDt@l@zCbCn@f@\\X|@r@zAlAlA`A^XLJf@b@~CdCh@b@jBzA|AlAlB|AtAhAVRTTRRVVFFNRFDJLPTBDRVRVFJJNZh@@Bh@|@HRTd@P\\N^JVTp@Tp@J^ZfAV|@X`ANd@JZ~BfIJ\\L`@HZNf@J\\FRL`@Lb@Nb@L^N^JXN^P^P\\NZBBR^T`@@@T^T\\RVNRVZRVXZTVXTPPVTTPXTVRNLj@b@jA~@XT~CdCbDhCLJHFVRVRb@\\pAbAxC~B^XPNDBbAv@XTl@d@nA`A`Av@l@d@v@l@JJh@b@VPVRvAhAfAz@j@d@l@d@LHd@^l@d@ZXj@f@TPTRDFPNTTFFNNNLXXb@d@^^TTl@p@HHBB\\^RVd@h@X\\d@j@VZx@dAV\\TXJNFFRVRVRZRVRVBBPRl@v@`@h@TXPVTXTXHJHJd@l@h@n@|@dAj@l@j@l@JH^^TTTTTRTTJHx@t@x@n@lA`ATPZVRNh@`@TPVRZV\\VXV\\ZJHPPXVVVPRTT@Bf@h@Z\\PTLPTXHH`@h@\\d@p@`AhA~ATZHJFHTZV^bAxAfBdCX^X`@t@`Af@p@JJV^h@n@f@n@f@n@FHLLVZPTRTPRXZh@n@@@h@n@d@f@d@f@LNFFFHp@v@pAxA~@dA\\^XZNPVZBD\\\\d@h@h@l@Z^TTFFNPh@j@Z^~@fAJJ@@LNLNjApAX\\HJv@z@\\`@FHTXn@p@TV\\^PRZ\\RVd@f@LNXZ\\^RV\\^?@ZZTXXXHJPRb@d@TV`@d@XZh@n@TTNRVX\\^LNj@l@@@v@|@n@r@X\\`@f@z@|@Z\\VTXVJHHFPNZRLHPLj@XVL@@VJTJTHHBXJ^JTFVD\\FZD\\DXBH@H?N@N@T@^?v@Bv@@t@@Z@p@@R@zBBX@X@Z@B?V?Z@V?\\@\\BX@\\BVDZDZDTB\\HZHZHTFFBTHTHZLZLd@Tf@XVNLHFFf@\\VTRNv@r@RTNNZ^RVNPV\\NRb@n@LTzAxB|A~BRVfA`BFHPVd@r@f@t@^h@FH|@rAPVNRj@|@X`@NTh@x@X`@t@hAJNJLTZ\\h@PXTZ|@pAfA`BPVv@hA^j@t@fAZb@FLNRt@fAV^FJv@jAd@p@FJ`AvAb@n@V\\r@`A`ApAf@l@t@z@@B`@b@BDvAbBB@RVZ^`@d@FFTXRTh@n@b@f@VZTVtA`B|@dAj@l@b@h@rA~Ax@~@r@x@fApAfAnAj@n@`AhA~@fAd@h@z@bANPn@t@XZz@bAr@z@d@h@bAlAZ\\PPXZLNJLd@d@BBVVHHZVl@h@VRNLVRVPRLPLZTXPf@XZPj@XNHRJd@RXLFBXJZL\\L|@XD@b@Lh@LVHPD`@Jj@LbAV~Bl@PDj@N@?HBVFZHt@RZHl@NFB^JPFVHbAZRFJBJBNFRFr@TJDVJ\\NLDb@NXJj@VF@ZLRJt@XlAd@JDRHl@VlAd@NFRHZL|@^@?~@^LFXLh@NXFXHH@FBNBd@FLBD?|@HB?N?\\@\\?T?^A\\AZAn@ClBIv@Ct@E`@Ad@AvAG~@E`ACpAEHAv@CPAH?t@EZA@?TAVA\\A@?XA\\C`@ALAvAEjAEZAXAXAXAN?TAt@Cd@AH?r@Ad@A|@Ab@AX?^AZ?X?x@AX?\\AV@\\AT?T?x@?lCAvE?XAnDCH?L?p@Ab@A`@AxDIp@AlACvAClAC|@AjAE|@A~DK\\?RA|@CTAN?hCGbACpACf@AhEKhFKtCG`JQpBElBErFKjACbDGj@Cf@ApACjBEnBCLAXAdBCv@C@?^Ar@AT?hACb@AlBEVA^?pACNAhAC`@AH?ZA\\?|@C~AC\\APAtACbEIdCEp@C`@A|ACtAEjCEvCG~@C`@AnBEnACdDGr@AZApACXAN?J?ZAXAZ?TAz@Cv@AXA@?pACpAAVA\\?XAX?\\ApAAX?jBAp@A|@Ar@?tAAlACH?@?F?H?P?F?`CCnBAZ?~CCfBCr@?v@AF?r@An@?B?ZAR?@?n@?p@AH?h@Ar@?t@Az@AvAAr@?bCCfAAr@Ar@?@?l@Ap@?@?p@ArAAnDAh@AjB?t@?Z?|A@bA?`A?~@@v@?vA?X@r@?r@@b@?V?\\?t@?r@@Z?\\?dA@`A?nB@dC?Z?Z?r@@v@?t@@Z?p@?X?H?r@@zD@nA@``@Lr`@JnIDhA?tFBvA?vA@|E@vEBpC?pB@nB@xC@rE@hB@pD@bJDjB?V?tGBdA@L?Z?Z?\\?L@vABvCDjBBzGL~DHfBB@?ZB`@BF@XBVB@@f@Fh@JD@`@H`@HJBHBNBLD\\JHBZJb@NLFd@RVJ`@RTLRHNHVPFDf@Zl@b@h@^TPPLv@n@jA|@lA|@`At@pA`A`BnArAbAtAdAnA`AdAv@lA~@`At@hAx@lBxAzAhAjA|@zAjApA`AzAhAb@\\n@d@PPHJTNXTVPRNZVRNl@b@VRj@b@DBVPZTJHDFn@d@DD@@`@X\\Vb@\\BBpA`Az@n@TR@?VRj@b@VRVRXRl@d@b@Z`@Zl@d@n@d@p@h@LHNHrDpCVRTPVPVRVPVPTRVPVTRLBBVP`@ZNLPLPLDDJHjA|@~AjAhBtAl@d@JHJFTRn@d@nCrBRPVPVRVRTPVRVRTNVRTPXRTPVRTP@?TPVRVPVRTRVRfA~@rAhAlAnAb@d@DFjAvA^b@x@fAnCrDLPRXjA|An@|@TXrAfBJNTZTXTZRVx@hAVZRXNRRXRVRXRVTZRXTXTZ`@j@@?b@n@TXV\\dAxAHHNTvBrCjBfCxAnB~@nAj@v@j@r@Zd@HJf@p@nAbB~@lANTTZRVRXtD`FRXRVRXh@p@xAnBp@~@pAdBf@r@|@jAf@n@f@r@V\\NRRXRVTZRVlCnDPVPV|LjPf@n@RXTV\\d@n@t@h@n@VZj@l@f@h@@@j@j@HHJJj@j@@@RRVTHHLJh@d@@@z@t@HFVRLJdAv@NL@?^ZfAx@t@l@lA|@hAz@NLPL^Zh@`@x@n@zAjAb@Zn@f@~AnAbCjBbAt@pAdAh@^\\XjA|@rAdA~@p@z@p@RPd@^^\\VPn@f@n@f@n@d@l@f@VPRPr@h@j@b@n@f@NJ\\VVRl@d@@?l@d@XTRNVRn@f@l@d@n@f@dAv@n@f@VRTPp@f@bAv@TPdAx@p@f@n@f@VRRNn@f@p@f@l@d@l@d@VRl@d@p@f@j@b@p@h@TPn@d@TPVRVRl@d@VRVPVTVPh@`@HFNNXPTRVPVRVRVRTPVRTPVRXRl@d@dAx@TPXTRNXTTPXRTPVR@@TPVRXTTPVPTPTRVPTRXRTPn@f@VPVRTRVRVPVRTPVRVPTPVRXRVRVRTRn@d@TPVRTPVRVPn@f@TPVRVRTPVRTPBBh@`@p@f@VR@@RNZVj@b@l@d@VPVRVRTPTRVRVRVTXTTRTPTTTRTRVTTRTTl@j@VTPPVVj@j@VVTTTRj@l@VTTVRRVTl@n@l@j@l@l@hAfAJLRT`A~@`A`AXXTRTTXX@@b@b@TTXXh@f@PRl@l@l@j@`@`@VXpAnAzAxAvAtAhBfBt@r@b@d@h@h@LLr@r@LJb@d@|@z@LNnAlAj@h@XXhAhAd@d@j@h@lAlA~@`ANLFFNN^\\p@p@`@`@|AxAlAlAt@r@TTTTTTRRTTTTVVTTRPTTRRVT?@VTVTTRTRBBRPTRh@f@VTRNBBVRTRfA|@TPn@f@XTRNVRVRTRVRXRRPVPVRPNDBTRVRRNDBl@f@j@b@d@`@jA~@|AnA|AnAzBfB\\XzEvDrB~AnBzAZVVRTRVRVPLL^VTRVRFFd@^TPVRBBhA|@fAx@v@n@t@j@`@ZRPj@b@FFb@\\JFp@b@v@n@j@b@n@f@n@f@`Ax@p@f@hA|@j@d@x@n@x@n@p@f@j@d@l@d@l@d@dAx@r@j@n@h@jA|@z@r@bAv@b@\\`@ZVRh@`@r@j@n@f@n@f@LLt@j@p@h@bAv@j@b@z@r@hBvA`DdCnAbAz@n@lCvBl@d@dAx@`BpAnA`Av@l@fBtA|@t@dAx@`Av@\\V`@\\^X\\Xf@^h@`@r@l@v@l@b@\\b@\\f@`@PLXTTPVRl@d@XTTPl@d@VTl@d@\\VXTd@\\TRVRVRdAx@|@r@HF\\VNLj@d@NJ@@FDVRl@f@n@f@TPPLZVVRVRt@l@|@r@LHHHl@d@PL\\VLJ^\\dAv@l@d@n@f@VRTRVRTPHFNLRNJH^XDDj@d@JFJHVTRLBBTRVRVRd@^\\VbBpAJJVRd@^LJ|@r@hAz@fBtAfBvApDtCDB`BnAfAz@f@\\HFx@f@j@\\b@Tp@ZLH`@Pl@TVJj@Td@N@?f@N`@JZHHBLB^HB@VDJBpAR^F|@J`BHF@t@Bz@@X?p@?pBGJANA\\ANCn@ERC^ETE^GVETEr@MFC~Bo@nAa@ZKj@Sl@Qv@Yx@Wd@OZKd@OHEPEdBk@r@WXIZK\\MRGd@QJEPGl@SlA_@fFeBTGXKx@Y@?\\MhA_@xE}AFCdA]LEb@KJE^KTGVGXGLCd@I^Gh@ITA`AITCTARA^CdAAh@?|@Bn@BZ@VBB?xAP`@FZDZFVDRD^JRFXF^Hf@Ln@Nn@NdAVHBXFZHpAZPD|@TXFj@Nh@Lh@Lx@P@@lFnAd@LvD|@JB`B`@zG~A`B^zA^~A^hAXpBd@vCp@|@T`Dx@zBh@JDzFrArAZ?@dAXxBl@h@N\\Lj@PXHRFh@RZJv@Xz@XB@B@^L@@n@VvAj@^N^N^Px@^\\NlB|@tAp@TLj@Z~Az@PHxAz@@@n@^d@Vv@f@zA`Aj@^TTfAr@HFFD\\TLHVPb@X`@Rl@b@j@^d@X|@l@b@XVNJHJFvA~@pA|@RLhAt@pA|@\\T|EbDv@h@v@h@JHv@l@v@l@tB`BLLTRd@`@n@h@jA`AHHBBt@r@l@j@n@l@LLr@p@h@f@BDDBnClCPPZZBBXXz@x@n@n@r@p@dAdATTTRNN|@|@LJRRp@n@z@z@HHtJnJpClCzAzA\\ZPN?@@@PPRPTTTTTRVVRRVVLJDFTR`@`@JJTRBDNLRTRRDBRRPPVTVXTPlAlABBdBbB^\\lAlAVTd@f@ZZ~@|@VTZZj@j@LLbD~ChAfALJ?@f@d@nBlBh@f@`@^j@j@NNZXj@j@PRVVn@h@NPRTn@j@f@h@\\ZTTf@f@rApA@@ZXb@b@FFTT~A|ArApAXZlBjBVVRPTV@?PPPRZXf@f@B@XXFFHHRPXZRP@BTRHFZ\\RRZZVTLNXVTTd@b@PNDDl@l@h@h@l@j@VTf@f@f@f@BBn@l@TVRPRR\\ZNL\\ZNNZXRNPNTRTRXVPLVRFDNLRPTR@?ZTRNVRTPRNVPVRTNXRVRZRTPXPj@\\JF^VXPVNTNLHHDd@XJFp@b@d@Vx@h@HDPJTNVLn@`@VNTNB@RLZPj@^VNXPn@^VNXPVPXNXRPJLFLHRJZRRLh@\\D@fAp@TLVNVPXNn@^VPp@b@fAl@VNBBNJXPdAl@ZR^TPJl@^XNVPTN\\PRNn@^JFd@XVPB@h@ZXPj@\\@?l@^VPNHJFTLVNn@`@VNn@^NJHFTLZPj@^n@`@VLZP?@p@^VNJHLHl@\\LHt@d@`B`An@`@l@\\XRbAl@XPJFJFlAt@n@^l@^p@`@ZPTLn@`@n@^l@^l@^fAp@r@`@l@^t@b@p@`@l@^h@Zj@\\rBnA`@Tr@b@p@`@l@^f@Xx@f@h@Zp@`@l@^r@b@VNTNVNVNDBPLZPj@\\p@`@j@\\B@TNXPXPl@^p@`@x@d@v@d@hBfAxA|@\\RxAz@^Vf@Xf@ZJFhBhArBlAb@VrDzB@?ZR@?vAz@`@Vp@`@^V|BxAhC|AjEhC~UpNz@h@VLx@d@dF~CxD`Cn@`@TNn@b@n@d@l@b@TPj@d@b@\\@@~@v@x@r@^^^Z`A`Ar@v@b@b@PTXZNPb@d@rA|A~@dA|DpEvB`CzBfC^`@VXh@n@JJ\\`@h@l@HHLNPRZ\\bAjAjBvBl@p@~FxGxA`BrCdDhDxD|BjC|@`A^b@pJtK|AdBnAtAn@p@PPx@z@n@n@TTp@n@HJlCbC@Bb@^h@b@d@`@j@b@n@f@n@f@f@^\\XTN`At@B@n@b@j@b@ZRDDx@j@x@j@h@`@@@d@Z\\VZTTP@@z@l@xDrCz@n@x@j@b@ZVR~AjA\\TPNRLn@f@p@d@l@`@z@l@JHx@l@HD@@bAt@TP`@XHF`CbBx@l@x@j@RN\\V^Vd@ZlCnBrBxAXTnCnBJHvCvB|AfAtB|ANJZTdAv@p@d@bD~BjBrAb@\\n@b@|AfAj@b@fAv@XRVRhCjBjAz@bAr@`Ap@lA|@l@d@TNZTHF^XXRl@b@|@n@d@^JFl@b@lA|@fAv@PL\\Vr@f@HFh@^f@\\^X`Ar@DBv@h@\\VPNJHr@h@ZTXRVPHDLJr@f@nBvAjBrAFDnCnBbAt@`@Zn@b@JHXTtA`AhAx@nBvAf@^`@XdChBt@h@bAr@B@JJ`@Xv@h@bD`ChAx@dAt@dAt@n@d@n@d@VPbGjEfDbCTNRN|ElDnDhCj@^h@^XPZPb@Vb@R\\Pf@Tr@VTH^L\\JZJf@LXFF@ZHb@Hl@Hp@HZBh@FH?d@B^B\\@Z?P?Z?B?~CClFCT?dAAV@~ACJ?f@?n@Af@?hAAJ?N?Z?X?jAA|BCdA?`@@Z?tBDxAJ`@BN@\\Bp@FL@p@Hx@Jr@L^FVDhARXFj@Jl@L`Ev@n@LpEx@fB\\F@H@d@JZDt@Nr@Lt@Nt@Nt@Lr@Nt@Lt@NXDZFr@NZDXFZFZFp@LXFZFVD\\FXFt@NZD\\HjATZDXFr@N`@FRDt@Nb@Hj@Jt@Nt@Lr@Nt@Lt@Nr@Lt@Nt@Lt@Nz@Pl@Jt@Nt@LXFZFXDx@P~GnAv@NnEz@lJdBlGjA~AZjB\\nATrB`@tAVb@FHBRDXFZFXDXFTD^HPBHBXFZDXF\\HVDXFZFJBNBXF\\FVFZFXD\\FZFXF^FRDD@JBNBTDPDRDJBNBNDTFf@ND@THNDTHJDPFTJVJNHRHRLTLPHRLPJHFHDPLRNRNPLB@RNJJLLLJLJJJPPPPRRPRVXTXBBFHJNHJJNNRX`@LR@@NTJRNVJNJTJRLVLTLVDJHTLZLXVp@DJL\\L^BHRj@Tv@Pf@FTDNNf@`@nALb@FPHVNf@L`@FP@FFPNb@HTFRL^HPDNb@`AFLDHJTLVJT@BHNJRJP^p@f@v@HJTZX^RVJNX\\b@h@DBRTHFNNTTVRTRLJJH\\TTP@@XPZRRJRLJFVNNHVLNFHDD@TJRHd@P\\Jd@LZHPFNBNDPBZFXDF@TBF@L@\\D\\DN@XB^@\\@\\@R?R?H?b@AT?R?N?VAX?V?j@ApAAdBAj@An@Ah@?hAAVAT?T?@?RAT?P?F?PAT?T?TAR?D?L?X?TAN?F?R?TAT?j@?T?TAR?T?TAT?@?T?TAT?F?L?J?b@AP?~@AXAT?T?J?FAV?T?HAJ?V?RAV?VAZ?p@A\\Ah@?ZAT?TAH?H?J?J?TAV?\\?BAR?b@?RA@?X?RAR?PAX?X?f@?X?Z?`@?@?^A\\?ZAh@?HAL?X?j@AX?H?r@AX?R?`@A^A\\?`@Ab@A\\?`@AF?h@?p@Al@AR?\\A`@?|@AdAAtAA|@Al@AJ?R?XAR?L?XAH?n@AR?TAd@?TAX?N?R?XAP?V?N?J?R?VAZ?f@AV?P?VAT?T?R?N?D?V?^@\\@T@R@F@J@ZBv@L\\H`@JVHZJ@?VJRJTJZPXNRLt@h@TRPNf@d@PRHJRTRV\\f@^j@NVLVJPN\\JTLZLXBJFNHRHXHVJ^FVBFBJDTFVH^F`@FX@JFf@Fd@Lv@Fl@Hz@Ht@JdAHx@BPB^DXHz@Hr@Df@@LJ`ALfALvAFh@Fp@?@Fj@Jr@"
                     },
                     "start_location" : {
                        "lat" : 42.310902,
                        "lng" : -83.098253
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 215
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 8
                     },
                     "end_location" : {
                        "lat" : 41.6910684,
                        "lng" : -83.5142803
                     },
                     "html_instructions" : "Take exit \u003cb\u003e208\u003c/b\u003e for \u003cb\u003eI-280 S\u003c/b\u003e toward \u003cb\u003eCleveland\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "mzm}Fl{u|NAp@?FN|ANfBBTJbAFj@B^@JBTD\\@R"
                     },
                     "start_location" : {
                        "lat" : 41.6914307,
                        "lng" : -83.5117465
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 313
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 14
                     },
                     "end_location" : {
                        "lat" : 41.68930779999999,
                        "lng" : -83.51689159999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e at the fork to continue toward \u003cb\u003eI-280 S\u003c/b\u003e",
                     "maneuver" : "fork-left",
                     "polyline" : {
                        "points" : "exm}Ffkv|N@B@L@PD\\Db@@N?@@H@F@F?DBHBLBLDNBJBLDJBHBFHRHTNTBFHLFJVXJLPPJJHHLHBBJFPLHDHBNHHBPFf@L"
                     },
                     "start_location" : {
                        "lat" : 41.6910684,
                        "lng" : -83.5142803
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 232
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 10
                     },
                     "end_location" : {
                        "lat" : 41.6872853,
                        "lng" : -83.5164661
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e to continue toward \u003cb\u003eI-280 S\u003c/b\u003e",
                     "maneuver" : "keep-right",
                     "polyline" : {
                        "points" : "emm}Fp{v|NJBP@LBL@H?D?F?F?R?H?JARADAF?DADARCPGRGb@OTIXKPGl@W@?PB"
                     },
                     "start_location" : {
                        "lat" : 41.68930779999999,
                        "lng" : -83.51689159999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "5.3 mi",
                        "value" : 8491
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 302
                     },
                     "end_location" : {
                        "lat" : 41.62126809999999,
                        "lng" : -83.47709660000001
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eI-280 S\u003c/b\u003e",
                     "polyline" : {
                        "points" : "q`m}F|xv|N\\QNGNGJCRGXK@?RGREREB?NCPATCPAH?ZAJ?DAtCCV?l@A`@AP?f@?XAn@Ap@AdAA`DC`@AbACfBAz@CjBAxFERA~DGzCIZAlAI|@Eh@E@?LA|@In@IbAMPAJ?ZCJ?f@Cb@CZAl@E~@A@?xAEr@GfCEfCEdBEhBGrACrDG^@n@@jCF~@@VAP?F?t@?N?xBK@?\\Ed@]DEf@Et@Oj@KHAb@M\\K@?@?p@Sp@SnBu@`Aa@LGr@[@Ar@_@jAw@b@c@^[JIHGJI@A~AsAJI~BwAHETMFE@AzAaAVQ@ADAXSzByABAz@k@x@a@f@]hGwDb@U|@m@NIJIr@g@\\UZW|@a@JEPI@A@?|AiA\\WTQ^WFGVY`@e@BAJOJINS@AFIl@s@DGZ]V[Za@^y@?AZs@T[|@iA\\g@Zg@X]t@aABEd@i@DGd@g@f@g@TSTSFId@e@JKv@q@@?b@a@v@k@\\W@?DEJId@W`GwDbDsBdAq@d@YFEJGl@_@r@c@RMRMPK@APKf@YRKRKPKRKRKv@_@@?@?b@SXMTKJEFCh@SRGh@Sh@Q`@Ot@Yr@Wl@URKRITKPKRKRKPMRMPMRQPMPOPQPOb@e@f@m@@CRUPUn@{@`@i@^g@V]PSNQ^e@PQPSNORURSRQ^_@d@_@b@_@POt@k@~AsAPMRONOv@o@d@_@b@]POPOb@[LMz@q@`@[@ABCLK`@[JI\\YLKBCLKBCLIDCJKDCPOPMLMTQLIRQRO`@]BCLKDCLKBCJKDCLKBCLKBELKBCJKBCNOPSLMBCJM@ABCJKBEJMBEJMBCJMBEJOPWLQLQ@CLQ@CHODGHMDGHQLUJSBEHOBEHQ@C@AFOBGLWFOBEFOBGHQ@EFQBEHU@Eh@}AHYHWFS@GFU@EHWFYH[?ADOJc@?AFUDQ@AFWDSDODSFURw@Ja@DQJc@ViADQBGH]BOLc@?AFWH]H[H[FWH[FYFWBGDQH[FWH]FW@CJ[FQHWDMFQFQJWBEFQBEHQBEFM@A@GNWLUNWLSDGDGNUPWJOBENQPSPQPSNONMLMDCNMPOBCLIDCLIBCLIDCNIDCPKLGDCNGFEHEFCRITIRGTGTIREVGPCDANCVERCXCPANALAN?JAH?V?PAZ?P?V?T?R?T?V?T?@?V?P?P?X?T?X?R?T?V?T?TAX?T?R?R?l@?X?V?B?V?l@?@?H?`A?@?T?R?X?^?"
                     },
                     "start_location" : {
                        "lat" : 41.6872853,
                        "lng" : -83.5164661
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 mi",
                        "value" : 1140
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 69
                     },
                     "end_location" : {
                        "lat" : 41.61119720000001,
                        "lng" : -83.4782646
                     },
                     "html_instructions" : "Take exit \u003cb\u003e6\u003c/b\u003e for \u003cb\u003eOH-51\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eWoodville Rd\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "}c`}Fzbo|NRN@?J@~@B\\@X@L@H?L?R@P?f@?B?nCAR?L?V@J@BA@A@?@?@?RA\\?X@`AArA?fB?`B?|@?l@?rD?vBAbA?rA?f@?Z@V@l@D@?@@@@@Bd@HLBPDRDTHTHLFZLpAp@hAl@B@j@V"
                     },
                     "start_location" : {
                        "lat" : 41.62126809999999,
                        "lng" : -83.47709660000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 mi",
                        "value" : 1861
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 166
                     },
                     "end_location" : {
                        "lat" : 41.6000385,
                        "lng" : -83.4616003
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eOH-51 S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eWoodville Rd\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by Marco's Pizza (on the right in 1.1 mi)\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_e~|Fbjo|N~AoCb@w@HOPYT_@NYBEtAcCFMVc@r@mAd@y@b@s@P]LU`@u@f@{@FMdBuC~@_B|AkCvAeCVa@bAcBPYr@mAZi@xAkCzAgCbDwFjCqEjB}Cx@wAxAgCR[vAaCn@eAb@s@f@{@l@_Af@i@hAqB"
                     },
                     "start_location" : {
                        "lat" : 41.61119720000001,
                        "lng" : -83.4782646
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "10.7 mi",
                        "value" : 17275
                     },
                     "duration" : {
                        "text" : "13 mins",
                        "value" : 755
                     },
                     "end_location" : {
                        "lat" : 41.6040195,
                        "lng" : -83.25566329999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eOH-579 E\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "g_||F~al|NKKcAmAm@w@k@w@_@e@OWMOGOWm@Su@EWCWGo@AWHc@AS?iA?kG?]CoBAeDAW?qBCq@CmHEyXA_KAoGA{FC_K?aIA_@Gca@?MAaI?iCA{LAgE?wA?wB?cCCuGAsECaNA}IAyFCuQCqF?WCeGI}MMiTKmPKmPIiKEeFO{RAcBM}TKsNGuJOkUEaEC}DC_B?uAAsA@y@?w@Bu@@k@DgADq@VgGFoABw@@kA@{AAqAA_AEcAEkAGaAy@cKEa@GgAG_AEsACoASoUC}CMcOEiGOyVE}EAwBAeAEuEE{HA}BCqBCkEAcCAwAC_GC{HAgH?_G?oAA{K?aIAsC@iLAmD?}I?{B?oF?qECqd@AqI?uSCcP?aBAmB?qOCql@?q@Akd@AcKAmFEaQE_RAiBAoDGaYEmSEeYCuEEaWA_HAiICsH?c@?w@O_`@Oe[AoBAw@@m@@i@@WBi@Fq@Fq@Fa@Hg@Fc@TiALm@Jo@Nq@He@H_@BOBO@O?GAG?G?GAICIEMCGEIEEGGEEKEGCMAIAKAo@?"
                     },
                     "start_location" : {
                        "lat" : 41.6000385,
                        "lng" : -83.4616003
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "42.9 mi",
                        "value" : 69030
                     },
                     "duration" : {
                        "text" : "41 mins",
                        "value" : 2452
                     },
                     "end_location" : {
                        "lat" : 41.40251019999999,
                        "lng" : -82.5850102
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eOH-2 E\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cx||Fzzc{NCiPCI?e@Ckf@@o_@?wAF{m@?o@@_EFuf@?]@iN?eE@aA?wABmQ?k@?wBDq[?g@Jw^AyGA_HAeE@cF@}A?iABoFJeO@mD?o@BoC@eHDmM@iH@oYF}OB_D?kC?iN?eF?g@?kL?uM@cBBmg@@uPEqR?o@A{GAkKE_SA{F?U?qAAuGAoB?yD?GAuC?yA?G?[@oAB}A?c@?S?cBA_HAeFEcHAaBAI?IC}@GyROig@AsBAkDAaF?q@C{EAeDAeBCqF?uA?o@?U?{ADiG@aABm@?AFkKBuEB}F@cBB{CBcF?C?S?C?CCYF_LDwFBoFB_DBqC@[@C?s@BwB@qA@m@BwEB{EFgKBoC@cABuADs@B]F_AJy@Hk@Fc@Jg@Lg@DQLg@Rq@^cARe@NY^u@b@s@j@w@j@o@Z[ZYr@g@t@e@r@_@`A]h@M`@M`@Ij@Gt@GfAC`AA|@?nA?jCBfA?zA?~A?zAChBEz@Cd@EjAC~CA~HEpECl@AzBAjECb@?b@?`BA~@Ab@Cb@Eb@Gb@I`@Kn@U\\QVOj@[|AcA@AtBqAnCgBh@]tA{@bBgAxBuAnIoFfAs@r@g@PMb@]dLkJrHiGjI_Hl@i@fA}@tHkG\\YvPiNxE}DbBoAJG\\Y~@s@bDsCbDmCDEv@s@rCcC^[BCV[nC}B`Aw@rBiBpFuEpDaDZWfIgHx@s@dCyBxAyA`AiAx@mAVc@PYVg@j@iA~@uB@Ax@oBr@eBh@mAr@cB\\w@tAeDDG`CcGvEkLN]~@}BhAyCp@{A`BcEfCkG~Qsd@xGmPxAwDfBsEp@aBl@cBJ[Pi@Ts@v@}B|@oCx@eCbA}CN]Pg@v@gC@IN_@tDiLRq@Rg@HSLYTa@FMZe@JOdJwMfCqDzBaD\\g@zCqEhA_Bn@}@|@qADGx@kANU\\i@\\k@LWLYL]^cAj@mBX}@pCcJzA_F~AiFjBaG~@yC~@{ChAsDJ[hBeG^gABKDMHYNc@Pk@d@sANg@x@uBZu@JSN_@DG?A@E?C?MZm@N[NURa@Xg@f@{@nAcCzDgH`AkBdAoBd@w@JGHENWh@cAxB{DrByDr@sABEn@iAvB}DP[Te@rAcCdB_DVe@DINYVc@R_@BEFKLWFKVe@Ta@@ATc@JSBCFMLWlAyBVc@pBuDLUBCFKTc@Ve@Vc@Vc@p@oAFKR]Xk@vAiCVe@P[DGFMLWNYFINYNYDKTa@Vi@Tc@Vc@Zk@Zi@`@w@FKTc@LSRa@FKR_@R_@JQ@ARa@FKTa@HQ^o@JQl@kAFK`@u@HOJQLUR_@r@qADITa@\\o@HMN[Vc@h@cAFMDGZm@NUZm@JSNWn@iA?Az@}ARa@BCb@w@LWpCcFx@{ATc@P[r@qA?Ar@oAx@}AJO\\o@P[Ve@JSNY@A`@s@`@u@R_@FKZm@l@gA@Ct@sAXi@bAmBZi@LWNWXi@NWZk@JSJQBEZm@LUZk@`ByCh@aAZk@LWLSLULYFIBENYBEHOh@aAh@cALSLUHQf@}@P]LSLUNYJSZk@NWXi@LUNWf@_A\\m@Xk@\\o@h@aAdAkBJSZm@DETe@LSXi@NYVe@P[LUdAmBl@gAv@yATc@R]DIBG@?JULSXi@HOp@mAf@_ANWZm@Zm@JSLUJWLUBIFMXo@Ri@N]HWLY?AHUJ[JYHWPi@La@H[Ry@XgAFYH[F[FYFYFYD[F[Ha@PkAJw@BUFa@Hy@Hu@B_@BYJsA@MBo@Dw@B]@]?OBe@@y@@]@iA?g@?_@?y@A}@?W?]?[A]?[?]CaFEkGAwACoFOoXEiG?i@A{@?[AuBAyAAwBAcAA_B?a@AmA?aA?i@?M?]?o@@eA?mA@qD@M?m@?A?]?e@@eC@wA@qD@oB@sB@{@@sBD_KF_Q@o@BgJ@g@@aCDyJ?{@@y@?M?eAAa@AaAC_BEsAAOEaAAKC]C_@AYC]E]C[C]E[CYCYE]E[EWE[E_@Mw@EYKm@AAGa@G[Qw@Mk@Kc@G[IWI]Qo@IYK]EOOc@GQWw@KYWq@KWKYKUKWMYKSUi@Q[KUKQMUKUOWMUMUA?[i@]i@OSOUk@y@SUqAgBk@u@_@g@a@g@{@iAk@w@i@s@q@}@uBoCCGq@{@IM]c@EG_@g@OQq@_AA?Y_@i@s@c@m@Y_@QU]e@s@_A_AmAi@u@q@{@GIAAmA_BMSGI{@gAOSQU]e@]c@SWQWGKIKUYSY_@c@S[OQKOCAKOSW_@g@k@w@U]IIe@s@IKMUMSCCKSMSQ[GMQ]Ym@CGO[IUYq@KWK[IWCGEOEK?AGOI[IYIYK_@GUG[ACEUGYI[G[CUAEG[COGe@CMOgAC[EYAQAKAKAQE]Ew@A[Ey@AAA[Ag@AW?C?WAY?a@?I?M?_@?Y?[@a@?K?M@c@@U?YBc@Ba@@YB]B]@YB]DYB]B_@D_@D[BY?AD_@B]BS@EBYD]B]B[D[BYD]B[D_@B[D]BYDa@BYD]BW?AD_@B[DYB]D]B]BYD]Fq@D_@B[D[Dc@BYD[B[Fc@BW@UD_@BYDYD_@B[B[Da@BU@EBYB[D_@BY@G@OD_@D_@B[DYB]D[B]D_@Hw@B]D_@BWHy@B[Fg@Fs@DYB[Da@B]Hs@BYHy@D[?GBUFo@@GD]B]BO@MBWD]B]D[BYFk@h@}FFo@D[D]H{@Hy@Dc@@KDg@XsCFo@?ADWB]Hy@Hq@Dc@Ba@Hs@B]Hy@Hy@XoC\\qDHu@@I@ODa@NaBFk@JiAP_BHw@Di@Fg@B_@H{@BQDe@Fe@Fq@BY?AD]De@D]@SFm@Fe@BYDa@@OD_@Fo@NwAPgBJcAJeAJmAD_@LqAH{@D[Hw@?C@KT_CPiBLoA@KDa@BQDc@?CDg@JeABQDg@J_AFq@D]BY?EHw@B[@YDa@@WB]@_@@UBe@@]@[@_@@]?U@[?C?a@@[?W?]?a@@{@@iD?A?{A@_@?[?{@@sA?{A@y@?{@?[?[@_@?Y?_@?[?C?]@W?_A@kD?EDwK?}@@}@?Y?k@@iA?C?sA@q@?i@?cA@eA?qA?g@?Y@Q?S?y@?C?a@?U?G@o@?}@?_@@]?s@?Q?cA@]?O?U?s@?EBiDB_BFgBFeAB[Dk@@QBUFi@BQD[D[DY?CDYF[F[FYJk@?CFSFUFWFUH[HWHYHYHYJYHUBEBINc@HQN_@JWJULWLYJQNWLULULUDGFKLSNQn@}@LQPSRUJMDEJMPQPQPOLMRO@CPM`@[RQPKNKBAPMTOHEFERKRKPI@APIb@SHCRKPERIHC@ARGXGVIj@MPEd@IDATCRCVED?NCZE^EVCRAVARABAPATAXCh@C@?TCNAVARAh@EVATC@?VCPAVATARC@?RAVAVC^CTAVCRALAF?TCTANARARAVCB?TCTA@?VATATCTARAHANARALAF?RCVATATCD?NAXCNAZAPAVCRATCRAVATCTATATCVATARCTATAVCD?LATAXCRATCTARAVCTATARCVARALAJAPAVATCVARAJAHARATAVCvAIVCRATAVCPAXATARCD?NATAVCTATARAVCPAXAHAJARATAXCVAPARATAXCPATATCTAXARARAVCVAH?JAPAPAPAPAJAJ?PCd@CD?j@ETAPATCTATARATCTAPA@?TCTAD?PALAD?PCTAF?LARCH?JAVARCTANAXARCVANAB?VCRARARAVCVAHAH?j@ERAFAJATAD?LATA@ARARATATCTAVCTARAXCRAp@Cr@EFATALA\\C@?j@E^CLAf@CvAIj@EB?h@EVAh@CPCVAVAZCLARAj@EFAPAf@CTClBMB?b@Cn@EZCJ?XCPCVARCVATCF?JAVARCD?NAVAPAVATARAj@ET?DANAVA\\EVARAVA^Cb@CTARCXAj@ENAXATCTATATAFAJ?VCTCB?NATCVAJAFATCTERC|@Sj@QXGPG@?TGPGTITIPIRITILGXOPKVMJGDCRKXQLG@ATQLIRONKBCPMRQLMTQFGDENORSRSLMTWJMPSFIJKJOLQBEJMNSBGJMNWRYLUBCLUJSZm@HON]HOBIDKHQL[LYHU@AJ[L_@@AFQDQL]HYDOH[Le@BMFUFWH_@Ha@@GDUFYF[Da@FWBU@ED[DYDa@BYDWB]?AJy@BUD]H}@Da@Hu@Da@BMD]BW@KBUB]DYDa@Fq@LoAFe@B[Da@BSB[D[BSBYHs@@IBYBW@KJy@B]Hu@Hy@DYBY`@{DPeB@ONqABUJkAJy@BWFk@Fm@De@RgBJcA@MNuAB[TsBB[Fc@BS@QFc@@KHo@DWJy@@IBOF[D[DY@CDYFYFa@DWBKBMDYPy@Ls@Pw@Nu@Jc@DQXkAHYH[H[FW@EPm@\\mARs@JYDOBI^kAJYJYTo@Tq@HS@AJYJWJWDKBILYRe@h@qAL[nBqEJWJUd@gALY@A^_Aj@qAVk@@EHOJWLYJW|@uBVm@JS@CJYVk@LWN_@Zs@n@yADM^{@Vk@L[d@gAd@eAHSHQPa@Pa@FMd@gAd@gAHSf@kAXo@BITe@`@cAJUXq@d@gA\\w@HOb@eA@Af@kAN]BGLYXq@Xo@Vk@Xq@Zu@HQd@gAb@cAd@gAp@{A@Ed@eAd@gAd@gAPa@Vk@^_A@Ad@gAd@gAFOP_@Re@f@mAZs@Vo@Zq@JWTi@d@iA@Ab@eAd@cAL]`@}@@AZu@Vi@@ABGFKLWP]r@qAZg@T]HMLSb@m@\\e@`@g@\\a@Z_@FGLONOTWPQDCHILMRSPORQPOFEHILIVSZUPMpAy@l@_@j@[LG@AVOVKPINGFCh@UZM^Mf@Sj@QBA`@Ob@ODCVIf@Q`@OFEjAa@FC|@]f@Q^Mv@Yh@Sf@STI`@Or@Uv@YRGj@SNGXKj@SHCj@U^MHE^MHEd@QRIRKFCb@UPIDCPKb@Wt@a@TOXQRMTQ\\YPMROHIXUb@a@TSNOXWVYFGTWRSRU^c@b@g@RWZ]PS^c@|@cA@A^c@j@q@h@o@h@o@TYNQBCZ]FGz@cATWNQ\\a@x@_A\\a@FIX]f@k@\\a@d@k@t@}@fAmAb@g@JMNO\\e@X[BCd@i@^c@b@g@LMHMVY`@e@Z]V[LOPSd@k@PSLO^a@^e@h@o@FGt@y@\\a@`@e@PSLQBALQPS^c@DG~@eAr@y@NSPQt@_ALM`@g@`@e@HIdAiAt@}@NQ\\a@TYPUX[dAkADGj@o@n@w@l@s@DEpA}Ab@g@RU\\_@l@s@?ALMNQ^a@?ARUFEJO|AiBp@w@X[d@k@d@g@LQhAsA~@iAh@o@l@w@PSNS^i@JOPW`@m@DGR]`@m@JS\\i@Vg@`@s@Zm@Zo@Tg@NYVi@JWHQ@EJUN[JYRe@To@N_@JYJW?AVq@Ts@Ts@J_@FSJ[Po@^oAFUNe@Lg@Rs@\\kAZkAJ]Le@XaANe@La@?ATw@^oA\\gA\\mARq@XeAVy@Ng@Lc@Po@BGNi@Ru@Rs@@A\\mAJa@Pk@J[Pq@Lc@DMf@iBV}@Pi@\\mADOLa@J_@Pk@Ng@@GJYRs@Tu@L_@FUPo@Tu@Ja@Pk@Ru@Rq@Ng@BKRq@Po@@ARu@Rq@Rq@?AZiAx@oCXaAFUHYHYHYHWH[DMDMHYFURq@Ru@BEDQJ]HUTw@Pq@HUH[\\mATs@HYHY@EHW@EDQRu@HUFYJ]FUH[HYHYH]FWHYXoAH[HYDW@AF[XkAF]HYFYF[H]BKHg@HYF]FYF[ReABOTqALu@FYBSHa@Jm@DWHi@DYF[BUHi@DUPqAJs@D[?AJs@?CD[D]DY@K@OD]DYD]BWD_@BU@ED[B[@GBUBYD]B[D[B[B[D]B]BYB[D]@O@MB]BYB[B[B]@K@SB[B[@YB[B_@B]?G@OB]B]@_@BW@]B]@a@HoBB_@?IHeC?C@Q@a@Bw@@_@@Y@]?C?[@[@_@@[@y@@_@@u@@y@?S?G@}@@o@?I?y@@y@?e@?Q?m@?I?[?_@?OAK?{AAOAaB?]?]A[?{@A]?Y?Y?KAQ?[?[A_@?m@?EA_@?]?y@A]?G?UAy@?]Ay@?{@A]?g@?MAyA?]?[Aa@?W?]?]?w@?[?]?]?]?]@{@?y@@[?[@]?y@Bw@?_@@[?]@Y@_@@[Bw@?_@@]@[@[@]B[By@@_@@WDy@By@B]@[B_@@]BWD{@B[Dw@?EBYBYDy@F{@Fs@B]B[Fy@B]Hy@BYJ_A@WJ{@Hy@Hs@?CD[BYD]?AB]LoAB]BYD]Hw@BWH}@BYD[B[DYB[D]B]D_@D[BYD]BYB]D]D[B[D]B]BWDa@BWD_@B[B[B[B[B[B[Fy@B[B_@BY@]B[B[B[@[B_@Dq@B_@Ba@@U@a@B]Bq@BaAB[Bu@Bs@@_@@e@?MBe@?[@]@Y@e@?M@c@@]@[@y@@]@a@?_@@Y?]@_@?]@[?c@@]?[?]?W?]?{@Aa@?S?w@?a@?]A{@AY?[A[?[AY?_@A]?E?]A]A_@?]A]A[A_@Ay@AE?WCu@?IA[A[AWCw@A]C]Cw@A[AGGqAAYC_@AWA[Cc@CYIsAKwAC]?KCSAWE_@AWAGCWKsAEa@CYAUKiAGq@EYCYC]E[C[E]E]Gm@Ge@MmAMgAYmCQuACYOsAIq@Iu@E]E]C]EYE]C[Kw@C[Iu@E[Iu@UsBKy@C[Kw@CUI}@E[E[Is@I{@E]E[CWIs@?GIm@E]AOOmAI{@E[Iq@Ea@QeBAKKw@Iw@E[?ACYE[OuAUkBIy@E[C[Gg@AQIo@Ec@CYC[E[C]CWI{@E]Gq@G{@C]E]CYAYAGIsAEg@AEGeAASCg@KgBA]AGCo@Ec@Ca@A[AUACA]CYE{@C]Eo@I}ACm@Gw@Ci@Ce@CYCm@C_@Em@?ECk@Em@Eo@Cg@G}@GiAA_@AIEs@ASCm@E{@Ca@IwAGiAGcACi@E_ACe@Em@C_@G{@Ca@GmAEk@Eu@Cq@Ca@C{@Cc@Ek@AWC[Ew@A_@MqBOqCC]Cg@Ck@C]C[A]Ca@AUEk@Cm@GaACo@Cg@OeCEaAEu@Eo@Ca@Cq@IyAEy@C]CYCa@Ew@AYC_@Ew@C]E}@OkCKiBAQEo@OqCIsAIsAOuCOoCG_AGmAQ_D?KOqCIsAE}@Gy@?KCc@G{@GqACg@Ew@Eu@ACKqBE{@MqBE}@QgD]cGQ}C?MCa@OkCKuBIwAGwAEyAAK?KAU?AAKAq@EwACy@Ai@AM?U?KAYEsBAuBA[AwA?}@?[?A?I?CAg@?y@@a@?I?m@?u@?i@@gA?]@}@?M?K@y@@{@ByABuAB_ADqADwADqAB]@_@Bu@Bk@Do@@[D{@Di@Be@Du@F{@F_AHeAFw@HeADk@@IHy@L{APeBH{@Ho@H{@@INoAJ}@Lw@Hw@Lu@PuARqALw@Lu@RsAFa@He@P}@Fa@Hc@RcAJg@@GXyAPu@F[Nu@@GRy@RaAJ_@No@FYH[FYJ]FWDQJa@Ru@Ja@"
                     },
                     "start_location" : {
                        "lat" : 41.6040195,
                        "lng" : -83.25566329999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 380
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 13
                     },
                     "end_location" : {
                        "lat" : 41.4009815,
                        "lng" : -82.58093099999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eOH-2 E\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eUS-6 E\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ulu{Fh{`wNh@oBH]DMl@wBFSBMPm@Ps@J]BMj@oBf@iBBKH[DKH_@HULg@"
                     },
                     "start_location" : {
                        "lat" : 41.40251019999999,
                        "lng" : -82.5850102
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "25.8 mi",
                        "value" : 41518
                     },
                     "duration" : {
                        "text" : "22 mins",
                        "value" : 1323
                     },
                     "end_location" : {
                        "lat" : 41.4032467,
                        "lng" : -82.1383338
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eOH-2 E\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ccu{Fxa`wNLg@Ro@?ARs@Rs@Pu@Rq@Rs@FYJ[Rq@H[H[HWH[JYHYJWL_@Ri@JWFIDKLYLWLULSNULUNSLSPSNSNQPSDEJKPQPOPOPOROv@i@f@YTKPITKRIRIRG\\KNERETGRETCRCTETATCVARAj@ATAV?h@Al@AtAATAn@?VAP?bACV?D?^?^AX?n@Ap@Ap@A|ACN?lBCP?D?|@AfAAj@AT?TA`AAj@?f@Ah@Az@AhAAR?rACR?fAA^AR?`@A^?@?XAV?T?`BC`AAtACZ?vACvAAtAAh@AD?`CC`AAVAf@An@?`@A`AA~ACnAAhBCj@AlBAzACnBC`@At@AjAGJAb@El@Gf@Il@Kf@Kb@M`@Kd@Od@ODCh@SXM@?b@Sf@W\\SXQVOb@Y^YZWt@o@@?^_@NOTSPSJMJKV[PSNS@Ad@o@R[NUNULUT_@NWJUJSLULUJWTi@Xs@JWJWJ]L[HWH[HYJ[H[FWFWFWFWF[Ha@FWDWDUHg@DWFa@BSD_@LoAH}@@ODg@Bm@Di@Bu@@e@@y@@i@?gA@y@?Y@e@@_B?g@?a@@a@?W?[?]?]@_@?]?I?O?S?I@[?G?W?[?]@]?[?[?_@@[?_@?[?]@]?[?]?[?]@[?a@?Y@]?]?y@?U?E@]?_@?[?[@_@?[?]?]@[?]?[?_@@]?Y?w@?_@@]?S?[?]@Y?]?[@]?]?[?[?[@[?[?]?_@@]?[?]?[@[?_@?]?[?O@M?[?]?[@]?[?]?[?]@[?]?]?[@]?]?[?]@]?]?[?[@]?[?]?[@]?[?]?]@[?]?[?M?M?]@]?]?[?O?M@[?[?]?]@G?U?]?W?C?c@@]?[?]?]@]?U?E?]?]@[?]?]?[@]?]?]?[@]?]?]?]@[?]?[?]@]?Q?i@?]@]?[?]@]?]@[?]@[?[@_@@[?]@[@_@@[By@@]@[?]@[B]@]@[@]@]@[B]@[B]@[@]BY@]@YB[@]B[@[B_@@Y@[B]@[B]@[B[@[@]B[@[B]@[HsA@]@[B[@]BY@_@B[@[B[@]@[B[@[B]@[@[B]@[B[@[B]@]Bi@@OBY@]@[BY@]B[@[B]@[@]BY?I@SB]@[@E@U@]?A@WB]@[B[@]B]@]BY@[B]@[@[B]@[B]?C@UB]?E@UB[@]@[Dw@B]@[B]@[@[B[@]B[@[B[?M@OFuAB[@[B]@[B[@[B]@[@]B[Dy@@[B]@[@G@S@[B]@[@[B[@[B_@@Y@O@M@Y@_@BY@]B]@YB]@[@[B]@[B[@]@[B]@Y@]@K?OB]@[?M@M@]@[@M?O@]@U?E@Y@]?]@[@[?I@S?[@]?A@[?[?I@Q?]@[@y@?[?[@{@?y@?M?i@?]?[@]?[?]A[?]?[?[?e@AS?[?]A[?]A[?]A[?]A[?]AYA]?]AYA_@A[A]?[A[A[A[A]?[A]A[A[A]A[?[A]A]A]A[?[A[?EAUA]A[?[A]A]A[A[?[A]A[A]A[A[?]Cw@AQ?KA[A]?Q?IA[A]AYA]?[AW?EA]A[Aa@?WA[A[A]A[A]?[A[AYA_@A[?]A[A[A]A[?[A]A]A[A[A]?]A[A[?[A[A]?[A[A]?[A]Ay@A]?E?SA]Ay@?[?]A[?[A[?]?]A[?]?[?[A]?]?Y?]?]?[?YA]?]?[?]?[?]?[?Q?K?w@?{@@[?[?]?[?]?A?Y?[?]?A?Y?]?[?C?W?]?]?O?K?_@?[@O?M?[?[?I?oA?Y?[?]?Q?K?[?]?[?[?]?[@[?y@?]?]?[?[?]?[?[?]?[?]?[?K?O?]@[?]?[?]?[?]?[?[?S?I?]?Y?_@?Y?]@y@?]?[?]?Q?I?[?g@?o@?[?[?_@?Y@[?]?S?I?[?[?]?[?]?[?a@?]?a@?a@?]?]?a@?]@[?G?wB?{D@aB?{A?_A?sB?y@@]?kB?eA?{@?_A?yB?e@?{@?}B@y@?aA?}@?_ABcV?wB?uC@wC?{A?{A@qD?wA@wB?eA?eA?_A?_@?sB@qA?yA?yA?aH?]?]?_@?Q?I?a@?_@A_@?a@A]?a@A]Aa@A_@Aa@A_@A_@Ca@A_@E_AC_@A_@C_@C]Ea@C_@C]C]Ca@E_@C]E_@C]E]E_@E]E]E]E]E]Ky@G]G]E]Oy@E[G]G[I]G[G]G]I[G[I]I[GYI[GYK_@I[IYIYK_@IYEOCKK[K[I[KYK[KYIWM[GSACKYKWM]KWMYKWM[MYISO[MY?AKUMWMYaA{BMYg@iAYo@MYMYYq@g@iA[s@MWMYYq@MWKYoAsCg@iAiAiCaGaN[s@oAsCO]IQi@mAMYqAwC[q@g@iAAEWk@e@eAACMWu@cBM[MWKWKWKUKUKWMWe@eAKWKWYk@Qe@Q_@Yo@KWSc@EIKWKWKUe@eAMWWm@MWKWKUYo@Wm@KW_AuBWk@ACKUq@}AYm@Wo@KUMWKUIQ[q@ACKUKWKUMWKUKWKWMUIUAAKWKWMUKWKWKWMWKWKUKUMYWm@MWKWO]Ug@Wm@MWEKEKKUKWs@}AGOCGYm@KUkAmCACIQKWe@eAKWACKSWm@e@eAQ_@w@kBYo@MYMYQ_@IQKUe@gAKUYo@KWMUKWKUKWMUKWe@eAKWMYo@yAMYiNo[aDmHMYKWKU_AuBiAkCq@{AkAkCUi@O[e@gAWm@MWKU?AMYc@aA?Ae@gA_AsBACc@aAO_@a@}@c@eAKQ[u@Yq@o@uA?CMWKSKYIMCIKSKYKUMWIUIOCGMWKUKYKUKUKWMYKSKYKUMYKYIUKWKYIUAEIUIWIWIUIWI[KYESAEI[IWG[IWI_@AGCMGWEWAEEUI]EWAEEWEYG[E[E[EYCQAKE[EYEYC]CQAKCYC[E]Cc@AMC_@C[A]CYA]A[C[A]?[A[A[A]?Q?G?]?WAa@?[?]?Y?_@@mC?y@?[?{@?[?kD?sA?a@@w@?Y?Y?]?[?_@?[?[?]?[?]?[?G?S?Y?_@?[?Y@_@?[?[?[?[?A?_@?Y?[?]?]?Y?]?]?U?G?Y?]?[?Y?C@Y?]?[?]?]?W?_@?[?]?]?Y?[?]?[?_@?Y?]?[?]?[?[?]?Y@]?[?]?]?[?Y?]?[?]?[?[?I?S?]?Y?o@?e@?_@@]?W?]?Y?_@?[?]?a@?W?qA?_@?[?]?]?[?O?M?Y?Y?_@?[?U?G?[?[?_@@[?[?A?U?c@?S?C?[?_@AM?k@A[?_@AYA[Aa@CeAI{AQgCCYC[EYC]EWCUE_@E_@Mw@Ku@EYCOCMG[GYEYGYOu@I[ACEWIYGWI]GSCIEMI[I[IWIWKW?AIWK[KWIUCEGUGMM]MWKWQe@Sc@Ui@M[KWKWKSKWK[KWKWIUKYIUIWIYK[GYI[IYGUI]GYG_@ESCKG[CQIe@SuAEg@EWGs@Ea@Eu@C]C[GwAEoACaACg@?GGaBEiA?AA]Ak@EeAEuAEkACe@Cu@A_@EoAA_@Cu@EsAEyACy@A[C_@A[Ac@Cu@A_@AUA]C}@C_@AWEoA?GCw@EuAA_@KqCEyAEuAE{@C}@EmAEqAAa@IuBEyAGsBGuAA[IsCMmDKoDEaAKeDI{BCu@A]Am@EaAOqECy@Cw@Cw@Aa@AYAUAc@C]GoBC{@EgACm@Co@Cq@A]A]GqBMeDA]GuBE{@C}@AYA[C{@C{@A[Ay@A[A{@A]Ak@?KA[?_@?[A]?[?]A]?U?a@?a@?WA]?[@a@A[@Y?]?]?]?]?]?[@]?Y?]?_@?[?_@?[@]?[?[?]?]?]@Y?]?[?_@?]?Y@]?_@?C?Y?[?Y?]?]@[?_@?[?]?]@[?]?[?Y?_@?[?]@[?_@?]?[?]?[@]?[?]?]?[?]?U?I@u@?]?[?a@?W?_@@]?[?[?]?[?A?]@[?_@?Y?]?[?[?_@@U?I?Y?[?]?yA?Y?{@?]?[@]?[?[@y@?_@?[@]?]?[?_@@[?[?_@?[?]?_@?Y?]@Y?]?[?]?]?_@?Y?_@@]?]?[?[?]@[?[?]?U?E?_@@Y?]?_@?[?[?O@u@?sB@cA?I?]?[?]?]?]@y@?{@?w@@y@?]?y@?c@@q@?{@?y@@]?[?y@@yA?y@?]?]@]?[?{@?w@@{@?y@?cB?gB?QAeA?sC?wAAW?}@C}C?e@Ai@?]?MAcB?wBA}@AwDA}CCaBCiBAyA?sA?iB?cA?kBC{AAeA?]?y@AM?iA?g@?SAu@?a@?y@?y@?]Ao@?{@?e@?[?S?KAy@?W?C?]?YA[?C?w@?_@A]?y@?[?[Aa@?w@?EAo@?}@?E?s@?]?[@{AD{BFiB@W?CB]@WB_@B_@BWB_@BYD]Hu@Hy@D]Js@Da@DYFWD]F[F[F[DYF[@EDSNw@F[FYF[FYD[F[DS@EF[FYBOJg@F[D[FY?ADYF]D[D[@KBMD]B[@IBQB[B]B]@[B]@Q?I@[@]@Q?K@[?[?_@?]?[?[A[?]A]A[A[C]A[C_@AYE]?ECWC[EWE_@E[CWAEEYE[G[?CGWESAGGYG[GYIYESCGGWOg@EKIYACGUM[KYKWISO_@IQCGEKKUMUMWOUMUMSS[OUQW[a@OUMOs@}@QSQSY]}D{EaAmAqA_BSU{@gAQSsAaB_@e@MOSWa@e@k@u@CCOS_@g@OSOS]i@MUOUMSMWOUKUMWMWMYISYo@AEa@cA?ASo@AASo@EMMg@Su@GYOs@Ow@Os@Kw@My@Kw@Iy@C_@CWG{@E}@Eu@AU?CA_@Aw@AwA?w@?a@?w@?y@?]?]@kA?qA?iA@q@?e@?c@?s@ByL@cF?wABgL?k@@e@?S?mA?eA@y@?M?i@?{@?K?iAAy@?[?]A]Cw@A_@AWA[Ac@AOAKA[C]AWAEEu@I{@ASEc@K}@CWC[KcAKiAIw@CWEa@Iu@MwACWOyAMqAKcAIw@?EMmAKkAAICUI_ASqBMsAE]Ec@KmAOsAGs@O{AAEMsAOyAQgBIu@Iy@QqBGo@KaAKwAMsAMqBGy@C]IsAC_@Ew@C[Ey@IkBI_BEwAAEAUA[A]A]A[C[A[AO?QA[C[A[A]Ey@A[AQ?KC[A[A]A]C[A[A]A]C[A[A[A]C]AY?MAQA[A]C[A]A[A]AMAOKsCAQAWA[A]C]A[A[A[C]A]A[A]C[A]A[A]A[A[A]A[A]A[A]?]A[?[A_@?[?[A]?[?[?]@y@?]?[@]?[@]@]@[?]@[@]@[@]B]@[@]BY@]@U@GB[@[B[B]@G@SB[B]B[D]BYD]?EBUD[B[D]D[D[D[BYF]D[D[D]FYD[F[D[F[F[@CDWF]FYF[F[FWF[F[Nu@H[Nq@FYF[Nu@F]FWFYF[FYF[H[F[FYFYNu@Ha@H[F[FYF[F[F[H[DYH]DYF[F[D[F[D[DYD[D[DYD]B[D[B[B[D[B[B]B]@YB]B]@_@BY@[@]@[@]@[?]@]?_@@Y?[?[?[?W?y@?aC?w@?e@?U?w@@a@?]?_@?s@?_@?w@?c@?]?Y?c@?I?{@?e@?o@?cD?{@?gA?YAc@?]?]@]?[?]?]?[?]?]?]?[?]?]?[?[A_@?]?o@AaA?_@Aw@Aq@AcACmDAu@CwCCoCAc@AoCA{AAkCAo@?cA?k@?oA?cD@uB@o@?m@@mB@{B?c@?}C@kD@gD?u@@u@?[@]?[?]@]?[@]@i@@S@W@[@[@U@S@YDw@Di@F}@B]D_@BY@Q@KBQB_@Fc@BUNiAFe@Lu@D]DWHe@Lu@Lm@@GF]Nq@Lk@Lc@Li@Jc@J_@@ARq@Rq@J]Nc@J[L]\\aAN_@Nc@DKVo@Pc@N]L[LYJWDIFOLYRg@Na@BCJ[Rg@Xo@Xq@L]LYJUFSRa@Ti@Xq@L[HSLWL[Pe@N]JURe@Rg@l@}AL[JUHSHSBGbAaC@Ef@iATg@@EJWN_@JWTi@N_@^_AJWJWJUFODKJUJYJWJU@CHULYHWDKHSDODKNg@Ne@HYLi@No@DUFYH]DYFWD[DYD[DYDg@B[B[De@Ds@@[@]@_@@c@?]@S?[?q@Ac@A{@Ag@?e@Ck@Ak@?QCq@As@GyA"
                     },
                     "start_location" : {
                        "lat" : 41.4009815,
                        "lng" : -82.58093099999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "25.5 mi",
                        "value" : 41103
                     },
                     "duration" : {
                        "text" : "23 mins",
                        "value" : 1391
                     },
                     "end_location" : {
                        "lat" : 41.4739902,
                        "lng" : -81.69891969999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eI-90 E\u003c/b\u003e",
                     "polyline" : {
                        "points" : "iqu{FpsitNAe@AYAU?UAa@?CCaACo@Ai@Ai@Am@KcEKeFAe@A_@AYCw@Ae@?SAe@GeCA[GkCCs@Cw@KuECo@?WA]M}EEgBC}@C}@?UEmAAi@Au@AYA[Cq@?GC{@Ao@A_@Cu@A_@?[Cw@Cu@Au@Cq@?[EkAA_@CgACsAEuAAU?UAY?AA]Aa@?AAYA[AYA]?G?OA]A_@AY?OAOA]A[A_@A]C[AYCc@A_@A_@?SA_@Am@?c@EuACuACuA?OEaBC}@AQC{@C{@?CCw@Cu@A}@Am@Ae@CuAAOC_BC_AAi@E}@Ac@Ay@Ci@?GAw@Co@C_ACm@?GA]A[A]A[Cc@ASA]C[C]C]C]EYCWAOIo@Io@AKCME]EWG[ACCQEQEWI]CMKc@I]GYCGEQIWI[EOCKIUKYCGGQIWKWGQKWMYACMYMWGOMWIOCGMUMUMUOWEIOWMUMQGIS[QUOSA?MQQSQSIKGGIKOOQQOMAAQSOMOMEEMKOMAAOKOMCAMKSOQMCAUOMIMIGE]Sa@SOKKEg@YSMOIYOSKSKSMe@WSMkAo@k@[UMQKg@YQKIE[Ue@YSQSOQMSQQOOQSQOOSWCAKO_@c@OUMQOSKOCEOWMQ?AMUKQ?AKQO]MWO[GMCIIUGMCIKYCGGOIYIWKYIWOe@Oi@KYIYIYIW?AIWIU?CKYK]IWIYK[Ss@I[IUYaAMc@IWCGEQIWSo@?AIWOg@g@_BMc@K_@GQSs@IWIWIYSo@IYSq@AGQi@[eAUs@IWGYKWIYIWIYIWIWIWKYGQEOQc@KYKWKUKUMWKSMWMSMU?AMSMS]g@OSMSOQOSAAMOOQOQOOSSOOUSUQYUAAg@_@_@WSKQKMIEASKQKUKQGSISKWIQGQEUGSGSESGUESE[EMCi@EUCSASAWAA?SAQAU?U?U?I?I?U?U?S?_A?S?U?U@S?U?S?U?S?U?k@?g@@K?]?i@?W?i@?e@@wA?i@?C?uB@{@?oA@K?e@?o@?_@@s@?{@?C?U?C?O?U?_@?I?U?K?GAU?SAC?QAi@CMAE?UCSAA?SCSAEAOCQACASCUCQCSEA?UESEEAMCUEOECAUEKCGCQEOECASGUGQIEAMESISGi@SQIg@UQIUKQKQISKUMOKSKQMQMSKGGIEQMGEKGQMQKQMQOQKQMSMQMQMc@[e@]YS[Si@_@KISMECKIQMIGGESMQMmBsAQMw@i@QMs@g@g@]QMSOgAu@QMOKAASMQMQKQOIEGEQOQMe@[QMQKQMGEKGQMc@]QKSOQKCCMIQMQMMKCASOc@[e@[QMUOa@YOKiAw@QMQMGEaAq@c@[IEGG[UYQSM?Ac@[[SIGc@[SMQMQK?AQMi@]_@YOKUOOKc@[ECk@a@ECQMw@i@SOQMQKc@]C?MKw@i@OMSOe@[c@Ys@g@AAe@[u@i@u@i@UOQMc@YQMQMSMCCKIe@[[UYS[UIEc@]]WEEQMa@[QQOMECMKGGCCCCQOQOCCKKQOMOAAQOKKCEOOQQMMQSSU]_@KKCEOOOSOQMSGGW]CCKMOSYa@SWKOAC[a@ACOSCEIMOSOSMSMQOSEIIIMSOS?AOSMQACMMMSOSMSOSMSe@o@GIMQOUSY_AsAGGMS]e@]i@CA[g@Y_@{@kAQWwAsBg@s@oBoCGKcAyAaDqEqEoG{CmEiBgC?A[e@o@_AW_@_@o@e@{@[m@]u@c@gAc@mAUs@Uw@_@{AQo@Q_AKk@OcAUgBMyAIy@IkAIsCAGAuA?]?w@?I@mA?KDgA?EDqAFsBJ_DXgI^qLBq@Bg@?QBi@@]@g@@S@e@@k@@gA@o@@i@@g@?e@@i@@m@?e@?y@?C@gA?Q?s@?y@?iB?_A?_@?_A?u@?s@?mA?Q?mE?wA?sA?y@?iD?_A?iA?iA?cG@q@?W?g@?_A?Q?w@?aC?mC?E?S?}@?I?_H?_E?wH?cA?mA?mB?uC?}B?W?S?_@?_@?U?qA@cB?eD?aE?iE@oB@qD?k@?_A?i@?C@iB@kE@oD@sA?{@?[@m@?w@@aC?Y@gB?Y?gB@i@?S?S?}@@i@?k@?_@@aB?[?o@?e@@_@?g@?_A?I?]@m@ByKBgGBkJ@qC?y@@o@?_@@eC@wE?]@iE@g@?i@?{@?k@Ag@?A?c@A]A]AW?I?ECo@Cq@Cu@C]AYC]Gy@CYKcAAMCWKgACMSaBEWG_@CMKs@Os@Ms@Qu@Mk@Qu@Qu@Ke@Om@S{@YiAGYK_@Kc@I]IYMi@ESWgAQq@Mi@I[s@}C_@{AS}@o@oC_@{AMk@Mg@]wAKe@EOOm@Mi@Kc@Mq@ESG[Ke@Mu@EUEWEa@Ks@E]Io@E]Ec@E]E_@Ee@Ca@Es@Ce@Ce@AWAMCc@?SCe@Ae@?WAW?U?QA_@?Y?u@?A?M?_@?[?oA?o@?G?s@?{@?[?y@?q@@Y?]?k@?G?i@?aA?e@@e@?i@?wA?[?o@?g@?u@@{@?eA?Y?}A@s@?S?k@?gA?[?W@uL?_B@kC?o@?eC@}A?oA?U?U?{@@yA?eA?k@?W@sB@qA?oBHgH@uABoABcAB{A@i@?EBq@Bw@BuAXyKDeA@[TcJ@e@F}BBaA@a@HwCJoDDcB@a@H}CFkBHsCBaA@m@NuFBy@FcC@WNaF?O@e@DiBBs@@O@e@FwBB_AZiLL{EDyA@q@Be@@gA@IBsB?Y?q@?m@?[A[?SAg@?AAi@Ac@Co@Ak@E{@Ec@Es@Gy@Em@CSKiAK{@CUMiACOYaCKw@WyBQqAScBGi@c@sDOqAAKS}AIo@Ky@Gg@K}@MaAEc@E]Ge@Im@K{@UiBEa@Gg@OmAUmB?AWsBUqBEa@Im@OqAEUGi@MeAAMK{@G_@MkAWsBKy@AQM{@e@_EAKGi@Kw@K}@K_AKq@QyAKy@Q_Bm@cF[kCOkA]yCc@qDIm@a@cD]eCOqAQuAAOIo@Gc@CSOuAIs@Iq@MoAIm@KcACKScBUuBQqAMmAY_C]qCEYYgCQsAUkBIk@Ga@MeAK}@I{@UgBWwBUkBS_BYiCGa@?C[kCAGGg@SwBUcCI_AM{AGm@Ei@IiAC]C[Ey@OoBIuAEw@AWGy@C{@AKAWAWA[GmA?KEiACs@EuAE_BGyD?IAMCeBAi@AiAAs@CgBCwBAm@Ay@A_@?EAs@CyAAo@Ao@Aq@CqACkBAq@?ECuAAi@A}@?i@EgCCgBEkCCoBAaAE{CCiAAw@?WA]?O?u@?aA?k@@a@@c@@]@Y@]@[B[@]De@@UFq@De@Fg@L_ABSL}@@G?AHe@@E?ALi@j@cC@GH[`@uA?A\\gARk@DOz@iCl@iBh@aBJWLa@Tq@HS`@qATu@Vu@Rk@DMVw@Ng@VaAPs@Ha@H[HY?CRaAF]Lo@N_AJo@BSFe@Fc@JcAJ{@H}@Dc@Du@FaA@I?KFeA@_@?A@o@Bw@@iA@c@?W@}B?}C@{A@wE?iB?kBBaF?K@wA?O?{A@}@@{B?_@?_A?K?UBsE?eA?C?oC?A?K?k@?cC?S?q@?a@?C?g@AoB?G?}B?G?gAAiG?e@?}CA}C?yBAg@?{D?g@?wB?m@?{A?cB?K?_@@o@?[?O?{@@O@iD@}A?uA?_@@Y?U?Y@eD?K@c@?_A@oC@sA?qA@o@@gB?{@?I@eB@_@?C?}@@iBB}D?qA@aB@gA?]@m@@OBw@Dw@Bo@F_A?EJsANeBD]Fe@D_@D[Fe@BQDUF_@BSBQZgBLw@t@yE@MVyAT{AbAsGTwAJu@DYJw@Ho@Dc@@MFo@Fw@Fw@B_@F{ABs@B_@@w@DuBFgF@eAFiGB}F?iC@}D?U?c@@U@qBByADsCJuEDqABqA@]DiB?GByB@uA@qC@qC@_E?wB@W?gC?_@?o@?_@@_A@cC?cC@oBBcA@g@Bw@@o@?EHmA@]Dy@Hw@JcAHe@Fi@Ji@Py@ZaBBI\\_Bd@eBFSNg@HYFQ@CTu@BKDODMFSPi@Tq@l@mBRq@\\iAp@wBDOl@oBHUBGFSL_@?CJ[FUJ_@DQJa@BMBKFUF[F[@EDS@GBS@GBU@ED[BU@G@S@GBW@Y@G@U?E@U@G@W?M?K@[?G?[?]?g@Ak@A{@Ey@Cy@C[A]A]CYA]C[A]A]C]A[C]AYC_@A[A_@CWA_@Ew@E{@Ey@Cy@SkESeEO_DWwFSwEMoCOaDMoCGoA?GKsBKwBMoCi@}LGaAOkDCe@EcAMaCMwAGq@E_@Ei@Is@CMOcAMy@Ko@Ic@O{@EUG[Qw@IYQu@K_@]uAEQSu@CIEMIYCMMg@c@}AKe@Qq@Ss@Qu@G]GWG]G]G_@Gc@EUEc@CWC[Eg@Cm@AMAQ?OCw@Ak@?]A[?]?]?c@?o@AmA?]?e@?q@?}A?_@?o@?WAS?_@?c@?S?Y?]?w@?[?i@AeA?g@?G?qB?}@?_@A[?]?I?OAg@?O?]AQ?KAm@?_@CsAA[Cw@Cw@Ew@AUAa@Ew@C_@AWA[CYCe@ASGu@Gw@Gy@Eo@?EGu@Gy@Gw@Gw@e@{GKsACg@Ee@WyDGy@C]C[C[C[C[C[Gu@Ca@CUAYE]Gs@Iy@Ea@CQKs@Kw@Ku@Mw@GYSkAOs@Kg@EOGUIYG[IUI[GWIWIWIYIYQi@O_@IWKWIWKWIWUm@MYIWIWKWIUKWKWIWKWIYKUIWKWIWK[IWIWGWKYGWIYIYGWCMCKGWI[GYGWG[G[GYEYG[CUEQEWE[CWEWEWAKAME]ACCUCYE]Gu@G}@Gq@AWC_@C]AYA]C[A[A[Cw@AWAUAc@A[A[?]A[A[?]AY?[?]A[?S?G?[Aa@?]?Y@]?_@@w@?[@Y?_@@]@[@[B[?A@]B[@YB_@@YB]B[@MBOB[BYBW?AD]NqAFc@Hq@PsADYD_@Da@Hk@D]Fa@?CD]D[J{@Ju@D]D[D]BYD]D]BWB_@B[BY?K@O@]@[@]@U?E?[?]?W?Y?Y?a@?a@Ac@?}@?]A}@?u@Ae@?[?[?k@Aw@?e@?k@AS?k@?YA]?m@?O?S?S?QA[?[?G?e@Ai@?UAmB?_AA{@?MA_A?k@?UAqA?_A?WAq@?w@A_A?m@"
                     },
                     "start_location" : {
                        "lat" : 41.4032467,
                        "lng" : -82.1383338
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 mi",
                        "value" : 932
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 41
                     },
                     "end_location" : {
                        "lat" : 41.4686798,
                        "lng" : -81.69310349999999
                     },
                     "html_instructions" : "Take exit \u003cb\u003e170B\u003c/b\u003e for \u003cb\u003eI-71 S\u003c/b\u003e toward \u003cb\u003eColumbus\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "mkc|FfysqNDg@@a@?Y?Y?]@_@?]?[?[@_@?Y@_@?U@[@Y@WBg@@S@O@SL]F_ADe@@K@K@I@IBQ@MBQBI@I@IBKBKBGBG@GBEBG@EDIDIFIDGFIPQHIDCBC@ADC@ADCFCJEFCDAFCDAJAJCHC`@IVEfCg@@??APULCTETERE@?TEREVERCTCTCTCXCRAh@CXAVARAT?FAL?T?J?H?R?D?P@T?T?"
                     },
                     "start_location" : {
                        "lat" : 41.4739902,
                        "lng" : -81.69891969999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 mi",
                        "value" : 1109
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 47
                     },
                     "end_location" : {
                        "lat" : 41.4590787,
                        "lng" : -81.69369820000001
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e at the fork, follow signs for \u003cb\u003eI-480 W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOH-176 S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eParma\u003c/b\u003e",
                     "maneuver" : "fork-right",
                     "polyline" : {
                        "points" : "gjb|FztrqN\\FL@R@VBR@`@D^D\\Fr@JTBh@Hp@JpAP`BVbBTz@LjK|A~@Lt@JzB\\VDXD~@LF@RBJ@J@D?N@`@FZCJAF?JATEJCJCRGXIJGTKPKDCDCFEHEFG@CNKNQPQn@w@FU"
                     },
                     "start_location" : {
                        "lat" : 41.4686798,
                        "lng" : -81.69310349999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.4 mi",
                        "value" : 3837
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 140
                     },
                     "end_location" : {
                        "lat" : 41.4267475,
                        "lng" : -81.6830331
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eOH-176 S\u003c/b\u003e",
                     "polyline" : {
                        "points" : "gn`|FrxrqNHINS^c@NSNQPS^e@NS`@e@NQp@w@NQ`@c@PQRQNMRQPKXSl@]`@Q\\ONGZIRGFALCRERCTETA@?RCTAF?LATAR?VA^?P?^AL?j@?d@AZ?R?T?R?R?VAT?T?T?VAR?T?TAJAF?TATATATATA`@C\\CRCPAD?TCRCTC@?PATCTERCTCTERCTETERERETGTETERGTETGNEXIRGRGTGRGRITGZM^MRIRITIRIRKRIRI@APGRKFCJGRKRKRKTMPIPKRMPKXOLIRMPMJGFERMPMPMPMPMRONMROb@]TQNMRQNMNOPOPQPOPOPQPOPORSLKLMTSPOPQLMBANOPQPOPQPOPOPMPQPMPOPMRMRONKRORMPKRMRKPKRKRKRKPKTITKPIRKTIPITGRINEZCLETGTGRGZIb@KRETETEHAJCRETCRENCB?`AODALCVCZG`@GTCRETERCTETCTETERCTETCTERETCTETCTETERCRCTEh@IREVETCTERCRETC?ARCj@IRETCTERCTEFAJCTCTETCREXCNCVCTCTCRARCTAVARATATAT?TAV?P?T?T?T?T@B?N@V?H@J?T@H@H@T@TBF?L@RBTBTBRBB@PBRBTDRDTDRBRFVDTFJBHBRFRFTFRFJBHDPFh@PRHTHTHPFRFTHRHXJ"
                     },
                     "start_location" : {
                        "lat" : 41.4590787,
                        "lng" : -81.69369820000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "8.9 mi",
                        "value" : 14361
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 522
                     },
                     "end_location" : {
                        "lat" : 41.4244424,
                        "lng" : -81.5327161
                     },
                     "html_instructions" : "Take the exit onto \u003cb\u003eI-480 E\u003c/b\u003e toward \u003cb\u003eYoungstown\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "edz{F|upqNNFRHRHRHRHRHRHRJRHTJRHRJRHTJPJRJRJRJRJJFLFTLJBNHRNFDVRLHPNJH`@ZRPJHXVJHXRFDLJ@@JFLHTLNHB@FBLDHBLDJBLBPDPBN@J?P?F?J?RALCLAHAPEJCNERKFCLGJIFCHGHGHIJIHIJKFIHKNUFMHMFODIDMFMBI@CFSDQBMDSDSDUD_@Ho@@C@K@OBY@WH_A@KLkADW@EDQ@GBQBOBKDQ@IDO@EDOFQN_@@GHQP[DIDGLULUPWLQNSLSNST[p@aARYBEf@q@b@o@b@k@JMZe@X_@HKPWV[PULQf@q@@A^g@V[T[LOFIDGBEFGDE@?JEBCJQNSNST]V]LQPUZ_@@C`@k@PUT[V_@V[BE\\c@^g@NSBELOXa@V[V_@X]b@m@PSPWl@w@\\c@Zc@d@o@PUXa@NUXe@NWLUTc@Ra@@EFKRc@Rc@HURe@Rk@FQHWJYDQHYPk@Ry@Ni@P{@F]Hc@Ny@J{@Hg@De@Hk@?K?C?AGc@JeAPmBXkCLuA^mDRoBLqALmA^qDHy@LqAjAgLN}ARoBVcCLqAFq@Fm@ZuCN_BHy@J{@ViCRqB`@eETwBXkCRuBFo@Fk@Fe@b@kETgCNuAF}@DWFk@BYDi@Dk@BS@MBe@DiADu@@u@@[@]@s@@cB?k@?i@?y@Aw@Ae@Cs@AWEgA?OC_@C]C]Cg@Em@Gi@KiAIw@CYMmAm@oGw@_ISoBCUSsBYuCE]C]MkA[}C?AI}@K{@Gs@Iy@E[I{@KeAC[Gm@Is@Ea@MqAKiAOyAK_AEk@K{@C]Gg@AMEg@U{BWeCIw@?AQgBQcBAQEc@CWE[C[E[Iy@Iy@MqAE_@CYE_@C_@EWIw@Gy@E[CS?GCUE[C[Iy@?CEYCU?CIu@E_@CYC]E]Is@C]E]C[E[AQGg@Gu@E]Iw@C]EYCYE_@C]EYC_@Iu@Is@C_@Iy@E[I{@O{AGm@E]C[E_@CWE]CWE_@KeAAKC_@EYCW?GIs@CWEa@E]Iy@Iw@C_@Gm@Gc@C_@E[CWC[E[AQGi@I{@CWIw@Iy@Gs@E]Iy@E_@Iu@AKEg@SsBIu@?EEWMsAIy@C]SqBSqBOsAMsAC]E[E]C[Ea@a@eE?Ce@yEWmCScBGg@K{@G]?CESG]E[EOG_@GY?AGYCGMk@I]Ka@IUGWK[GSIWM]IWMYIWKWKUCGIQKUKUMYMYKUMWAEIOMYMUKSMYIQO[e@cAu@}AKUCGSa@O[KUWk@AAMYKQM[MWSa@e@aAWm@MUO]Sc@Q[KWGKGMISMWMWMWMYa@y@Q]KUKSIOOYQ]MUEICGMWMSQ[IOMWk@cAOWWg@MSCEi@aAg@}@[k@MUCGYe@OYIQCEKQMUMWAAOWIOMWAEWe@O]KWMUKY]w@CKKUKYCGGSM]IUKYEOEKUs@IYISK_@IUIWK[ISIWMc@Oe@GOOe@EUKY[gAAAK[K]?CIUI]GUIYEUI[G[Ou@Mu@Ks@G]E]Ea@MeACa@E_@?KAKCa@Eq@?GC[AU?EAYA_@A]?]AcB?u@Ak@?eE?yA?YAw@?K?iA?_A?q@?c@?[?Q?q@A_E?iEAyD?cFAeC?qB?qCAs@?_@?{BA[?{A?]AeB?i@?[?gD?IAuB?aA?oAAeC?g@A_B?w@?{AAeE?]?a@?]?W?_@?}@?_@?iAAi@?W?_@?I?O?_A?i@?eA?c@?u@Ay@?]?]?[?]?a@?y@?K?K?_@?y@A]?]?a@?y@?w@?a@?A?s@?w@A_@?G?Y?w@?c@?W?c@?y@?W?c@?]?YA_@?[?y@?_@?q@?G?]?Y?u@?{@AI?U?y@?]?}@?Y?y@?g@?U?a@Aw@?wA?]?{@?C?U?[?_@?}@?e@AcF?W?a@?Y?[Aa@?[?]?Y?{@?]?[?]?_@?_@?YAW@OAs@?sA?_@?wA?a@?U?_A?{@C_@?Y?[@mA?G@]?]@{@@YB_ADkABu@?G@]FwAH{BFwAD{@HsB"
                     },
                     "start_location" : {
                        "lat" : 41.4267475,
                        "lng" : -81.6830331
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.6 mi",
                        "value" : 5855
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 198
                     },
                     "end_location" : {
                        "lat" : 41.3818123,
                        "lng" : -81.513215
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e at the fork to stay on \u003cb\u003eI-480 E\u003c/b\u003e, follow signs for \u003cb\u003eYoungstown\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eI-271 S\u003c/b\u003e",
                     "maneuver" : "fork-right",
                     "polyline" : {
                        "points" : "wuy{FnjspNPY@ABe@Dk@L_BDa@Hk@B]BSFc@D[F[D[L{@F[F[DWFYFYH]F[H]FYFUJ]H[H[HY@CDQHYTs@HSFQJYHW@CJWHULYVq@JSJWN[JUFM\\s@LWP_@N]\\u@Rc@Rc@LYPa@HQFOJWXo@BIHOL_@LYJUJW@AHSVq@JYJUL]HULYHUJWJYHUN]BGDKHWJWJYd@mAfAqCL]HQRk@JWNa@HSHQL]J[b@gADKPc@J[`@cAb@iAPe@Xs@L[Na@JWLYLWRe@P]NYHOBGVg@NYZi@l@aALSNSNSNULSNQNSNSNQb@g@^c@Z[DEt@u@lCiCBErAoAp@m@`AaA~@y@tAsA~@_AxAwANOXYNOjAeAHI`@a@h@g@Z[@A`@_@b@_@TSXWdAw@NKTMRMRKRKRKRIh@SRGTGRGTGTERETETCRCTARCb@CH?P?TAT@B?P?V@T@F?^BB?TBR@dAJZBPBr@Hr@J|@JfANx@Ll@Hr@Jj@HF@ZFp@Jz@NTDRDXFp@LxAVjATRD|AXRDLBj@JzAX@?VDb@HvAVXF\\F`@HJ@JBbAR@?b@M\\Hb@Jn@NpAXl@Lx@P^HTDTF~@R|@RdATdATbARzA\\n@L@@PDb@H@@VFZF@?vAZx@Rf@JXFl@NTFvAZLBVFj@LPBh@L~@Rz@PNDH@xA\\vAZb@HHBv@Nh@JLBJBPDv@ND@PD\\F\\DTDH@RBLBL@TBb@DXD^Bp@FF@B?zAJX@H@R@D@tAHlAHhBL`AH@?t@DL@n@DL@^Br@BB?z@FbAD"
                     },
                     "start_location" : {
                        "lat" : 41.4244424,
                        "lng" : -81.5327161
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.7 mi",
                        "value" : 2760
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 96
                     },
                     "end_location" : {
                        "lat" : 41.3575257,
                        "lng" : -81.5142426
                     },
                     "html_instructions" : "Take exit \u003cb\u003e23\u003c/b\u003e toward \u003cb\u003eOH-14\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "ikq{FrpopNPT@@F@`@B|@FP@ZBXB\\BZ@H@F@P@N@R@L@P@l@DL@fAHt@F~@FN@P@TBT@VBv@D`AFN@V@TB\\BZBD?n@FB@x@Hp@FB@H@p@Hd@DH@NBr@Jv@JF@F@B@x@L@@PBTDVFTBNBb@HZF@?NB^HnBb@@?t@P@@`@HLD`@HJBTFn@NVFRD|@RPDVFTFTFz@R@?\\HLBFBdB^fHdBLBj@Jn@Lv@JxAN|AFjA@N@nAAJ?p@?VAHA`@C|@E@?XC`@E`@E`@GdAOXEPEh@KBAJCnA[TGVGbAWdCs@t@STG`AWf@ONENEPEb@MlA]zDeAtA_@l@OHCFCRGvBk@BA"
                     },
                     "start_location" : {
                        "lat" : 41.3818123,
                        "lng" : -81.513215
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 160
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 5
                     },
                     "end_location" : {
                        "lat" : 41.356125,
                        "lng" : -81.5137833
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to continue toward \u003cb\u003eI-480 E\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "qsl{F~vopN^KTETGVIp@O`@INEPC~@S"
                     },
                     "start_location" : {
                        "lat" : 41.3575257,
                        "lng" : -81.5142426
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "10.5 mi",
                        "value" : 16950
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 564
                     },
                     "end_location" : {
                        "lat" : 41.2549406,
                        "lng" : -81.37003079999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eI-480 E\u003c/b\u003e",
                     "polyline" : {
                        "points" : "wjl{FbtopNVE`@GPEPCNCPCPC|Di@TEPCTCVETETCXEJCTETE@ARERERETITGPG@APGRITIRKPIPI@APKRKPMRM`@YROLKHIFEPONOPSPQPQX_@LOLQHKNUNSLULSFMJOLWNWVk@JWJWLWJWLWd@gAHQVm@JWLWTi@bA_CN_@Tg@b@cAj@sARc@JUn@yABGJWJWLWJWFMRe@Vm@Xo@p@_BLWTi@HQDKHQLY`@aAP_@?ARg@Xo@BCn@_BDGTi@hAiCJYLY@CBGDIXo@Xq@JUHQ@GLUJYd@eAn@yAf@iAJWZs@Vm@HQBGjAoCh@oAFKJWJWLWJUJWd@eAJWLWJWXo@JWLYLUJWd@iAJUXq@LYLYJULWHSnCkGXq@Vo@LWJWLYjAoCfBcEd@cABIJSJWLWJWJWLWJWJWLWJWJWJULYJWLWJWJULWJWJWLWJYJULWJWLWJULWJWLULWXk@LWLUNWLULULULSNULUNULSLUNSNUNSNSNULSPSLSNSNSNQNSPQNSPQNQPQNQNQPQPQPQPQPQROPQPQPOPQxAsAt@q@bDuC`@_@LMTSPO|@w@l@k@POPORQPOPOPQPOPOPQROPQPOPOPQPOPOPQPOPQPOPQPOPOFEHIPQPOPOPQPOPOPONOPOPQROPQNMDEJIPQPORQPONOBALMRQNORO@CNMPOPQPOLMBCPQPQBCLKPQNQPQPSPQNQPSRUNQJOf@m@LO?APSNSLQPULSd@o@Ze@?AHMFKDG@AJQBCDIR[HONUDIFKLSLWNWLUBGLYBEFKVg@Zo@JULYJULWJWLWJWL]JWJWJWL]b@gA^cAFSb@eATq@LWVs@JW`@gAJWJWJWJWJYJWHWJWHS@CHSL]JWJWJWJWJYJWJWHWJYLYHUJWHUL[JWJWJYJWJWJYJWJWJYJWJYJWLYJWHWJYJWJWJWJYJWHWJWJWJWJYJUJYJWJWJWHWJWJWJWJYJUJYJWJWJWJWLYJUJWJWLWJULWLU`@{@R_@NWJUNULULSLULULS@Ar@kAd@q@PW`@m@`@i@dByBbAiA|@_Ah@k@LMXYXYPOPQ\\]HGJK\\]j@i@b@c@\\[r@q@jBkBPQn@o@Z]TWn@u@PUDGBCPSJOJMNSNUNSNSJQx@qANWJQLUd@}@LWNWl@oALWLYRe@BGJYJWJWL[HW@CHUHUJWHWHY@EFQ@CHYHYHYHYH[@EFUPq@Ps@FYH]Nq@F[FYH[^iBH[Lm@R_AXqAFYFYFYNs@FYH]j@gCVkABK\\_BLe@l@oCXsAF[F[FY@EFWFWH]FWHWFYHYHYHYRs@FUJ[HYJYJYHWJYHWZw@FQJUJWJWPa@Te@JWJULWHQBELWZk@LWLULULULULSFKDGNULSZe@`@m@`@k@`@i@LQNSPSLOPSRWPS^a@PQJKLMVWt@s@d@a@RQNORQPOPM\\WXSd@[PMRKPMPMRMRMNKTOJG`BcAd@YZSLId@[l@_@j@_@\\Sb@Yr@c@v@g@l@]v@g@h@]d@Y~@k@v@i@v@g@`@WdAq@p@a@|@i@TORMb@Wn@a@p@e@f@[h@]f@Yn@c@l@]`@W`@WVOROVOb@YPKRMVQ\\UZQ\\UZS^UXQ\\UVORM`@WTMTOd@[@?RMZURMZSf@[d@Y\\UTMTO^UTOTMNKVOVO`@WVQ`@WRMRMf@YPMRMTOPKf@]RMPKRMRMPMTMRONKRMTMPMROPMRMRONMRMPORQLILMPMXWNMPQRQb@a@NMLOTSRUPQ\\]RUPSPQNSRUJKPUNQNSNSNQd@o@HMNUPST_@T]xBeDn@_A|AaCZc@\\i@\\g@PWjBsCJOd@q@bA}Ad@q@d@q@h@{@|@sA|@qAp@cAhBoCj@{@\\g@~@uAlAiBJQ^i@NW\\e@\\k@^i@^i@LQBEJO^k@LSNSj@}@^i@\\g@P[JOl@}@^i@\\i@\\g@Zc@P[^g@NWNSLSNUNS\\g@LUBCJONULSl@}@^k@\\i@^g@NULS\\i@\\g@^i@\\i@^i@\\i@LSLSl@aA\\m@f@_AZm@LWJULWVm@d@gAJWJWVs@Rm@JYHYTq@Rs@Ru@@ENk@H[FYH[Nq@DYJg@Hc@DWLo@Fc@Fc@Js@BUD[Ho@?GDYBSDe@B[D_@B[?CDe@Di@HeAHeA?A@MB_@LiBJgAFw@Dq@De@Dk@B[BUBa@Fw@D]JuAF{@Fw@B]Da@?GJgAHw@Hy@Ju@D]D[DWF[D]Ha@Jq@DSBILm@Nw@H]FWLc@Nm@FWLa@^oAPg@HYJWFQL_@L]Ti@LYJWLWN_@Te@NYJSFMN[PYP[\\m@\\k@T]V]T]NUTYNSZ_@RWRSX]@A`@c@RS\\a@RSRU^]XYDGRSJKt@w@NOb@e@\\]DEPQPSZ[VYb@e@`@_@NQNQBC\\a@RS^e@^e@^i@\\g@^i@^m@dAaB\\i@b@o@f@s@~A}B"
                     },
                     "start_location" : {
                        "lat" : 41.356125,
                        "lng" : -81.5137833
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 mi",
                        "value" : 639
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 36
                     },
                     "end_location" : {
                        "lat" : 41.2508392,
                        "lng" : -81.3646775
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eOH-14 E\u003c/b\u003e",
                     "polyline" : {
                        "points" : "krxzFtqsoNj@y@l@{@zDsF|@oA`@k@p@_Az@oA~@sAdBeCLQZc@JO@AV_@f@s@p@aA"
                     },
                     "start_location" : {
                        "lat" : 41.2549406,
                        "lng" : -81.37003079999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "10.7 mi",
                        "value" : 17264
                     },
                     "duration" : {
                        "text" : "17 mins",
                        "value" : 1026
                     },
                     "end_location" : {
                        "lat" : 41.1572507,
                        "lng" : -81.2193078
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003eOH-14 E\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eCleveland - East Liverpool Rd\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "wxwzFfproN`@k@DG@G@K^i@^e@T[Va@lAiBJOXc@JMn@_AfA}Av@iAPWn@aAHKh@u@n@_Ah@w@JOn@_A^i@`AsA`@o@bA{AfBgCBCfA_BlBoCfAyALSV_@HMXa@`@k@LQhAeBHKZe@n@cAR[f@w@T_@NU@AxAwBjAeBXa@T[FKR[JMLS`@i@d@s@BE\\m@DGHMNYZo@L[Vm@FSRg@BIPo@DSHWJe@H]@ABKBMF]DWDUBYDYH{@D]@U@ODo@?O@Q@[?q@@g@@y@B_D@{C@E?w@?[?s@?S@Y?_@?w@@M?S?O?i@@_@?m@?Y?M@q@?OHmA?EFu@Dc@`@qCNs@Pw@BKb@}AFQFU@CDM`@gAPg@Na@DOVq@JUPk@Z}@Tm@Na@N_@r@oBJYDKFQnAiD@ElAeDZ{@DKDMTk@La@N_@Pa@N_@FMVk@P_@l@gATa@`@o@Zk@DG|@wAJOHQl@aAfBuCZg@T_@p@eAXc@Xa@Za@VYRWVYd@g@f@g@t@s@~CwCtAqAf@e@pAmAxBsBx@w@JIrBqB@ArAqAbAaAlAkAfBcBHKz@w@ZYv@s@v@s@vBqBNOvAqAXWxBqB\\]|@w@NMv@u@RQh@g@h@e@t@s@fAeAtBkBDEvAqAZYFCFCNOz@s@r@o@PQh@e@t@s@LK|@}@d@e@LM`B{AbAeAbBcBPQ@ABCDIhBgBnBiBb@a@`A}@jBeB\\]vAqARSpAoAj@i@JIj@o@`@e@^c@HKNSPWNW\\k@Zm@BENYZu@Pe@?ARg@ZaAFO^iATs@Pg@Rk@Xq@Rg@Vi@f@}@Tc@@ArAwBtA{Bp@iAz@yA`@o@BAT]^_@Z[FGn@e@j@a@\\Ub@YlAo@`B_A~DaC~@i@BAx@g@`Ak@\\Sn@a@~CkBnCaB|@i@lAs@h@]bBeA`HcE`DkBz@i@FC^WTOt@i@x@o@ZY\\]TULMLOV[JM\\e@X_@@Cn@_Ad@q@hAcBf@u@bBeCn@_Av@gAxAwBrAoBXa@bCqDj@}@tD}FPQtDwFx@wATYd@u@bBmC`A}AP_@R]`@o@x@qAl@_AlDqFVa@n@aA~BqDn@_AP[|@qA@En@_ALSb@q@\\g@f@u@`@i@z@mAh@s@V_@`@i@RYNQ|@oArAiBpBoCRWpEeGp@}@l@w@fCmDXa@b@o@h@_ANWt@gBTu@J[Jc@Nk@H]DUDUBS@C@KJ{@DWB_@Dc@Bc@Bm@Bg@@_A?o@@kA?eB?oB?sB?w@BaA?iG@aF@mD?sH?g@?i@C_@@wN?cA?eF@}D@}P?gB?aF?mG@yAFq@@m@BcEDkCFwCBe@@k@DsAHqBC]FqAHmALsAFaALuALuANi@\\mCPuA^mCHi@RmAVuALw@Lq@Ls@F[?YR}@Pw@No@Nq@Ni@?ENi@Le@Nm@V_AZeA\\eAZeAPUZ}@b@kAXw@FORk@Xs@v@mBHOj@sADK~AeDh@gAVe@P_@FWfAmBx@uAHOv@yAdB}C~DcHhFgJh@_AtBqDd@{@t@mAl@}@j@s@b@g@l@o@h@g@h@a@XUPMVOb@WHEfAk@dAc@t@SnA]`@GrAQv@EfACzA@~AD`BFfGTnCJjBFjEPvADnAEVAZJD?HATC^Id@MVINGXKNKPId@[ZSh@_@"
                     },
                     "start_location" : {
                        "lat" : 41.2508392,
                        "lng" : -81.3646775
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "5.0 mi",
                        "value" : 8054
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 375
                     },
                     "end_location" : {
                        "lat" : 41.1047855,
                        "lng" : -81.15505589999999
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003eOH-14 E\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOH-44 S\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow OH-14 E\u003c/div\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "yoezFtcvnNZU^UNQP[VSROt@q@j@g@bA{@bBwAnAeA?AfA_AhBcB@An@g@z@u@f@a@j@e@TE`@]^]fA_AdA{@PM?ANMvBkBJIz@u@|@s@~@{@^[RQNWPQf@c@b@e@X_@JMR[Zi@NWlAyBLUJSdAmBpByDFMz@_BDKXi@t@sANY^k@f@s@`@k@|@eAPQbBeBz@}@vAwAhBiBRS\\[j@g@t@o@JKjB_Bp@k@r@k@PMxAmArBcBXURQRQnAcAbBuAn@i@lAaAt@m@tAmABAXUlAmAFIt@w@|@eAx@eAr@cAR[NSp@gADI`@q@HQR_@t@yAn@yAh@sAf@wAXy@Nm@\\uAPs@RiALm@N_ANmAHs@LgAJcALkAHu@TwAVqATeARu@Rq@Vu@`@aAFK\\q@b@y@Zk@h@q@j@q@f@g@HILMh@c@b@[z@k@|CsBrBsAxA_ALKl@e@h@e@FG`@c@^a@hA{A`@k@\\e@`B_CXa@\\g@t@eAV_@bAyAFKdBaCt@gAbAwAl@y@l@{@l@u@f@k@XYNQPMVU@CdBoAp@e@tAcA`Aq@pAcANM`@_@BAZ]r@w@HKX_@DEd@q@FKn@_AzCmEVa@dBeCXe@RYhAeB^g@T_@tByC`@m@nBqCFK~@qAf@s@p@aAXa@b@m@h@u@NUFKr@aAr@cA?AV_@lAcBpAmBJM`AuAJOVa@nDaFV]T]hBeCNSHM~BgDjBqC|@mANMLQ@A`@i@PW`@i@p@aArAiBp@eAVc@LS|@sALSR]zA_CjBmCzAyB~@sAPWf@u@@At@kAbCkD"
                     },
                     "start_location" : {
                        "lat" : 41.1572507,
                        "lng" : -81.2193078
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "16.9 mi",
                        "value" : 27189
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 889
                     },
                     "end_location" : {
                        "lat" : 41.11017450000001,
                        "lng" : -80.83355990000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to merge onto \u003cb\u003eI-76 E\u003c/b\u003e toward \u003cb\u003eYoungstown\u003c/b\u003e",
                     "maneuver" : "ramp-left",
                     "polyline" : {
                        "points" : "}g{yFbrinNQW[_@OSGMa@q@MYKWMe@I[E[G_@Eu@AGAw@?y@A_A?c@CcB?m@Aq@A{@?AMg@CqF?[?]Aw@?S?c@?_@?Y?C?y@AaA?mAAy@?]?[?]Aw@?[?]?M?e@AgCA}C?_@?iBAc@?}@AcD?oBA_@?_@?w@AuA?y@?w@AsA?yAAy@?[?]?Y?]AuA?y@?w@?[A{@?w@?y@A[?[?Q?g@?[?]?q@AaA?[?[?]Ak@?i@?YAuA?y@?]Ay@?uA?y@AwA?sAAsB?]?uA?uA?]?Y?{@?w@?y@@M?i@@y@@y@?]Bw@?[@]@y@By@DuA@]Bw@By@Bw@By@FuABy@By@Bw@@[B]@Y@[@_@Bw@By@@[Ba@@W@[Bu@DwA@[F{ABs@@]@Y@]Bw@B]Bw@Bw@@]By@@[B[@[@S@e@@[@[@[B[@]@[@[@]Dw@@_@Bu@@]Dy@?WBa@@u@@]@[@]@[?[@]@Y?M@O@y@?[@]?[?[?K@m@?]?[?]?y@?[?[?U?_A?]?]AsAAw@Aq@?[?CAYAy@Ay@Cy@?]AMAi@C{@Cm@?KA]Ew@Cy@Cy@C_@A[Cy@C_@AWCy@Ew@Aa@AYEu@A_@A[Ew@A[A]A[C[Cw@A]Ey@A[Ew@A]A[C]Cu@C]Cw@A]Ew@E{@Cu@C]A]GqAA_@Cw@C[?MCk@A[A]?[A]AKCgA?]Cy@Aw@Ay@?QAcAAuAA]?u@?A?[?[?[?]?[?]?w@?y@?y@?i@?M?]?[?{@?[?W?_@?[?[?_@@u@?]?y@?[?s@?a@?y@?y@?W?a@?]?u@?]?[?y@?y@?w@?W?c@?[?]?Y?y@?y@?[?[?[?]?G@wB?k@?y@?]?[?[@[?]?[?]?]?w@?w@?]?[?U?E@]?w@?]?[?[?]?[?]?]?Y?[?_@@u@?u@?a@?wA?w@?y@?w@?uA?y@?y@?[@uA?sB?]?w@?]?y@?Y?a@?oB?Y?[?]?]?O?M?[?Y?]?oA@a@?[?]?I?S?[?]?[?]?w@?_@?Y?a@?[?c@?m@?_@@[?]?Y?Y?[?W?uA?}B?[?W?c@?[?y@?c@?q@?Y?_@?Y?c@?s@?]?Y?uB?i@?K?_@?eC?e@?qA?_@?]?Y?]?[?W@aA?[?Y?]?[?a@?oB?sC?iC?w@?]?y@?w@?s@?mA?M?_@?]?]?oA?cE?_C?{A?sA@s@?oA?s@AkC?W@sD?}C?sA?M?gA?[@yD?k@?G?C?eG@mJ?cA?uA@aB@iA@g@@uA@y@?I@WBeADcB@YB{@@o@@GHeC?CBW@WJ_CDy@B_@NgCFw@B[@Q@G@U@G?AL{AFu@NgBT}BBUJeAHs@D_@Hs@D[RaB@IJo@@M@CPwARkA@MTwAZoBBKZgBP_ARmABIJg@Lo@BMZyAPy@f@aCBGFUJg@\\{ALk@DUJa@FUBOBIb@sBHYXsADULi@@CVkAZuAJg@f@wBJg@H[Jg@XqAb@mBVkAx@uDBMPaAPcABQJm@@G@EHk@L_AJs@@KBSDYBYD[Dg@J}@Di@Fs@H_AB[Ds@F}@@[@[HeBFgB?CD_B?]@o@?K?e@@c@?u@?W?a@?a@AwFAqBEeO?o@?m@A_B?o@?o@A{@?m@?g@AgDAgE?_AAiA?uBAaA?y@AcD?C?o@?O?o@AA?A?k@?aCAa@?[?w@?I?S?w@A_@?y@?w@AuA?}@?]?a@AmC?Y?WAWA{E?I?_@?{@AwB?i@CwG?m@?S?w@?UCeF?s@?cBAS?sA?w@?A?[AaA?Y?aA?qAAK?eB?m@Ag@?qA?}A?A?AAiAAkEAwD?]?M?OCyG?C?o@CmLAyA?i@AgE?mAAeEAk@?iCAo@Aq@Au@Ac@EqAAs@AEIuBGgAK_BKsAEa@Ea@KkAOyAIk@Io@?AOgASsAMy@SiAOy@UqAKk@Ia@Ms@Ms@Mo@Ga@Mq@O{@a@yBKm@CM]gBG]UsAUqAIg@CMSsAMs@Ky@Ku@Ku@EYACKu@E[Gi@AMKw@Iw@CKGk@Iw@C[E]Iu@Iy@Gw@?AIw@Gu@G{@C_@CWGy@Gy@Ew@C[C[C]Ew@A]C[A]AYC]A[A]C[A[A]A[A]A[A]A[A]A]AYAY?OAOCwAAaAAm@A}@AW?qAAa@?[?w@A]?[?{@?_@?k@?K?o@?]?g@?K?w@?k@?Y?]@[?[?C?y@?{@?sA?]?{@?W?c@?y@?y@?o@?I?y@?S?eA?}@?w@?y@?{@@y@?Y?_A?eC?_A?w@?O?cB?w@?W?G?]?s@?m@?M?I?cB?c@@sB?eG?c@?_E?C?eE?o@?_B?y@?c@?q@Au@?g@?YAkAAm@CgA?OCkA?[Cu@Cu@A]Ac@?UCy@GmBAe@AYA]Cu@Cy@A]Cy@Cy@Cu@Aa@EsACy@Cw@AYC}@As@C_@A]As@AUEcBA[GaB?CC}@Co@?UEqAG{BIkCCw@CiACi@Ai@Cm@E}AEwAKyDk@_SAUAu@GsBEuAC{@EuAEuAA_@IaCg@{QOkFQmGQqGMkEKqDGkBEkBUiHIeD_@sMAc@A[EuACy@Cw@Ay@Cy@Cy@Cw@Cy@Cy@Cy@Cy@Cw@Cy@Cw@A]A_@Cw@Cy@Cw@Cy@Ay@Cs@Aa@A[?]Cy@?[A[A[?]Ay@Aw@?y@Ay@?y@?y@?y@?w@?y@@y@?y@?y@@w@?y@?]@y@?[?[?]?y@@w@?w@?y@?]@[?i@?O?y@@y@?w@?y@@y@?y@?y@?E?U@y@?s@?E?y@@w@?W?a@?u@?]@w@?y@?I?o@@y@?[?]?a@?W@y@?y@@uA?]?}A@{@?K?Q?]?s@?y@?{@?u@?w@?{@Ao@?C?y@?u@As@?C?y@Aw@As@?_@Aw@Aw@Ay@Au@Ay@Au@Ay@Cw@?QAe@CaAA]A{@A[C{@AYA_@Cw@A]A[A]Cy@A]A]Cy@A]Ey@Cy@Ey@Cy@Ey@Cy@C[Cy@E{@Cw@Ey@Ey@Cy@E{@Cy@AUEaAEy@Cy@Ey@A]Ew@C{@Ey@Cy@GwAEy@A]Ey@Cy@C[A]A]EgAAMEy@Cy@?AGuAEy@Cy@Ey@Cy@Ey@Cy@Ey@Ca@Cc@AQAYA]C]Cw@E{@Cy@C[Cy@Ey@A]A[Ey@Cy@GyAEw@A]Ey@AUAc@C[Cy@Ew@A]C{@E{@Ew@IsBCy@C]AWAa@Ew@C{@E{@Cw@C[IuBCy@Ew@E{@Cy@Ey@Cy@Ey@Cy@Ey@Ey@Cy@A[E{@C{@Ew@Cw@E{@Ew@C}@Ey@Cy@E{@GuAMmDC]Cy@Eu@C{@Ey@C{@GwAEy@Ey@Cy@Ey@Cy@A["
                     },
                     "start_location" : {
                        "lat" : 41.1047855,
                        "lng" : -81.15505589999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "4.1 mi",
                        "value" : 6522
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 218
                     },
                     "end_location" : {
                        "lat" : 41.123737,
                        "lng" : -80.7593993
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eI-80 E\u003c/b\u003e",
                     "polyline" : {
                        "points" : "qi|yFvxjlNC_@A[Ey@A]IoBAa@C]A]A[C[A]A]C]Cy@A]C]A[AQ?IEy@A]A]CYC_AC[A[Cw@G{AGsAAYC_@A]Cw@C]AWCy@C]A[A]A]C[Cw@A[AOAMA[A]C]A]A[A[C]A]AW?CAUCc@AWCk@@WCi@KgCAg@Cc@CeAEsAAy@Aw@AiAAYAyB?[Ao@Ao@A_@Au@A]AYC_@A[C]A[C]Gs@Ea@Ky@Ks@G]EWE[GWOu@I_@Os@Mk@Qs@CSOk@I[Ke@EQCMKc@Qu@Ka@ESQs@IYKe@EQMm@K_@G[Ok@GYEQMi@[qAEUMk@EOW_AQy@I[Oo@I]GYI[Qs@G[IYGYG[IYGYIYG[IYGYGYI[GY[oAGYGYI[GYI[GYIYG[GYIYGYIYG[IYGYIYG[IYIYGYKYGYKYIYIYIWIYKYIWKYIWKYKYKWIYKWKWWq@IWKYKWKYIWKWKYIWKYKWKWIYKYIWKYIYIYIYKYIWI[IYIWIYIYIYKYIWIYIYIYIYIYIYIYKYIWIYIYSs@IYIYIYIW}@{CUs@IYIYIYIWIYIYK[IYIYIYSs@IWK[IYGUK[IWIYI[IYIWIYKYGWAAIYEMCKI[IWKYIYIYIYOg@Me@Uu@IWI[IYIYIYGYIYI[GYIYG[IYOu@IYG[G[GYCICQG[GYG[G[EYG]GYG]EYEYSuAG[E[E[E]E[EYE]C[Kw@C]E[C[E[C]C]EYC]C[C]C[C]C[C[A]C[C]A[C]A[A_@C[A[A]A[A]A[A]Cy@?WAE?]A[?]A]?[A]?[?[?}@A[?]?[?]?[?_@?[?[?]?]?]?[?]?y@?{@?[?]?[?]?]?[?]A[?]?]?]?[?]?[?]?]?[?_@?[?[?_@?[?[?wA?]?[?_@?w@?]?]A[?[?a@?W?[?]?[?]?]?Y?]?]?y@?]?uB?Y?]?[?]A[@]A]?[?]?[?]?]?[?]?[?S?cA?[?[?cB?_@AsIAeC?wFAgE?eB"
                     },
                     "start_location" : {
                        "lat" : 41.11017450000001,
                        "lng" : -80.83355990000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "13.8 mi",
                        "value" : 22280
                     },
                     "duration" : {
                        "text" : "12 mins",
                        "value" : 735
                     },
                     "end_location" : {
                        "lat" : 40.93210930000001,
                        "lng" : -80.71951159999999
                     },
                     "html_instructions" : "Take exit \u003cb\u003e224A\u003c/b\u003e to merge onto \u003cb\u003eOH-11\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "k~~yFfi|kNNI@?@qC@cA?i@?_A@w@@c@BmA@c@B_@?]@C@]B_@@WBa@@WJo@Py@Ng@JUHSR_@`@k@X]\\WTQZQTId@OVETE\\CP?L?P@L@NBLAH@PDD@D@ZH@?NDTHXHbAZjFlAb@LJ@J@N?j@Jz@LzAPdBNRBT@TBTBT@T@f@DdADfBFT@T@jDLlBH`Md@T@b@@dADhEPd@BR@V@R?V@R@T@T@T@R@T@T@T?R@T@T?T@V?R?T@RAV?R?TAT?TATAZANATCRATCRATCZELAVERCXE~AWfBa@`Bm@JETIRIRIRITIPIRITKRKRIRKRKRIRKRKRIRKRKRIRKRKRIPITMPITKPIRKLGZMPKRIRIRKRIXKLGRITGTIRIRG|@YRGTGRGRGREVGRERGTETERGRCTERETETCTERCTERCTCTCRCNAXCVCRCzAIp@EbBGjB?|BDbDHnFLD?T@R?T@T@T?R@T?V@R@T?H@J?R?T@b@@F?T@T@R?T@T?f@BV?N@^@rBDH?z@BvABD?tAD|@BbABpABj@@h@B|@@r@BV?lBF`CDt@Bv@@lCFbCFjCFR@|ABdCF|@B`BDdABpABt@B~BDdABdABxBFnABB?b@@r@@R@b@@hAB@?l@@~@Bn@@J@xABB?tA@@?h@?z@?D?X?f@?f@AZ?TAR?R?@AP?r@A\\AZARATA~@ET?d@CZCD?h@EB?p@Eh@ED?x@GhAKbAKHAtAO~@Mf@GTCh@Ir@KLCj@KRC~AYl@Mr@Mh@MRCTGREVGf@MhBc@t@Q~@Ux@SpCq@lBe@rA]~A_@~DaAlEeAh@OzG_B~Cu@lD{@b@KLCRGtFsAj@Md@MxJaCfFmArA]x@S`Ck@b@Kd@MBAb@K^IhBc@\\I`Ba@h@MrCq@f@MXINCRGhCo@~@UNCRGnAYrCq@vBi@jAYjAYrBg@hFoAbAU?ANC`EaAn@OnA[~A_@t@SpA[p@OtCs@~FuAfFoAl@MbB]bB_@REh@Kb@Iv@Mn@Kf@IxBYjAOZC@ATCh@El@Gr@Gn@GnAIz@GFAD?ZC\\ArBK|AEzAC^AR?n@Ah@?x@A`D?L@~A?jA?fB?xE?xB?vA?h@?j@?T?fA?b@?b@?xA?B?P?R?R?J?r@?~@?N?Z?bB?F?z@?rA?b@?d@?V?fA?f@?hB?V?L?`B?p@?hD?fA@T?h@?\\?B?\\A`@?^?X?F?LAT?TAj@C@?n@E`@CNAt@I`@Eb@Gj@Ih@IPEp@MVEh@M@Ah@MPEt@S`@OVI^MFCh@SRIVK@?LGRKh@Uh@Wb@Wv@a@TOd@YLI`@Yf@]d@]LIj@e@~@w@v@u@t@s@|@aAt@}@LMt@_ArAcBnBcCn@w@^c@`@g@^e@DCV[n@u@BCNOl@s@BAt@w@r@u@p@q@jAkAlAiAlAeAh@e@^]`BuAhA{@f@a@`@[RMd@_@x@k@JIVQTOb@[ZS`@W\\Ur@e@v@c@RONIVOf@Yx@e@\\Qt@a@PITOf@W\\O^SpAm@d@Sl@YNGl@Wh@UVKx@]fAa@bA_@`A]v@W|@Yp@Uf@MNGf@MVIh@Mz@UJE\\IlAYzA[hAWZG|@Q^GJARELCFAXERE~@OXCREf@GXEj@GTEVCj@G~@KVCTCTCTCbAKbAKr@IJAj@GVCTCTCTCTCTCVCTCRCTCTAXEh@ETCTCTCVCTCJCH?TCTCTCTCTCTCBAPATCVCTCTCTCVCRCTCn@Gl@Gh@Gh@GRCj@G@?h@EVCj@GTCjAM^CBAHA|AOHAt@INA`@Ev@IpAO`@Cn@Ih@GbAKv@I^ERAhAMj@GpD_@x@IDA|@I~@KjAMrAMf@Gl@Gb@Ej@GtBSfCYVCf@Ex@GNCH?|@Il@EZAD?t@Gd@Al@Eh@A`ACz@Cn@C~@AtAAN?r@?J?bA?l@?Z?P?`A?f@?~B?hD?Z?zA?`B?\\?t@?bB?n@?n@?zA?\\?lA@pA@jDFd@@fABd@@bADN?dADn@DJ?pAFz@Bp@F\\@n@DrBNnAHxALvBNpBN|@Hp@Dx@FzAJvAL~ALz@FL@z@FZBh@DbAH`AH~@FR@dAFt@Dd@@z@Dj@@h@Bt@@R@J?r@@fA@bB?f@?t@?r@An@?x@C`AA`AE\\AdAEj@Cp@Ej@Cr@GRAx@GrAMp@Gt@I^ETCVC^Gf@GpAQr@KDAjAQn@IpAS@?`AQtASFAb@G`AOTC^GZEHCt@I`@ENAXCb@CF?j@Cl@?T?^@`@?l@BZB"
                     },
                     "start_location" : {
                        "lat" : 41.123737,
                        "lng" : -80.7593993
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 315
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 31
                     },
                     "end_location" : {
                        "lat" : 40.9296374,
                        "lng" : -80.72122069999999
                     },
                     "html_instructions" : "Take exit \u003cb\u003e27\u003c/b\u003e for \u003cb\u003eOH-46\u003c/b\u003e toward \u003cb\u003eOH-14\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eColumbiana\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "upyxF|otkNRN@@d@HVFRFLD@?RFPFRHFBXLB@XLFBPJHDJFJFHDPLRNVRNNPNLLDDFHJJ?@RTDFBFNV"
                     },
                     "start_location" : {
                        "lat" : 40.93210930000001,
                        "lng" : -80.71951159999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.4 mi",
                        "value" : 3898
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 209
                     },
                     "end_location" : {
                        "lat" : 40.9001035,
                        "lng" : -80.69760599999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eOH-46 S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eColumbiana-Canfield Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "gayxFrztkNrA{@vA_AlAw@xCmB|AcA~@k@ZSl@]\\Qf@Uf@SZMLCBCTG\\Kr@U`@Kb@M`@MfBg@\\KfA]DApAe@LG`@Ob@QXOh@WZOvCcBVQb@Uz@i@`B_A?AfEgCv@g@|@k@bBgAxA_A^UFEtA}@lAw@nD{B|AcAXQtBsAdFaD|FsD^U|BwAvCkBjAy@r@k@BA^]XYZ]FIPULSHMV]`@u@d@y@Te@zAqCvDeHbAkBTc@pCiFf@}@DKn@gALWLS`@s@l@_Af@s@^e@FI\\_@j@k@JKVWZ[`Aw@DEl@a@RMTMJG`Ak@nAo@j@WBA`@Q\\O\\ODCLAB?@A\\Qd@Sp@WVK^ONEZMxB_A"
                     },
                     "start_location" : {
                        "lat" : 40.9296374,
                        "lng" : -80.72122069999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "10.3 mi",
                        "value" : 16598
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 883
                     },
                     "end_location" : {
                        "lat" : 40.8501005,
                        "lng" : -80.51910049999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e after Burger King (on the left)\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow OH-14 E\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Pennsylvania\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "shsxF`gpkNAS@yC@m@?OAs@?U?w@?{A@oBAiBBkE?sB?sB?eB?q@@Y?]B{ADmABw@FeAFmAB]Da@B[BWDa@@K@SDW@MBS@KFa@J{@Hg@Ji@V{ALo@Jg@No@FYViA`@wAX_ALa@\\eATk@Vs@Tm@`@}@\\u@FMb@}@b@y@Xe@Ve@n@cAj@y@RY`@i@V[V[vAcBpAwA|@eA`@e@RSv@_AnGkHz@aAz@_ApB}BpB}BbBoB|@eAb@i@NSV]b@m@Ze@^k@f@y@NW\\m@h@aALWJSFOHQLWLYHSRa@N_@j@yAL_@Z{@Tq@BKL]Ni@Ni@Pk@@GJc@DKLm@Nk@Ns@Lq@N{@x@oE^yBFYFc@`@{B\\kBTqA^uBBORgAN_AJ}@Fi@Da@Dc@B_@Dk@Bu@?U@_@?qA@u@?gE?iB@mF?}D@_E?m@?i@?c@?e@?Q@S?c@@c@Bk@@WB]JyAFa@Ly@N_ADWJk@dAcGf@qCf@qCPaA\\oBZiBDUP_AXaBNy@Hq@BIJw@Fe@Fi@Fq@B[De@Fs@Dm@BUBa@DoAF}ADiB@sA@}@@a@?g@@c@@a@@c@Bg@Be@Bi@Fu@Fu@Fs@NkAFe@Ly@Ji@Jm@Ji@Le@Ps@Nm@Pm@L]DQRi@^cAt@oBx@{BFOjAyCL]b@iAh@uAd@mAf@uA`@eAVq@x@yBDOvAqD|@aCl@{AFSL[HWL]H[BM@EFYFWD[@CBOBMBU@QBUBU@]@U@W@c@?G?[EmB?EIwDS_KK}EU{JEyBS}IMmFI}DI}DI{DCo@I{DI}DQkIGmCGmCMqGEiBAo@I{D?IGsCCsC?wAAeB@yB?uA?w@@yA@cBJaEBcAD{@Dm@Fc@NeANu@BONi@\\sA?CRs@|F_T~ByI|@cD^{AXeAf@sBH]|@kDp@oCVcALa@FQTm@Te@f@}@jAkBhBmCbB}Bn@y@Z_@|AuBx@eAT]T[JQBERa@JYL[Pm@Lc@Lq@Fa@BUB]B_@@Y?C@_@?K@cA?Y?_B?K?a@?gA?eAAq@?c@?iB?cA@a@@g@?EBWBa@B]BWJy@He@BOBMLe@\\mADS\\iAJ_@Pi@BMTw@X_APi@d@_BDOV{@Nm@VcAFa@Ha@BS@IDi@Dc@?CBY@UDcAFgABo@Bo@B[@QDk@?ADg@Jo@N}@T}@Rw@XmAj@yBTy@Ni@\\uANi@^uANi@zBwIlAuEtAmF`@aBNw@Nq@Jm@BOl@aD`@_Cl@gDb@wB|@iFZiBX}ABMPcAPs@BMBKF[La@HWNa@JWHUt@yAb@y@j@iAl@gAhC{ETc@Te@BCbAmBj@gAb@y@JQ`AkBj@iAZo@Z}@N]HYV_AJc@Lg@?AZuA|AiH\\aB\\_BZwAnAaG\\}A|@eEbB}H`CyKpAeG`BqHx@wD`@oBdCcLZyALi@b@sBzAcH~AsH^cB\\wAViA\\sABIJ_@XkAl@{Bh@iBr@aC\\gAn@sBl@kB`@gA`@iAL]JUv@oB`@cAPe@f@oA"
                     },
                     "start_location" : {
                        "lat" : 40.9001035,
                        "lng" : -80.69760599999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "10.1 mi",
                        "value" : 16271
                     },
                     "duration" : {
                        "text" : "12 mins",
                        "value" : 749
                     },
                     "end_location" : {
                        "lat" : 40.7649901,
                        "lng" : -80.3637751
                     },
                     "html_instructions" : "Continue onto \u003cb\u003ePA-51 S\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by AutoZone Auto Parts (on the right in 9.3 mi)\u003c/div\u003e",
                     "polyline" : {
                        "points" : "cpixFjkmjNnAsCDMTe@BE^{@p@uAdAyBp@sATe@HO`@y@Re@`AqBTe@`BiD`BiDHQxA{Ct@{ARc@b@}@LWd@aATe@BC~@oBRa@Te@~DkIpDqHBIZm@z@iBj@iATe@`AqBTe@bEsIbAwBZm@Zo@~@oB|CmG`@{@Te@b@}@\\q@Te@Rc@@ATe@h@gA@CTe@N[n@sAP]Ra@PMr@oAh@_Ar@oA@CTc@R_@@Cj@iA^u@bAuBl@oAtBiEP_@xCgG\\s@v@cBTe@FMHMj@kAvAwCDIj@kAbBmDXo@n@oABGt@_BDIBGP]l@sAd@eAd@cA`B{DHOz@uBXq@Xs@`@eAJUz@{Bb@gAb@mA?AjA_D|@cCDKp@kBd@sAb@oAxA_Ej@_BHWvBcGnD{Jt@kBN_@j@wAJWFOj@sAl@wAHMBGj@oAhA_CbAqBJUPYZm@NYz@{AhAqB\\i@hBwCbAyAT]NSzAwBv@gAl@w@p@{@t@_ABE`AiA@ArA{AJMNOBCvC}CLM`F_FhAeApCqCl@m@x@u@dCeCzByBxAwAtDqDpAqAfAgA`AeAjAuAX]f@m@j@u@h@s@jAcBr@cAVa@h@{@@Aj@_Az@yAR_@R]lA_C\\u@DKP]l@sANYXs@Vk@|@}Bl@}ADMd@sAd@yAj@eBTs@|@oCnDwKd@wAdAeDPe@?C~A{EZ_ApA}DNe@Vw@vDmLNc@pEkN~@uCj@_BxAsEfBqFn@mBnBgGdA}C@EPg@Ni@Pi@Ni@FSX_AJ]BMNg@?ANi@FYh@uBBKLk@Li@Nk@d@wBnAoF\\{A^}Af@wBd@uBt@aDVgA@EPs@XmA?CLg@R_Ad@mB?Ad@qBTeAJ_@f@}Bj@{BLk@H]J]j@{Bz@aDz@}CBG~@}C^mA\\iAh@cBDM\\aATs@d@uA|AgEf@qAFQdAkCL_@Xs@d@oAh@qAL]\\}@p@aBVs@t@kB|A}DBGd@oABEb@iAL_@|C_IDKZw@`AeCj@_B~AcEb@iAp@iBxDyJjBwEFORg@@Ef@oAb@iA@ENa@h@uAv@qBBEx@uB~AeE`@eARg@v@qBbBkEDKfAqCZw@lA_Dx@wB\\y@p@cB|@}Bz@yBj@{ArHqRRg@z@}BRg@`@aApGkP\\{@d@oAl@{ARg@DKpAgD\\w@b@cABEx@kBBEf@cA^q@nA_CvAkCXc@v@oA~A_Ch@w@xAsBLOlAaBlAcBvDaFTYPUX_@nAaBr@_ADEn@y@rAeBTYtAeBbBwBdByB"
                     },
                     "start_location" : {
                        "lat" : 40.8501005,
                        "lng" : -80.51910049999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "16.4 mi",
                        "value" : 26441
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 916
                     },
                     "end_location" : {
                        "lat" : 40.5628097,
                        "lng" : -80.280277
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eI-376 E\u003c/b\u003e via the ramp to \u003cb\u003ePittsburgh\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "e|xwFr`oiN\\QFADCDADADAB?@?BAH?P?H@V@H@L@l@BD?b@BP@r@@`@B|@BlBFXBTB`ALd@Ff@JJBXFF@LDl@PhA\\r@VbBj@@?ZA`A`@v@Xz@XTFZJPFVHF@JBp@NB@TDh@JNBH@PDVBRDTBH@J@TBTBR@VBR@T@ZBP?T@V@Z?Z?@?P?R?@?T?NAD?RAVAh@AVATATAT?RATAVAh@CRAl@CV?f@CTATATAR?TAVATATATAh@ATAB?PATATATATAbACTANAVARAl@ATATAF?JA@?VA\\AJ?T?RAT?T?T?F?J@V?R@P@D?T@TBXBN@TBHBJ@VDRBRDTDPDNBB@RD@@VFD@LDTHRFVHNFRHVJRHf@TPJTLNHTNPJRLPLNJRNRNRNNLPLTRPNRNLJRPPLRPPNNLRNh@b@h@b@XTRPPNPLPNRNPNPNf@`@^Zf@\\PNRLb@XRLRLNJTLPJRJRJh@VRJRHTJf@RTHRHh@PTHPDTH`@J^JTDTFTDXFNBTDVDRBVDRBTBT@J@B@ZBT@RBT@T@T@R?V@T?V@P?V?R?XAR?TATATAVARATATCRAVCTCRCTCTERCVERETEVGRERERGVGPETGRETGTGRETIREh@Oh@MRGTGh@MVIRETG|@WRETG|@WXGNETGTGn@Q@?`@KRGRGb@KTGDATGRGREVIREBABA^KTGREVIREr@S^IRGTGVGRGTGTEPGTETGj@KRCTETETCPCB?RCTCRAVCTATATAd@AF?RAR?V?R?T@T?T@T@V@R@TBR@h@FVBTBRDTBh@JRDVFRDRFTFRFTFTHRFRHPFRHTJNF`@PTLRHPJTLPJPJTNPLPJPLRNPLRPNLd@^fA|@NNPNTPPN~G~FRNRPNLRPRN`@^d@^NNRNLLRPRNFDJJNLf@b@`@\\PNn@f@^\\PNJJb@\\?@TPZVNLVTPLPLRNPLRLTNTJNJRHPJ@?TJRHNFPFD@THTFRDVFRBJBH@H@NBf@FTBT@V@X@b@?V?T?TAPAB?TCTAVCPCTETETEHAHCVGRGTGRGJEHCRITKPITKRM\\SFCPMROROROPMHKDEROPQNONS@?NQLQRUNULQNUFIDILSNUNWLSNUXe@PY^o@Xe@Zi@\\i@NWLULSNULUVc@PWPYv@sA@ALS\\k@h@_AR[Va@Zg@@C\\k@b@s@lBaDz@wAJQPWLQLU^i@LQNSNSPWHKBENQPSNUNQNQNQNSNOPSPQPSPQLOPQBCLKPQt@s@POLKTSb@_@b@a@RQBAJKd@_@PQb@]RQb@_@b@_@b@_@b@a@PMb@_@POd@a@b@_@POPOPORQNMPOPO`@]p@m@r@m@PO^Yd@a@^]\\YXWXU\\[hA_Ap@k@XWZYz@s@NMNMv@q@POPOx@s@r@m@b@_@\\YnAgA@?d@c@r@k@DEJINM@CzAqAz@s@NM`@_@p@k@b@a@POHIDERURS@AHM^e@PULONYV_@JQTe@HMVi@Pe@@?BGL_@@C@CBIL[Rs@Pm@Pu@@CLo@Hc@Jo@Dc@DUFs@Fg@Bk@@KB_@@Y@g@Bq@B}@?WHmDBeA?MDwABqA@{@J_F@o@HyC@gABw@@w@BcA@S?Y@W@w@@]@Y@_@Du@@MDk@B_@B_@@]BYBYJs@?AHs@DYD[F[DYF[Jq@Pw@H]DWHYFWH[HYHWH[HUTq@Tq@JWJWJWJWJULYJSLWJULULW\\i@T_@DI^i@\\g@^e@^e@PSPUNMNQ`@a@HILMNOLKDCJITQPMNMPMTMPMJIXOPMRKRMLG`Ae@FEJERKRILIDAl@[d@URKRKf@UPKTKRK^Q`@SRM\\QHCLGLILGJEpAo@RMf@Wh@WRKRKTKRKPKTKBALIRIRMTKRKRKPITKf@Yh@WRKRKRK\\Q\\QLGZONIJGDALGPKTKVMRKNIRKRKHEHEPITKb@URKRKRKNIRKRKPIRKPKFCXMDCRKBARKVMn@[BAJGTK@ATKNIRKPINIj@Wd@URKRKRKRKPIrAo@d@WxBeAXO^STKRKRKPIRKf@WTMRKPIf@WNG@?BCBAx@a@RKZOZOvAs@nB{@DAPIRITKRGTIRIJEHCRGBAPERIRGTGTGPGTGLCFCTEPGVETETGTETETETEB?NCVETEh@Gj@Ip@GLAPCVCl@ERAVAj@CTAj@ATAR?X?Z?LAh@@V?~@@N?bABD?j@BT@j@DT@TBT@PBTBVBRBTBTDTBTBRBj@HRBVDTB^FH@VBPBl@HRBTDTBRBVDf@FVDh@FVDRBNBD?TDTBVDRBTBTDf@FB?TDRB\\DL@NBF@TBPBVDRBVBTDRBTBJ@HBh@FVDTB`ALb@F@@@?\\DB?TDL@j@HT@TBP@|@FB?V@T@F?L?V?j@?|@Aj@Cf@E`@EFAFA`AORE\\GB?j@OTEPEj@Q\\M`@O`@MJG^OVMLGRKJGl@]f@[f@[d@YPM\\U^UJIb@YHGLGPMRMJGz@k@HEr@c@^UZSx@c@z@c@FERKr@[f@Sj@W@?ZM\\Mb@O\\Kh@Qj@QRETIPERGTGPEVGTEPEj@MRETEVEPETCREVCRCTEXCf@EVCTC~@GTCj@CTAVATARAl@AR?PAbA?T@j@?T@V?R@V?T@T?T@j@DT@j@DT@RBTBj@Dh@HTBTBh@HTDTDTDTD~@Pf@LVFh@LRFTFTFRFB@PFh@PTHTFt@XB@XLf@P\\NRJ\\Nf@VRJ@?d@TTLPJRLPHTNNHRLRLRLRLPLRLPLRNB@NLPJPNRLPLRNPLRLRNPLRNPJRPPJPLRLRNPJRLPJRJRHTLPHTHRHPHNDD@RFTHRDTFRDB@NBTDTDJ@FBTBRBTBT@TBP?T@T@V?T?TAVARAVATARCVCTCRCTCRETEREVGRGRETITGPGTKRIRIRIRK@?RKPKRMRMRMPMPKPORONMNMPOPQRQNOPOPQPQPOPONQPOPQFEHIPOPQPONOPOPOROPMPORMRMPMPKTOPIRMRKRIRKPGVMRIVINGRITGTGTGh@MRERERETERCVERCTCTATCXAh@Ej@ERAj@ETATAl@ETAd@E`AIl@Ih@If@KTEj@Mf@Oj@Qd@Qh@Sh@URK`@STMHEFERMBANKDCLIPMLIBCPMROPOPOBC^[ZYFGNQPOPSFGFINQNSPSNQLSNSNULSHKDGLULSNWLULUJULUJWLUJWJWJWJUJ[JWHWHWJWFUJ]HYFWPq@?APs@XoAPu@Ps@Hc@Li@Pu@Pu@hAiF|@aE~@aEBMFYFYFYHWFY?AFWHYHYHYFY@AFWHWHYJW@IPg@BMPc@HYRk@L]HWJWJWJWJWJWJWJWBEFQJULWJWLULWN]HOXk@JS@CLULS\\o@JQLULUj@}@BCFMPYPUZe@NSLSXa@TYNSNQNQPSNSp@w@VW?ANQl@m@^_@b@c@b@a@j@g@JI`@]NOVS^YRONMRMPMPMHGj@_@\\U`@Ud@Y~@g@NIRMPIRKRKHCJGPIPITKRINGl@Uf@SRGVKPGRGRGTIHCnBk@bBg@jGkBbFyAbF{AdEoAxEuAdA[~Bs@lA_@hDcAxC}@v@Uz@WVIpA_@rBm@|Ae@j@QdDaAlCy@|DkArA_@h@Q|@WdA[tAc@JCd@OvAa@PGTGTIZKNEPGb@OBCRGVKRIRGj@Wb@S`@Q^Qt@_@h@[b@UVOLIRM@AVO^UNMJGVOVSf@_@j@c@l@e@t@o@VW`@]l@k@b@a@p@s@j@m@j@k@f@g@l@o@dAeAbAeAp@q@d@g@r@q@p@s@p@q@d@g@XYTSf@c@RQHIVS^YRQh@]JIZSTMTOJGb@Wl@[\\OXM\\OBAVKRIPGRIb@ODATIRGTGRGTERGREFALETERETERCTEVERCf@GFALATCRCVATCRCRCVCTAPCZC|@Ib@EZCVCh@Eh@Er@I|AO`@E~C["
                     },
                     "start_location" : {
                        "lat" : 40.7649901,
                        "lng" : -80.3637751
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 mi",
                        "value" : 559
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 37
                     },
                     "end_location" : {
                        "lat" : 40.55838929999999,
                        "lng" : -80.28154839999999
                     },
                     "html_instructions" : "Take exit \u003cb\u003e48\u003c/b\u003e toward \u003cb\u003ePA-151 E\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "qlqvFvv~hNJJz@G`BITAT?NAL?@?@?@?H?N@@@B?D@HBFBDBDBFBFDHHDFPR@B@@DHHR@D@@BHJ`@Jf@BNDLFNDFFHBFDDDDDDHFHDHDD@NFJ@F@D?J?@?L?h@GlAMDAjBUdAK"
                     },
                     "start_location" : {
                        "lat" : 40.5628097,
                        "lng" : -80.280277
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "98 ft",
                        "value" : 30
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 4
                     },
                     "end_location" : {
                        "lat" : 40.5581251,
                        "lng" : -80.2814987
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to continue toward \u003cb\u003ePA-151 E\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "}ppvFt~~hNPC`@E"
                     },
                     "start_location" : {
                        "lat" : 40.55838929999999,
                        "lng" : -80.28154839999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 mi",
                        "value" : 653
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 44
                     },
                     "end_location" : {
                        "lat" : 40.5609508,
                        "lng" : -80.27521329999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003ePA-151 E\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "iopvFj~~hN?MCu@Cm@A{@KaDCk@Ci@AQAOAKESEY?COw@]cAUk@g@cAEIAEACg@{@Wu@a@{@QYKQSYSW]_@aAiAOQMMWWMKMIQKOIQG?A"
                     },
                     "start_location" : {
                        "lat" : 40.5581251,
                        "lng" : -80.2814987
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.5 mi",
                        "value" : 2468
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 155
                     },
                     "end_location" : {
                        "lat" : 40.5405019,
                        "lng" : -80.27619850000001
                     },
                     "html_instructions" : "Sharp \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBocktown Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eGringo Clinton Rd\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Gringo Clinton Rd\u003c/div\u003e",
                     "maneuver" : "turn-sharp-right",
                     "polyline" : {
                        "points" : "}`qvF`w}hNNEFAD?D?D?V@B?fAFX@l@Db@DT@LBb@FJBl@Th@XVNFB^T^R^RLFPL~@l@LJNJ^TTNHBTFLBH@R?D?`@G@?PCNEj@KXIlB_@bB_@b@KVGHAZGb@I^IBA`@IB?^G`@Il@IXE^EBA`@GXCDAB?b@Cb@EL?P?B?~@Bf@FJ@v@Rb@L@?LDr@Rb@JbAXb@J`@JF@XJb@J`@J`@JNDh@NZHF@@?XHD@ZHF@PDFDB@\\Nb@Rn@d@ZVBBFD^VhA~@VRb@`@TPFD^X`@\\ZP\\Vf@PH?RBD@P?J@NARCLADALCFAZKTKHEHETQ@ADCRMHITSJOLOPWFKLWFK@EHUDKDKFODKDMXs@Pe@@CDINYDG@APW@ADETQBCDCFEVMd@K^C@?N?^?TBL@N@R@T@F@D?j@BZ@T@L?J?H?^?PATAb@ATAB?"
                     },
                     "start_location" : {
                        "lat" : 40.5609508,
                        "lng" : -80.27521329999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 mi",
                        "value" : 661
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 41
                     },
                     "end_location" : {
                        "lat" : 40.53548,
                        "lng" : -80.2772004
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eEconomy Grade Rd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "camvFf}}hNdAEZCl@Ez@ITEz@UTIf@SZK`@QNEPI`@MTIDC~@W`@IJCPEB?F?PAJ@H@XFTFNDp@PB@LDRFPFPLHFDDHJJNR`@Nd@BNDL@DDVF^DXDZDP@LDNBL"
                     },
                     "start_location" : {
                        "lat" : 40.5405019,
                        "lng" : -80.27619850000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 mi",
                        "value" : 814
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 54
                     },
                     "end_location" : {
                        "lat" : 40.5308315,
                        "lng" : -80.2706826
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eEconomy Grade Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "walvFnc~hNFDFDFDFBHBH@LB@?LBH@`@MJCb@MDCVM@ATQ@?LSFIDKBGFM@CHOBINi@DM`@sAH[DMJYDOHYVy@DQHWNi@bAeDNi@`@sAPi@HY\\_A?A@CJ[HU@CFMPe@v@cA^e@t@s@XQf@]XQDERS"
                     },
                     "start_location" : {
                        "lat" : 40.53548,
                        "lng" : -80.2772004
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 mi",
                        "value" : 1455
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 90
                     },
                     "end_location" : {
                        "lat" : 40.5409174,
                        "lng" : -80.2607349
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eSpring Run Road Extension\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "udkvFvz|hN[e@KQMOYa@Y_@YYc@[AAg@W}@Sa@EA?q@?uA?GAc@G[Ei@SYSu@k@WSGE{BsBy@s@CAcB{Aa@_@{@s@i@e@o@g@e@e@m@u@m@{@}@aBi@oAGQOi@Qg@Qi@Oi@EOKWGO[m@IKe@m@]_@IGUOi@]y@c@uAs@i@c@m@y@k@kA[u@Wm@a@mA"
                     },
                     "start_location" : {
                        "lat" : 40.5308315,
                        "lng" : -80.2706826
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 mi",
                        "value" : 1118
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 133
                     },
                     "end_location" : {
                        "lat" : 40.5380855,
                        "lng" : -80.2486972
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eScottsdale Dr\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wcmvFp|zhNLUBGLUDO@EFY@g@Ci@CWGm@Cg@?[Hi@BEhAcDrAcERs@Fm@@CHaALc@d@g@Z[PUz@y@ZYXc@@ALe@@ADi@?A?mAC_A?G?g@?OB_@Bm@@SBYH}ADWRmBFk@D]?C@i@Bo@?o@?m@?o@AsA@mABYBm@?ALiA"
                     },
                     "start_location" : {
                        "lat" : 40.5409174,
                        "lng" : -80.2607349
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 mi",
                        "value" : 764
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 84
                     },
                     "end_location" : {
                        "lat" : 40.5337737,
                        "lng" : -80.2439741
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eMeade Dr\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "arlvFjqxhNLF`@TFDv@^@?`@JLDv@Fb@ERANE`@K~@i@^Y\\W^WJIp@c@^W\\WLI\\YTOZ_@FGLQHOXi@\\s@HSTk@Lc@Nk@FW?UD}A?}@?o@?o@?mC"
                     },
                     "start_location" : {
                        "lat" : 40.5380855,
                        "lng" : -80.2486972
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 266
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 50
                     },
                     "end_location" : {
                        "lat" : 40.5316771,
                        "lng" : -80.2426969
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBashford Dr\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "awkvFxswhNfAEB?h@CVINEf@Sh@Sj@]l@k@BCd@s@R]X["
                     },
                     "start_location" : {
                        "lat" : 40.5337737,
                        "lng" : -80.2439741
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 266
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 54
                     },
                     "end_location" : {
                        "lat" : 40.5337737,
                        "lng" : -80.2439741
                     },
                     "html_instructions" : "Make a \u003cb\u003eU-turn\u003c/b\u003e",
                     "maneuver" : "uturn-left",
                     "polyline" : {
                        "points" : "_jkvFzkwhNYZS\\e@r@CBm@j@k@\\i@Rg@RODWHi@BC?gAD"
                     },
                     "start_location" : {
                        "lat" : 40.5316771,
                        "lng" : -80.2426969
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 mi",
                        "value" : 764
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 88
                     },
                     "end_location" : {
                        "lat" : 40.5380855,
                        "lng" : -80.2486972
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMeade Dr\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "awkvFxswhN?lC?n@?n@?|@E|A?TGVOj@Mb@Uj@IR]r@Yh@INMPGF[^UN]XMH]V_@Vq@b@KH_@V]V_@X_Ah@a@JODS@c@Dw@GMEa@KA?w@_@GEa@UMG"
                     },
                     "start_location" : {
                        "lat" : 40.5337737,
                        "lng" : -80.2439741
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 mi",
                        "value" : 1118
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 131
                     },
                     "end_location" : {
                        "lat" : 40.5409174,
                        "lng" : -80.2607349
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eScottsdale Dr\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "arlvFjqxhNMhA?@Cl@CXAlA@rA?n@?l@?n@Cn@Ah@?BE\\Gj@SlBEVI|ACXARCl@C^?N?f@?FB~@?lA?@Eh@A@Md@A@Yb@[X{@x@QT[Ze@f@Mb@I`AABGl@Sr@sAbEiAbDCDIh@?ZBf@Fl@BVBh@Af@GXADENMTCFMT"
                     },
                     "start_location" : {
                        "lat" : 40.5380855,
                        "lng" : -80.2486972
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 mi",
                        "value" : 1455
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 97
                     },
                     "end_location" : {
                        "lat" : 40.5308315,
                        "lng" : -80.2706826
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eSpring Run Road Extension\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "wcmvFp|zhN`@lAVl@Zt@j@jAl@x@h@b@tAr@x@b@h@\\TNHF\\^d@l@HJZl@FNJVDNNh@Ph@Pf@Nh@FPh@nA|@`Bl@z@l@t@d@d@n@f@h@d@z@r@`@^bBzAB@x@r@zBrBFDVRt@j@XRh@RZDb@FF@tA?p@?@?`@D|@Rf@V@@b@ZXXX^X`@LNJPZd@"
                     },
                     "start_location" : {
                        "lat" : 40.5409174,
                        "lng" : -80.2607349
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 mi",
                        "value" : 1500
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 105
                     },
                     "end_location" : {
                        "lat" : 40.51871250000001,
                        "lng" : -80.2670124
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eSpring Run Road Extension\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "udkvFvz|hNPGXMXSJIFEPMh@c@p@w@XW^Y\\UPMn@UJEx@Sf@I^ETAL?B?P@R@\\FhBXTD`@FLBTDF@f@JTDVFn@\\DB@?TZHLBDj@`ABBJLJLB@NDND@A\\ADANEPGLC@APKLIJGDCJKd@e@DGJKNQJMHM\\e@JMBCHMX_@JMDGHG^WVQ|@a@j@WNGPKJEz@]j@MRCNA@?t@D@?L@R@T@LAN?jACr@GNARANAB?p@SHCBAn@_@NKNOLINMLKPMLI\\WJIDCJKPM"
                     },
                     "start_location" : {
                        "lat" : 40.5308315,
                        "lng" : -80.2706826
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 mi",
                        "value" : 803
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 70
                     },
                     "end_location" : {
                        "lat" : 40.5123346,
                        "lng" : -80.2708772
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eFlaugherty Run Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}xhvFxc|hNZJr@NbCj@ND`Ch@HBZFfCj@H@@?jATb@H@@l@JTD@@JB@?NDD@@?HBVHPHXNNHB@NL\\\\HHTV\\`@VXNNf@h@@BBBBBBBFLf@n@JLX`@v@`AHJx@lA"
                     },
                     "start_location" : {
                        "lat" : 40.51871250000001,
                        "lng" : -80.2670124
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 mi",
                        "value" : 1625
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 75
                     },
                     "end_location" : {
                        "lat" : 40.5046844,
                        "lng" : -80.282404
                     },
                     "html_instructions" : "Take the \u003cb\u003eI-376 E\u003c/b\u003e ramp to \u003cb\u003ePittsburgh\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eAirport\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003ePennsylvania Turnpike 576\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "aqgvF~{|hNFZ@FBJ@J@TKdAOzA_@bECPMzAEZAPs@vHIz@G~@Cv@?L?D?Z?P?J@\\Bf@Bd@Fh@DV@LF^@HH^@@FVDPBJL\\FPJTDJTf@Zf@NTTX@?VZB@VTLLHFRNPLLFPHLFRJb@JLBTF@?HBD@RBNDNBr@LTDLBPBB@F@J@VFTDD@F@B?PBD@HBVDF@F@LBTDLBD@JB\\H`@Jp@LhA`@|@X^JfBj@dA\\v@T`DdAr@Td@N`@LRD"
                     },
                     "start_location" : {
                        "lat" : 40.5123346,
                        "lng" : -80.2708772
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "11.4 mi",
                        "value" : 18339
                     },
                     "duration" : {
                        "text" : "11 mins",
                        "value" : 632
                     },
                     "end_location" : {
                        "lat" : 40.42471820000001,
                        "lng" : -80.11439109999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e at the fork, follow signs for \u003cb\u003eI-376 E\u003c/b\u003e and merge onto \u003cb\u003eI-376 E\u003c/b\u003e",
                     "maneuver" : "fork-left",
                     "polyline" : {
                        "points" : "gafvF~c_iNH?DBZFXHB@|Cz@NDVFVFTDVDb@H@??ATGRBR@TBN@\\@@?d@?V@RAB?f@Aj@CTCh@G@?RCTEREh@KTGRGVGPGRIRIRITKPITKPKPIRMRMNMh@_@`@]NMPQRQNQNORU\\a@\\e@|@qAnAeBz@mAt@cAhA_B?AjAaBxB}CFIf@s@l@{@FKHM^g@xB}Cp@_AV_@RYNUPU\\e@JQ^g@JONUFGV]l@{@LSNU`@i@`@k@d@q@pAiBl@{@p@aA\\e@\\c@NWl@w@h@w@Xa@fA{AhAaBRUtAiBZ_@BERWPSV[JMLONQTWJMNQp@w@xBaCLONONO`@e@`@c@`@c@p@w@`@a@j@o@d@i@`@c@LMd@g@@Cj@o@BCVYHI`@c@`@e@d@i@JMNQNQ?ANSNS@A\\e@LQNUHOBCNULULSNUJSLSJU@AXk@Zm@Tg@Zo@Tg@Vk@Xk@Xm@Tg@b@}@Zq@^w@DKRe@DGTg@@CXm@@CJSJUJUXm@LYXk@Rc@DIRc@BIXk@LWJUJWLWLUJULWBEFMNYLUJULS@CJQLULSPYLSNSLQLS^i@PUNQNSLOPSNOPSNQPQNOPQPQTUHKPQNONORS@ANONODELMNQHGVWLMRUHIXYNQNMZ[DGb@c@LMRQHKVWVWj@k@DG^_@p@q@r@s@`@c@@A\\]RSr@u@r@s@PQ`@a@r@u@`@a@b@c@PQ`@a@b@c@`@a@rAwAb@a@t@w@^_@NQNORUNQNQNUNSNSNSLULSLSLULSNWLUJWLWLWJUJUJWJYJWHWHWJYJ[HWFYHWFWFYH[F[FYFYF[DYLu@BYD[D[DY@K@OB[D]@YB[B[@[@Y@M@O@[?[@o@@c@?[?i@?c@AY?[A]AYA[A]AYC]C[A[C[EYC[E]Is@E_@E[EYG[EWGYG[GYGYGYIYIYI[IWGUIYKWIYKWKY?AKUKWWo@Ym@Wo@Wm@MWKWYo@ISM[KSYq@KWKWO]GMKWEKGKWq@Wk@KYKUIYKYKWIYIWGWI[IWG[G[I[GY?AEWG[EYE[G]CWE[E]C]CYCYC]C]A_@ASAAAc@Eq@Cc@Cs@Eo@C_@Cw@Es@AQCm@C]AY?EEw@Es@Cm@Cg@IsAGyAIcBMyBCy@GaAe@}JGeAEu@Cu@GaAAOEy@?IEu@AUCa@AQ?KASA[AMAM?GAWA]AY?K?OA]?O?O?Y?[?]@[?[@YBc@@[@]Dw@Hy@B[B[D[D[F_@Hk@Hg@DUNw@FUDS@EFYHYH[J]FSJYTq@?ATk@JYHQN]Tg@LYXm@Zo@Xm@`@}@BGb@aAZo@N[HQHSNYDKTe@JSJYBCHSXm@DIDMLWJWJWJWBGDMJ[HWFOBGHWFWHY?AH[HYFY@GDSFYFYBO@KFYD]D]DWBYDY?GBSD[B]B[DYB]BYB]@KFi@Hy@Fw@Fw@Hs@@MFu@LiA@IBQF[D]F]H_@Lk@FYHYHYFYFSHUX{@BCFQLWJYFKDIJWLUFKDILULUJOBELSNUNSBCJMNSPQHKBERQNQPQPOPOPOn@g@~@s@fAy@t@k@DCfA{@hA{@f@]@CZUDCROFGn@e@^YFEVSZW`@Yf@a@d@]d@]POPMRORQPO`@_@PQPOJOHIHId@g@\\c@dAuAFIxAqB|@qAd@o@LONUFIx@iA~@oA|@oAd@o@NUTYX_@V_@NS^g@DGHM\\i@LQLSNULWNUJS?ALSLWJUJUJUBCVo@JUJWJWHYJYJYLc@DKHYHWRs@FYPq@HWH[FYHWH[FWH[FWHYHY?CHUFYHYH[H[HYFWPs@Pq@HYDQBGH[FWHYHYFWHYFYH[BE`@aBFWJ_@Nm@H]Ns@F[F[@GBMF[DYD[F_@DWDYD]BYBWFe@BWBYB[BY@SDi@B[B[B[BQBe@B]BYB[D_@HoAJoAB_@BYB_@JoAB[B]B_@Fs@D]B[D[B[FYD[DWFYF[FWHYHYLa@FQHWJWLYJSBCHQLULUNULQPULQNQJMDEPQPONMHGHGFEJINMPMHE`Ao@VORMb@YXQJGPMTMVQJGRMRMPKRMRMf@[PKPMDCNKjAs@RMPMRKf@]`@YTONMRMTSPOPOHGFGPOPQFEHIPSBCJKNQHIFINO@AZa@RWPSJOBCLSNS@CJOLSFKFIJQNUJSNW@ELULWLUFMDGLWHULYN_@FOLWJWJWJWJWJWFMDIJYJUJWJUL[HS@CJUJYVo@DIDMJWLWJW?CJSJYJUJWJUHUN[JWJUBKHOHUHSN_@Vm@JWJWXo@JU@GHQJWJWLWHWLWb@gAVo@LYJUFOBIJWVo@JWDGFOVo@Vo@JWLYFOBG|@uB?AVo@Vm@LYVo@JYJWJUJYJWN]HOJWJYJWDIDKJUL[JWJW@CHSJWLW?AJUJWJWJW`@aA^}@|@wBPa@Zy@LYbAgCL[Xq@Ti@bAeC~@{BfAmC@Cz@sBf@oAt@iBDKPa@Pc@DIVq@BEFOVo@LYBIP_@Vq@JUBETk@LYHULYJWFMBINa@FKXq@Rm@JWFM^aABGZ_AFMVw@Xu@Rq@`@kARo@Vu@^kABIPe@^iAHYFQBGJWLa@Nc@BGFSRo@@ARk@l@kBPk@HUJYHWTs@Xy@Pg@\\eAL_@Rq@`@kAHYTq@DMNa@Ro@DKDOTq@Ne@Nc@FSLa@HQJ[X{@DOTo@Ne@DMTq@J[HUTs@BKX{@ZaANa@Rm@Vw@@EZ_AJ_@Lc@BKRs@Ps@?APs@XsALq@Hc@Jk@@ENcABMHq@Ju@Hw@B[Hu@Dm@Dk@HsA@[?ABo@DuA@c@@]@]?w@@y@?w@?uA?wA@y@?a@?oA?w@@uA?]?G?S@]@[?[Ba@?UDw@@]BY?ODi@B[B[Do@"
                     },
                     "start_location" : {
                        "lat" : 40.5046844,
                        "lng" : -80.282404
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 mi",
                        "value" : 1098
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 48
                     },
                     "end_location" : {
                        "lat" : 40.4198439,
                        "lng" : -80.10373
                     },
                     "html_instructions" : "Take exit \u003cb\u003e64A\u003c/b\u003e toward \u003cb\u003eWashington\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "omvuF|i~gNTQ@??ADc@Fs@D_@PqABSL_A@I@I@KBSDU@I@I@I@G@K@K@G@I?C@IBI@M@KDU@K@I@IBU@IBUBK?GBIBS@I@KBOFk@@CD_@D_@DUBUDKHe@BMBIDQN_@Re@NWFIHONONQNONMJMPOJMNMRSHKPOJOJKHMDGNUBIFKHSFQ@ADMFYBKDQHg@N{@NaABMN{@F_@H[DQFWL_@JUDKDIBGJQ^k@RUVWHK`@[RQ^W`@WDAVQ@?@AHU"
                     },
                     "start_location" : {
                        "lat" : 40.42471820000001,
                        "lng" : -80.11439109999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "7.2 mi",
                        "value" : 11605
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 400
                     },
                     "end_location" : {
                        "lat" : 40.3345221,
                        "lng" : -80.136286
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eI-79 S\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "_ouuFhg|gNRIHCFCVK\\KJCNERE@AREREPCVE@?RALCJAPAB?PATAV?P?PAV@T?T@R@L@H@F@L@PBL@RDJ@VFNDB@TFLBJDJBRHPFTJRHRHJFXNf@ZNJ@?NJRNRLBB`@XPNB@x@n@TNNLRNNJPNNJBBPLRNPLPNPLLHDBb@\\NL`@Z`@ZZT^XZTv@l@B@`@Xb@Xf@Zd@VTLJDXLNFVJXHZJRFZF^Hr@J\\Db@Dn@B~@BV?b@AXAPAD?VA^EXC\\Eb@En@IRCHALAb@E^Gh@Gh@GTEPCj@Gj@ITCRC\\ETC\\EXEh@GNCh@GBAhAMRCb@ELC\\CJAHAt@Kj@I~@Ol@Gd@GXEn@IH?\\Eh@Gb@EHA\\GHAVEf@Iv@O\\IRGh@Q@Af@Q\\OHC`@SRKZQb@WJGTOXQLIb@]^Wn@g@d@]HGl@c@j@e@f@_@v@k@z@o@BC^Yb@]TQ\\Uh@c@^YBAXUf@_@TQb@[VUTO`Au@|@o@`Ai@@C^U^UJGTMr@a@PIb@S^QLITILGh@UFCNGl@UTI\\MVKVIVI`@OHCj@SLEv@Wb@Qj@Q~Ak@TIPGd@ODAl@ULEd@Ql@SJEXKj@SLE\\M`@MDAn@Ub@ORGRGTIRIRGRITGRGRGVKPGTIPGTITGBANGRGRGRILE\\KRIRGBANETITGRGNEVIRETGPEBATEPCTERCVCRARATAT?T?T?T@R@XBTBRBTBTFRDRDRFRHRFTJRHPHPHTLRLRLNNTNLHPNNNTRNN@?NPPPLJj@h@DFh@h@n@n@DB^`@JJVV`@`@b@b@`@`@XZFDLLRTZZB@`@b@`@`@d@d@`@`@ZXFF^^^`@HHZZPNZ\\BBPP^^HHHFb@b@TTBDRPTTFFXXb@d@^`@\\^XZDFn@z@^f@?@Xd@LTXh@P\\Pb@HPDLRj@Rl@ZlA@BLn@Nz@RtAPlABZBZ@ZB^Bl@B~@B|A?\\@v@@v@@t@BfBBrC@rAFfE?NDfBDjA@ZDn@Dd@BXBZDXDZDZLr@H^FXJ`@Nj@@DTp@Vr@P^Vj@LVLTLRLTRXPTV^NNPRNNNPPNPNPLPNRNNJRLRJRJRJRHRHTHPFRHTFRDTFTDRBTDR@TBR@TBV@R?T@R?T@V?T?h@AB?N?X?V?d@?h@AjBA`A?P?fAAnCAlDAfAApAAnDAlBAT?T?p@AjCAV?b@?|@Ad@Af@At@CH?JATAJ?\\Cj@ClBMbAKzAOf@If@GJCpAQn@KhFu@VE`AMbAOZEHCVEbAORC~@OtASXCRETCTEj@ETCj@CZAJA`@?j@Af@@R@T?T@j@DT@TBLB\\BTDRBTDXDVFJBF@@?t@Rl@RTHTH@?RHRHRHRJRHRJRLRJLFFDPJRLRLPNRLPLPNPNRNd@b@PPPPNNNPNPPRPRNRPTRXZb@LRNTZj@NVXh@LTZp@Tj@Xn@Tl@LXJTL\\j@tAxAnDd@jAJVVj@Vp@LZd@fAXt@Vl@Vn@LXn@|A|FrNXn@JVXl@JVLTLXf@`Af@`AZj@h@~@j@~@NRj@|@Zb@`@j@^h@NRNRtAbBVX@@B@f@l@bBdBNNdBbBXXv@n@dAn@dBhAfAr@"
                     },
                     "start_location" : {
                        "lat" : 40.4198439,
                        "lng" : -80.10373
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "13.1 mi",
                        "value" : 21131
                     },
                     "duration" : {
                        "text" : "13 mins",
                        "value" : 751
                     },
                     "end_location" : {
                        "lat" : 40.1908864,
                        "lng" : -80.2473823
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eI-79 S\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "wyduFxrbhNxEzC~JtGlD~B~DjC^T\\VzHbFrClBvBtA|DjCnCfBrGfEFDxA~@r@d@dBhAh@\\\\V^T^Vb@ZnAz@RN|AhAvAjA|@r@hA`Av@r@hC`CTR~CrC?@LJbA~@hAhA~@x@|AnADDZVTR@@XTZVb@^XTTPXVZXtBdB~@t@h@b@ZXNLJH`@Zj@d@^\\x@t@z@t@pAhAFDZXz@t@vAnA^\\JHrBhBjAfAJJh@f@pBrBzCdDnB~BbArAx@jABBh@r@xAlBTZ\\b@r@`A`BtBj@v@?@X^V`@d@l@rAbB`BvBr@|@VXlBfCrBnC~CdEtCrC^Vf@VRLf@TLFZJTHTHf@JVFpB^vA^xA\\bARh@Hj@JTBTDf@Hj@JnFr@jIvA`APn@HfDj@\\FrARD@B?hBDpCAPAlAOTCTETEPEXGd@KZKNGTGRIRINGVKVMb@Uf@[z@k@PMPOZYZWTUXWpAyAlAsA^a@bAiAbAiAp@w@bAiAt@{@l@q@NQPSNONSPQ`@c@NSNORS^c@^c@PSJKBEPQPS`@e@LORS`@e@BCl@s@NOJMTWp@w@NQPQbAiANSb@c@`AiARS`@e@JMBCPSNONSPO@CNOPOPQPOPOPMROPMJGBABERKRKPKTKDCJETKRGTIRIRGTGTETERETCTE@?RCVARCT?VARAR?V?V@R?V@R@T@N@H?N@T@T@TBT@h@Dh@Fb@Dr@FTDl@F|ATx@Nj@J\\Fb@JTDTFf@Jf@LTFRFRDTFv@TVH@@RD`@ND@PF\\LLDRHVHRHTHRJRFTJRHRJPFTJRJNHVJ@@`@RTJRJRLPJTLRLNHp@d@LJXTLNNNTRPPJH^b@JLZ`@TXRXFJT^PT@BJPLXNTDJFJHRJRJVLXJTRh@BFJXHVDPJZJ^FXBH@HHZDXFXH^DXFXFZDZDVF\\FXDZFXDZF\\FXDXFZF\\DXFZFZFXDXFX?@FVHZFXHXJZHVHVJVHVJVJVJVLTJTLTNVJRNRLTLPPTNRLPPPPRFFDDNPPPPP`@^PPPNPP`@^@@PNPPPNNPPNPNPPPNHJDBRRPNLNFDFFPPPPPPNPLP@?NPNRLPNTLRLRLRp@tAJRJVJVHRL\\HVHXHVHXDLBJPp@HXjBxHHXHXHZFVDNBJFVHTRn@HXJVHTLZHRJRZl@NVDHDFLRBDJNPTLPPRVZNRNPVXPPNRHHBDNNPRNPNPBBLLNPBBJNFFBBFFLNBDFDFHHJBBNPPTNPPRFJFFNRLRLTNTLTLRJTLVN^JVPd@Nd@Pf@Rp@Rr@HXRp@HV\\jAJ\\z@tC\\lATp@Pl@?@Rp@FRBHRn@HXL`@?@DNHTBLNb@L^FPDHDLJV@DJRHRJTJT@BLRLVHPBDLRVb@BDZh@\\l@FJT\\JRNTJRNVXd@@@NTNVR\\FJLTT^FHLTT`@BDPXNTDHFJLTZh@LRNVNVNTBDT`@NTLRBFV`@HPDDJRNVNVJRLTJR@BJTLTJTLX?@JTJT@DHPRf@BFJZJVJTJZLXFRXr@DJN`@j@xAL\\DLP`@Vp@JZBFRf@JVFRN^b@fA?@HT^`AJXLVHRLXJVVf@P^HNLRJRNVFJRZPXLPNRNRLRLN@@NPNRPPNPLL@BPNPPNNRPPP@@JFTRFDHFPNHF@@TNRLRLVPDBHDPJRLJHFBNJTLd@VVP^Tz@f@jAp@DDHDh@ZRLRJJFJFp@`@fAn@|@j@f@XRLXNJFTNb@V@@PJd@X@?PJPLRJRLPJB@NJRLLF@@RLRJJFHFPHDDLF\\RFDd@XRLl@\\PJRLHDNHTN@@RLRJRLPJPJRLPJLFDBRLd@Tf@XB?b@TRJXLB@\\NXJJFh@RVJJD\\Ld@NTHB@d@LTHF@`@LRFf@LJB\\HJBb@Hd@JF@`@HXDB@b@Hj@Hh@Hh@Jh@HZDb@Hb@FD@f@Hj@HTDf@HRDVDh@Hf@Hl@Jh@HVDh@HVDNB`ANTDTDh@Hj@Jh@HTD~@N|@L~@Nh@Jn@JbANLBh@HbAPRBNBZF\\DJBf@Hf@H^FPDVDPBh@Jf@Lf@Nh@PB@b@NRHf@THDJDPHRJRLFBJDPLPJRLNJXRLHRNZVFFPNNLNPRPNNPRNNDDJLRTJLTVNRNNJNNPPTJLNPPTPTNNNRPRJNB@JNPRNPNPLNBDPTNPLPRTPRLN^d@PR^d@NR^d@RTNPLNRVNR`@d@BBJNNPPTPPNTNNLNPVNPPRLPPRPTJLPRNPNPNRBBJN`@d@NPNRNPBBJNNRPRHLRVBBBDHJNTJPNVNVHNPXHRLVDJDJJTHVBDHTFRJ\\HVHXHXBNBHFZFZDTDX@FDTD\\DXD\\BZBXBZBf@@ZBd@@f@?\\?V?D?X?\\?XAZAXA\\?\\AZA\\C\\AZAt@A^AXA\\AZCv@AZA\\Cv@AZCv@AVCt@AXEhAAr@A\\Cx@A^AZA^ARAN?\\AN?ZAv@A\\?X?Z?Z?\\@^?T@`A@X@^?H@f@B\\@`@@XBX@^BZBZBZ@X@DB\\BVBXB\\D^DZBTD\\Fd@Fb@DVDZF\\DXDXH`@DRFZFXBPBJFVDTH\\H\\HXFVHXHXFVJZHVHVHXHVJXHVJVHVJXJTJVJVHPBFJTJVLVJTLTLTLVJRLTLTJPNXNRNTJPNTLPNTNRNRNPNRNRNNNRNPPPTVLLLNPNPPNNFFHHPNRNPNb@^PLPLRLPNTNNJRLLFBBLHLFJFRLNHVLRJRJPHVJPHNFVJVHPHRFNF\\JNDVHRFRDTFTFh@JXFNDTBRDTBTDTBTBRBVBTBR@T@TBV@R@T?R@H?N?T@R?j@?j@AR?TATANAD?TATATCTATCRCTCTCTERCTETETCTGRERETETGRETGTGRETETGRGVERGTEh@MTGTEd@Mj@MDAb@Kh@Md@KTGFANCRGREPETGTEh@Mh@MZILCh@MTGTEREBANCTCTCVCRATAT?T@R?J@J@R@RD@?TDTDRDRDB@NBTFPDB?l@Nb@JLB"
                     },
                     "start_location" : {
                        "lat" : 40.3345221,
                        "lng" : -80.136286
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.6 mi",
                        "value" : 5714
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 217
                     },
                     "end_location" : {
                        "lat" : 40.16251219999999,
                        "lng" : -80.1962291
                     },
                     "html_instructions" : "Take the exit on the \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eI-70 E\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eI-79 S\u003c/b\u003e toward \u003cb\u003eNew Stanton\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eMorgantown\u003c/b\u003e",
                     "maneuver" : "ramp-left",
                     "polyline" : {
                        "points" : "axhtFbixhNL?@?LBVBD@TB^BN?J@V?NANAJ?FAFAHAHAHCJCTIJEHCFEFCHEFEFEJILKHGJKHKFIJOFKJOFIDKFMN]DMDMDIFWBODSBQDWBS@U@S@U@Y@c@?m@?O@e@Ac@@SAaA@s@?A?U@q@@a@@[BY?K?AFu@B]@M@MDg@Fe@D]CW@IDY@GDWDWDYDYL{@Ji@DWDUHa@Nu@Ns@FYNq@F[FYFYNo@DYFYD[FWD[D[DYFc@RsAJw@Js@BOJo@D[Ju@Ju@Lw@DYD]DYJu@D[Hw@NuADe@Fi@Fe@BUFc@@OBS@OJu@BM@GD[@I@E@KFYDYDSBO@IR_AJe@H_@T_A\\mALc@To@@ENa@L_@LYN_@Pe@FMBEDMZo@Xk@Ta@b@y@\\g@PYV_@HMRW`@i@\\c@LOX]NONOHIJKRSNO^]h@e@h@a@^YRO^UPMTMf@YjAm@dBw@RIDCXMr@[bBu@z@_@\\OfAi@ZQZQHGHEZUVSPMPOLMPOZYRSd@k@h@s@RYXe@b@u@^u@L[LWN_@N_@J]L]FWLa@\\sA@CPw@HYFYH]Lg@RaAFQXqADMR_ALi@DKF[Jc@FWLi@Pw@H[Nm@FYBINo@d@kBLo@H[R{@DOXoANk@Je@Nm@XoAPu@Ni@ZuAPu@Pw@FWF[F]Ps@`@gBZmANs@ZqARq@Rq@Tq@JYHSXq@Xk@Zm@\\i@LUX_@T[NSV]HGNQPQNQPQPOROPONMRO`@YVQPOPMd@]d@]RMPORMb@]ROPMd@]DCLKf@_@`@Yb@[|AkAd@]PMROPMd@]b@]LKBEb@_@PQPOPQNQFGHK^c@LO\\e@BENSNSNSLUNULSZk@LUJULWLWJWLUJW@EHQHWJYJWTq@HYHWHYHW@INk@H_@No@DYHe@DOD[F[D[DYD[D["
                     },
                     "start_location" : {
                        "lat" : 40.1908864,
                        "lng" : -80.2473823
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 343
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 18
                     },
                     "end_location" : {
                        "lat" : 40.1605189,
                        "lng" : -80.1937667
                     },
                     "html_instructions" : "Take exit \u003cb\u003e21\u003c/b\u003e for \u003cb\u003eI-79 S\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "ufctFlinhNHG?A@AHm@PmAJu@Js@BODSFUFQDMDKDINUDIRSBCFGFGPMJGHCDCDCNGJC@ANCLE^ERAJ?L?N@@?RA"
                     },
                     "start_location" : {
                        "lat" : 40.16251219999999,
                        "lng" : -80.1962291
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "45.0 mi",
                        "value" : 72403
                     },
                     "duration" : {
                        "text" : "39 mins",
                        "value" : 2354
                     },
                     "end_location" : {
                        "lat" : 39.5832457,
                        "lng" : -79.9791725
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eI-79 S\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering West Virginia\u003c/div\u003e",
                     "polyline" : {
                        "points" : "gzbtF`zmhNt@Jd@JZHZH@@HBRFVHRHRHRHPJTJRJRLPLRLRNPLNLRPRNHHFFNNNN\\^BBNRPRNPNRNRLP\\d@PTNTNPNRLPPTNR\\d@NRFHV\\LPPTLPLP`@h@LPPTNRPTJN\\d@NPPVLNNTPR\\f@^d@LRTXHJPVJLNRPTPTJLNTNRBDf@n@RVJPPRLPNRLPNRLPPTLP`@h@LPRTLPNT^f@TXJNJLFHFJLNTZJLLRPTNPNTHJFHLNLNNRRTLLPRPPJHXXNJNNRLDDXRVNTNPJRJTLPHPH@?RHTHPHPDB@RFb@LF@TFTDRBVDRBXDP@VBTBh@BB@Z@L@J?TB@?dADXBP@X@Z@L@dAFP@T@R@J@J@P?B@V@L@Z@L@F?f@DV@J@X@D?P@XBP?J@L@T@z@DJ@d@BJ@F?T@XBP@P@X@T@VBP@T@L@\\@F@N@T@T@V@P@T@TBT@f@BX@R@VBX@P@L@D?l@DN@D?V@R@D@R@P@T@T@R@J@b@BL?b@BnAFTBd@BJ@N@J@VDH?F@^FPBH@f@HNBXFRDTDRDh@NRFRFNDD@PDVHTHRFF@JDRFRFTFVHRFRFh@PtA`@PFB@PFTFRF@?RHVFPFVHPFRFh@NVHd@NFBLBRFVHPFTFPFB?RFTHRFTFRFn@RB@JBRFLDF@RDNDF@JB\\FTBTBTBLBF?TBN@X@R@p@@^?P?`@AXANAXAVCRCF?LC\\ELCVEPETGTERGNEBATIRGTIJEFCLGFALGDCVMNIRKDCHE@ARKDEJGRMPM?ARMPMf@_@@AjA{@jA{@^WPMRMPMJIFCPMROXO`@YRMPKRMRMPKRMRKRMRKPMRKRKRKRMRKRKPKRKRKRKDCLGRIRKRKRKRI`@Qh@WVMh@UpAk@f@UpAi@|@a@h@UNGRIRINI@?TITKZKJETId@OZKPEh@Ob@MB?tA]RETEf@KXGhAQhAOFAv@If@EbAKB?PAf@EZAh@CrAEXAP?`AAX?bB@r@BV?L@bABzELZ?t@A|@A`AGn@E|@K`AQd@Kf@Mj@Od@Md@Qj@Sb@SBAPIVOr@_@XQVOBCx@i@BCVSXSXUVWXWl@m@\\a@DEHKZ_@\\c@V_@LQLQPWLSLSPUj@}@\\g@l@_A\\i@|@sALQ\\i@\\i@p@}@h@q@p@w@RUNO@APQPQNQPOPOXWVUHGLKPM\\YXSRMZUHELKVORKZQZOJIJEPIPI`@Sp@YXKj@SJEDALEh@QTGRETGZIPEFAXG@?RELAJCREl@IB?PCLAFATCPCVATCD?NAp@CLATAP?ZAJ?H?T?P?V?T?N?D?f@@X@j@Bh@@T@T?j@Bh@@R@V@T?j@BH?D?B?T@T@V?H?H@T?X@P?V?R?T?~@@V?D?N?TAT?D?N?H?D?D?TAT?V?PAb@AJ?RAF?N?@AR?TArAE@?TARAR?VAB?PATATAV?RAVARA@?RATAV??AT?RATAVAb@Ah@CF?ZANA`@Ar@CVAT?TATAF?LATATAXAP?j@CB?f@ATATAT?BAP?TARAVAD?L?RA@?VARATAT?ZAPARATAT?PAVAb@Ab@Cb@Aj@CTATAT?TANAF?XAn@CB?`AG@?VCVCRCB?NCVCTCTETCVEPEBANCVGRETERGRGVGPEXIRGRGRE@ARERGTGRGNEFARGTGPE@AXGLEj@OTGh@MFCFCVGRGTGTGRERGj@ORGTGREFCLCFCJC^K`@KB?NETG^KHCXGNEPEXITGJCFATGRGZIb@MTGTGPEVGNEl@QREVGRGFCFA`@KhA[BAf@Mz@UFAb@MXIFALCVIv@SVGHC`@KRGTGHAJEb@KDARGBAPERGTEPGVGHCHCTERGFCLCDALETEXIPETGRGRGXGNETGDAPEPE`@KFAVGPCVGREVELABAXEPATETCRAVCTCRCpAKNAlE]`AGbBO\\Cj@ETCRAB?f@ETCRAVCRC@?TCTCTCNABATCTCTCTCTCTETCTCRCTETCTEj@I@?h@ITEf@IVEHCHATEBAPCh@KJCf@KLCRETE@?RETERERE@?REVERENEDATETERETE@?REREREVEBANCTETGRCREVGv@O^IPCXGp@Mj@Mb@Ij@K~@QzHyAtAWTEv@O^IRCVGRELCHAh@KRETETERERETEVGRCPEXGb@IXGTETERENCDAFALCRETETETERETETEJCHATERETETGp@Mf@KVGpA[~@UfBe@xAc@fA]TGpAc@@?f@ORIVGRI^MZKVIPEh@QTIRGPGt@Wf@OTIRGTIRGTGnEyAj@QRG`@O`@M`Bi@VITIl@QRITGRIPERIPGXIRGTIPGXIPGRIXIp@ULEZIRIRGRGTITGRIRGTITGRIRGVIRGTIPGRGl@SRGRGRIPEXKTIRGXK|@YRGz@YXIRGf@QTGRIPE@Aj@QRIh@QTGh@QTIf@Oj@SRGVIRIRGRGVIRGTITGTIRGRITGTIPGLEHCRGVIPGRITGRGXKNGRGVINETITIRGFALETIRGTGTGTGTGRERGTETETETERETEVERCTCVEf@GVCTAVCPATCTATA@?j@Ch@At@AH?X?T?V?T@X?P@T?R@V@V@TBP?B@V@TBP@^D`@D@@PBVBJ@HBVBTDTDRDh@Hl@L~@PxAXp@LbBZdARNBTF\\FtAVn@Jt@Nh@JF@p@L`ARhARv@Nd@J~@PZFt@L@?RDVFPDH@`@Jb@LVFB@h@PRFF@LFRFPHJBLFTHd@TRJRHRJTJFDJFPJPJTLPJTLRNPLLHLJPLNJBBPNPLPPB@NLPNNNPPPNNPPPNNPRNN`@f@NNNTPRNRLPNTNPNTLRLTNTNTLTLRLVLRLVJTLTLVJVLTJTLVLTLXJRLXJTLTLVJVLTJTLVLVJTLXJRLVLVJTLVLTLXHP@BLVJRNXJRLTNXJRLTLRNRNTNTLPNTPRNRRTVXNNTTPPHHRNNNJJDBJHFDRNPL\\VDBTNf@XHDZNTLPFRJTHVJPFTHRFTHRFRFB?RFRFVFTDRDXFXFTDTBRBTDl@FTBVB@?PBTBR@Z@P@V@N@X@R?X?V@P?B?RAX?N?XATARATAVAj@ETCj@Gl@Gj@ITETE|@QREVGTGRGf@MTI@?RIRGf@QVKPGTKdBo@RIPGPGNG`@O@?^Ot@Yh@QRIb@OdAa@TIRI|@]bDmA\\KRInCcA|@]f@Q~@]dBo@RITIPG|@]z@[h@Sf@Sh@Qd@Sj@SRIRGTIf@STIx@[dBo@RIf@QRIVIlAe@RIrAe@f@SdBm@RITIRI`FiBd@SXILG|@[z@[TKf@QRIh@QRIf@STIPITIRGf@SRIvDuAh@QXKLGTIRITGDCNERIrAg@JEj@Sj@SlAe@TIRIf@QTIf@S~@]f@Q~@]|@]pAe@TITId@QzAk@RIf@Q|@]RITGf@SJE`@OLERITIRIRILEFARIRIRIRITGRIJEFCRIRIHCHERGTIRIRIRINEXKRIRIRITIRGPG@ARIRIDALETIRIRGTILGDARIRINGB?TKRIHCHERGRIDALETIRIPIPGB?RIRITGRIRGRGTIRGTIRGHCHCTGRGTGRGRGRGTGFAJCTGRGHAHCTGREHCJCTEHCHCTERETELED?TGRETETERETERCTGD?NCDANCRERCTETETERCTETCPEVERCTETERCTETERERCTETETEHAHCTE^GJARERETCFCJATGRETGRGRGLCHCPGTGRIRIRIRIRKVMNIPITMJGFERKHGHEPMLIDCPMRMj@a@LIPMJGFGPMRMLKBARMRQTODCPMPM@?PMRQPKPMPMPMFCLKROPKRORMPOJGXSRMPMJGFGPMRMPMRMNM`@YFCPOPKHGRMPMTQ`@YRMNMRMPMPORKPO@ANKRMPMPM@APKPMPORMPMPMPMRMPMRMPMPMTQFEJGPMNKTONIVOLGTKRKNGDCRGNGd@MDARETERCTCTCRAT?TAT?T@R?T@RBTBTBTDRDTDRFHBJBHDPFRHRHLFFBRJNH@@TJRHRJRJRHRJLFDBRJRLRHNHB@RJRJRHf@XRHf@VRJ`Bv@B@f@VNHPHRJPJj@Vf@VjAj@l@Zv@^f@TXNLFRHPJp@\\`@PFB`@Pv@XVHd@LTHRDJDRDZFn@Lj@HRBVBTBR@TBT@T@h@BT?V@j@?RAj@AVATARAVCRCTARCVCRETEj@KRETEPEl@QRGh@On@WLERKRIRKRKRIPKTMPMRKPMRMPMROPMPO^[~BmBz@s@DEVSDERQr@k@BC|@s@XWTSRO@Cd@_@ZWPMt@o@d@a@b@]NMd@_@@Ab@[b@Y`@WBCf@W?Af@ULGXOf@STIBAPGf@QTGFAJCh@OTETENCXG`@GHAj@GRCTAj@EVAj@A`@AF?l@@h@@j@@`@BF@j@Bj@BF@`@B^@H@j@BF@b@BR@V@b@BD?l@BN@XBX@R@h@Bh@@T@l@@T?R?R?X@j@Aj@?j@Ah@CJ?JAbAERCRATA^E`@C^EHArAQXEj@I@?f@KPEXGj@Kz@QDAPE\\KJCh@M@Af@MRI^KHE`@MFCRIRGRI@?RIRI@APIRIPI@?h@WJEXO`@QDCTKd@Yd@WLGFCPMRM@?PKPMHGFERMLIFEb@[LIDEPMTQNKd@_@FGXUd@_@b@a@b@a@`@_@`@c@PQPQ^a@RU`@c@^e@FIV[X[DGNSRUJQRYJM\\i@\\g@^i@LUNUZi@@AZi@R[d@w@NWNULULSNULSLUNULSLUNSLULSLULSNULUNSLULU@CJONULULSLSLSNUNUPWJQLQNSNSNQNSNSNQPSNQPQNOPSHIDEPQNOPQPOPOPODCLKNMPOPMPORONMTQPMPOPOPMZWFGPMPODCDEBABCLKTQPOPODEJGPORONMPOROPOPMNK?ARQROPOPMPOVUJIPOPMPMROLKBCPOROJIDCPOPOPM\\YDEROPORONMRQPMRQPMRONMPOROPOPOROPOPMPOPOPONMRQPOPOPOPOPOPOPQPOPQPOJKVWNOPOJMDENORQNQPOPQLOBAPSNOPQFIFGNQBCLMNQNQNONSNONQFGX_@p@w@HIvBgCbD{Dr@y@p@y@t@}@r@y@X]@AZ_@r@{@TWRUX_@Z]dAoAlAwAv@_A\\a@`@g@DELO`@e@NQNQNQPQPQHGFGPQTULKRQNMd@a@TQb@[TOROj@_@NIb@WDCXQNI\\OTMRIb@Q?AXKPGDCRIb@ODAh@Q~@WHCJCVGTGLCj@K^Gr@Kf@GXEZC^CRCH?h@CXAHAH?LA\\?b@AX?^@P?`@@`@@bBDH?b@Bz@BpBFtADP@bABR@h@Bn@Bh@@Z@b@@j@B`@B^@f@@j@@N?\\?P@p@Ad@?XAz@CD?b@A\\Ab@CJAHAl@ERAf@E`@ELCj@Gb@GD?h@IhASp@Kd@Il@MlB[f@KfASb@GnAUv@Ot@MrCg@jAS\\GbCc@x@QJAFC^IVGZKVGPI`@OZMHCf@W@ATOh@[@Ab@[POPMPQZYFGNOLOPSRWLOJMZc@@CHMFIXa@R]@?l@}@Zg@T[\\i@FKZc@l@_A\\g@NULQZc@PURWZa@PQNQJKTUPQd@c@BCLKPOLKZWFEVQNKPM^Uj@[HELGPIRKTKXMFCXKVIjAa@XILERGjBk@d@MVIXIhA]`@Mr@Ur@Sz@W\\K@?l@QNEz@Wh@QXIj@Qt@Uj@OFCr@SpAa@h@Qh@Oz@Wf@Oj@Qd@Oj@OrAa@PGf@OZIRI`@MFAd@OVIn@SXKZKPGTKNIVMTKPIPKj@[NKBANKPMPMPMROFEHIPOPOFEHIPONOPQLKDENQPO@ALMRQDEHKPQPONOPQPQPONQDEJKNOROPO?APMPQFGFEROROLK@AROPKFGHEROPMDALIPKRMHEHERKLGDCRKRK@APGRKPIRITIJEFCLEDCRGFAJGRGPG@ATIRIRGTIPG@ARGRIRGTIRIJCHCRIRIRI@?PGTIRIXKRGNGRGRIRGTIRIRGBAd@QPITIRIRGRIRGFCLERIRGLEDCRGFCLEPGTITIRGDCNGRGPGTITIBAPGTIRGTIRIRIPGf@QTIJCFCRIRGTITIRGRIB?PGNEBATGFCJCVI`@Kn@MTGRETGTEPCVGRCTETCRETCTCTETCh@GTCRATCRAVCRAj@ERANAF?h@CTAl@ERATARATARCj@CVATARATARCTATATCTATAj@ETATARCTCTATCBAB?LCRCh@ITERETETEf@KRGVGFALERGTGRGTIRITGRITIPITIRIRKRIf@WPKRKRMRMPKRMPMRMRMPMPORMPOPOPMPORONQPMPQPQNO@ANQLMNQPSNQFGFINQPSLQBALONQNSNQPQNQNQNQNSBCLMNQNQJOBCNQPSPSLONQPSNONSNQFGHKNQNQTWj@q@PSLONQNQNSNQPQNSNQPQNQ^c@NQNQ`@g@HKDEl@s@b@i@NQNQNQPQLQPQNSNOPUNQNQNQNQPSNQNQNQNQPSNQNQPSNQNQNQPQNQNQPQPOPQb@_@PMNOROPMPMRMNMTMd@[PKRKRMf@URKRIRKTIRIPITIPITITIRIPIRIRITIRIRIRGRIXKLGTIRIRITIRIPGBANGDAFCZM~@]ZM^Oh@SBANGRITGRI|@]RGFC^O~@_@\\MLEjAc@b@QXKRIl@Ub@Oz@]t@YTIn@UnAe@RITILEn@W\\O^Mb@Q`A_@n@Ut@YRIXKLGPGTKf@UNIBAd@YRMPMf@a@^[POLOTUTYHKNS^i@LSLUVe@LU@EJSJW@A@CFOLUJWJU@CTg@LYJWJUVm@BCHS@Cp@{ARe@dB}D@C\\y@\\w@HOd@iAd@eAd@eA`BuDn@yA^w@Tk@NYJWLWHOBELUt@{ANULUHOR[JQDIFK\\i@LSNSLS`@m@`@k@NQJOFIPUPUn@w@NQPQRWPS\\_@X[h@k@h@m@HINQ^c@f@i@JMb@c@PSn@s@t@y@l@o@HGZ[l@g@h@c@PMh@_@b@YTOj@[JGVM^SDC`@QLEr@YbA]b@MZIv@S`AQTEp@KZEZCTCPA^C^Cf@ATAZ?|@?l@@V?V@j@DzBNbAHv@F`BLH?N@bCRn@DR@VBJ@dAHdAFJ@dAHtAJL@D@\\Bb@BZBJ@j@DtAJT@x@HfDTl@Fb@BXBj@Fh@HZDTDPDTDRFTF`@NXJ`@PHD`@RZNj@ZHFtAx@^TrAx@^TRLLHj@^HDHDZRb@Vh@ZZRb@VTN\\PVNRJl@Xf@Rl@RNFDBTFf@NPFr@Nj@LH@TDTBTD`@Db@DTBV@\\Bf@@V@`@?`@?p@Ad@CTAp@EVCXELA\\EHANCj@KB?b@KpAYTELC|Cq@JCTEVGr@OlAWTEZGNETEj@Ml@MLCn@Mh@KTCB?LCZCZE`@CRA~@E`@AF?L?f@Al@@R?x@B\\@@?h@Dd@DNBn@FpANZDRB~@JzAPz@L~@J`AJvAP`ALhBTl@F|BXP@vAPhCZ`BPf@FPDTBTBTBRB@?RBTBRBV@RBR@T?T@T?T?T?h@CTCB?PCTCTCTERETE@APETGRGRITIRKRIPKRKRMRM@ANKRMRMb@[d@[RMPO@?PMPMRMPMPMRMBANMPMPMd@[PMHEZUROPMPMRMPMRMROPMPMPKROPMRMNKROPMRMPMPMROPMRKHIFCROPMRMPM?APKRMPMRO@ANKRMPMROPMRQPMPOPMPORONOPOPQPMPQNOPQPONQPQ\\]f@i@f@m@\\_@X]T[n@y@t@cAb@o@NUZe@j@_Ah@}@h@_AP_@|@cBlGcM?AxC_GTc@Zo@R]|@iBP]^u@n@mA`@y@P[Zo@xAuCl@mAh@cAhA{BZo@P]Te@jA{BDGN]Tc@R_@Te@FIHSP]P[f@cAVg@b@{@P[b@}@\\q@Zk@Ve@NUJOHMXa@PS\\_@RULMPONMTQPMRORKd@WRKPIRIVKPEj@Q|@QFAd@Eh@ED?RAf@Aj@?X@R@XBd@FPBTBpATTBdARt@Lv@L~AXtB^XD\\Fv@Lx@NdAPb@HB?LBh@JLBRDp@LZD^Fz@Nd@HTDt@LtATD@b@HzCf@~@P`BXb@FdBZF@\\FbBXJBPB~@NB@H@LBRDJ@PBRDf@HNDVDTDf@HB@`ANPB^FF@fBZH@t@Nv@Lr@Lp@Jx@Nj@Jv@NdAPt@Lb@H@?rAPf@FPBH@h@Dj@Bj@@T?T?V?XAZAd@CTCRAVETCTETERETEHCJATGRGTGDCNERIRITIRKRKRITMBANIRMHEFETOPMd@]POPMPOPORORMPOPOPOPOd@]POBCLKd@_@POPORMHIFEPOHGFEPOPORONMTQb@]b@_@PMRQPMROPOPOPOPOROPOPOPORMPOPM@APMPORMPMPM@?PMRMRKFCJGRKRIRKLEDCTIRIRGTITGNCBATGTERETETCDANATERCVCTCRCTCTCTCTCTELAFATCTETCj@KRGTETERGTGTGRGB?PGTGRIRGTIRITKRITIRIRKRKRKRKRKRKRKRMRMPMRMPMRMRMPMRQNKBCLKPM@ANMVUJKDCJMDCJMBCPOLM^_@PUPQBEJMNQDEJMBCJOBCJMBEJMNSNSBCXc@BENShA_BBEJMv@gAFKNS^g@DGv@iALORYJMBEHOBCJOBEJMBEJMBE?AJMBCHOBEJMNSBCLQLQBE\\g@JOPULQ\\g@@C@?LS^g@DKJMHKFKJMLQPUJORWJMNSNQPSNSBA?ALMPSBCJKBCLM@A@A\\]\\[DEDCJKPOBCRONOROPMRORMPMPMRMRMRMn@]JGRKRKRKLGDARKRIRKTITIPGJEHCTIRINEDATIRGJCHATGTGREBAPETEf@M@Az@S~A_@NENEd@KTGB?PETGRGPEBATGRITGLGDATGRIRKTINGBCRITKRKRMRKRMPMRMDCLIRKROPMRMPMRKRORMPMRKRORKPMRMNIBARMRKRIRKTILEDCRITGTGRITETGTERETETETCTCTCTCTATATATATAV@TAT?j@?`A?l@?@?R?T?T?j@AV?T?T?D?N?TAV?T?TAJ?HAT?TCTATAFANATANCD?TCDANAPCB?TETETETCRE@?TETGTERG@?RGTGLEFARGPGB?RITIh@QNGXKTKRIRKRKRKHCHGTKFEJERMHEFETMPM@?RMPMRMPORMHGFGROPMPQPOFGHGRQNOPQRQNQPQNQPQPQ@ALONSPSNSNSNSNSLSNUNSLSNY\\i@NWJSLULULWZm@FMP_@Xo@Vo@Xo@Vo@JUHO@GXq@Xm@JWJWLULWJUNWLUTa@DGLSNSNSNSNSNQPSPQNO@APOPOPQPOPK@APORKPMHGHERMRKRKTKRKFCVMFERKRIRKFC`@SRKBCLIRMRMFEJGPOHG@AFEPOPQDEDEDEPQJOBANSNSLQ@APULSLULULWLULWJWJW@EHSHWJYHYHYHWH[FYHYHWHYHYF[@CFUH[FWHYHYHYFYHY@GFQHYFYHYHYH[BIBMHYH[T{@FUHYFYHWHY?AH]FUHWFYHYHWBOBKHYRs@FYHWHYBMBMHWHYFYHYHYFYHYHYFYHYH[HWFYJ]FUFYHYHYFYHWH[HYFYHYHWF[HWH[HYFWHYHYFYHYHYFYHYHYFYHYJYHYHWHYJWHWFOBGJWJWLWLWJULSLS@ALUNSLSBCLOLQPQBCLMPQNOLKVSPOZQHGZSLGVMd@STITIBANERETGREHAHADANCVCTCRATCTATAP?VAl@ALAF?d@AVAJ?HAT?FAL?RATAv@AF?l@C|@CP?zAETAf@AB?j@CTARAVCTARCD?x@Kj@IJA^It@QFARERGTGRIRGPGXKRIRIt@]DAPKRKPKDANKRKPKPMRMRONITORMXQ`@Y`@Wp@c@VOb@Yd@[RMPKLIXQPI?ARKRKLIj@WRKRITIPIB?d@QRGTG?AREFCTEJETE@?LCXGd@IF?PCTEZCBA^CRCTAf@CXCPAVALAZCVARAVCHAH?jAGtBMHAJALAJ?PADAd@Ch@ETATCVCf@EXE@?d@ITEDALCNERGXITI@?PGJEVKXOLGBCb@W@ARKRMBCLIPONORQNMPQPQNQNO@ANQLQ@ANQLQNSNQHK^c@^c@FKNS\\a@DGd@k@TYLQNSPQLS@?DIHKHKDCNSNQ@AJQPSNQLQ@?NQNSFIj@u@@?FK`@e@TYLQJMNQNSNQFKDE`@g@FIFGNSDEHKFKFGLOPSBEBEf@m@NSDEHKNQNSNSBEX]p@{@RUZa@NQDGHK^e@JMRWTYHKNQBEJMNSNQBCJMNQ?ANQNSFGV]PSLQNQJOBCNQNSNSFIFGNQNSRWZa@LOPSHKBEPSNQ@ALQRWDGX_@JKNQNSBELMJM^g@PUNQJOBCNQ@ALQNQZ_@DGNQLS@Af@k@DIPSLQPS\\c@NQLQPUTYLMh@o@d@m@PSl@s@VYv@w@^_@d@a@BCr@k@x@i@BCf@]t@e@v@c@r@]RKDAp@[VMlA[jA[~@SXEf@Ib@G^E`@C\\CRA\\CLAX?PAV?PAX?T@X?T?T@N@@?X@f@DH@ZBd@Dr@Hp@L`@Hv@Nz@TF@\\JRFtA`@|@VvAb@f@N`AXtA`@pA^`AX|@XbCr@jBj@hBh@ZJLDlA^tAb@VFtAb@VHx@VxBn@~Br@`Cr@l@R^Jl@RVF`AZf@LPDd@Lt@Ph@JRDVDVDTDPDVBTDVBTBVDTBR@TBVBT@TBT@T@V@R@T?V@T@V?P?V?V@RAT?T?V?PAX?TAB?NATAVALAF?TATCXATCRCj@EDANALCFARCTCVETERCVERETETETGTETGVGRETGRGTGRGTITGPIXIPGPGBATIRITKTIRKPITKRKRIRKTMPKTKTMPKTMRMFEJGPMPKTQNKTOPMPMTQPMPOROPOPORQNOPOPQRQNOPQPQNOPSNQPQNQPSPSNSNQNSPUPS@CLOLSPUf@u@BENSPYLSLSLUPWLUJSNWJSNWXm@BCJUJSLWHSN[JUJSN]JSJUN]Xo@|@uB~AoDj@oA?A`A{BFI@ELWJWJSP]HQNWPY@CJQJQRWLQNSPSPSLMPQ@CNMPONMROPKPMPKTMPITKPIVK@?NGPEVGTGPEVGPCNCHARCXATCTAX?TAVAP?X?JA^?b@Ad@Ab@?rACv@AV?TAf@?bAA~@ARAV?`@A^?R?VAR?T?RAtAAB?TAj@A@?~@A@?P?T?TAR?j@AX?B?R?TAT?T?h@AP?VAf@?@?TAh@CTAFA"
                     },
                     "start_location" : {
                        "lat" : 40.1605189,
                        "lng" : -80.1937667
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 mi",
                        "value" : 898
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 33
                     },
                     "end_location" : {
                        "lat" : 39.5788292,
                        "lng" : -79.97325720000001
                     },
                     "html_instructions" : "Take exit \u003cb\u003e148\u003c/b\u003e for \u003cb\u003eI-68 E\u003c/b\u003e toward \u003cb\u003eCumberland\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "ibrpFx|cgNTL@?l@AZ?T?PAP?F?R?TAV?R?VAR?f@AN?XARAVAVCLADATCRGREVGPGZM@?JGTKPMPMBALKPONMRSNQ@CLOLSNULUJULUHUJWJ[FUH]FSD[F]D[BYBY@Y@]@W@]A]?[AO?SAIAYA[CYQkCG{@MwA"
                     },
                     "start_location" : {
                        "lat" : 39.5832457,
                        "lng" : -79.9791725
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "37.7 mi",
                        "value" : 60697
                     },
                     "duration" : {
                        "text" : "34 mins",
                        "value" : 2030
                     },
                     "end_location" : {
                        "lat" : 39.6775057,
                        "lng" : -79.37870269999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eI-68 E\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Maryland\u003c/div\u003e",
                     "polyline" : {
                        "points" : "ufqpFzwbgNKsAOeBI_AEm@Ei@Eg@Gq@M_BUiCASKqAE]AMAOCYGw@C]CWE[C[CWC]EWE_@CWE[C[E[EWE[EYEYMy@EUG_@EWEWG]GYEWG]GYGWG[GYIY?AGWG[GWI]GUOu@Oo@I[WmAGWI]Oq@Ka@CSGWMg@[yAOs@[oAGYUgA[sAGWo@qCOq@CQQs@Kg@Sw@Oq@S}@Ou@Qw@Oo@GYMi@UaAKg@c@oBWgAMg@GYMm@Ka@EW]wAUiAOo@GUCMWiAEQGYGYYkAOs@ESKa@q@yCGYq@{CcAkEa@iBOw@a@gBWgAQy@Oo@YoAOs@I[iAgFQs@iAiFOo@AGKc@CKI]S}@UaAOs@Qs@GYESAGOq@Qs@EQIa@Qs@Mm@?CKe@EOQw@GSG]AEESMi@Mg@EUAEEQGUG[GYGYCGESGWGWGWG[GYGYIYGYGYIWGWIYIYIYIWIWIWKYIWEIEKKYKWMYISMWKSACKUMUUc@QYOUOU[g@a@k@CEg@m@MQSUMMQSOQw@w@]YQOQOQOQMSMSOSMQKSMAAQKQISKSKSISKOGCASISIUISGSISGSEUGUGUGSEUESEUCUEUCSCUCUCSAWCUASAUAU?UAS?U?W?S?S@W@U@U@S@UBU@QBC?UBUBUBUDSBUDWDSDSDWDq@NSBE@A@WDg@Ji@JUB{@PUDA?SDMBc@HIBWDi@JQDWDSDSDk@Hi@JYDc@HWDe@HWDk@JUBUDUBSBC@SBWBU@WBY@W?U@]?[AKAU?KAi@Eg@EuAY[IYIYKUKQG_@QYO_@SAA]USMQOSOi@e@QQAAUWUWW[e@q@OUWc@S_@MUSc@Se@Wq@Uo@GQGQAEOg@Qi@]mAQk@Oe@AGM_@Qk@Qk@Us@K[IUK[CGg@wA_@_A[u@O]GOWk@IOCGO[Sc@O[MUc@{@]k@]m@]o@CES[]i@}@uAq@aAi@w@QUu@}@w@}@{AgB]]a@e@gAoAs@w@_AeA{AeBwA_BiAqAoAwAcAkAY[i@k@kAsAs@y@e@i@}AeBOQy@_Aq@u@[a@u@w@u@{@u@{@}@eAQS{@_Aq@w@]_@[]cAkAq@u@s@y@oAwA]_@a@e@SUUWeAqAQUOQOSOUOSMQOUOSMUKMCEMSOUMUOUMUOUKSOUMWMUMWKSMWGIGMKUMUMUMWYk@KUOWKSKS[m@MWMUMUMW]m@MUOUMSOUMSQWIKOSOQQSOSMOSSOQQQOOQQSQe@a@QMQOQMQMSMSOSMQKUMSMSKQIUKSKSIUKSIUGSIUIi@OSGWGQGUGUGUGSGs@Sa@Kq@QMESGUGUGUGi@OUGSGUGUGUGSGEAOEUGSGUGUGSGOECAUGUGUGSGUGUGCAQESGk@OSGUGSGk@Ou@Su@Si@Ok@Oi@Ok@O}@WUGi@Oi@OWGiBg@UGi@Oi@Ok@Ok@OkA[q@Sk@OMECAWGUGGCMCUGsA_@kBg@SGk@OuA_@i@Oi@OUGQEm@QSGSEUGUGSGUIi@OUGUGUGSEUGSGUISGUIQGUGSIUIUIUIOGUKUKoAi@QKSISKSKSKSMSISMQKg@YSMQKQMQKe@[SOOKSOQMQOSMOMSOQMQQSOQOOMSOOMQOSOOMQOSOQMSQGE[WQOQOaAw@g@a@QOQMMMi@a@SOMMCAOMSOQOAAOMQOQMQOQOQMCCKIOMSOQOOMSOQOSOc@_@QOQMOMSQQMSQQOQMQOA?OOQMSOQMAAOOSOc@][YECw@o@c@]QOQMQOKKQMSQQOQMQOQMQOQOSOQMQOQOQMQOQMQQSOOMe@_@QOQMQOQOYSMMOKQOQOQOQMQOSO?AQMQOOMQOQQQOQQQOOQQQOOOOOSQSOQMSQSMSOSMUMSOUMUMUMSIQMWMUISMYWk@MWKYKUKWKUK[KUISMYIUWm@KWKWKWMUK[KWUk@Wo@MYISSg@KUKWKWMYIUKUM[KWIQKWYq@Um@KUMYIUO[ISKWIUKUM[Uk@MYKUKWKWKWIWKYKWKUKWIWKWKUIWKWKWKWIUKYIUAAIWKYKW?AIUKYAGM]K[CGEOIWKYIYIWIWIYIYIYIWIWGYIYIYIYGWIYIY?AGW[mAACOo@Qs@[kAGWI]c@eBm@aC[mAOo@Qq@IYQs@Qu@IYGYIYGWGUOq@m@_CGYMk@WcAACGYGQAEI[Oo@CICOQs@IWGWGWAGEQm@cCQu@I_@Qm@AEIa@IYGYQq@Qu@Qq@GYI[CIMk@GWIYa@eBIYOo@AEGYIYWgA?EGYCMESKi@Ig@Ig@Is@Gs@Ei@AYC_@A[A[?[A[?Y@[?]@a@@_@@a@@]@a@BWBUBYD[Hm@?ADYFYDYFWFYFYFYFSH[HYHUNe@HSFOHWLWHSLWJULUNUJSNSNULSLQNSNQPQNQNOPQPOPORONMRMPMRMTMPKRKRKRKRIRITKPIRIVKz@]FC`@Q`@ODCZM^O|@]XMv@[f@STKf@S\\MHEf@Sj@UBA|@]h@Uh@S\\OFCRIf@STIPIRIh@UPIHCJERIRKRIRKPITKPKRMRKPMVOPMROPMPOPOPOPQNOPQNQPQNQNSNQNSNWLQLSLS?ANUFKDINYJQJWLUJWJUJWJ[HUJWJ[HYHWHYHWFYHYHYHWFWHYHYHYHYHYHYFWHYHYHWHYFWH[FWL_@HYFYHWHYPq@Lc@Nm@HWZiARs@FYHWHYFYHWHYFYHYNq@F[FWF[F[F_@F[DYD[D_@BUD[B[BYBYB[@YDi@@Q@[@[@[?[@_@@[?]?[?YA[?[A]?[AYA[C[Aa@CYAYIaAIw@Ea@E[Mu@E]Mw@UiAMw@GYIYEOCIIWIYIWa@gACIGMKWKWIQACKWMUIOAEOYMUAEKQKSMUCEIOMWMSCCIQMUMUIOCCMUS_@GKMUOYMUKOAEMUMUEGGMMUMUMSMUCEIOMSMWCGGMMUKUISACKWKWKWIYACGQIYMk@Ia@Mu@?AG]CYE[C[?ECWC[AU?CA]A[?[?W?C?]?[@Y@Q?IB[@[B[B[DYDY@OBKDYF[FYFYFWDOBIHWHYHWBEFQJWJUFMDIHO@EP[JO@CNSLUHKDGNQLSNQDEHMNSNQHKDGLQNSNUDIHKLUJSLWFMDGL[HUJYBIDOHYFWF[FYDYD[D[B[B]B[@[@[@[?[A[?[A[AQAKAYC[E[CUAEEYE[I]G[GUAAGYKWIYIWCGGOKYKUK[ISEKEKKWKWCIEMKUKYKUIUOQKWKUM_@EOM_@AEGOG[IWCMCKGWG[AECSG[EWAMCMCYC]CO?ICYC[AW?EAYA]?U?EA]A[?[Am@?CAW?a@A[?[?KAQ?]A_@?SAk@AgA?EAe@Aq@AS?_@Ay@AY?CAy@?[AQ?E?[A_@?S?GA[?[A[?[AO?KA[?a@Ac@?O?[?[?S?I?Y?]@EDmA@E@SD_@B[DY@GDSFYFWBMDKFWJYHU?AJWLYBEFMJUJS@CLUJSDGFMNYLUNWBEHQJQLWLULWJULUJWDIDKN[JWHWBGFOJYBGDOJYFUJY@EFSFYHYBKBKHYF[DM@KFYBKBMF]BK@KFYD[D[@CBYHu@@GBSB]BYD[?I@QB[B[@[B]?M@M@[@[?[@[?K?O@[?aA?SA]?YA[A[Cw@AYAOAOEu@AWACC[C[AOAIC]EYEe@AQCYCYAICOC]Gi@?GIu@AOOyAGu@CSCa@Gu@?KCYCi@Aa@?W?KAcA@I@o@@k@@YDg@Bc@BSB[D[DYDYDQBODQFYF[HYBMBIFWHYHWFOJa@JWHYHUHYHWHYFQJ]HWHWPi@BGRq@HW@CFSPm@J[Ro@@ANe@BKHUHYRo@HYFOLa@HUHYFUJ[HYDOBEHYHWDQ@GHWFYJa@DQBQ@GFYDYF]BYD[@M@KB[B[B[@[@[@[?Q@K?Y?[?[?S?G?]A[?YA]AY?S?KAW?]A[?[A]?YAY?IAS?[A]?WA]A]?YA[?]AW?GAWAqAA[?WAa@AY?]A[?[A[AY?[AY?_@Cy@?YAS?I?YA]?YA]AY?]A[A[?YCuA?[A_@?WA[A[?[?[A[?O?M?[@[?[?[@O@g@@Y@[@[?E@UB[B]BY@S@EB[B]BYBO@KDYB[D[DY@G@QD[D[DYD]DWB]BM@KD[DYBQ@IB[DW@GBUBYBS@ED_@BW@K@QBYB[B[@M@KB[@]?G@S@[@[@C?Y@u@@[?Y?Q?M?]?Y?[?]?[Au@?[?[?Q?K?Y?]?[?[A[?Y?[?[AY?]?[?[?E?W@[?[?[?Y?U@G?[@Y?]@Y@]@]@Y?E@U?[@S?G@[@[@Y@]@[?[@[@[@Y?I@S@[@]@S?M@S@[@[@[?A?Y@[@[@[@[?KBo@?Y@[@Y@[@U?E@]@[?Y@A?[@S?G@[@Q?I@[@[?[@[@]@[@[@Y@Y?A?[@[@[@]@[@[@[@q@?C@[@]@[?E@U@[?WDyADwAFgCDcBBgADsADoAD{@F{@Ds@Fs@F{@Fq@Fw@Jy@Hu@Hs@Jy@Ju@Jq@Lu@Lw@TkAP_AReAVoATkANu@VkAToAVoAVmAVmAHa@Lq@Lo@VoAVoA\\cBVuAVqAViAToA\\eBN{@Js@PkAL{@Hu@BSFw@Fo@Fw@Dq@Be@Bw@B]@[@w@By@@w@?y@?}@A{@As@Ay@EkACaAEoACy@IsBCw@Co@?GCy@Aw@A{@?s@?a@@u@Bw@Bu@@a@BWDy@Fu@LsAHu@@ENkALs@Nu@Ha@DULk@F]^eBR}@DUR}@Lk@Lq@Ls@FYD]Ju@Hs@D_@B]BYB]@]@]@e@@m@?Q?c@Cw@A_@A[A[C]C[C[EYC[E[EYG]EYG[GWG[IYGWIYIYKWSk@MYKWMYKUMUAAKQMW[g@QWMQCCMOU[UY_@e@UWMOa@e@_@c@QUOOOSa@e@QS_@c@aAkA_@e@OQEEGKQSMSa@i@[e@Yg@OWMSYk@O[IOWm@Wo@Wo@Ws@Sm@Qm@AEI[IWI]GWG[GWIa@ESE[G[G[Im@My@Ku@Iw@QqAIq@Ky@OoAQsAK{@Iq@Ku@OsAM}@Is@M{@?CMeAKy@QqAKy@Io@Ga@QoAKu@Mw@Ms@Os@Ou@G[Ow@Qq@Os@Qs@Ss@[gAMe@Oi@K[So@Uo@Oe@CIWq@Wq@Wm@Si@CEc@cA[q@Ym@KSMYi@cA_@q@Uc@MU]k@[i@[k@[k@]k@[i@[k@[i@]k@]m@Yg@[i@[k@Yi@OWYk@KSMWKWMYKUWo@KWUq@Us@So@Ss@ESGWK_@Os@Ms@SqAE[CQAIEWE[C]CYE[C]AYC_@C[Cq@Ca@?WA_@AO?K?[A]?u@?u@@_@?W@E?[@[@]B[@Y@]BYB_@BYB[D]Fs@D[D]DYDYLs@Nw@Ls@Ps@H]FURs@Rq@Tq@To@Xq@DKBEL[HSLWLULWJUBEHM\\o@Xi@NWLSXi@\\k@Zk@Zi@Zk@Zk@Zk@Xm@NYJQVm@P]Tg@FON]Xo@Tm@Vq@Tm@FONe@Tm@Rq@Rs@Ro@DKLg@Rs@Pq@Po@Pw@@GLm@Nq@H]DYF[H_@@EDWHi@F]F_@Jo@Ju@Lw@Hw@Jy@Hs@Fs@H{@JoAJqAJwAJuANmBJwAJsAJ{AP}BBYBc@L_BDc@B[B]@YB[D]B[@YB]B[BU?EB[B[B[B[B]B]@E@QB[B]B[B[BYB]BYB]B[B[B[B[B[B[B[BYB]B[B[B[B]?C@UD]@YB[B]BY@K@OB]B[B[B[B[B[BS?MBUBYB[B[?CBWB[B[?I@QB[B[B[B_@F{@B[@[@[BW?C@[@]?[@[@k@?c@?M?S?U?]A[?[Aa@A[A]C[A[AUC_@C]C]CSEa@C[CUEYE_@EUAICSE[GWE[G[GYGYGYGYI[GWIYIYIYIYIWKWIYEMk@wAKWGSSe@KSEIk@eAo@kACACIQ[Ua@q@iAOYsA}Bw@sAWe@MScAiBYc@GMg@y@_@o@q@iAk@cA{@wAq@kAw@qACGUa@Ua@EIYk@EKO[Q_@Ug@CKSi@EMWu@IUI[Su@GWK]S_AI_@Mu@Oy@Kq@AKMaAKcAMyAGeACq@?ECy@Cu@?A?w@?y@@sA@q@?EFsA@YBa@LqBLuB@IHkAJaB@SBe@JoALuB@IJ}ARgDBWLuBJ_B?ELwBDm@Bs@Bi@?A@_@By@@o@?G@y@@w@@s@?E?q@?c@?wAGeD?]?EGeBEuA?ICWAYC_@A[CYA]C[C[C[C[CYC]E[C[C[E[E[ASCOCQE]CYE[E[G[EYE[E[EYG[EYE[E[EYG[EYE[E[G[EYE[EYG[E[EYE[GYE[E[EYE[G[EYOsAEYC[AGCSGw@E[C[CYC]A[CYA[C]A[C[A[A[A[A]A[?[A]?[Aq@?[?a@?[?]?O@g@?[@[?U@]@[@]@Y@[@i@@OB_@@[BYB_@BY@[B[BUDa@BYB]D[BYD[DYDYD]DUDYDYD[FYD[H_@DYFYF[FYFYFYHYFYFYHYFYF[Po@F[Pu@FWH]FYFYHYFWFUH_@Nq@H]DQJa@FYFYH[FYHYFYFUH_@FWH[FYFYHYHc@DSFUH]FYHYFYHYFYFYH[FYPu@FWH[FYFWF[HYF[H[DSFYHYFYHYF[FYHYNs@HYH]Nq@FYHYF[Ps@FYHYFYF[Rw@DWHYFYFYHYFYHYF[FYHYPu@FYFYFYH[FYPu@FWF[H]DWFYNw@DYF]DWF]DYDYF[D[D[DYJw@B[F_@BWB[D[B]D[B[B[B[B[B[B]B[@[B]Ba@@U@[@Q@Q@[@W@[@[@[@]@w@@]?]@[?]@[?]?[?[?]?[?]?[A]?[A]?[A[A]A]?[A[C[?KAWA[A]A[C[A]A[Cs@E_AGuAAWASAa@Ey@A[Ai@Ck@?EAWA[A[A]A]Ai@?m@A]?Y?[A{@?y@@y@?y@@]@]@u@@]?YBa@@u@Bw@@]BkABcADuADuADoBDwA@]Bw@BsABy@By@?EBw@BqABy@Bw@By@By@BsABy@Bw@By@By@BsABk@@k@Bw@B{@Bw@@{@Bw@By@Bw@@{@BsA@y@?y@?y@Aw@A}@Au@Cy@Ey@GqAG{@Gw@AMGi@C]Ku@Kw@Kw@E]G[EWKw@Mw@Mu@EUM}@Ow@Mw@Ge@Ie@Ga@EWE_@EYE_@CSGc@CYC[C[CYGw@C[CYA]C[A[Cw@Cw@A]?[A]?w@A{@?[@[?]?w@@wA?E?U@uA@uA?s@?a@@]?w@@uA?]@w@?mA@_@?_@?]@[?[?]?[@y@?y@?]@w@?y@@[?Q?}@@o@?_A@oA?O@y@?w@?[@y@@uA?sA@y@?{@@w@?[?[@qB@y@@uA?y@@uA?w@@c@?qA@qA@w@?_@?]@u@?[@}@?Y?uA@uA@sA?_@@cB?M@w@?]?]@u@?]?S?c@@}@@kBB}G?W@w@?{@?w@Aw@?]?CAUA_@AYEu@Gu@Iu@Ku@Mu@EWOs@Mk@Kc@Qq@Sq@Qq@So@Qq@Sq@Qq@Qq@Qs@Qq@Ms@Ms@Mu@Ea@CQE]Iu@Es@Ew@Eq@Ay@Ai@?i@?u@?o@@g@FgFF{DBaB@_A?{@?u@?QAc@?]Cu@Ey@Eu@Em@E_@C_@Is@G]EYEWE[G[GWOs@Oq@GSK]Sq@IWIWKYKUK[KSWm@GMO]Ym@]w@Qa@MWMWKUKUMWO_@EGM]MUIUMYIWKWKUIYIUIYIWIWIYIWI[GWGYGYGYG[GYEYGYE[CUAAE[E[MoACYC]CYC[C[A[AW?CC[A[?[A[A[?[A[?[?C?W?[?[?[@[?C?W?[?[?]?Y@[?W?E?Y?S?I?[@[?[?[?Y?]?]?[?[?[?Y?[A]?[?[A[A]AY?I?SAYA]AYC[A[A]C_@AUC[A]C[C[AYAIAQC[A[C[C[CYA[C[A[C[A[C[C[A[A[Ew@A[C[A[?KAOA[A[A[?[A[?[?S?C?Y?[?[?]?[@Y?]@[@[?E@W?YB[@[@[B]@YB[BYB]B[B[B[@IBQBYD[B[DYD[D]DYDYF[D[FWD[BKBODYFYFYD[F]DWP{@Hk@vAaI?Cb@aCRmALu@\\mBF_@Lm@DYF]F]Lu@DULq@ToARiAN}@Lw@DSF]h@yC@ILs@^uBDU`@aCFYHi@PaA`@{BHe@PaA@MF[FYDWN{@BQNw@V{Af@qCBS\\mBPaAJk@Lw@BIHg@N{@FYN}@Ji@Ls@DYNw@Lw@Ls@Lu@F]Lq@DSZkBNy@TsAToATsA^wBBMDUFWF_@Hc@DONq@H]FS@INi@J[Pk@J[JWJWFQL]LYXm@Pa@LUDKZm@JSZi@LUXk@@?Xk@\\o@LSJULULULUHSBALWJWJSJU@CHUJWJWJ[?CFSHS?CHYH[H[FYDUFWFa@DWD]BO@GBYD_@Dk@Dg@@O@O@S@_@?W@_@@[?[?WA]?_@Aa@?MCe@Cc@AUCWCWCa@ACCUCYG[CYG]EWGYG[CKGSGUGWIYGWK[IUKWGOCGIUGOEGKWKSACKQKSKSEEKSCCKSMQQUMQQSCCKMOQKKEGOQOQg@i@KKq@u@QS_@_@CEKMSSOOQSMQOO_@_@ACc@e@OOOQEEm@q@IIEEOQUW?AMMOOa@c@SUMMMOQSIKGGq@s@QSAA]a@OQMKIKKKQUa@g@IKQUGIEGOSOUGKEG[g@GIUc@MUEGEKMWKUO[MYGOEIEMEKQe@Uo@Oe@CESu@I[GOMi@Mg@G]G[GYG_@ESIc@AOESIo@Ea@Gm@CSCWC]C_@Ca@Eq@AYAUAk@Ck@?]?]A[?Y?W?E?Y?Y?]@Y?C?Y?Y?M?O?w@?[?sA?_@@[?uA?gA?cA@u@?s@?[?[@kF?W?yB@}C?a@?oA?E?[@[?[?]@[@[?Y@[?A@[@Y@[@O?KB[@[@U@G@[Fs@B[B[Bc@BQBYBW@GBUBYBYFk@D[BS@IFk@D]Hs@?EFi@P_BNqARkBFm@@KHm@JgAP}AFk@D[Dg@BSFu@Dq@B[@Y@_@@Y?Y@]?_@?S?E?E?U?[A[A[AU?GAYAK?OC]C[AOAIC[AICSAEASE]CYMoAE]C[C[E[CYE]C[AEAUEYC[EYC[C[E[C[EYC]EYC[C[E[C[EYC]EYCYCYC[E[C[EYC[C[E[C[EYC[E[C[C[EYC[C[EYC]EYAOCKE[E[CYCICQEYG[E[GYGW?AG[IYEQAIIYGWIYIYIYIWKYIWKWKWIWMYKUKWMWKWMUMUMWMUIOCEMUOSMUOSOUMQOSOQOSOQOSQQOQQQQQOOIIYWOQQOQQCCMKOOAAOOQOQQEEIIQQQOQQOOQQQOQQQOGIIGOOMMQOOOQOQQQQOOQQQOQQQOOQKIEEQQQOQQQOQQQOKKCEQOQQQOMKCEQOQOSOOOSOQQQMQOQOQOSOQMSOQMQMSOQMSMSOQMSMSMQKUOQKSMSMQKSMSKSMSKUMQKUKQKSMSKSKKGGCSMCAOIQKSKSKSMSKSKSKSMSKQKSKSMSKSKSKSMSKSKSMSMQKSMQOSMQOQOQOQQOOQSOQOSOQOSOSMSOUMUMUMUKUMWKWM[ISKWIYGQAEKYGWCKEMG[IYEYG[Ms@"
                     },
                     "start_location" : {
                        "lat" : 39.5788292,
                        "lng" : -79.97325720000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "73.9 mi",
                        "value" : 118986
                     },
                     "duration" : {
                        "text" : "1 hour 8 mins",
                        "value" : 4081
                     },
                     "end_location" : {
                        "lat" : 39.7130552,
                        "lng" : -78.1922857
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eI-68 E\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "modqFzsncNEYE]Kw@Iu@E[EWE_@EY[kCg@_EEk@?CQwAs@wFEa@QsAE_@CQKq@EUKi@EYWwA[wAOq@Ok@GSEO_@oASq@c@oAM]M[IQg@iAc@aAaAuBaCaF_@w@oAkCUe@mAgCuAsCISS_@_@y@o@qASa@mAgCsC_G_AoBYq@Qc@k@uAAEUm@KYGUUq@Qk@_@uAOo@Oo@EOCOQ}@Ic@Oy@Ii@Ik@Ku@Ik@Iy@OaBUeCAOGi@Gk@CWEc@Go@AGASIy@KeAEg@C[Io@C]Kw@K{@UuAKq@Qy@WoAS}@I]Uw@Qq@K[[eAM]KYIUGQKWGQ[w@[q@]s@a@y@KSEIWc@S_@c@s@o@aAYa@_@g@QU[_@SWAAWY[_@}AiB_@c@WYMO]a@_@c@QScAkA_AgAk@q@[c@W][e@CEe@s@g@y@Wa@Wc@KQi@cACGQ]MUMYEM[q@c@cASe@a@gAAAM_@_@kAM]K[EOCIM_@EOEM[mAI[Me@GYCIAIWeA?AIYGWGWMi@U}@Qw@Mg@UaAQo@GY[qAAEI[CMSy@AEU_AMk@Mg@i@{BOo@AAG[Mi@GUKg@CMCIG_@EWEYG_@CUAOCOAUCUC[Cg@AG?QAO?KAM?OAM?S?C?I?c@?a@?E?m@@]@M?M@SF}@@K@QD_@BUB[Fa@Jo@DYLu@ZgB\\kBJk@Jo@PiAJs@B[D]@K@KB_@BY?G@U@YBs@?C@[?]?w@Ak@?I?QCi@A[Ew@?CEg@CUAO?ACQGc@CYG]EWKi@CKGYEOAIIYGWGYI]K_@IYW}@EMESCGOg@Qo@CGAGOg@GWGUEKa@{ASs@KYQo@I[{@{Cy@sC[iA]oAYcAc@}AGUM_@Ka@c@{AGW]oAEMQo@GS?AI[Kg@Ia@Km@EQEWKk@Ge@Ky@I}@AKCWCQG}@ASC[?MCi@Ci@?YAU?KAS?W?K?Q?e@?u@@a@@m@?I@W@c@JmC@UD_ABY?E?IDaA@SB[DcA@OFuA?C@QBg@?U@OBk@Bc@?CBm@FsA@M?KJaCBi@HeB?EB[@e@@MF}AFkAFyA@QJgCD_AB_@@a@Bg@D}@Bu@HeBB_@Bq@FuA@K?QBa@@c@@I@YD{@@s@?ABe@DiAFsAFsABw@@I?EBa@DeA@MB_AFsA@G@SD_AF}ABo@@K@e@Dq@FkADq@Do@Fu@Fu@D_@JaAHq@F]D_@Jm@DUN}@TiA@EPu@VgA@AJ_@Ni@Rs@J]Pk@Rk@@E\\eAHWz@iCFSFQTs@Pi@J]JYJ[n@oBDKHY@CNc@Vy@HYd@wA^gANg@\\eAFSJYTy@Po@?CH[Nm@Nu@Nw@?AJo@Hk@Jq@D_@B]BSFk@Du@Dc@@YDu@Bw@@m@@{@@k@Ag@?Q?o@AmBAyA?yAAY?oBAg@?c@?g@?eB@m@@uABcBFwB@[@]@Y@]B[@[@YB]@[Du@B]@[B[B[B[B[B[B[B[B]BYB[D]Fu@PoBRmBFw@RoBFw@Hu@Hw@LsALqAB[Di@BMFu@Hw@Fw@Hw@Jw@BYD_@RoAD_@DUD[F[Lu@VkA?AVmAPq@F[H[Pq@HYHWBGFSFWJYHWDODIHWHWJWHWJWVo@JWJWJUJWLWJUJS?ALUJWLULWBCHQLUPYLUBEHMLU\\i@P[Va@NWz@uAPWf@y@NWz@sAfAgB\\k@vA}BLSj@_APWZg@JQPWLSLUNULQZi@l@_AhAiB\\k@Zi@\\g@PYJQNWJOVa@T_@R[DIJQR[BEXc@LUj@}@NUNU\\i@Ta@FILUNUBEHOT_@FIj@_AJOBELSLSNULS@CJQLSNULS^k@LUFKPYNWNSFKDINSLUJQBCJSJMBGLSLSNULULSHMDGLSNUHOBENSJU@AJSHODGJULUJU@AJULYJWJWHWJWDIDMHWJYHYHWHYHWH]FUFYH[FYDYBKDO?CDUDYF[D[@IBOD[DYD[B]DYB[B]BYB]?C@WBY@[@[@]B]?[@[?]?w@@[?[?K@gA?u@?_@?[@[?]?c@?U@u@?[?m@?I?]?[?K@O?_@?Y?Y?y@@w@?[?]?[?w@@qB?]?u@@]?gA?i@@sA?[?[?y@?w@@]?w@?w@@Y?y@?]?Y?[@]?y@?w@@uB?g@?W@m@?eB@}@?U?w@?Y?M@y@?I?aB?wA@gBAG?]?YAW?WAYAi@A[Eo@AMGaAASEe@?AEa@E_@Ga@AMGe@EYEYAEQgAEUACGYGYG[EQMc@I[Sq@AGOe@KYSo@AAg@oAKWSc@[s@c@aAw@gBGOe@cAIQWo@e@aAYs@[u@M[i@uAa@gAUq@So@Qm@a@sA[kAU}@_@}AWmAOs@Ia@Mq@Ms@EYKi@Ik@Kk@g@gDi@kDAEi@eD[yBIc@[oBCSCQG[EY_@_CGc@Mu@EYG]CQGa@SoAE[GYE]EYW{AIi@Mu@E[E[QcAAKG[Ku@E[GYKu@Mu@Mu@E[E[GYE[EYG[E[GYEYE[AECUGYEYMu@G[GU?CGYIYGYIYIYIWCIGOIWKWKWKWMWKUMUKUOUMSMU_@g@MSQSOQOSQQOOQQOQQQQQOQQOQQOQQOQQQQQQQS][ACc@c@OOQQQQQQCEKIOQeAeAOQOOSSOSOQMOAAOSOUMSOUIOCCMUMUKUMWKWISACKWKWIWKYGWK[GWGYCMCKGYGYG]EYE[E[K{@?CC_@AMC[C[A[C]A[GsAIsAGsAE}@KiBA]C_@C[GqAAYGuAA[Cm@?MAe@AQ?]?u@?[?]@w@?YBy@@W@G@YB[@S@GB[B]BYNoBB_@Da@Dm@D]BYFw@B]Fu@D[BY@K@OB[Fw@Hw@Fy@Fw@Fu@Hu@B_@BWBa@?ABUHy@BWBYB_@BSB_@BYLwAFu@BY?AJkA?EFw@Fw@HkAHuADw@B}@Bw@By@Bw@@u@?[@s@@_A?iA?aAA[?_B?o@Aa@?[?Y?{@AaB?MAsBAyA?k@?cA?I?O?[@[?Q?M@[?]@G?M@_@Dw@@]Dw@@YBWB[F{@BYHs@H{@Fg@Hm@D_@RiBHw@DURmB@AFw@D]B_@BS?CFu@Bw@FmA?Q@k@@q@@}@Am@?a@?]Cw@C}@AUAWAIEy@Gw@Iu@AKGk@Ku@Ku@Ks@GYEYQu@COCMc@sBMk@GWEQKk@Mk@iAiFqAcGcAwEMk@u@kD}@eEYuAScAMk@Kk@Gc@Km@Iw@EWC]Iw@Ce@C]Ck@?GAK?OAKAO?KAy@Ai@?m@@u@DiA?CFcADi@@EDe@Ju@DYRoAJu@DQD]Ls@NmAJq@Dg@BO?CDc@?IDk@HaABu@Bs@@q@@_@?w@?m@?i@Aq@CgAC}BE_BCaBA}@CmACaAEoCIsEA}@Ac@?]A_@@w@?_@Bu@@c@B_@HoAFk@@IFm@Jy@L{@F]F[Je@F]Jc@BMT{@Lg@@ANi@HWZcA`@kAf@aBX}@X}@X{@XaAJY\\gATs@BIX}@J]Tu@HSRo@r@yBLc@V{@`@qAf@aBRs@T{@Pm@ZoALk@H]Pu@XkATkAPy@Lq@@KFUDSJo@BMLq@F]XkBf@sDRyAf@qD@Gd@oD\\eCf@sDd@sDBM@SBQ@STeBFc@VgBL_Af@uDf@sDl@wEViBh@{D^qCTcBpBgOdBqMHk@ZgCHk@\\gCRyADUBUp@_Fp@iFv@yFNsA^aDReBFi@Hw@Hw@TgCDe@Fs@B_@LkB@EDw@Du@B[LuBRuERgFFgBBg@FwA@WB}@FwADeAHmBBo@F}AJeCBq@@I@c@Bk@DeA@YDm@@k@Do@Bo@FyA?ABm@By@@K?OFmA@a@@[FkABo@F{ANiE@QR{E@]HkBDoAPiEBg@FuA@e@D_AB}@@OBc@@[@_@?G?U@Y?]?[?Y?A?]?MAO?[A[?ECs@A[C[AYC]CYC]CYE]EYKy@E[EYKs@Ky@Ks@SsAKu@ACCWE]EYE[C[C[C[C]AYC[Cy@?EAU?[?[A[@[?E?W@y@@Y?E@W@]@U@WBa@B[D]BYDa@DYHu@@GHo@VkBJu@R_BXyBTgBFe@PwAJq@@MNgAD[J{@Hm@D_@BYBUBa@B[BYB_@Ba@Bm@@_@@Y@]?]@]?Y?Y?[?[?a@AY?]A[A]Co@AMAWAWC]AYCYC[C]E[CWEYC]M}@c@eDYsBEWa@aDEY?EKy@Gw@AECc@Cg@GcA?AAs@Aq@AmA?ABoA?Q@[B_@Bk@Di@Ba@D_@Fw@D[f@gFPgBLwALoABWDc@NiB@_@Bq@@QB_A@o@@oA?K?y@A]Ai@?SAa@Cs@Es@Ce@KwAOyAIu@Im@Q_BMkAQwAIq@EY]wCMgAIq@SkBWsBy@cHMmASaBMqAI{@AUI_AAMCe@A[A[C]A[A[A[?[A]?[A[?[?]?[?]?A?W?[@[?]@Y@_@?[@K@O@]@[@IBa@Dc@@M@Q@[Dy@Dw@FaAFmALuB?EH}AH}AFgA@ODkAFcAHsBFcBDqADmA@e@@o@@[@eA@e@@mA@iA@s@?w@@cA?{A?iBAcA?m@AsACuAAy@Aq@C_BEyAEmAGaBEeAGuAEy@Ck@GcACc@McBE]MsBGq@G{@Ea@CSC]C[CWIw@Ea@MoAIw@Iu@Ky@Ku@Kw@Ku@QsAKu@Mu@Kw@Mu@Ic@CQMu@Mw@Mu@Mu@Km@?EUqAMu@Ga@ESMw@Mu@Mu@Ie@COMu@Mu@Mw@UuA]sBm@qDm@oDSoAQgA]qBGYKq@Mu@COCMMs@EYKk@]uBMs@Mu@Ku@GYMw@EYGYE[AGCSEYE[C[E[C[C[C]Eu@A[A[AYA]?[?[A]?[@[?[@]@[@[@[B[@[B[B[BYFg@BQBYDYF_@DWDYDS?CF[Pu@FWHWFWH[HYJYHWJYPe@JSBGL[Zm@JULU@CJOLULULQ?ANSNUNQNSJOBANSPQNQPQNOPOPQROPOJKBCRONOPOPQPMRQNMPOb@a@b@_@NM@AfA_Ab@a@b@_@@A^]d@_@b@_@`@_@b@_@\\[DEb@_@XUZ[b@]PORQNMPQn@k@DCLMVSp@m@^]f@c@POb@a@POtAkARQPQPMf@c@LKb@_@VSt@m@b@[TOh@_@\\URMd@YLILIJGPKPIf@YVOJEj@Y|@a@p@[^ODAp@Yn@SNGVI\\Mn@Qn@QRGTGRENEb@K`@INCPE\\GPEl@I@?HCd@I`@G`@Gb@Gd@I~@Oh@IXEl@KDAJAf@IXEPCRETC^Gd@G`@G@A@?rASLChASr@MJCB?r@KVEVEn@Kb@GTGVCPEZERCTE^GLANC^G`@GHC`@Ih@MRETGTIPGTIb@OXKFELEd@UhAk@d@YPKROVQh@a@\\YDEPOPQDEHI\\[VYZ]PSj@s@RWDGZa@|@kAZc@b@k@l@w@d@m@HILOFG@CVWFGFILMNOVURQZYh@e@d@]PMPM@?b@[BANIVQ\\SVMf@Uf@WRIRIZMLERIRGTGRGRGVGRGRETERETETEREVCRETCTCTCTCTAXAPAVAd@CV?T?V?T?T@X@P?T@V@R@P@V@TBh@FVBh@HTDTDRDVDPDTDTDRDTDd@JZFRD~@NLB\\FRDTDRDVFRDTDPDVDTDTBTDR@TBTBT@RBV@R@T@X@T?R@R?V?T?T?TAR?TATATATATATATATCTATAT?RCTAVA^EJATCRAVETCRGTETENEVGTIRGRGVKf@QRIRKx@e@PKTMPMROPMPOPOPOPOPQPONQPQPQp@s@b@c@`@a@NQPQ`@a@HIVYNOdAgA`@c@`@a@PQHIDEPSPOTWHIPQPQNSPONQPQBCLM`@a@TUJMb@c@`@c@`@c@POPQNO?APQ`@c@l@m@DEPQLO`@a@PSLMh@k@f@m@V[LQPS^g@NSLO@CLSNSNSNS@AJSNSLSNULULSNUZi@FMR]LWJSNYHSLWLYHSJYHUJYFQ@EJYHWFU@CHYFWFSHa@FYH[DWF[FWD[FYD[D[Jm@@GD[DYDYD[D[D_@DWDYB[DYD]Fg@Fi@D[D[Fu@Hu@Hw@Fq@H{@Fo@?GHw@Du@Hy@?GDm@B[@QBe@Fy@Bi@@MFsABi@@ODq@@_@Bq@D_ABgABcAB{@BiA@IBuA@y@?[FuB?W@u@?o@?iB?y@?o@AmA?I?i@?QAoAAy@Aw@A[CgAAaACeAEiB?OAg@Ay@AY?Y?o@?}@@aA@c@@e@?I@S@[@_@Bo@Be@Fw@Ds@HeAD[Dm@BWJiA`@mENyAFm@Di@Hq@TkCFi@FaAB_@H{@JgA@EFy@BW?CBYB]@U?E@[@[@[@[?]@[?[?[?]A[A[?[AYCa@A[C]C[C[C[E[C[EYE]EYEYG[EYEUI]GY?AWeAAIIYG[GWGYI[Oq@I[]}A[uAQw@GYGWQw@Os@YmACIg@yBAEIc@CGMi@?Ae@uBEMCKGYQs@I[GWI[GWSu@GWIYGYIYIWQs@I[IYGYSs@[kASs@]mAIYIWIYGYIWIYSs@Sq@Ss@Sq@I[GWIYIYIWI[GSMc@Qm@IYIWGYIYK[GUIYIYIYIYIWIYIYGYIWI[IWIWI[IYIYIWIYIWIYIYIYI[IUQs@IYIYIYIYGYIYGYGYG[GYG[?CEWGYE[E[EYE[Ku@Ku@OaAQqAGg@OeAEYE]EYE[Ge@CME]EYCSAGE[AGCQE[CQGc@E[E[C[EYEa@EWCUCYE]AWC]G}@C[A[C[C[C[A]CYC]C[A[CYC]A[C[C[A]C[C[Ew@A[C[A[C[A[A]AWACAYA]A[?]A[A[?[A[?]AY?]?]AY?[?[?]@[?[?[?[@y@@[@[?[@[@[@]@[@]@Y?]@[@[Bw@By@Bw@?[@[@[?]@[?[A]?[A[A[?CAWA[C[CYC]C[Gw@Gw@C[C[C[A[C[C[A[A]AYA]A[A[?[?]A[?[?[?[@]?]?W@_@@[@[@[B[@[@[B[BYB]B]B[D[BYB[D[DWD]D[D[FYDYF[F[DYNs@F[FYFYF[FYFYF[FWNu@F[Ns@Py@Lq@HYF[Ns@VoAVqANs@FYF[FYF[FYDYF[FYF[DUNy@D[F[Ju@FYD[Lw@DYD[Lu@BYF]D[@MHg@Jw@DYD[D[Jw@Fc@BQJw@Ju@Hw@Ju@@CHs@Ju@Fg@@OJw@Hw@Hw@NsABWNuAJu@B[Fi@BMD[D[Ju@Lu@Jw@Ju@D[DYD]DYD[D[BYJw@BYD_@Ju@Hu@D[B[D[D[B[Jw@B[Ju@Hw@D[D[DYD[FYBO@KD[FYDYF[FYD[Nu@H]DWLs@Nu@Nu@FYD[FYF[FYF[DYD[DYD[D[B[D[B[B[@[@]@[@[@]?[@[?[A[?_@A[A]A[C]CYEu@E[C[Iw@?CCWEYC]CYE[C[CY?AC[AYC]AU?CA]AYA[Ae@AS?YA]?Y?]?[@[?[@[?[@c@@S@[B[@[Dg@?OBY@[B[B[@[Dw@Bc@@SJgB?EB]@YDs@?C@[@[@K?Q@Y@]@[?[@[?[?[?[?]?[A[?[?[A]Ac@ASA[A[A[A]CWIqBEw@Ew@GuAA[A[Ca@Ci@Ck@Ew@c@oJMgCA[C[CYAKAOE[E[EYAOCKEYG[EYGYGYIYGWIYIYKWIYIWKWKWKWKUKUMWCEIQKUMUMWKUMUMWGKCI[m@KUMWKUMUMWKUMUEIGMMUKW[m@KUMUKUEKGKKUMUKWIOCEMUYm@MUKWMUKUMUMWMUMUCEIOMSMUMUOUMSMUOSMSOUMSKOCCMSOUMSOSOUMQOUMSMSOUMUKUIQAEKWKYIWG[GWCOAKEYE[C[A]A[A[?[?[@[B[B[D[D[D[DQ@GFYHYFYFYHYFYBIDOFYHYFYFYD[BKBODYJeAHgAFsA?K@O?[@]?[AO?K?IAQA[?AA[AUAEA[AGASCY?AC[AOEg@C[C[C[AYC]AO?KC]AYA[A]A[?_@AcA?K?Y?o@?Q?U@[?[@]@O?K@[@[@[B]@YBS?GB[B]BYB[D[B[DYD[D[DYD[DYD[DYJu@B[DYD[B[B[@YB]?[?[A[A]AYC[E[E[EYEYI[GWIWIWAAKUIWMWKUMUMUMUOUi@}@MUMSMWMSMUMUMUKUMUMUKWMUKUMWKUKUKWMWKWKWGQO[IWKWKWIWKYIWKWIWUs@]gA?AIWIYIYI[Qo@GWIYGYGU?CGYIYI]_@qBCMGYG[E[GYEYE[G]Ks@EYE[EYE[C[EYC[EYGi@Go@C[C[CYC]CYC[AYC]C[C[A[A[C[A[A[?EAUA[A[A[?[A[A[?[A]?[A[?[A[?[A[A[A[A[C[A[C[C[A[C[CYE[C[Iw@Is@E[GYE[EYE[GWG[E[GYEOAICICOGYAAGWGYGYG[GYOu@Os@Mk@WoAI_@EYGYE[EYE[EYEYC]CYC[C[C[A[C[A[A[?[AY?]A]C_H?o@?[A[?cBAcBA_AAqB?]AYA[C[C[E[EYG[EKCKIYIYKYKSKWIMEGMSOSOSOQW[g@o@QSo@w@OQOSOS?AMSKUMWKWIYIWGYG[EYE[AIAQC[AQ?IA[?]?Y?C@Y@O@KB[?EBSDY?CJw@BQ@QHm@@I@GP{ANqAJw@BYB[BYB]@[?A?e@?c@?GA}@CUC]CYACCWEW?CIg@GUAIIa@G[EYE[AGCQC[E[?ECUC[?KEk@A[?[A[?AAY?SAIAc@?QA]As@Cu@Aa@?[A]Cw@C]CYC]CYEYE[ESG[GYGWK_@GUIWKWIWKWMUMUKUOUOUMSOQOSIIEGQQQOOMAAOOSQQOu@o@OOgAaAQOc@_@QOYWIGOQe@_@s@o@QOu@q@QOQQQOGGGGOMKMGEOOA?OQa@a@QQKMCCQQQQOQOQa@e@OQQS_@c@OQOSA?OQOQOSa@c@KOCAQS_@c@?AOOOQQSGGGIQSQSOQY[YYOOQUQQQSQQOQq@s@c@c@GGGIQOOQOQQQUUm@q@_@a@OOAAc@e@e@i@IKa@c@QSY[CCk@o@y@}@QQa@a@OQQQQQOQOOQQAAMOQQ_@a@eAgAOQQQOQQOOQQQOQGGIIOQQQOOQQa@c@q@u@QOOQc@c@OQOQQQQSEGGGQSOQOS_@e@OUOSMSOSOSMSMUGIEIOU]m@KSMUKUMUMUGOCGKUMWg@cAKSMWMUMUMSUa@GIMUMSOS]g@OU]e@OSOSOQOQOSQQOQOQGGIIOQOOAAQOOQQOQOQQQMQOQQQMQMSOQMQMSMQMSMQMSOe@Ye@[QMy@g@QMSMQMSMQMSMSMe@YIIm@_@QMAAQMQOQOQQOOOQOSOSOUMSMUMUKWKWKWIWIYIWAAGWGYGYEYE[E]EYCYC]AYA[AG?SA[?]?[@]?cA?m@?e@@mB?M?E?g@@s@?K?M?Y?u@?[@Y?u@@cD@qC?kA?G@cA?I?]?[?]?]A]?[AK?QA[A[C]A_@CYEy@C[?AC[C[A]C[C]C[A]C[C]C[C]A[C[A]A[?CAYA]?]?[?]?[@O?M@]By@B[@U@GB[B[D]D[D[D[F]DWF[H[F[HYHYFYv@_CH[JWHY^kAJ[h@cBHYJYTs@HYTq@HYJYHYTs@Ng@Le@HYH[Pq@DQLg@F]F[H[F]F[F]F[F]F[X}A|@aFHe@ReALw@P{@DUD[ReAJe@Lw@Nw@D[F[D[D[D]B[Fw@Ba@@UB_@?[@]@]?W?q@?_@AI?]A[A]C]A[C[C]E[C[E]EYE[G[E[Qu@G]IWGYIYAEISK[IWKYKUKWMYKUMWOWMUEGGM{@uAOUOUMUOUMSOUGMU]OUMUMSOUMUMSQYOUMSKOCEMUOUMSm@aAMUOUMSOUMUQWMUOW]k@MSMWMUOUKSOYg@cAi@aAi@eAKUa@y@a@w@e@cAKWKWMUKUKY[o@KWKWKWMWIWA?EMGOGMEMGOq@eBOc@Qc@?AKYIWKWK[KUK[IWKYKYIYIWK[IWK[IWIYIW?AKYIYIYIYIYIYCGEQIYIYI[IYIYIYGYIYGU?CI[I[GYI[GWQu@?AI[GYG[GYGYQw@G[UeAIe@G[GYG]GYG]EYAAEWE[Ow@[qBI_@EWMu@[kBYgBSgAEWCMGYE[GWG]GYG[GYEYG[ACEUGYG[GWG[GYG[Kc@EQEUI]GYG[G[GWGYCMCMGYGYGYI[GYGYGYGYGYG[IYGYG]GWG[GYGWEUAEI[AIKg@Qu@GYG[IWGYG[IYGYIYAICIIYGWI[IWIYGYIY]iAEKEMGWKYIY_@iAIWKYIUKYKYIWKUKYIWKWKWKWKWKWKUAAIWMWKWKUKWKUMWKUISCEKUMUKUAAKUMUMUKUMWMUMUMUKUOUMUMUMSMWMSMUOSMSMUOUMSIMEEMUOSMUOSOSOSMSOSEIIK_@e@OSMQOSOS_@g@OQKMCEOSOSOSOQ_@g@MSOSMOCCMSOQoAcBMQ_@e@QUmA_B_@i@OSOSOQ?AOQGIW]GIe@m@OUGIQUqAeBa@i@oAcBOSSWYa@MQQYKOOYKSOYKSKQMYKUUk@MYQk@KYSq@Oi@I]I[GYI_@EUEYG]EYC[G[C[CWE_@CWC_@KsAEs@AYGw@Ck@C_@Ei@KeBGcAKaB?EEq@IcAC[A]C_@OuBCi@C[C[C[?CCWCYC[C[C]CWACCUC]E[E[E[EYCWKq@G_@GYE[Os@COCMGWG[GWOs@Qq@K]GYGUIYEKEQQi@K[KYIWGQCGIUEKGOWo@Uk@MY[q@IOMWKUMU[m@MS[i@[g@MUAAOUYe@OSa@k@]e@MSMOQUMOOQOSOQOSSSOQ]_@SSOQOOOQQQQQ_@a@OQQQMMIKGGQQq@s@KKW[MO_@c@SU_@c@a@e@MOOSMOCEU[_@e@W]?AKMQWYa@QYa@k@MQMSOWMQOUOSKQQWGKCC]i@MSOSGMSYMSMSMUIOKUCGQ]KWKWGQKYKYGWKY?AGUGSAEIYGWG]EWEWGa@G]CU?AEYCYEW?CKw@AIIs@MiAK{@Ge@AMGa@Ie@?EIe@GU?CI[EUEMAIIYEQAEIYIWKYKWKYKWIQg@eAMSKSEGEGGMKOACOSOSOSIMEEOQMMOQCCOQQOSQOMQOQMAAOMQMQMc@[w@m@UOc@]OM_@WKIQM_@Y]WuAcAQOSMQOOKUQQMQOQMSOQMMKWSKKWSQQKIUSQQMMSSMMOQQQSUMOSUIKSWAAUYY_@MS[c@OWU[IOKOCGOUMWMUKWIOISISQc@ISK[EOK[K[GYI[GWESI]G]?AGWEYCUEWE]Ea@C[CYC[AOAGC_@AYA_@A[AW?g@Ac@?S@_@@k@@Y@W?K@Y@UFw@B[D_@B[DWBYHi@DSDYH_@BSHYH[FY@EDQDMJ]BIL_@FQLYNa@FOJU@CN]Xi@JSNULSBELSLQBG\\e@PULQLOT[n@}@JMNST[Xa@@APWNQJODEHMDEZe@RYHK`@k@@?PUXc@^g@@ARYPUZc@NSP[^k@Zi@JSLSN[R_@Re@JWL[Vk@Nc@Ri@La@Ng@JYHWNi@Li@HYHYF]H]DOHa@F[DUN}@FYJo@D]Fa@D[DWHm@Fk@D[Da@@O@EB]D]BUBa@@MB[HiAB]@[BY@_@BY@g@Bq@@]@U@]?G@Y@]@u@By@?E@[?_@Bm@?c@@E?[@[@i@@o@@]?U@g@Bo@RmKFaDL}G@_@?_@@[@_@@{@@O@WDeC@]?e@@GDoCJwE@g@DaCDyBDaCFyC@e@@y@FqCLkG@]BeB@o@FcDBwABo@BmABuA@]?]DuA?_@@[@_@Be@Bm@@YDy@B]B]B[Fw@D]B[D]H{@Hu@D[Fa@BWF_@DUFa@D[Lo@Ha@Ls@Nu@R{@VcA@GHWPs@J]FUDOZ_AHUZaA@CBGHWL[FOJUBGFQJUXm@N_@HMBEJUDIDGNYFKDIJONWBEJONSNULSLOPWJMPQNSTSLOPORQFEDGLKXSROROPMdCeBt@i@h@_@DEHEPMNKTQRMNMPO@ANMNONORSPQ@ALM?APSNSNUJOHKFILUNUJSLSLYLUJWJUJYJUHWJ[JYFWHYH[DSH]FYLs@DYBUHg@LiADa@BYD]B[DYD_@BWD[Hw@B[D]BYD]Hw@DYHu@@S@IDWD_@BYD[B]Fi@BSBQHw@Dc@BSBYBUNqAD[Hw@B[BUFa@B[DYB[BUDa@DYB[DYBYD[@OBOBWD_@B[D[D[B_@DUB]BUJ{@B]D[Fc@VkCPwAJgAFk@NoAD_@D_@BW@GJiADa@D[PkBBWH}@BWHw@B[Fw@De@Do@B[Du@BYB_@@[BYD{@@U@OB]Bm@FcA?ABcADeA@WBm@Bo@DwA?OBeAByA?[@_@@o@?a@@u@?U?g@@]?U?a@?U?c@?q@?_@?yA?W?[A]AwAAu@Aw@CsA?g@Ck@A]?]Cs@CcAGgBCYA[Cu@C_@Ew@A_@C[Cc@AWCSEo@Em@Eo@Gq@I}@E[CYKcAAQIu@Ga@Gi@Gg@Ko@E_@QmAE]E]CQEWCQGc@OcAEU]eCG_@AMAGIk@EWOgAKq@E]Kw@Ks@EY?EE[EUAGGm@Ea@AQAMGi@?ICWC[ASAQAWAWC[A[AYAi@Ak@?_@?W?E?U?G?M?U?o@?a@@U@]?U?C@]@S@O@U@W@YF}@@S@GB[BYB[D[B[DYD]DWD_@DYF[DYFYDWF]FYFWH]DS@CFYH[HYHWHYHWHYHURq@Tq@J[HWHYHUH[JWH[^iAHYHWJY`@sANc@^kAH[HWJYHWHYTq@HWHYJYHWHWHYHWDODIHYHYHWJYHWHUHUJW@CJWHSLYLULUHSNYLULQLSNUNUNQNUFGFIHKFINOPSNOFGHIFGFGPOFEJKNMPOPOPORQFEJIPO@A^]RQNMPOPOTQLMJIHGPOPONONQPORSNQNMRSLORU^c@LMPSLOTYNQNSDEFGNSNQPU@ALQPSb@k@LONQPUNS`@g@NQ@CPSJOPSb@k@^e@NSPSNSNQb@i@LQV[JOHIf@o@PUFGFKNQPSbAqAPULQd@i@p@}@DEFK^c@BELQRUNSDEJMNS@ALQNSNWLSBEHMP[JQDKFKLYN[BGDKLYJYDMDMHUJYHYJ]H[No@Lk@BMF]F[D[DWFe@BSDYJ_AB]H_AFk@Bc@BYB]@]F}@@UBq@@i@@U@M?[@W@]@cA@sB?]@_@@sA@{A?[@]?y@@Y?E?[@[@}@?]?C?[@Q?M@U?K@O@_@B]@YD_@B]B]D]D]DWB[F]DYH]DYJc@DUH]HWHYFWJ_@BEFUFS@C\\mATu@J[HYJYHYHYRs@J]HWr@aCJ[^oAHYX_An@wBTs@Tu@Rq@BKPk@HYJ]Ts@Le@DMHYHW?ADMDOFYH[FYF[D[F[D]D[D[B[D]B[B]@_@B[@]?]@U?E?]@]A_@?[A]A]A[A]C]C]C]C[C]C[A[C]E]Ey@C]Ei@Ei@I{@A]C[C]C[C[C]C]Gw@Cc@AWA]?]A[?_@?[?]@U?_@Ba@?A@[@[@Q@IB]BU?ED]B[D[DYDO@MFY?EFUF[DU@CFWH_@F[HYF[FY@EXkADWJe@DQH[F[FYH[FYH[FYF[HYF[H[FYF[HYFW@EHWHYJYHWFS@AL[JYJUFOJS^u@P[LSBEJOJQNULORYTWv@{@\\]@A\\Yd@]NKROXQNKTKBCPIPIRKTKTKRIHEHERKVKPIBAPITKPKJEHERMRKFEHGTMRMRMPMRORO@APMPOLKDEPONM@Ab@c@vAcBX[Za@`@i@Zc@hA_BJSNYNWLULYLSJWN[DKDKJYJULYHWFON]BKFMFSL_@VaAXgANq@H_@F[HYDYF[F[DYF]BYD[Jy@D[D[B[B_@B[BUBc@B[@O@O@Y@_@@]@[@]@]?E@U?]?]?S?s@?O?[A_@?[A_@A[A]A[AU?GA[C[C_@A[?AC[C[C]A[G{@CYC]AYE_@A]C[C_@AUC_@C]AEAWCWCYEaAAMAOC]C[C]A[C[C]AUAGC[A[C]C[Ca@Gw@A[C]C[C]C]C]A]C[Eq@AICYA]C]C]C_@Gw@C[Ca@?ECa@CWAWAGAYC]AWCi@?YAW?W@[?Y@]?KBQ@[D[@I?KD]F[D[BOBKFYH[FWHWJYHUFOBGJWLWJSLYb@}@BCVk@JSLYLWLUJULUJULYJQN[JUJSLYJSLUJULWLWLUJWLUJULULWJULWJSLWJWJSLWLWJSJULULWLWHULYHSLYFU@?J[FUJ[FWH[@IBKFWF]F[D[BWF_@@K@OBY?CBW@U?E@I@Q@S@e@@c@?M?Y?a@?CAY?YA]C[Eq@Ca@CYE[CQE_@CKCSEWEOIe@Ka@EQI[IWGSM]IWKWIQMYKSOYMUKQOWOUOQMUOSOQMSQSOSOOCEKKOSQQOQQQOQQOQQOOQQQOQMQOCCMKQMe@_@UQOKOKUOQMQKUOQKYQMIOIUQSMOKSMSKSOQKe@YSOSKSMSMOKUOQKSMe@YUOOKc@YUMSMe@[e@YQKWQa@Wc@Ye@YSMUOUMa@YSKSMSMQMQKSMSMQMSMe@YSMOIWOQMQMSMSKQMQKc@YWOe@[SKQMg@[e@[QKQKSOSKQMSMSMe@Ye@YSMe@[SMQKg@[SMQKe@[SMSMu@g@mAs@UOQKSMQMkAs@g@]SMUMSMUOu@e@UMe@[KIyBuAoAw@u\\{SMGWQc@Ye@YMISMUOECMIQMMIQKCCWQSOKIUMQOSOQMSOUQOMQMOMQOUQCCMIMMUQOMWUKIOOSQMKYWEE_@]MMOMOQQOOOWWAAIIWU_@a@MMOQQQOQOOUWOQKMOQKKEGa@c@SWKMOQQSMQQSMQOQQUOSOQk@w@U[MQKOOSOUMQa@k@MQMSMQm@aA]i@]i@ACIOU_@{AgCYk@i@_Aw@{A[o@Yi@O]Ue@Wk@MWWm@OYISMWc@cA{@wBWq@MYIWKUKWKYKWIWKWIWKYKYIUIWIYIUKYIYISI[KYGUK]IUGSUw@IYMe@EMCOACSu@I[GYEQI]GWQw@Ke@Kg@Mo@CEIe@?AIc@I_@GYEYG[EYCKCOEYE[GYEYKq@E[CYE[E[E[EYE_@CUE[Iu@Ea@KiAEc@?ECOEm@IaAGw@A[C[E_@A]CYC]?CCWCYC]Cc@AUCWC]CYEm@Em@AS?ECUC[AO?EC]Gy@C[?ACYAS?CEi@AMAK?OC]C_@CM?IEc@?IC[AGASCY?AC[AOAKCWC_@CW?ECYC[CY?ECWCYC]AKAMC[C[AOCKC[C[?CCUC]CYCMAMC[Ea@CUCYC[C]CYCS?GEa@E[?CEk@E_@Ea@Ei@E_@Ec@Eg@Gu@C]EYC[C]C[EYC[C[C[C[C[C[C[C[A[Eu@C]A[C[A[A[A[A]A[AY?]AYA]?[A[?]?[A[?[?[?[?[?]@_@?s@@[?U@i@@o@@Y@]@]@Y@]@[BY@_@@[B[@Y@]B[@YBa@@[@W@[B[@]@[B[@Y@]B[@[@Y@[B]@YB_@@[@W@]BY@_@@[BY@]@YB]@[@[B]Bu@@[B[@]@YB]@[@[?sA?[?[?_@AYA[A_@CWA[Ec@Go@C[E[Ga@CSGYE[G[GYIYGYIYIWGUIWKWM]KWKWMWIOYm@QYMUMSOSMQEGKOQQMQSUKKQSOSQSQQOQQSOOOSOOSUOQOQAAOQMQAEOSKOMSMUOYKSOWIQKWO]K[GOK]IUIYIYI[GYIYEYEQGa@GYCSGe@E[C]AEAUCYC[A]A[AMAKA_@C[A]AYC]A[A[AWAYCa@A]C[A[A[C[AYA]C]AYA]AYA_@A[AQAe@A[A]A[A[?MAMAw@AWAa@?[A[?[A[?WAa@?Y?]Ao@?I?[?[A]?W?_@?]?[?[?]@[?Y?[?_@?Y@]?W?_@@_@@w@?E?U?Y@[?]@]@W@a@@_@@W@U@a@B]@YB]BYB]Ba@Di@Da@Fi@Fi@Fi@Hi@Js@F[D[F[FYDUHa@BQJ_@XoADO@IHYHWHYHYHWHYJYHYHUHWJYHYHUJ]JYJWHYHWHWHUL_@HWHWHSHYL]HWJYFWHWFOLe@?AHMb@kBDWH_@DQBMDYJk@@EJk@Hs@Hi@@KBUFo@BQHaAFw@Du@Bq@?EDaA?WBo@@q@@}@@e@@sA@k@?A@m@@kA@{@@i@?G?a@?[?_@AQ?A?]Ce@A]Cc@Ce@E[C]C[ACCUE[E[GYEYGYG]GUGYCICKK_@IYGSK[KYMYIUKWMWKSMWMUMUMSOUQWKOQUMQOSKKCE[_@SWOSQSOSKMSUCCKMOSUYIKOSOSOQOQOSQQOSOQOUQSMOOSOQOSOQQSOSOSOSOQOSOQMMOUIIY]MQQSOSOQQSMQOSQSOSOO?AOQOSOQOSKMSUIMUY]a@a@g@AA_@g@[a@GIu@}@U[QUMOOQOSGEIKc@k@[a@[c@SYQ[S[We@GKCIKUO_@M]Mc@GQCKQs@a@kBSgAIa@Ou@Ie@Ms@Ms@G[Ms@Ia@Mm@Mu@Ou@EUGYG_@Ig@Ou@Ic@COKk@CMUiAKm@Mm@Q}@EUI]GWGWGSCOOk@IYACEOIWMe@ISMc@K[KWOa@KWQc@O_@Se@]u@U]MWKUMUIOEGYi@MQEIIMKQMSOUOUMOMSQWMOAAMQOQMQA?OSOQOQCEKMOQOSOQMMACa@g@MM]c@QSGIAAEEMQCCMQOQOQOSOSMSMUKSMUMUISACKUKWIWKWIYGWIYGYGYEUACEYG[EYC[E[C[CY?OAKA[A[A[?[A[@[?[?G@S@[@[B[?C?I@I?C@AFs@DYBS?EJm@Lq@BKFW@EFQ@IFOHWHWJYHUJU?AJULWLSFMBGNUXe@PSPULONQPQPOHIHILKRMPMDEJGRMPKRIRKRIPG@ARGTIRERGTERETELEZEh@MRETETEPETETERETGDAb@IREREREVEREHCJARERE@ARETEHCHATGRGJEFCTGRIRIHEHEPIRKRKPKRMDCJIRMPMPOHGFGNOPONOPQNQNQNSLO@ARYJMJQ@CLSLSLUDGDMLUJULWHUJUJYHWHSBKFUHSBKBOHWF[J_@F[@GBQF[Fa@DYB[D[B]BYB[B[B[B[B[B[@YB]B[BYB]BYB[B[B]@YB[B]BYB[B[B[B]B[@[BYB[B[B[B[B]Ba@@UBYB[@K@OB]Dm@PyB@[B[H_ABa@Bg@B[Fy@B[BWFw@B]D]D[D[@IHi@DYDY?ALs@F[F[Nq@DMBKH[FWHWDMBKHYHWHWJYJW?CHSLYHSJYLULYJULUJSLWLULUNULSNSLU^g@LQNUNQNUNSLO@ANULSNSBCJM^i@NQ\\g@NSLSNSPULQNQFKFGBGJMNSLSNSNQLSPUNSLQT[HKNUNSLQ^g@NSNULOPULQNWPSJONSNUNSNSLQBCJONSJO@CPUNSTYFKNULOPUNULOLSNSNSNSNUNQ\\g@PWNQPUJOPWJOBEX_@PULQPUNULQNSPWHONUJQDGHQLULU@CJSLW?AJU^}@BGHWTs@HUHYH[HWFWH]DUF]FWF_@DWBO@G?CF[BWDYD]@WDa@BY@[BY?A@YB]@[?[@Y?Y@A?_@?[?W?_@Cy@AY?]Ew@C]CWC]C[CYE]E[EYE[EWG[E[GYGYGYI[GYIYIWGWK[IWKYIUKUK[CCISKUKUMWGMEGMUMU[i@OSOUMSOQIKEIOQQSCCKMOQMOCCOOOMSSQOGGGGSOSOOMUOQMSOQMQMQMA?QOSMAAOKQMSOQMAAOKSOQMQMSMEEKIQMSM]WGEc@]QKe@_@GCIIg@]e@]QKQMSOQMSMSMc@YSMIGGEg@[QKSMSMSKSMKGECSKe@YSKSMSKSKQKUKQKSKSKg@WSKSISKSKSKSISKSKSISKSISKSKUKQISKSKSKSISKSISKUKQIUMAASISKGCKG[MMGQISKSKSKSKSKSMOMSOQMIIGESSOOKMCCOQMQMOCEKQQWKSMUMUMWIUKYKWIWIWIWGYI[GWE[GYAKCOCWE]E[C[AY?CAGAOA]?[AY?Y?C?[?[@]@Y@[B]?AB[BYD[DY?AD[DWF]DYDYDY@AD[BM@KBQHc@?ADWF[BS@GBQ@GFYBO@KF[DYD[FYD[F[DWD[@EBSF[D[FYD[F[DY@KBOFYDYDY@IDSDYF[BM@KD[Ls@F[D[DYF[DW@IHe@Hc@BU@EF[D[DWDYF[D[FYD[F[DW?AFYD[F]DWBM@KF[D[FWD[BM@KF]DYDS?GF[BYDYD[B[B[DYB_@BY@]B[@Y@Q@K@[@]?[@[@[?]?Y?]?]?YA[?]AM?MAYA]A]?CCWA]C[C[CYCYC[C]E[Gw@Iu@C]C[EYC[CW?CC[E[CYC[?AC[EYCYC]E[CYC[EYC[C]EYC]C[AECUCYC[E]C[CYC[EYC]C[AGAQE[C[CQAKAOAGC]CYCQAKCYC[CYE]C[CYE[AOAKC[E[CYC]CYAICQC]CYCYE]CYC[Ec@E[Ei@AMCW?CC]CUE]Gw@Iw@CSEc@Gw@Iu@C[Iw@Gw@Iu@C[C[MsAKsAGw@Eu@Gw@AUEc@?IEm@Eu@Ew@Ew@ASCe@AYA]C[?OAIA]Eu@A_@?ACk@Ce@A_@AK?KA]C[Aa@I_BEm@Es@"
                     },
                     "start_location" : {
                        "lat" : 39.6775057,
                        "lng" : -79.37870269999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "187 ft",
                        "value" : 57
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 4
                     },
                     "end_location" : {
                        "lat" : 39.7131416,
                        "lng" : -78.1916373
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eExit 82C\u003c/b\u003e (signs for \u003cb\u003eI-70 W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eUS-522 N\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eBreezewood\u003c/b\u003e)",
                     "polyline" : {
                        "points" : "smkqFx|f|MESA_@AK?ECa@AM?K"
                     },
                     "start_location" : {
                        "lat" : 39.7130552,
                        "lng" : -78.1922857
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 206
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 9
                     },
                     "end_location" : {
                        "lat" : 39.7127354,
                        "lng" : -78.18933729999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eright\u003c/b\u003e at the fork to continue on \u003cb\u003eExit 82B\u003c/b\u003e",
                     "maneuver" : "fork-right",
                     "polyline" : {
                        "points" : "cnkqFvxf|MDQ@A?AAI?IA]?C?O?E?Q?S?U@]B]B[D[D[DYDU@EH[HYHYHW"
                     },
                     "start_location" : {
                        "lat" : 39.7131416,
                        "lng" : -78.1916373
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "52.0 mi",
                        "value" : 83617
                     },
                     "duration" : {
                        "text" : "46 mins",
                        "value" : 2732
                     },
                     "end_location" : {
                        "lat" : 39.3979345,
                        "lng" : -77.42797759999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eExit 82B\u003c/b\u003e, follow signs for \u003cb\u003eI-70 E\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eUS-40 E\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eHagerstown\u003c/b\u003e and merge onto \u003cb\u003eI-70 E\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eUS-40 E\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow I-70 E\u003c/div\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "skkqFjjf|MLYJULWNULSLSJMHMNMLM@ANMPKLKz@m@r@c@VQj@a@@?\\U^WPKLQ~BaBdBgB|@}@j@_Ax@eAV_@Zc@Xe@Zk@R[FKTe@HQ@AHORc@d@gA^}@Rm@DODKXgALi@DOT_ARcANy@h@wCRgA?AReALo@DWHe@@EBOLk@He@FYFe@H_@Jk@Jk@Ji@Ny@Jk@DYHa@Lm@F_@F[Lu@P_AF]Jk@Ha@Ls@DSN{@Ls@Jm@@IXwADYFYDWFYPeAF[FWTqAHm@Hg@ReAFc@Ju@NeAHu@Ho@BOBSLiAFi@BWFm@De@D[Dk@JmADa@Dm@@QJiAF{@@UDy@?IB[B[D]B]B[B_@BYBYB]@Q@IB[B[?AB[B[B]B[B[B]BYB]@Q@KB[B[B[B]BYB]B]B[D[@[D]JsAB[B]Fy@B[B]B_@Fq@D[D]D]DYD]DYF[F[F[HYF[FYHYHYHWJYHYJWHUJUJWJWLSLWLU@AJSLSNSLQNSLQPSNQPQPO^]f@c@PMPOPMRMFG\\UHGHGDE\\Ub@]f@]HGHGh@a@HGPKRQROPMPOPOPOTSPQPS^c@PSPULSNSNULULS`@w@Te@JWJWJWJWJYHYRu@DMJc@H[F[FYFYH]FYNs@F[VqAFYF[XqADY@A^kBNs@F[F]Ns@Pu@F[Nu@F[BMBKF[Nu@Pu@?ANs@F[^kBPw@Nu@FYVwALo@Fa@DUBIBQHg@@IF]Jo@Ly@D[Jw@Hq@PwALqAJs@NuAXiCHw@B[DYNuAHu@v@iHTuBv@aH@KLoAFa@D[DYF[BWBMBMLw@FYF[FWF[BKJe@Jc@DOH[FWPs@DKBMPq@Ps@?AZmARs@Ps@FWHYHYFYH[Pq@HYFYHYHYFYFWFYFS@KFWF[FYDYF[DYF[DYDYD[D[D[DYB[D[B[BQ@IBYB]DWB[@Q@ID_@BWB[B[BO@KFu@D]BYB]B[@ABWB[B]DYB[B[D[B[B[B[DYB]Hu@B]Fu@D[BYB]D[B[B[D[BYBWH_ABYBYD]B[BYD[?ABYX{CDg@Hw@De@Fm@?AFs@D]B[B[Hu@B[B[DY?AB[B[D[B[B[D[B[BYD[B[B[BYD[B[D_@BWB[B]j@gFBWB[B[DYB]BQ?GBYD]B[B[BYD]BWB[D]BY?EBSB[D[B[B[BYBYD_@BWB]BYD]?CBSB_@BWB[BYD]B[B[D[B[BUD[D]B[DYD]BYDW@EBWF[DWD[?CDWF[DW@CDWFYFYDWF[H[Lq@H[FWH[FWH[HWFYHYHUH[HUJ[FUL]HUHYHUJWJYHS@EHSJWJWJWHSDIHQHSLYJUJSLU@CJUJSLWLULULULSLSLWLSLUNWLSLSJSNULSLULUNULULSDId@w@JSLSNULULULULSLSLULULSLUZi@NULSLULULS@CLSLSJSNULULULULSLUNULULUJSNWJSJSNWLSLWJQ@CLUJULSLWNYHQLULWDIFIJULUJW@AJUJSNYHSLUJS@CJULUJWLUJULWLWJUJWLUJUJULWJUNYFOP]JSLWBEFOJWLUJUJUBEVg@JUJULWJSJWLUJWLUJULUJUJWLUBG@CDIDIFMHSNW?AJSJUJULWJUJWFMBGJULWHULWJYFQ@AJYHUJYJWHWJWBIBK@AHWHYHUJYHWHYHYFWHWHYBIBOHWFYHYFWF[HWDWH[FW?CFUF[FYDWFYF[FYFYDYFYF[FYDWF[FWDYBKDQDWFYFYF[DYFW@IDOF[FY?CFUFYFYFYFWHWFW?CHWFWHWH[DKBIHYJ[HSJYFULY@EFQJUJWHUJWLWBGFOLWHUJUHSBCHULWJWJUJWJU@CHSLUJUJYJUJWHM@GJULW?AJSLWJWXk@Vm@LWJSLWLULUJSLULULUHMR[Zi@\\g@LU\\g@\\g@\\g@\\e@^i@PUJO^g@JOPWNSNST[FI\\g@NSJORW\\e@\\g@\\e@^i@FIFGLS\\g@PSHMBELONULQ^i@DE`@k@T[LSLQ^i@LQPU\\e@NSDIFI\\g@NSLQPUJOBE\\g@\\e@NSNSJQNSNSHMBENSRWJQJOl@y@|@oANSLQz@mAl@{@NQNUNSNSLSBCFK\\g@DEVa@^k@JOPWNWXe@b@s@T_@LUXe@DKHMDIFKXk@JSHOBGXk@@?Vk@@C^s@FMNYJSJSXm@d@aANYLY`@y@@CVg@Zq@Xi@Pa@DIZm@xA{CJSP_@HOJUFIP_@LWLYHQXk@FMDGVk@Zm@JUFKDKLUP_@Xk@Xg@NY@ABGNUJSLUNWFGDINSLS\\g@LO@CNSLORWJMX]JMHKX[\\c@FITWJMNQRUNSPQLO^c@NQNS@AZ_@@ARUPUr@y@NQZ_@d@k@`@e@^e@VYX[FK\\a@RSh@o@BCbCyChD_EFINQNSNQPSHKDENQNQNQNSNQNQNSNQNQPSLQPSLQBCJONSFIFGNU@CJMLQ@ALSNSLSNSLULSLUNSLULSLULSLUJULUNWJSJULUJULULU?AJSLWJULUJULUJWLUJUDIFKJWLUFMBGLUJULUJU@AJSLWJULUJULULWJULUJUJULWLUJULUJULWJU@AHQLWLUJULWJULULUJULUJWLUJUBEHOLWJUJULULUJULUJWLU@AHSLULWJSLULUJULULULS?ALSLULULSNUJSNSLSNSNULSNSLSNSLQNSNSNQBEJMNSNQNQNQNQPQNQNQPQNQNQPOPQNQ@?NOPONONM@CPONOPOPOPOPONOPOPOPOPQPOPONOPOBALMPOPOPONORONOPOPOPOPQNOPMb@a@POBCLKNM@ANOPOPOBCLKPOPOBCJKPONO@APOPONOPONOBCFGDC@ANOPQNQNOBCLOPOLO@A@ALOPQ?ALOPQLQPS@ALONSLQNSNSNSNSFIDGNULQNSLSNSNUDG@CDENULSNSLSLSNS@CZe@PYJMHKBGDGHMFKHKJOJOHMDGFIp@cA|@uALSNSLSNUFKDET]FINUFKDILQ^i@LSLQ?ANSNUNSLSLSNSBEHMl@}@LQLST]HKLQNULSBCJONULQBEXc@LSJQBER_@R_@LSLWLULWDKDIJUHOBEJWHQ@EFOBEFOBGFQBEFQ@CDK@EBEFS@CHUHWJYFQ@E@AFWHWHWHYDQBGFUH[FWFYHYDW@CFWDWF[FYD[@IBKDYFYDYD[@MBMBWD[D[BYB[BU@E@U@GBWBYB_@@Y?ABY@]BU@]@Y@]@Y@[@k@BaB?[?[?Y?[A[?[A[?[A[A[A[?[AWACA[A[CYA[ASAC?AAUAGCYAUAEASAGCU?ECYEYCYE]CMEc@E]EY?ACUE[E]C[EYCS?EE[EYC[EYIw@E[CYEYIs@CQAIC[YcCGe@Ea@?ES}AAOAACQIs@?GKy@AEGo@Iu@Iu@E[Im@?EIw@EYCYAA?ACWE[CWE[CYE[Iu@E[Iu@OoAEW?ACYE[E[CYE[CYEYC[Ku@MoAEY?CE]MiAC[E[CYE[AIAOE[EYC[EYC[Is@E]CYEWC]E[CYEYE[C[EY?ACWE]EYCYEY?ACYACAKAKAECSC]EYC[ACCSC]EYAOAKCYCYC[CYAECWAYC[CU?GCYAYC[C[A[AYA[C[A[AYA]?YAA?AAs@A]?Q?GAY?]?YA]?Y?[?[?]?[?Y?q@?G?Y?C?s@?[?[?C?q@?_@?[?Y?[?Y?G?C?O?]?Y?S?G?[?[?[?w@?[?Q?G?]?[?[?K?M?]?Y?]?[?[?Y?[?[?[?[?Y?[?[A[?[?[A]?WA]AYA]A[AYA]CYA[AW?AACAWC[CYC]CYC[C[EYC[EYE[CYAIEQCYEYGYE[EYGYEYG[AAEUG[GWEQAEG[IYGU?AIYIWIYGWIWKYIWIWIWIWGMCIKWIUKWKWKUKWYm@KUKUA?KUMUMUKUMSMUMUMUKSMUMSMUMUMSMUMUCEIMMUMSMUMUKSMUOWKO?AMUMSMUMSMUMUKSAAKSOUKQ?AMUMSMUMUMSKUOUMUMSIQCAMUMUMUMSKUMSMUOUMSMUKSMUOUMUMSMUMSMUMSMUMSKUMSMUOUMSMUMUMSMUMUMSMSACKQMUMUMUKSOUKS[i@MSMSMUKSMSMUMUMSKSGIEKMSMSMUKSMSMUMSMUKSMUMSKSOUKSMUKSMUMSKSMUMUKSMSMUKUMSYi@MUKUMSKSMWKSGKEIKSMUKSMUKUMSMUKSKUOWKQCEcBeDMSKUMSMUKUMUIQMUKQAEKQMUMUKSKUOWKSIOMWMUKUMSKUEGGMMUKSMUIQCCo@oACEKSKSMUKSKUMUMSGMQ]KSKSOWKSGMQ][i@Yi@Wk@KQOYKSYi@MUMWMSKSGOCEKSMUMUIQMYKSYk@KUKQKYKUMUKUISKWKWKUKWKUISKYKUIWIUISM[IUIWKWIWGSCEIUIUGWIWKWGSIYIYIWIWGWIYIWGWGUIYIWOo@IYQo@GU?CIWGUQq@Om@I[Qq@GUQq@Qs@GWGUIYIYOm@I]GUGUIWACGWIYGWIYOm@GUAEQm@GWGWIWI[GUI[Oo@Qo@Qs@IYGUQs@GUGSI_@Om@Me@Kc@IYOq@ESSy@Oo@Ke@CMOo@]{AIa@UeAGYGWGYGWI_@GWGYGYGWGSG]GUGYGWI[GYGWGYGYGWGWGYGWIYOq@GUG[GW?COo@GUGYCQCGGYEWGWEYGYEWGYEYEYGYEYEYEYEYEYCYEYEWC[EYCU?EEYCYCYCYE[CWC]AYCYCYC[AYCYAYCW?OAMAYA]AUC]AW?YAE?WA[A]AY?YA[?YA[?[?U?[?]?Y?[?M?K?Y?W?[?A@]?Y@Y?W?C@Y@Y?M@O?Y@Y@Y@K?Q@U@[B]@[@Y@[@Y@Y?ABY@Y@[@Y@[@[@Y@Y@I@Q@[@Y@[@Y@[@Y@YB[@[@W?I@Q@[@Y?K@O@YBq@@C@[?M@Q@[@[@S?KB]@Y@_@Bg@DgAB{@D{@By@D}@Bw@Dy@@_@Bo@@M@]@_@B[@_@@]@[B]@[?C@W@]B]@_@@[?C@YB_@@[@[?I@U@[@]@_@@[By@@_@By@@e@?S@Y@c@@K@m@@[?G?WBuAB_A@y@?A@y@@W?c@@w@@_@?_@?Y@O?M?]?]@]?]?[@_@?w@?{@@w@?}@?{@?_@?Y@_@?[?yA?[@}@?[?]?w@?a@@Y?a@?]?u@?E?y@@]?{@?]?o@?K?W?Y?I?W?}@@[?S?k@?[?Y?_@?]?[?]?Y?E@[?q@?_@?Y?[@_@?]?_@?y@?{@?{@@w@?w@?}@@{@?[?_A?y@@y@?_@?]?]?]?[?]?]@[?_@?y@?[?Q?I@Y?I?Y?_@?]?_@?Y?_@?[?[?S?K@[?]?mA?g@@[?a@?[?U@c@?[?a@@]?]?Y?M?S@[?]?[@_@?]@u@@a@?]@[?]@_@@[?S?K@]?[@]@]?[@]?G?U@]@w@B}@@{@@]?_@@[?]@]@_@?O?K@c@?SB_A?[@[@_@?]@]@]?Y@K?Q@}@@]?[Bu@?_@@[?]@[@{@?K@Q?[@_@@]?[@]?]@[@{@@a@@]@w@?[@]@_@?[@[?]@a@@[?c@@Y?]@[?Y@_@?]@]?[?]@c@?W@y@?_@?]?[@_@?[?]?]?]@y@?[?a@?w@?i@@W?w@?y@@y@?{@?]?]?y@@]?]?m@?W?Y?]@]?Y?_@?Q?M?]?Y?_@?C@W?]?]?]?]?]?[@]?]?[?c@@u@?]?W?a@?}@?O?I?[@y@?W?K?[@]?C?Y?_@?A@Y?]@_@@[?G@U?[@[@]B_@@Y@[B_@@O@e@F{@@Y@C@[B[LyAB[H{@B[D[D]B[D]DY?AD]FYD[D[D]F[D[DU@GF[D[FYF]FYF[FYH]F[FW@E?CHYFYH[HYF[HWH]HYHYH[?ATq@Ru@HWJ[JYFS@EHYJYHYJYHYDKDOHWHYJ[HYTs@@EFSJ[DMBKHYHU@EHYHWDMBMJ[HYFWBGFSFWH]HYHYH[HY?AHYF[HYHYH]FWF[H[F[H[FYF[F[H[?AFYDQBIDYH[FYF[F]FYH]FYF[DO@KH]?ADUH[DSDUHYF[HYBMBKHYFYHYBGDOHYHWDSBEHYHYHYJYHUHYHWHS@EJWHYJUJWFS@E@AHSJYJWJUJWJW@AJUJWHSNYHQLYLUHSLUJUBGHMLWDIFKLUHOBELULULQ?ANULULSNSLUNULSNULSLQLSJQLSLQJQLSLQLUFIHMJQPWLULS@?LSNULSLSNSNULSHMDELUNSNULSJQ@CLSHMBGLSBEHONULWLULUJSJU@CLSLWJU?AJULWDIFMJU@CJYNY@EHSL[JU@EFMBIJWL]JYJ[@CHSJ[HUJ_@Nc@FSJ[HYDMDMH[Rq@FUNg@HYJ[H[J[HYH[HY@AFUJ[H[HYJ[J[HYJ[JYJ[HYLYJYJYJWJYLYJYJWLYLYJULYJUBEN[LWLWNYLULYPYLW@ALUNWPYFMFINWNUNW@?NWNULSPWPWLQRW@CLQPU^g@RULSb@k@V_@X]RYFIT]PUJOBER[LS\\i@NWj@_AXg@P[PYLULWLUNWLYJSLUNYLYLWLWJWLUJWXq@JWLYDKDIj@wAHSJYJY@AJYJYJ[JYHYJWJ_@JYJ]DOBIHUJ_@JWHYJ]HYJ[J[FWJ[BKDMJ]J[H[JYNi@Ne@DODKJ[H[J]HW@CH[L]HYHYH[L]FS@GHYJYDMDOHYJY?EHUJ]J[@CFWJYH[La@J[H[BIFOJ]@EFSBIDMV{@BGPo@HWL_@J]H[J[HWJ]J[BMDMFURq@J_@BIFOH[J]JYHY?AJ[H[J[J[BMDMJYHYFS@EHYHYHUHYFUHYFO@GHYL]FUHYFS@CH[JYFUJYFUJ]HW?AHWHWHUHYHYBIDMJ[DQBEHWFWJYHYFWJ[HWHUDML_@JYJ[HWFOHUFQN]FSDKFOJWFKPc@HOLWLYLSJULUVe@@?JQP[HMBGJONUBGHKPWJONSHMFGJONSNQLQTUJMBENQNOPQLMNQPOPQNOROPQ@?NMPOPORMPOPMPMRMFEHGRMRMd@YRMPMPK@APKRMRMPKRMLIDCRONI@ATOPKRMRMRMRO@?PKVQ\\SDCJIPKFEJGRMPMRMRMVONKRMPKPMXQ^URMPMPKTOPKRMRMPMRKROPKRMTONKRKRMPMRMHELIRMPMJGJGPK@APKPMRMNIJIBAVQh@]BANKPMTMNKTORONKNKBCPMRONONK@APORQPOPONQDCJKPQFIFGPQ@AHIBENOPS@?LQLO@CPQLSPSLSBCJONSLSNQ?ALSPYNWLSLSP[LUJULULWBGFMLWJUJWDIDIL[HULYDODGHWJYHWJYHWHYHWHSH]BKDOHYHYFWH[FYFYFYFYF[FYDYBMBIF_@DYDU?EDYD[DYD]BYDWD_@BYB]B[B[BYB[B_@@[@YB[@Y@_@@[@[@]@[?Y?K?Q@W?_@?]?[?W?O?Q?[AuAA[?Y?]?YAg@?S?[A[?Y?_@?[A]?[?[A]?[Aw@?]?g@?QA[?[?[A]?[?[?]AU?_@?[A_@?W?U?EA]?]?[?UAa@?]?]A[?[?[A]?[?E?SA[?_@?M?M?[AY?Y?_@A]?[?Y?WAc@?UAc@?Y?]Ay@?Y?WA_@?K?i@A_@?[?_@AY?Y?_@A[?u@A_@?y@A[?[?[A]?_@?WA]?Y?[?OAi@?M?OAY?S?G?]?M?OAY?q@AW?]?W?[A]?]?M?M?]?[?[?]?W?_@?[?O?M@U?]@a@?Y@]@Y@[@W?E@[@]@Y@]@SB[@UBe@@O?MBYB_@?E@UB[B[@[B[B]B[@YB[@YB_@Do@@G@]BU@O@Q@YB[FmAB[?EB]BY@]BYB[@]Du@BYBe@Be@@QDe@Dy@@K@ODq@HwAJiBBg@JiBFuA@[B[Bw@Dy@Bw@B{@FkB?]Bq@@w@@{@BaB@eA@yB@kA?{A?A?o@A}AAqBA_AGmFAu@A_@A_BE{CI}HCmB?SA_@Aw@?A?EAu@?g@Ao@Aa@AWCqC?]Ac@A[?[?W?E?YAw@?]?k@?g@?wA@[?c@?UBuA@w@BqADmA@m@Bo@B]Bw@Du@?E@ODq@FmAFmA@M@KDk@@C@KDk@BS@KLsABc@D]?EBOFq@?AFk@D_@D[DWDY@KNcAD_@He@F[@MBMTuADWJq@BKFc@P}@BQJg@FWHa@Nq@F[BKBEVmADMZwA@GHWt@yCPq@Ja@J_@FUT}@`@aBHYFWPq@BO\\qAb@iBNi@Ry@f@oB`A{DJc@FWTy@ZqAT}@Nm@p@qCRw@Le@Lk@BMDULi@BQDMJi@Lu@Jk@Jo@DSD[Fc@VcBBS?APwA?A@GFk@D_@BUL}A@OBUBc@FaA@CHyABc@@c@Dy@?S@I?MBm@@}@BuA@w@?[?_@?[?u@?[?]?[A[AuAGmCCsACcAM{EAe@As@Cm@G_CI}DCw@A]Aw@Cw@Ay@EsAA[A[Ai@Ac@MgF?AEoBCqAAa@EaA?QK{EAa@MaFCw@EyBGeCCw@?YA_@GoBGeCKcFAc@IkDKaEA[A[A[?WEwA?IAm@Ci@Am@Cs@?]A_@EaBCe@?[Cm@?IA]A[A[Ae@?OAS?GA[?[A]A]?[A_@?Y?]?S?]AQ?K?W?[@]?I?O?]@Y?[@_@?[@K?M@YBy@@]?QBe@@WB]@Y?AB[@[B[@UB]B_@B[BWB]B[D[BWB[DYB]Jw@D]BUJu@DYD[DYF_@@IDUBOFYD[FY@IDQDYFYDQ@IH]?CFSFWF]FWHYDUHYHWFYHYHWBIBOBGDQHWHYJWHYHYHUHYJWJWHWHWL[BIFKHUJWJWJWJUJWJUJWJWLU@EJQJULWHQ@ALWJULULULULULUJSDIFMLULSDKFKLUJULULUFMDGLUFMDEN[@AP[BGJSj@eALSLUDKR_@LUBGd@{@JQPYXm@Zi@BEHQLSLWLUJS@?LWLWLULU@?JUHMBEJUPY~@gBR]DMZi@Zk@d@}@LUt@yALQJU?AZk@b@w@R_@^q@HOXk@JQNYFIR_@Xk@Ta@Ra@|@_BDKt@wADGFKLUTe@R]JSLUp@oAf@_ADIt@yAVe@N[HMFOHMTi@@Af@eAj@kAJWFMJULUHUL[JSLYHU@AZs@h@sA?AJWJUJ[@CDKN_@Z}@Zw@To@JUX{@Nc@HSN_@Ne@Vu@f@wADKrAuD~BwGj@_BHYJW\\_ADMJUBGDMJWHUFOVq@LWHSJUHSLUTe@@EJSLWXi@LWTe@NUJULQ?ALSNYLSJONWNUJQJMJQBENSj@w@NSJQNQLQNSTYJMJMLORURUDEFGLQPONQLMNOLMPQJKJKNO`@a@JI`@_@hAgAVWNOJILMHGDEJKXY`@a@@Ab@c@VWp@o@^a@JKDEPONOFGFGPQ`A_ABCb@_@NOPQ^a@`@_@x@y@PQf@g@PQPOFIFE`@a@POLMRSPOPONQPOPOPOPMPODG@?ZWPOJIVSNOPMPOROPOPMTSLIPOVQdAw@FEDCLIb@YZSXQZUPMPMRKVQ`@Ud@YvBoAbAm@bAm@nAu@DALKJGBAf@[tAy@^Sh@[RMjAq@LId@WLIBARMXOjAs@b@U^Up@]\\UXQLITOBC^UZOJEFEZQ`Am@t@c@\\SHGj@]DAPMVOXSNITMTKVQ|@c@~AaAzA}@tCeBdBeARMxFeD|M_IlC_BBAnDwBjAq@NIXQZQPKLIPKb@W\\SpAs@BAn@[RKRIPIPGf@SvAg@`@MPEBAd@Mv@Qj@Md@INCLCbAOHAf@EVCZCx@INAhAKdAIn@GxAOr@KhBW|A[j@MvA]d@Mj@QDAdA]j@STIlBo@~Ai@nAc@BATIDAJEr@WtAe@|EcBVKp@SRGf@O`@IJCh@M^IVEVEb@GFA@?p@IJAHARANAd@CZAN?r@CV?@?F?\\?l@@t@BJ@ZBF?J@t@Fj@DJ@x@HF@VBH@p@FB?RBB?PBRBR@PBj@D@?f@FVBP@V?P@F?L?pA?\\CNALALAFAJAFANCLAZGRERE@?f@MVIj@SNIPGXOLGVMLIPMb@W@AZUTO?AnA}@\\UZS\\WRMPMPMPMVQLITMj@[JGTKt@]NGlAc@LE~@Wl@Of@Kr@ONCTCLAFATCFALATCVERATERATCTETCTCTCHAJATCB?PCTCTCJAFAVCTCRCDAh@G`@EZETCTCVERCTCTETETERETETGB?PGRERITGTIRGRIJGHCPITIHEHERKLGNIRKBCNITMPMRMPMROPMPOPMPOPO@?PMNOROPMPOFGHGHG`@[POPOr@k@POt@m@`@]PMPONMPMPONMv@o@PMb@_@ROb@]NOROPMPOPONKTSNMb@]POPOROPMPMd@]PMRMPORKPMRMRMd@YPKRMRKRKPKRKRKRIRKRKRIRIRKTI|@_@~@]zAi@JEv@Y`@OFCj@SdAa@|Ak@TIPGTIRIRIJCFCRITIRIRGRITIRIRGLEDCRITIRIf@SPKRKPI@APKv@m@RONMPQNQBELM\\c@LSHKDGLSLUJWFMDEJWJWJWRo@HYHWFYFYFYFYDYDYF[DYDY?AL{@PiADYDYD[BMBKD[DYPoAF[D[DYDYr@yEJq@BO@IBSBQDQ@K@I@C@IDW@EDYDWFa@DWFYBOBKDYFYFWHYJ_@DQPq@JYHY?AJYJYHUHWJSVo@JUJULWJUHOBEBGFMZi@LULUNSLULSHOBEZi@LUNSR_@T_@JSx@uALSLUNSNWLUJSLSLSLULUNSLULUZi@LSLUNULUNUZi@JSd@u@jAsBr@kAR]x@sAJUNSP[JSJOLUNWLSLSJSNULULSLUNUh@_ALSJSNSl@eAf@{@?ALQh@_ALST_@R_@\\i@p@iADK\\i@LSZk@LSHMDGXe@DIFMLQLUNUJSDIFKLUNULSZk@LSZk@DEJQv@mANULSNUJQFIFINULSRYJOLSPWLONUNSLQNSNSLQNSLO`@i@NSNSNQJOPUNULSLQ@ALONSLONQT[\\c@PWV]Za@`@i@FILQNU\\c@@CZa@PUNSNS^g@FKV[FKFILOLQRYNSJMNSNQNSNUNQLQFIFIPULSNQPSJOLSHIx@gAV]RYjDuE@AHMNQV_@X_@@ALSNSV]Xa@Zc@Zg@LUNWZo@LULYBEN]N[JWHUJWJYRo@HUDMLe@HWHYFYH[FWFYH]DUF[F[DYJu@D[DYD[BYD]B]Fs@TeCDc@HiAB[B[H{@Fw@D]JmAFu@Fu@F{@H}@BSHgAL{AHw@B_@Fq@Fi@@MBYBYD]BS@GFe@BKD]FYDYNu@FWF]FYDQ@EH[Pk@Tu@Ng@FSFQHSHUJWJUJWLUJYJSJUNWZk@HQPYLSLQNUNSLSV[RWPURWdEyEzAcB`AgATYVWj@o@vAaBrEiFNOPSLOPSNOPSLOPSNQPQNQLQPQ^a@PUPUBCJMNQ^a@NQPQJMVWz@cA@APSPSLQ@Ax@gA^i@NSNUl@{@LSNUV]nAoBLWh@{@PYJQNWJQhAmBf@}@LQ?C@?NWNWJQDINWn@aA\\m@LURYBEd@q@@An@}@j@w@JQNYNULU\\i@LSj@}@j@aAj@{@Zk@j@}@j@_ALSLUNSLUZk@\\g@PYHQ\\i@h@y@HOR]Zi@LSR[d@w@j@}@\\i@Zk@Xe@PYLUNUZg@\\i@LSNUHO`BkCn@gA^k@NSTc@@?LWFIp@iAT_@FKjAmBZg@^i@FKb@q@hAiB\\i@fAgBtA_Cv@sAhAmBdBmC^k@\\e@LQ\\g@LO`AqA^e@Xa@jAyAtAcBLQTWHMv@aAz@cA`BsBV]JMl@u@NQ\\c@LOHMFGv@cAp@y@nCiD@Al@u@^e@NQNSNOPQ@CNONMTSLKNMRONMRORMDCJIRMTMh@YLGl@WPGPGRITGRGTGRETGTETEREf@InB[LAp@Md@I`AOfF{@ZG~@Oz@Mf@GZGB?LCTEj@IREPC^GZGHATELCLCHABANCDAPE@?TGPGRGBADAJERGTKTI@ABAJEDANIPKPILIFCPKPKXSHGFELIPOROLKDENMLMDELMRSNQNONQ\\c@BELOFKDE@CNSLUDEFOLSLSLU?ALWLU@EJQRg@JUPe@HUHQFQ@APg@Pc@@CHSHUJUJYJWHUFOBEJWHWL[JUFSRe@Pg@DKBEFQ@CBEFQRi@@CHUVq@JWHQBG?CFMHU@CJUHUFOBIHSBEDMBIFQBERi@JWRk@BEHSHU@EHQDOBEBGFQJUHW@?HWLWJWHULWLUHQLUJQ?ANULUJQNUNSLSLQLO@ALQNOPQPSLONORQPOPOPOPMPONIDELIRMPKTKNKTMPIRIPIRITIRIRGVIRITGPGRE?ARETGREXGNETERCVEPCTERCTCh@EVARCRAVAj@CR?VAR?B?P?V?R?h@@f@?D?f@?V?f@@T?J?b@?N?T?B?R@f@?fC@N?|A?d@?T@R?T?V?B?JAV?@?TAT?TARAPAD?d@CRAD?NATCXAVCRCRCTCPA`AOTCNCLCFAB?PERCXGREZGBA^ITGJCXIPEBAPERGRGXINGTIRGRGTK`@Of@Uh@SXMRKRKPIVMNIPKNIVOTMPKPKPK`@WBCRMPKPOd@[TQNMPMPMPONONKNODCXWFG\\[Z]RSFG@Ad@g@JKJK^a@DGHIJMLOV[LOHKRWLQHK`@k@T[LSLSPWLSFIVc@PYJSLULU@AJSLUJSNYR_@DMLUN[JSr@{AHOBGLUXk@JWDIFMJSN[HOFKDIJULULW@Ad@aANWFMP[HOP[FIFMJOP[JO?APWLSFIFKLQPWNUPUBEHKNUNSPSJMRYb@g@PSJMNQPS@APQTWDEDGNOVUVYRQBCPOHKNMZY@?RSLKRQf@_@POv@m@VSLIXQ\\UXSJGRMRMRMRKVOPKZQHETMHG\\QZQLG@AVOLGPKBANINIDCTMRKLIPIRM@Ar@a@BAVODCHGVQDC^UTQPMBCLIJIFEDEHGBANO\\YBAFGLKPOPODEJKNOHGJMNMNQRSLMBCLORULMNQBCJOPS@CPSZa@@CFIHKNSNULQPUZg@NWFIBEPYPYHQPYJSJQNYJSLYLWLUL[HQFMBEHSBEJWHUJUL[HUJYJWHY@C^eAFQJ_@HYHYHWPq@HWFYHYFYFYFYH[FYFYDYFYF[D[FYD[BKHi@DYD]DYD[D]D_@BU@M@MD[@M@MBY@S@IBWB_@B[@]BYB[@[B[?G@SDo@Bc@Dy@PeDB[HaB@OFsAHsAB]@[B[B]@[B[@]B]B_@Du@FwAHyAB_@@YB[L}B@a@@C@MHmBFy@@]NkC@OBk@B[B[@YB_@Hy@B]B]D_@B_@BSDc@D_@D[TeBDa@D[DSFc@F[BQFa@P}@@IBOH]DYFYFYH_@H]FYBKBOFUJ]FYH[HWH[HYHYH[JYHYHWJ]HWJYJYHUVs@JWTo@HUFQBGHWJYFQHWJWJYPe@L_@JYJYHWJYHW@AHWHYj@oBNg@FUFUH]Jg@FYFWLm@DQH_@FYDYDYDUD]DWDWDY@GBQD]D_@DYHu@Fu@DYBW@YBWBW@WDo@D}@?]@K@g@DiA@eA@u@@[?Y?W?W?C?Y?Y?Y?Y?Y@Y?A?[?W?Y?M?K?[?q@?[?]@cB?qA?[?O?I?Y?[?s@@}@?Q?[?[?Y?[?Q?I?W?A?[?Y?[?G?Q@Y?]"
                     },
                     "start_location" : {
                        "lat" : 39.7127354,
                        "lng" : -78.18933729999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "30.0 mi",
                        "value" : 48304
                     },
                     "duration" : {
                        "text" : "28 mins",
                        "value" : 1690
                     },
                     "end_location" : {
                        "lat" : 39.03498099999999,
                        "lng" : -77.1443151
                     },
                     "html_instructions" : "Take exit \u003cb\u003e53\u003c/b\u003e to merge onto \u003cb\u003eI-270 S\u003c/b\u003e toward \u003cb\u003eWashington\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "a|moFzsqwMJW@E@]?[@[@[?A@Y@[@[@Y@CB[B[B[BW?ADYD[DYDU?CF[F[FYFWBGNm@HYHW\\gAJWFMDMFKHQFMFMFMFKDGFKFM@ADIHMLQLQLQHKHKFKBCJKX]VY\\_@^]Pg@PO^[PQPOPQNMPORQPOFGHGRQNOLITUZU`A{@t@o@z@u@fAaAROTSPQRORQRQTS\\Y^[d@c@bA{@hAaArAmAJILI@Cb@[|@y@`@[jAeA\\[nAgAr@k@vAkAt@m@NMnCcCPOPONOTQr@q@rBgB@?Z[p@k@HG`@]DEb@a@f@c@jAcAl@e@lAgALIr@c@^Wx@g@v@i@x@u@j@g@tAkA\\[vAmAbDoCjAaANMZUVUBATQPMVOJGLI^S@Af@Wd@UDAbCkAx@_@f@UTKPGPIBAPGRIRIRG@ATIPGTIRIRGRGTI@?PGRGTGRGVIRGd@OB?NGTGRGRGRGHCJCTGHENCFCRGTIDAb@ORGTG@APG@?TIRIXIRIXK`@OBAPIVIDCNGTIRKVKTKRKRI@ARKTKPIVKNI@ATKRI@ATKPKTINIVMPIPIDCRIh@W@APITMPIRK@?PKRI@ANINGBAVMTMRKRIBAPKPIBANGTKRKPIRKPI@APIj@WNIVKPKJEDCRKDA?AFCNGTKHEb@UPIRKRITMNGPIVMf@UJG`@SRIRKXONGZORIPKXMNIPIJGNGLGTK`@SDALGVMPKb@S`@Sv@]d@UHCLGd@Uf@U`Ac@@?RK|@a@h@UPIVMbAe@b@S@A^QDAZO`@SVMrAm@VM\\Q\\OBA^SFCd@SPK\\ODC^Q@AFCBAPKB?LGj@YPITKNILG^Q@A^Q@A`@QHERKRILG\\Q@AXMFC@AXMLGXO^Qf@UBAPKNGDCPIRKPG@A@Ad@SLGFCTKRKJEDCTIRITIRG@APGDAJCFANGNCDCZGLCTETGFA`@IREVERGVGPEPELC@ANERGXGPGTITGLE`@M?A`@OJEDCRIRIPI@ABANIFCJEJG\\QRKPITOPKRMTMPMRMROPMROFGHGPMJIDCRQNMRQROPOJIBARQPOPORONMRQPMNMRQHGDEPOROPONMHGHGPONMRQPMPOPMNOROPORQBAPOPMPOx@q@RQPONKRQPOHGDGROPMTS`@]XU@?DGTQNMPMPOb@_@NKx@q@HGFGNMROb@_@POBAJKRQRONMROPOPOPOPOJIDETQ@ANMPOPOPMVUROJKPMFEHIPOHGHGDENKLMPOXWHGRQJKBARSNMBC^]NOf@g@DEFGRSFGFGb@e@NQNO@ANQ@CJMRULOHIX]PUV]DE?ANQFIFINSPULSV]FI?ANSNSFKFKPWJQDGr@iAFKFILS@AJQLSFKFKLUHKBGLSNUNULUFKFILUXc@PYNUR_@FILSNUDEFMNQLULQNUNSLSNSNSHMBCNSNSNSRW\\c@NQPS@CLONQNQNQPSNQ`@e@NQNONQRSBCLMNQ@ANMNQPONO@CNMPQPQPO?APMPQPONORONORO`@_@RQRONMPORONOROPOPMPONM@APOPORORQNMPOPORQPOPOPOBELMRQNOb@c@PSLOPSPSLM@CNQNQPUNSPUNUNQJO@CPULSLSNUNULSLUNULWLUNWLUJULWLUJULWLWJULYJWJWJYJUJYJUHYFOL_@JYJ[HWHYHYJYHYFWJ]DS@EHYFWF[H[FWFYF[H]DYFYBMBOF[DWBQ@GF]@KBMD[DYD[DYDYD[BYD[D[BI@MD]DYDYD[B[D[@?BYDW?EDUD[BQ@ID]@GBUD]D[BOBMD[D[D_@@GBQD]D[D[DY@GDUD[F]D[DO@KH]FWFWDSJa@BINg@JWL]JS@AJW@CJULWLUHQBGNUFKFILUBCLQNSPULORSPQPS@ALMRQPOPMJKFCPORKRMRKJGFCRKRKZMLEh@SRGTGNEBATITGRGTGRGTGRGFCLERGTGRGRGTG@AREh@Qr@Sr@S~@YRGh@Oh@ODAd@ORGTGTGRGRGTIhA]HARIv@U\\IRITGRGTGRGTGRGTGTIRGRGTGRGTGh@QRGTGRITGRIRITIRKRIRKRKRKRKRKRMRMPMRMPMDCLKPMPOPOPOPQPOPOPQNQPQTWJMPSLOJOBCNSBEJMLUNSLSR[HOLSNSLULUNULSLUNULSLSLULUDEHOLSNULSLUNUDIFILSLUj@_A@CLSLUNSLUNULULSLSNULULUNULSLUNSLULUNULULSNULSNULSJSBCJQNWLSLSLULSLSNULULSLSLSNULSLSLSNUNQNSNQPQNQNORQNOPOPMROPKBCPKPKRKRKRKRITIRGRITERGTGTERCTERCTETCTETCTERCTETERETGTERGREVIRGTIRGRIRIf@UTILIDARKPKRKd@YVQNKROPKZYXUPOPQNOPOPQPQ`@c@^c@NSNQNSNSLSNULSNSLUNSLSNULSNSLSNULSNSLSNSNSNSNQJMDELONOJKNOPQPMDELKPOPMROPMPKRMRKRMPKTKRIRIRIRIRITGRGTGTGh@MTERCRCTETCTCTATCRC|AQ~@Kl@Ih@Ij@MREh@Ml@Oz@Yh@Sj@Wz@a@l@]f@Y^Wf@]`@[d@a@t@o@v@w@DEPSPQNQNOPQPQNQNORQNQNOPQPQPQNOPQNMNO@ANMRORQPOPQPMPMRMPOPOPORMPMHEFGRMROROPKTOTMJGDEPKNKPMRKRKRKBANKPKTMDCJGDALGRK@?PKRKRIRKTIRKPG@APGRKBAPGTIRITIPI@?RIRITIRGTIRGTGRITGNEBATGJEFATGRGTGTGRGVIRGRGRITIZKLEDCJETKHE\\ORKRKTMHEXOh@[RMRMNKRMPMNMPKNO^Y@APQNMRQNQPQFEHIPQNQPOPSLORUHIDGPQNQPSNSNQNQ@?NQNSPQLSPSNQNULQNSNSDIHKLSNUJOLQJQDIFIFIJSHMP]LULWLWDGFMJULWJULYJUJSHSJUHWPa@L[JS\\w@LW?A^u@LUNYLSDGFMNSBCJONSLQPSNQPONSPOPQPOPOPMRMROPKRKTKRKRKDCLERITKPGRGDAPETGREVGTERCVETCRCTCVETCTARCVCf@GVGVERCLEFAVGFALCTGTGTGRGVGTITIRKTIHCHERGTIRKTKRKRMRKPM@?PKRORQPMROPMPMTMPMPOj@a@XSXSRORODCHITOXQJGd@]h@_@NKVQLIZWHGRORMTQ@AJIRMROBCLIRMRMROPOLIDERMZSPMBCFENKHILIBCd@]r@i@PMf@_@hAy@ROJIj@a@PMb@[@At@k@DCLKPMLKBAFGBCNKHGFGLIp@k@POPMf@c@LK\\[DEPOPOPONORSNORONOJKDEPOJKBEPOLMd@e@r@s@LKBEPOVYHGNQPQBALORQBEHIPQ^a@PONQPQVWDCPQPQBALMPORM@CNKTQPMBA`@Y@?b@Y@Ah@YNIf@YFCJGRKRKHELGZQZQRK|@c@HGHERKRKRKRKRKRKRMFCJERMBALGRKDCVM`@UXOd@WTKHEHGPIp@_@NINGRMPKNIt@a@DERMXODCFEPMf@[j@c@TOJGLKBCLIHIFEROl@e@d@a@VUPQHGNOBARSDEJIHIXUHIRQDG\\Y\\[LMZWFGNO^[VUd@a@\\[h@g@DCXYNMNMRQf@e@VS@Ah@g@BCd@a@JKNMPOBCLKJKRQDC@A@AFG^]RQNONMPOPOv@s@POPONOLKDCLOPOPONOHGDEDCNOPOPMJKDENM@APQLKd@a@PQRQRQDEDCJKFGTSTSHIXUNO\\YNQFEXWRO^[RQNMBCHGf@c@RQ@CPOFEJKFGFEt@q@HIRQ@ANM\\YJKFGBAHIHGb@a@FGBCVUFE\\YDE@CLKZYd@c@^[v@s@fAaAp@m@^[VSPONMJIhA{@p@i@j@c@XS~@o@r@c@ZSHGd@YtBmA|BmAx@a@r@]rAo@NG@AjAm@nAm@tAq@BAZO`@S^QjAi@n@Yv@]FCfBs@VMb@Od@SLENG^Mr@YdA_@nBq@xBu@d@O~@[BAPGJCBAFCv@YTGv@YVIPGZKv@Yf@OTIj@S\\MB?TIhA_@nBq@x@Wx@Wp@UjA]XIPGVG`Be@~@U@ALCHCp@SlAYPEd@Kx@SXGJAHCBAXGz@Qd@KHAPEJCREl@KlAUp@Mx@OVEFAZIpAUVE`@Ib@I^I~@QREPCl@M|@Qt@Sb@M^KHATIRGx@Wr@Wb@QTITILGr@Y^S^O@AXOBAv@_@hAm@^U`@Wb@Y`@WHGBAXUVODCDEXSDEVQ?A@ALKZUXUPQ^[r@o@POp@q@BCf@g@d@i@^c@PQRUn@y@`@g@X_@FIhBeCRYXa@V]V_@^e@Xa@DG@A@CDE@An@y@`AmAPUNS|@gAlAwANQFGx@_Aj@o@r@w@d@g@b@e@LOVYRSr@y@t@y@VYXY|@cAZ[NQNQXYVWf@g@lAkAXWBCFGBCBA\\]@?HINMdAy@ZWd@_@\\WXSj@a@d@[dAq@ZSRM\\SXQ\\SHEh@Yz@e@@ApAo@`Bu@NGbAc@`A_@RI^Ml@SNGTIZK`A]z@YBAjAc@LEn@UPGfA_@LELGrAe@DAJEj@SRI^Ox@]RKNGbAe@XOd@UPKNIVOz@i@x@g@HITOVSHGVShA}@DCb@]PQVUVUj@g@JIPQx@s@JIfAcADEHKZYBCn@i@|@w@BEBCj@e@@A@CDCp@k@^]`@a@f@c@BCDCXYh@e@HGr@o@ZYvAsA`A{@JKdA}@VUx@s@dA}@TSh@a@z@u@HG|@s@j@c@NMf@a@|@s@RMPO^W`As@n@e@~AiARQROLIFE`@Yt@g@TM^WPMf@[l@_@RMRMd@Yf@Yv@g@JIl@]r@c@zA}@nAu@r@a@rBiAd@U|@a@PIXQ`@SFE^QPKh@YNGFEPKZQr@_@pAq@\\QJGf@YFCJGz@c@TMNK\\Qf@WHEf@Y@ARMPK@ARK^WLGJIRMPMRO@?PMPMROPM@ANKf@a@NMBAb@a@NMTSb@_@`@a@@Az@y@X]NORSNSPQ^e@JKBE^e@^g@NQPU\\g@`@k@NSLSNUNUBCHOFKFILWLSLWLSDI~@cB@CJSNWFOBELWLWDKFMHS^w@Re@HS@GVm@N_@FQJWFODMDI@C?CXq@JWHYJWJWVo@DKDMJWHULYHWHSLYFSLWJWJWN_@FMJWBIFMDMDIJUXq@JULWJW@CVg@LWJULULWLWJSLWLWBEHMLYNWVi@BCLWJQNY?ALSLWLULUHOPY\\m@FKDILULSXc@T_@DGBGHMNSLULUBCXe@NUNU@CBCHKNULQBELQNUNSNSNSLSNSHMDEBGHMNSLSNSRWJODGHKNSNSLQNSNSLSNSFIFINSNSNSNSNSDGHKNSNSNSNSNSZa@RYNSHM~@qAZc@d@o@h@y@TYf@o@V[NUNQl@w@NSPSRY\\a@LOBCr@y@~@_Ah@i@lAkAdAaAXWt@q@x@s@VU|AiAn@e@ROZS^Yf@[f@[PMh@[LKRMVOPKh@Y|@g@d@Wz@c@z@a@BAx@_@~@a@`@QXKh@SrAg@JE^MTIPGbA[^M`@Kh@Qr@SJC`@MTGHCXIb@Mv@UhBg@LEvAc@h@Qh@Q|@Yd@QB?TKh@Q`@QZKTKnAg@j@Wj@UvCuAr@]z@a@`Ag@`@U~@g@`BaAx@g@l@_@v@i@LIBCb@YdAu@LIdAu@d@_@z@q@PMROb@]b@_@b@_@d@a@d@_@b@a@`@_@f@e@r@q@RQNOv@u@bAaAd@a@b@a@NQ`@_@d@c@NOt@q@PQPOPQPONQPOPOPQPQNOROPQNOROPOPOPONOROPOPOd@_@NMPOROROPMROPOPMROPMPMRORMPMPMRMPMRMROPMRMPKRMRMPMRMd@Yf@[d@[lAu@bHmE|AcATMPMJGFEPMd@[RMFE\\WPMRMVS^WPORMPOROPMPONKBANOROPOPMRQNMPOPORQPOb@_@b@a@POPQPOPQNOPQBCLMNORQNOPQPQNOPSPQNONQj@m@RUn@s@r@u@`@c@tA{AvA}AxA_Bd@g@jAqA`BgBvA}Ah@k@p@u@`BgBt@y@x@{@fBoBbCmCRU^c@l@q@jAmAnAuAv@}@VYpAsAv@{@hBoBv@y@FINQPQBCLMNQPOPQ?ANOPQPOPQNOVU\\]BC^[b@_@d@_@PQPMPO^YDEPOPMROPMPOPMRORMBCLKRMPMRMDEJGRMPM@?PMRMRMPMRKRMRKRMPMRKRKRMRKRKFCJGRKRKRMRIJEFERKRIRKTKRIRKRI|@_@NGBCTIRIRITIHEHCRITITIRGRITIRGTITGRGRITGPGBARGRITGVIf@Q`Bg@v@WVIv@WDA~@[HCDAPG`@MDAXKd@O`@MHCVKLEl@QFC@?`@MNGPE`@OLEHCj@Qb@Od@O\\KbA[n@U`@MRG~@YLEXK`@MJCTI`@K@A`@Mt@SLCNEjAY`@Kn@OXGj@OFA@ANCl@OHCJC|@S`AUXGZIXG@Ar@Qt@Ql@O^IHCHCHADAZI^Ij@MlHeBHCVGpAYFCx@S~@Sn@O|@UhA[RGVIVId@Oh@Sf@Qh@SVKh@Uf@WVKZQXOj@YPKd@U|@g@d@YRKPMRKNKLI\\SPKRMRMROTMHGDCv@i@f@]ROPMNM@?d@]d@]ROXU\\Yb@[b@_@@Ab@]RQNOPOPOPQ^]BCPQ`@a@b@c@^c@PQNQHKPSNQPSNQNSNSPUJO^e@PUJQ^g@BCV]PWPW\\c@LSPSLSBChA}APWLO^g@DGV_@NQNU^e@\\g@T[DGRW\\g@NSNQ\\g@^g@^e@NSNS^e@PSNQNQNSNONQNQPQPQNQRSNM`@a@PQVUJIb@_@NOROPOPMPODCJKRMb@]n@c@HEb@[RMd@Y@?PMRKPKRKRMRKRKRKRK\\O\\QRIPIVKPIRITIRIRGRITIRGRITGRGRGRGRGNEBAh@MTGREf@MPEVEPE@?TGh@Kl@M`@I~@Qb@IXGZGhCg@NCx@QnAUFAp@MVGf@Ij@MdASh@KB?ZG~@SXEl@Mh@KTEREn@Mh@Kd@KXEf@MRERETERERERGb@Ij@M~A_@n@O`@KPERGPEREPGREREPGNETG`@Kd@Mh@Od@MREd@OPERGPGRG\\KVGb@MRIRGVGdA]z@Yv@UNCRG`@O|@YdC{@hAa@v@YTIj@Uj@S|@]\\ERIf@Uv@Yx@]|@_@|@a@p@YNEf@UtAk@~BcAh@UTKfFwBl@WrAk@f@UREXKr@[bFuBbIiDdCcAbCeA|Ao@h@UFCb@Qh@Uj@Uh@Ud@Q|Ao@b@Sf@U@?h@UHELENG`@QHEd@SDCf@S"
                     },
                     "start_location" : {
                        "lat" : 39.3979345,
                        "lng" : -77.42797759999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.4 mi",
                        "value" : 3834
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 144
                     },
                     "end_location" : {
                        "lat" : 39.0214277,
                        "lng" : -77.1060433
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e at the fork to stay on \u003cb\u003eI-270 S\u003c/b\u003e, follow signs for \u003cb\u003eI-495 E\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eSilver Spring\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eCollege Park\u003c/b\u003e",
                     "maneuver" : "fork-left",
                     "polyline" : {
                        "points" : "s_gmF~fzuMDY?AJIHELIXQROVQDEDCHGTSVYHIPSPQFKFINSNULSNUJULUJUJWJUHYJUH]Ja@DYDOH_@@KDUF[D]D[B[B[BSDi@HcBJeCHaBFwAD}@FcAFcAFmATaEBc@B[@W@OFcABSBa@Dm@Fu@B[@SH{@HgAD[?EPgBHu@Hu@ZkCLmALaAFk@D]RmBFg@NoAVaCj@_FRiBHu@J{@NyAFm@Fk@?AFk@Dk@@ADe@H_AFw@HaAD_@?CH_ADg@TaDHcAJoA?AHkA@KDa@Di@@IB[HmA@QBYL{AB[Fw@B]F}@Di@@QD]B[B]Dm@BUBUDm@De@@GJcA@CLiA?ANcAL{@Ji@@EHc@Je@Ns@Ry@BO@CFUHWDODQBEHYLc@?CFOTo@Xy@To@Xu@@C`AsBJSd@_AVc@BEJQVc@LS`@m@PWh@s@LOb@i@PSp@y@BCZ]^]`@_@LMh@e@JGNOz@q@@A|@s@f@c@|@s@t@k@VS`Aw@BCVSLKBAJIHGRKFEVMDCBANGZOJCt@WVI"
                     },
                     "start_location" : {
                        "lat" : 39.03498099999999,
                        "lng" : -77.1443151
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.8 mi",
                        "value" : 2933
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 123
                     },
                     "end_location" : {
                        "lat" : 39.0050677,
                        "lng" : -77.08130079999999
                     },
                     "html_instructions" : "Take the exit onto \u003cb\u003eI-495 E\u003c/b\u003e toward \u003cb\u003eCollege Park\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eSilver Spring\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "}jdmFvwruM`@ITITGRGRGTG@?RGTERGh@OPGFANG@AVKBCLETMPIBC@?LIBALIRORORQNOLKDEJKNQPQBELODGHKZe@BEBELSBGFKDILWLWHQ@CNONWTi@Zo@JWJSDKFMJU@AFSFODOVq@Ni@H[FUH[Ns@FWD[RkAF]PaAJo@F]TyAZiBFWDWF[DY@C@MDOJk@FW?CFSFYHWHYHWHWJYHU?A@CHOJUJUBIb@w@NSLSNSNQNSBCDEDEPQNOPOb@]d@[PMRKPKTMPITMPIPKRKRKRMFEHERMd@]ROPOPQPQRYJMNULWDIFKJWJUHWJYHYBEDQPs@H[FYFYLe@F]FUHYFWBKDKFYDKBKJWHWJW@AJUJULULULSNSPQ^a@PQPOPMPMRMPMRMPKx@e@RMv@i@LIBCROPOPOPQNOBCLONQNSLULSNWJUXk@Vk@JULUJWJUd@cAf@iAdA}BJWP_@j@oALWJUFQBEJWJWHWDKDKHYHYHYFYDW@AD[D[BUDe@JoB"
                     },
                     "start_location" : {
                        "lat" : 39.0214277,
                        "lng" : -77.1060433
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 mi",
                        "value" : 1207
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 101
                     },
                     "end_location" : {
                        "lat" : 38.9961352,
                        "lng" : -77.07727939999999
                     },
                     "html_instructions" : "Take exit \u003cb\u003e33\u003c/b\u003e to merge onto \u003cb\u003eMD-185 S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eConnecticut Ave\u003c/b\u003e toward \u003cb\u003eChevy Chase\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "udamFb}muMPS?A@c@@_@?AD}@@K@SD[@EDW?CFUBKBIBIDMDQN_@Zq@b@w@@CHIJQL[HUFSJe@F[DODS@E?ABMBEBGDGBABCPU`AKhBQfAIdCYhAKjBQfAE`AEl@ATBb@@b@@R?P@fAH|@Db@DF?ZB@?D?b@BZB\\@L@j@Bl@?j@?H?|@?V?`A@"
                     },
                     "start_location" : {
                        "lat" : 39.0050677,
                        "lng" : -77.08130079999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 218
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 42
                     },
                     "end_location" : {
                        "lat" : 38.9965435,
                        "lng" : -77.07963339999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eManor Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{l_mF~cmuM?zACp@Ab@CRCJITGNa@f@KXCLEVBf@?F?j@@D?F?D?B@@"
                     },
                     "start_location" : {
                        "lat" : 38.9961352,
                        "lng" : -77.07727939999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "338 ft",
                        "value" : 103
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 18
                     },
                     "end_location" : {
                        "lat" : 38.995968,
                        "lng" : -77.0805596
                     },
                     "html_instructions" : "\u003cb\u003eManor Rd\u003c/b\u003e turns slightly \u003cb\u003eleft\u003c/b\u003e and becomes \u003cb\u003eLongfellow Pl\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ko_mFtrmuM?B@B@DBJDH@DDHP^FNBFDFBB^f@RX"
                     },
                     "start_location" : {
                        "lat" : 38.9965435,
                        "lng" : -77.07963339999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 172
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 56
                     },
                     "end_location" : {
                        "lat" : 38.994963,
                        "lng" : -77.0790434
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLaird Pl\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yk_mFnxmuM~@yAn@cAVa@FINYFKLWFQJU"
                     },
                     "start_location" : {
                        "lat" : 38.995968,
                        "lng" : -77.0805596
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "39 ft",
                        "value" : 12
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 4
                     },
                     "end_location" : {
                        "lat" : 38.9948644,
                        "lng" : -77.07898349999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eLaird Pl\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eLynwood Pl\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "oe_mF~nmuMRK"
                     },
                     "start_location" : {
                        "lat" : 38.994963,
                        "lng" : -77.0790434
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "230 ft",
                        "value" : 70
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 38.9948754,
                        "lng" : -77.0781707
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLaird Pl\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{d_mFrnmuMCS?M?_C"
                     },
                     "start_location" : {
                        "lat" : 38.9948644,
                        "lng" : -77.07898349999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "472 ft",
                        "value" : 144
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 36
                     },
                     "end_location" : {
                        "lat" : 38.996166,
                        "lng" : -77.07816529999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLoughborough Pl\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_e_mFpimuMmC?sB?"
                     },
                     "start_location" : {
                        "lat" : 38.9948754,
                        "lng" : -77.0781707
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "253 ft",
                        "value" : 77
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 39
                     },
                     "end_location" : {
                        "lat" : 38.9961352,
                        "lng" : -77.07727939999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eManor Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "am_mFpimuM@c@Bq@?{A"
                     },
                     "start_location" : {
                        "lat" : 38.996166,
                        "lng" : -77.07816529999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 mi",
                        "value" : 922
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 122
                     },
                     "end_location" : {
                        "lat" : 39.0042274,
                        "lng" : -77.07748339999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eConnecticut Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{l_mF~cmuMBc@kB?c@?}@?mBCk@EgAGc@CC?]CkBKuBMUA_A@g@@C@A?qAHkDZc@Dm@F}@Jc@Dc@DUBc@B_@DcBLeBR"
                     },
                     "start_location" : {
                        "lat" : 38.9961352,
                        "lng" : -77.07727939999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "6.8 mi",
                        "value" : 10970
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 446
                     },
                     "end_location" : {
                        "lat" : 39.0191158,
                        "lng" : -76.9591839
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eI-495 E\u003c/b\u003e via the ramp to \u003cb\u003eBaltimore\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eSilver Spring\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "m_amFfemuMOGEAE?Q?W?UAMCA?ICA?KGOMCCMOIMCICKI[O_ACSACWiBWaBKy@Gq@Ue@Es@Es@A]C[AYC[A[C]?IAQCYAYKmAEw@C_@CYCe@Eo@C[C[C]A[C[C]CYC[C[C_@CWC[C[E[E]EWEWAGGUI[GUACIWKWKWMWEIGIIQSYMSIKEEQSQOSQQOOKCAQMSOSMSKQMSMSMQMSMQMIGIEQOQOQOc@a@QQOSQQMQOQOUQSMQQSOSMQOSOQOSSUOQOOOQQQWUMMQOQMQO_@WOKk@]IGKGIEKIUMSMQKQKQMSMOMQMQMQMOMOMQQOOOQMQOSMQMUMUIUKSIUKWIWCKCKGWGWCMAIEWEYCYE_@AQAYA[?Y?[?Y?Y?Y@S?G@W@Y@Y@E@S@Y@W@WJiBBY@YB]Do@@UL_BH}@Ba@BU@[@U@E@Y@]BY@[@[B{@@S?G@W?OBo@BkA?[BuAB{E?[@]?]?[@[?_@@[@wA?YDuE@y@@yA@y@?M?O@_@?Y@_@?Y?[@w@?[@[?]@Y?]?[@[?[?[@_@?W@[?]?[@]?[@[?c@?U@Y?_@@c@?S?]@[?K?Q?[@O?K?]@[?Y@{@?]@Y?_@?[@[?_@@W?Y?[@O?K?Y?[@Y?]?[?Y@]?]?Y?A?w@?[?[?[?[?[?[?QAe@?[?[?[?[A]?Y?[?[A]?S?G?[A[?S?GA]AYA]?KAOA[C]C[E[CS?GEYE[EUACG[GYGWAEGSIYIWIYKWKYKUMWGMSc@KUMWMUKUKSEIEGMUMWMUIQKUOWKUMUMWGMEGKUKUO]KUKWCIGMKWIWKYIWIYIWIYIYI[Ke@CKGYGYGYG]GWE[E[G[E[CYE[E[C[C[C[C]CYC[A[A]A[AYA[A[?]A[?[?[?a@@u@@]?[B]@Y@[@[BY@[Da@@WD[B[B[DYB[Hy@DYFm@@IB[Da@Da@Fk@@M@IB[D[BYFe@Fo@BY?ALoABQDa@Dk@?ED_@?MDk@Bc@Bg@B[@[@Y@[?[@_@@U?[@[?[?[?[?[A{@Ae@?g@AYCo@Ac@A[A[?ACYA[Ca@Gq@AOAIC[C[AQG_AGo@Es@C_@CYC_@CWC_@CYC]C]C]A]CYA]A[?]A]?[?]@Y?[@]@_@B[@[B[B]B[D]D[D[D[D[DU@EFYDYF[FYF[F[FYJi@DMD[FYFYBKTkAHc@BSFYD[DY?AD[B[D]@M@MB]HsB?]@]?]?{@A]?CAYA[A]C]C]C[C]AIIm@E]EYEa@ESESCOEYGYEYOy@E[G[CMAKG]Mw@AGEQE[GYCOAKG]GYCOIe@EYG[EYG[G[E[G[Mw@G[G]E[G[G[My@G[G[G]E[G[G[G]EYG[E]EQAGG[E[EUAEEYG[EYGYESAGEYEYGYE[GYCOAIGYEYG[EY?AG[G]G[E[G]GYE]G[G[G]E]G]G]G]G_@G[G]G]G]G[G_@E[G]G[G]E[G]G[G]G[E[G[G]EYG]E[E[G]OiACYEYEYCYE[AIAMC[EYCYCYC[CYCYA[CYCYA[AYCYA[A[A[AYA[A[A[?YA[?YA]?[?Y?[?[?Y?[?[@[?Y@_@@Y?Y@[@[@[B]@[@YB[@[BY@YB[BYBYB[B[BYD[BYB[DYB[DYB[DYBY?ABUBWBUDYHw@D]D]BYD]B]DYD]B]DYB[D[D[BWB[D[BYD[BYBYDYB[BYB[BYB[BYDw@BY@[BY?C@W@YB[@[?S@G?[@[@Y@[?[?[@]?[?]?Y?]?Y?]A[?]?]?YA[?]?[?]AY?]?[Ay@?]AqB?[?[A[?[?[?]A[CuC?s@QuHIkCC_@A[E}@?ECo@Eu@Eo@Ce@ASAIIsAEu@ACEw@KqAC]Gs@?AIy@C[MuA"
                     },
                     "start_location" : {
                        "lat" : 39.0042274,
                        "lng" : -77.07748339999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 mi",
                        "value" : 2068
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 89
                     },
                     "end_location" : {
                        "lat" : 39.0295684,
                        "lng" : -76.947778
                     },
                     "html_instructions" : "Take exit \u003cb\u003e27\u003c/b\u003e for \u003cb\u003eI-95 N\u003c/b\u003e toward \u003cb\u003eBaltimore\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "o|cmFzavtMP]AQEk@GkA?IASA]?YAS@OAEBg@?I@I?GB_@DY@KDY@KBMBM@C@IFUFYHUHWHUJYNWHQJSLQZe@^i@h@w@DSDIJYHUDOBKDQHa@Fe@BU@W@a@@OAU?]AWAWCUCMAMEYG[CMEKEUIQGSKSIQIOOWGIGKGGCEAAQSSSOMOMOICCSKOGk@SUGe@MSGw@SQE}@Ui@Kk@MWESEc@Ik@IUCi@Ig@GQCeAMcAOSC_AMUCUCSCUEUCSCUESC_AKC?SAuAMUCSCm@Go@Gk@Gk@EUCSCYEUCUCUEWEUCWEUCWESEWCUEi@KUGWEi@OWGUGSIUICAQGSIUISIUKg@WA?SKUMg@Y"
                     },
                     "start_location" : {
                        "lat" : 39.0191158,
                        "lng" : -76.9591839
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "18.5 mi",
                        "value" : 29701
                     },
                     "duration" : {
                        "text" : "17 mins",
                        "value" : 1004
                     },
                     "end_location" : {
                        "lat" : 39.2209497,
                        "lng" : -76.7229289
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eI-95 N\u003c/b\u003e",
                     "polyline" : {
                        "points" : "y}emFrzstMOKWOQOWOUS[YOOSUi@g@OMQSSS_@a@_@e@_@e@]g@U_@GI]k@OWMSMUKUs@yA?Ag@cAe@cAACWg@MYe@}@ACg@}@OYMWOW[g@CGy@oAMSKQa@i@MSKQEGEEMQOSOSOQIKEGOQOSQQOSOQOOQSQOOQQQOOQQQQQOOQQOQOQOQOEEKIQOQOQOSMQOQOQMSMAAOMSMQMSMKGEESMECKGSMSKSMQKSMSMQKKEGGSKSMQKSMSKSMQKSKSMQMSKSMQKSKSMQKSMQKSMSMSKQKSMSKSMQMSKQKYOMISMQKUMQMSKSMQKSMSKSMQKSMQKSMSKSMSKQMSKSMSMQKSKSMSMSKSMQKSMSKSMQKSMSKCCOISKQMSMSKQKSMSMSKQKIEKGSMQKSKSMSKSKSKSKQKUKSKSKSKQKUKSKSISISKSKSISKSIUKSISIUKSISISIUISISISIUISIUGg@SUISGUISISIUIgBo@SGSIUISGUISISIUISGSIi@SUISISGSIA?SISIUGKEGCSIUISIUGSISIUISGSIUISISGUIUISISISIUGSIGCKEUISISIUISISIIEIESIUMQI?ASKSKSMMGWSSMQK?AQKSOQOQOQOQOQOQQQOWYIIOQQQOSQQEGIKOQMSKMCEOSEGIKMSOUMUMSMUMUAAKSMUCIGMMUKWKS?AKWKWKUGQCGKWGSACKYIWIWIYGSAGIUGYIYIYGWI[IW[mAGUAAIYGYIYIWGW?AIYIWGYIYIYGQAGGWI[GOAIIWGYIYGQAGIYMe@AIEOIYIYMi@CGe@gB]qAMc@GWIYIYGWIWGWIYIYGUGU?CIWIYIYIWIWIWAEGQKWIWKWKWKUKWCEGOISMWKUMUKUEGGKKUMUAAKQMSMSEGGKMSMQOUSWIMOQOQOSSWKIMQOOQQOQQOMMAAQOUUMKQMACOKOMQMQMSMMKCAQMSMQK]SIGw@e@SMQKOICCy@g@]S_@UMIg@[g@[_@UECUMcAm@GEWOiAs@SMSKkAs@OKoAu@SMsAy@KGe@YSM]S[Sg@[SMw@e@SMA?QMSMSKSMQKe@[A?c@YUMYSKEQMSMIEGESMSMKGEEQKSKe@[AAe@[SMaAm@y@g@]W{@i@QMUOQMMGEESMSMQOUMc@[SM_@WGESOQKQMQMA?QOSMSMAAQKQOg@]QMSOSMQMUOa@[A?g@_@EC_@W{@o@OKQMe@]e@]_Ao@_@Yy@k@QMSOw@k@y@k@i@_@u@k@A?SOw@k@SOQMg@]SOQMg@]QMmA}@QMAAmA{@SOg@]AAmA{@c@[g@_@QMSOSMQMg@_@OKAASMQOQM{@m@MIAAsA_AeAw@kAy@c@]g@]SMQMg@]QKSMUOUMu@e@g@WAAQKSKQKWKSM[OKEUK_Aa@AAy@]_@M]Mg@SSG[KOGSGo@Sc@MUGUGQGWEQGUGSEWGi@Kk@MeB]i@Kk@MWG[Gg@MSEMCGASGUEa@I]Ik@Ki@KOE[Gi@Ki@Kk@KUESGUEUESEUEUESEi@KYEUEA?UEWGSGUEQESEQEWGw@QEAg@KSGUEi@KYGUGUEUGA?SE]IQEWISGYKWIUISGUIUISISKUISKSKUKSMSKSMUMSOSMSMSOSOSOSOQQSOSQSQQQQQSSOOQSQSQQAAMQQSOSOUOSQUMSOUOUGKEIOUMWOU[m@OWMUKUMWKWIMEIOYYk@MWMUi@gA[o@IOCEMWOWMWOYMUOWMWQWIOo@gAQYOUMSQWQWOUOUAAKQOSOUCCKOQUQU[c@QUOQQUa@g@OOo@u@SWa@c@c@c@W[YY[YWYQQQQa@a@SSQSOOQQSSOQSSOOOOSSMOOOSUOOUYY[OQQSOSOQQS_@e@SUYa@KMGI[c@OSOSMQOSU]OUOSMSEGiAcBo@aAYa@W_@Yc@{@qA_@i@OU[g@SY[e@OS{@iAAA_@g@_@e@QSOQOQ_@c@c@c@c@e@OQOOSQe@c@a@_@_@]g@a@QOSOQMQOSOQMUQQKe@[SMSMQMSMUOQKQKEC_@S_@SUMg@UQKUISK}@a@eBw@y@]g@UCAe@Si@W}@_@aBu@gBu@QKy@]}@a@k@WQGy@_@g@UUKe@UUKQIQIWOa@Ug@Ye@WSOc@WUOc@Yc@[SOa@[CAa@[c@_@c@_@QOc@_@OOc@a@OOSQOQa@c@QQQSOOMOQSOQQS]c@Y_@MQW]QWIKSYW_@S[OUOUMSOU[k@OUMUKSMSO[MUKSMUMUKUMWKUKWKUCEIQKUIUKUM[KWIUKUKYKWIWKWIWIWISK_@KYCKEKGUIWIYIYIWIWQi@Mc@IWIY?AIUIYIWISAEIWKWEKCGIWKWCGO_@M[ISCCIUMWOYKUOY]o@IOCEOWMUOWOUOUOWOSOSQWQUOSQUCCKOQSOQAAQSQSQQSSQQQSSO?AQOWUqAgAkBqACAy@i@gAs@gBiAUOSKUOSMSMSM}@k@uA{@sA{@y@i@UMYSECSMIG_@UKGg@]UMSMSOQKIEMISMw@g@eAq@QKsA{@g@]QKCAi@][Sc@YMGYSIGs@c@WOOKSOUMg@[UOc@Ys@c@WOSMSOQKQMSKGEOK_@Wm@_@g@[cAo@UOq@c@MISMUMSMSMUQUMSMcBgA[SOIUOSMUOSMSOSMSOSMEEMISOSQSOSQSOIIGGSQQQQQSSQQQQQSQSQSQSQSOUa@i@OSQUS[[e@MU_@m@MWOWMWMWMWMWMWMWMYKWMYKYMYKYWs@KYIYK_@KWIYIYGWIYQs@?COo@CGESEYI]GWEYG[G[COIe@G]UmAUsAEYG[k@aDG_@EUMw@Ow@QgAMu@SkAMo@G[Ie@Ms@UqAW_BACEYMq@UoAAEIc@[aB[sAMg@GYIYCKCMIYIWESIWK]Qk@YcAK]Ma@KWACGSKWIUCEGSKWKWKWSg@O]KUCESg@e@aAO[MUKWWe@O]e@_A]s@MUIOCGYk@MUKWKQACYm@[m@GKw@aBu@yAO[MWi@gAo@oA[s@e@}@O[MWKUMUYm@MWWg@m@mAyCgGO[MWWi@_@u@]s@i@gAKSACYk@KUWe@AEu@yAuAsCaBgDmAcCMWIQO[GMCGMUKSKSMYMUEKEIMUMWMWEKEIMUKUACKQKWMWEEISKSKSOYKUGO_@u@OW?CMUMUISCCIQEKGKKUQ]KQM[IMISCC{DcIuBiEi@eAa@{@g@aAAEm@kA_AoBSa@wAsCuBkEc@{@OYaAqBQ_@S_@s@{AQ]}@iBiDaHmAgCcAqBqAkCaBeDQ]_@y@s@wA_@w@_BaDq@wAOY]q@o@qAe@aAoAgCk@kAk@iAy@cB{@eB}@mBa@w@CGu@yAe@aACEKUKSYm@Uc@EGYm@e@y@EGYg@MS]i@OSS[SYW]GG]c@OSyA_BIIUUQOQQOOKGGGOOSOQOSOQOOKAASOQMQMQMQMSOSMSOSOSMSQSMMKECQMQOQOSMQOSQQMOM?ASQQMSQQOQOQOSOOOMKCCQOOOQQOOSQQOQQOOQOOOQSQOOQQQMMSSQQQQOQQQMMAAQQQQOQQQOOOQQQOQQOQQOQOOOOQSQOSSa@c@OQQQOQQQOOOOAAOQQOOQQQOOQQOQQQOOc@c@a@c@c@c@c@e@MMSSQS_@]OQQSOOAAOOQQOQOOa@c@QQOQOQOOQQAAMOOSQQOQOQOQOQOQOSOOOSQSMQOQOQOUEEY]EIGIMOACOS[a@GIIM]e@OSMQMQOU[e@OSKQOUMSMSMSOUMQKSMSOU[g@MUKSOUKSMSOUKUMUMSMUKSMSKUKSMUKUKSMWKSKWKUKUMWKUKUKWKWKUKWIWKUKUKYKUKWKWIWKUKWKWKUKYKWACGQKWUk@MYIUKUKWCGEOKUKUKW?AIUIQACKWKWKWSi@KWo@aBIOAEKWISQc@IUACISKUKUCIIUKWKWMYKUK[ISM[MYIUEKCIMYM[ISAAKYKYKSKYMYIUKYKUKWEMEIKWKYKWEKGOKWKUEKEKKWM[KWIUM[IQACKWKYKUIWCEISKYMWIWEIGOIUMWKYCIGMKYKWKU?AISKWM[KUKYEKCIMYKUK[CCGSKUM[ISKYKWAAKWKWKWKWKYISAAKWKYKYKUAAKWIWMYISMYAEGOKYO[IUMYIUKWKWIUCEKWKWKWKWKYKWKYKUKWACISKYKUKYKWAAKWIUM[Wm@ACIUKUKWM[IUKWKYISA?IUKWKUISCIKYKWKUKWKWIUKUIWKWKUM[IQEMEKKWGOCEAEKWIQCIGQYq@IUMYKYKWMYEM?AKUCIMWIUKUEOEIKWKWKYEKAAIUEKEKEIKYGMCIAAGQMYKWKWGOO_@ISACGQO]KYIQGSO_@KWUi@M]ISSg@M[IU?AKUGOSg@a@cASg@e@kA[w@KWIQWo@KU[s@Wm@AAKUg@eAm@oAs@uAOYWc@MWU]MUGKMS_@m@w@mACEwBgDAA_@o@i@y@AAgAgBGIm@aAk@w@OUOUS[IMOU_@m@MQMUOWOSMUOSOUCEIOQWi@{@ACOUOWOSMS"
                     },
                     "start_location" : {
                        "lat" : 39.0295684,
                        "lng" : -76.947778
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.2 mi",
                        "value" : 5175
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 178
                     },
                     "end_location" : {
                        "lat" : 39.2502325,
                        "lng" : -76.67899299999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e at the fork to stay on \u003cb\u003eI-95 N\u003c/b\u003e",
                     "maneuver" : "fork-left",
                     "polyline" : {
                        "points" : "}iknFh}gsMOUOUOWOUOUMSCEKQKQCCMSEIWa@OUOU_@k@OUMUOSKQCCOWMSOWOUa@o@i@{@QWOUMSOUMSACMQOSAAOSOUQSOSQSACMMOSMMKKOQQOACMMQQQQSQAAOMOOSQOMAAQMSQSOe@[WSMIOKCA[SKGSMkC}AQKSKSMy@e@QMSKe@YSKQMCAOISMQKSKSMy@e@QKQMSKsEmCg@YSMSMQKSKe@YSMOIUMQKy@g@QKSMg@YQKSMQMSMUMQMQKSOQKe@]QMQOSMSQOMQOQMQOQOOOSQQOOOSQOOQQOOUWm@m@a@e@a@e@OSQSMQOSECIMQS]e@]g@OSOUMQAAKQOUCEKMMUIOCEk@_AQ[KSEGKUOYOYOYKUKWO[GMACe@gAIOIUO[IWKSGQKWSi@CGK[KYGQGQGQEQK[ACOi@GWAEI]Ic@I_@ESCSG_@CYEUCYAMCYAO?CCSAUAYCc@?OAM?IAc@A[Ay@AY?a@AUAa@?YEsAA[AQAIA[C[K_BEe@E_@Iy@CUE_@EYEWGa@EYKo@Os@EWI[GWI]EUACI[Qo@I[IWIWIYGSK[IUKYISUk@CEEKEKKUMYIQQ_@Wg@MUMWA?g@_AQYOYKOMSMSMWm@cAGICEMU[g@g@y@?AACAAS][i@]k@OUKS_@o@MSi@_A[i@S[o@iAEE[i@OYw@qAYg@KQEIWa@MWOWMSWi@]m@MWYi@GMCEO]IQ[o@MWe@cAKUKSGOEIYq@ISKUKWKWMYM[Si@KWGOIQUo@EMa@aAYu@Uk@KYKWKWO]Sg@KYIUKWKYc@eAIWQc@KWIUCEIUKWKUKUKYKSOWEI?AMUMUMSOUMSCEIM[a@QUSW"
                     },
                     "start_location" : {
                        "lat" : 39.2209497,
                        "lng" : -76.7229289
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "26.5 mi",
                        "value" : 42596
                     },
                     "duration" : {
                        "text" : "26 mins",
                        "value" : 1570
                     },
                     "end_location" : {
                        "lat" : 39.3586959,
                        "lng" : -76.5039767
                     },
                     "html_instructions" : "Take exit \u003cb\u003e49B\u003c/b\u003e on the \u003cb\u003eleft\u003c/b\u003e to merge onto \u003cb\u003eI-695 N\u003c/b\u003e",
                     "maneuver" : "ramp-left",
                     "polyline" : {
                        "points" : "}`qnFtj_sM[CA?AA]WWQSMQKKEIEICQGMEQEKCCAEAIAGAMCIAMAOAE?G?EAG?O?C?I@K?E?G?E@I?I@I@I@I@A@K@ODIBQDKDQFKDGBC@]RSLMHIFQPA@QNOREBGJGHEDILMRMTKREHABKVGNENCFABGRENCNGTEREX?BCTCNAHAH?JAFAZA\\A`@@X?VDx@?BGRHx@JlALvAB\\@N@h@@N?P?N?R?J?L?TAX?B?TARAF?HCXAREb@Gd@E`@CNCLGVERCLCh@m@bCe@nBELk@`CG\\Qv@Q|@CNGXGXSlAGZABEXKj@Y|AS|@I^CNCLKp@Mv@WvAKr@Mv@CLI`@Mv@AHCPUpAKr@Q`AAJUpASlAG\\Mt@Ot@Kn@WtACPUlAOp@K`@Op@GX[dA[hAIVIVUj@Sn@Wn@Uj@Wj@IPMZWl@Yl@ADa@|@EJSd@]v@c@~@KV[t@i@lAWj@u@bBmApCa@~@a@|@Wl@Yl@EJ]v@y@dBk@pAk@pA_@x@_@z@IP_AvBa@z@}AjD]t@m@nA_@t@Yl@CFGLINKTMTWj@MXKRMVKRGL_@x@[l@OZIPu@|AIPu@~AIPMVQ^IPKROXIRMTYl@MVYl@KTKPMXMXGHQ`@[n@Wf@KVMVa@|@QZYj@KVWh@_@v@INKVg@bACDUh@MRKVMVKTg@bA]t@S`@IRKTS^IPKVMVKRWl@MVMVS`@CHMTEHELMRKTMTYj@OVMTWb@c@n@MRGHEFKLQTOPMNSRSPOPKHEBQPOJGDKFSNOJULSLSJSHQHQH[LSFSFGBMDQDUFSFWFUFe@JSDg@La@JiARm@NSDYFMDWFSDWFi@Ji@LUDSDUFSDWDC@QD]HIBQDa@LQDMDSH]LKDSJQHSLSJQLQJSNKHEBGFOLKJQPQPGFGHOPOPMPQTU\\KPSZS^GLS`@IROXO^Q`@MZMTKVIPi@jAc@`AYn@Wj@Wl@iAfCOZMXQ^CHILg@hAg@fA?@o@vAMXe@bAc@`AINO`@g@jAm@rAs@|Ay@hB[t@OXe@fASb@]t@Yh@KT]n@[h@EHMPW`@CFc@n@sAhBg@j@UXQPMN[ZYX_@\\MJ[ZQNIFQLIFg@\\UNKHID]T]RoAr@s@\\CBUJYLWJA@]NYJWJm@RUHs@Ri@LSDQDWFWFa@H}@Lg@HI?]Di@Dw@Fg@BuBNcBJM@cAFqHf@kHb@]Bc@D[@s@DiAHo@DW@Q@UBu@DO@S@E@K?O@SB]@a@Di@BkAHmAHkBJa@D_AFgDT_AFQ@aAFyAJU@uAJm@DaCNeBLc@B]BW@m@DcEVS@i@DgBJiBLaBJsBJgDNS@w@BqAD{ADE@_BBg@@[@}@@K?K?m@@{@?aA@mC?_CAeA@[?sC?K?I?cA?s@AM?a@?iA?i@?Q@oC?wC?k@?{@?g@?{@?s@?S?iAAg@?g@?a@?{@?cA?kACI?y@?eB?kB?}@?aA?i@?{BAA?sA@{B?C?_@?eDA_A@y@?c@?}@?c@?iCAk@?G?sA?S?o@?]?w@?iA?w@?aA?A?aA?uE?W?e@?A?k@AcA?I?K?c@?E?o@?e@?I?K?gB@u@A[@C?g@?iBAi@?i@@o@?{@?Q?kB@W?S@q@?U@{@@I?cA@c@@oADm@@i@@A?aBHC?g@Ba@@a@By@BcBHm@Bc@BE?S@E?I@[@U@U@U@S@W@U@U@U@S@U@i@BU@_DN{AFu@BS@W@U@S@a@BiBHcBFg@BW@Q@S@m@BS@U@M@mBHI@aADI?Q@S@W@I?I@U@U@G?K@U@S@U@sAFcBFE?wAFgBHw@DI?U@G?M@S@I@K?U@E?O@U@U@O@E?U@U@U@U@U@U@U@O@C?W@G?K@U@U@U@U@U@M?q@DU@U@U@S@U@U@W@U@U@S@U@U@S@U@E?O@U@U@W@U@S@W@U@U@S@U@q@Bo@B_@BS@K?I@U@Q@o@BUBA?S@U@M@G@U@UB[BM@U@UBK@I@U@SBQB[BUBQBA?UBUDUBSBWBE@OBSBUBUDUBE@MBUBUDSDy@NIDmATUDkAVi@JSDm@LSDUFaARSDWFi@JQDWDc@HC@m@HC?OBSB_@BO@U@_@Bk@?c@?S?YAU?SAi@Em@IUCUEYEe@KUGOECAWIKC[KUISIQGAAUIQIw@]IEQGm@WMGg@UUKUIWMk@Wk@UgBw@GC_Bq@?Ag@USIUKSIEAMGg@Ui@Ug@SKGEAi@UQIAASISIi@Wg@QyBaACAaBs@QISIUKQISISIUKQISKWKOIGEKGe@WAAQMOMQMYW_@_@}@kAMQMSMSAAKSMYKSKUGOCGIUKWK[IWIYACGSGUI[IWK[GWIWIWIYIYI[IUIWI[IYGUI[IU]iAIYKYIWIS?AKYKUACSk@_@w@Ue@MWIQOYOUKSOUMUOSOUMQMQQUOSCCKMOQOQQSOO]]EG_@_@g@i@MK]_@QSQOOQGGk@m@c@e@MMQQOQQSOQMOAAMOQUOSMQQSMUOQMUOSMSMSMUMUOUKUMSMUKWMUKUKWMUKWKUKWKWAGGOKWKWGQAEWo@IWEOCGKYIWIWKYIWIYAEGQIWIYIWIYGYIWIYIYGYIYGWI[YoAOq@G[GUGYOs@GYG]EWGYEYG[GYEYE[EWAAE[EYG[EYE[EYEYC[A?C[EYE[E[CYCMAMMoAE]E[CW?AC[C[CYCY?AC[C[C[C[AYAAA[CYC[A[AS?GC[A[A[C[A[?IAQA[A[C[?WACA[?[A]AYAI?QA[A[A[A]AYA]A]AYAY?AA[A[A[A[A[A[AU?EA[A[A[A[A[C[A[A]CYA[C[A[C[C[?CCWKoAAS?CCWCYEYCYCYAIAME[CWEYCY?AEWCYEYEYEY?AIs@Ic@Ga@G[CSGYEUG[EYKg@Kc@I]Ic@CGGWKa@GWOi@K_@u@kCA?UaASu@Sm@g@gBWy@W{@Qo@Us@Og@K_@EMWaASs@Om@Oi@I[GWEWIYCICMGYGWEWGWEWGYES?CGWCOG_@EWKo@EYEWEYE[CSE]Ik@Is@Gi@Gg@Gw@KoAIaAG{@Ew@Eq@Ck@Cq@EkACm@?GAs@As@Au@?y@AM?_@?u@As@AkA?y@Au@?i@Ai@?gAAm@?c@As@A{@?E?g@Ag@?i@Ag@Ci@A[A]C]AU?AEk@CYCYC]CUGk@Ga@E[Kq@G]EUGa@CMg@}BI[Ma@GOIYIWAGGQIUKYGQCGIWKWKUKYAAKSKWKUMUMWCEIOMUMSEKGKMSMSOSMUS[IMMSMUEGe@u@i@q@[g@GKwA}BOSMUe@q@S_@QUKSQWMQIOCCOWi@{@m@aAe@u@i@y@GKk@}@m@_Ag@w@QYOUAEi@y@MQQYGICEs@kAq@eAWa@Yc@Wa@k@{@?AW_@g@y@i@{@EIWa@KQGKEIOUKSMWYm@Ui@AAKWg@oAGOK[M_@EMIYIYIYEOK_@Os@GWG[GYQaACMG[YwACOGYG[GSAEGYGYEOCIIYY}@CKUm@Sk@IS_@w@MUKUMSKQCGMSMUMQOSMUOSW]YYaAiAw@y@IMi@k@u@y@qB}Bg@k@SUMOKMSSGIu@{@OQOOCG]_@SUQQIKAC{@aAmAoA_@c@a@c@IIu@y@_@a@SSSUIISUY[e@i@i@k@c@c@_@c@g@i@WWQSQQkAqAm@o@OQEEw@}@m@q@eAoAu@_ACEGIMOu@_A[e@g@s@e@s@OUYe@[e@Yg@e@y@o@gAISm@iAIQo@qAa@{@e@eASe@Qa@AAGOSe@a@eAOa@CGOa@Ws@Qi@M[K[AGYy@GUY{@IWEQGQGWSq@Sy@IYOk@Ia@GWMk@Ia@GYCOG[E[G]E[E[CQGi@CMEc@AQIcAEa@AQE{@Eu@EeAAo@?IA_A?gA?Y?w@@Q?IBw@@[Bg@DaAFy@?APmBLkAHk@DYD[Fc@P{AFc@RyAHq@Hg@PyALcAL_AL_ANiAh@cENmA\\qCNkAf@yDTeBZ}BHm@Fc@D[Fa@BOF]F[He@Ji@Ns@Ha@Lq@XoADMPs@Pw@H[Nk@H[J]Ng@J]^uAb@uArAoE~@{CzBmHjAwDfEkNn@wB^kA`AaDNe@J[FYPi@DQJ]H_@Ja@Ny@Ha@BQF]BUDa@D]D_@Di@@WBq@@U@W?M@U?i@?o@?e@Ac@A]Cm@Ei@C_@Ei@CUCWGe@S_B_@mC]gC]gCYaCKcAGu@Ca@Ci@CWA]Ae@Ac@Aa@A_@?S?O?s@?e@@u@@u@@a@D{@Ba@N}BJmBb@_HLsBLwBBUHyAVyDJoBDs@DeAD{@@_@?a@@_@@Q?a@?_@@[?a@?U?KCwBGgCCu@C]C]Ca@Ei@G{@Gs@Io@Ec@CS[{BUsAM_AEQOgAU_BAEE]E[E]AICQE_@C[Ea@CYC]C[C]A_@C[A_@C[A]A]A[?AA]?]A[?[?A?]?]?_@?]?]@K?Q?]@]@[@]@]@]Bc@@UB]@[B[B[B[B[DYB]D[BY@GBSD[D]DYD[FYD[F[F[FYFYDYHYF[FWHYDO@IHYFWHWFS@EJYHWHWFSL[HWJWJWHWJUJUJWJULUJUJW@?JULULULULULULSNULUHMDELSLULSNULUNSLSNWBCHO\\i@PWbAaBzAaCVc@T]\\k@LS\\i@\\k@x@qAR[z@sAHM\\k@NULSLS\\g@Zi@b@q@z@wAd@s@b@s@FILUNSLULSNUHO\\i@v@mADGLUNULSVa@pD{FZi@`@o@r@gAv@gA`@q@`@q@Zg@HO`@o@h@}@DGn@gAn@eA^u@BEDKr@gBBGHUPk@HYJ_@DSBQF[FWFa@DWF_@D]BYDk@Fs@@O@o@@_@@m@?y@Ai@AQ?IASAc@C_@AUAQEg@Gi@Ea@Iq@a@_DM_AMeAK{@Ee@AEAUEg@ASA]Co@Ag@?_@?_@?W?W?Q@I?I@]?MBY@a@Di@H{@Da@@CHk@Ly@Hc@DUJa@BKLg@Rs@Nc@HUf@oAJWBKfAiCl@{Ab@aATk@FQt@cBd@kAf@kA`B}DfAgCx@kBJUFMLWd@cAb@_A`@{@Tc@P_@l@gATe@FO|@aBh@cAl@gAxDiHx@{AhC{ETc@Vc@z@_BP_@P[LSLUNYHQLUh@aALULWXk@FOP]Re@L[DKLYFSFOBIHUFS@CFUHWFUHW?AFUFUHWNq@DMJ_@FYNm@No@Pq@VcAPq@No@No@Pm@DWHW`@_BBOZoAn@gCz@mDhAkEPs@Ru@VaAHUJ]Ja@FSf@gBL_@b@{A^iAX{@d@wAPk@Vs@Ts@To@Pc@p@iB`AcCJWTm@l@wAN]LWJWJULWJWJUZo@Xg@JULSLUJS@ALSNUJQ^k@^i@Zc@PUJMf@o@Z_@r@y@`@a@h@k@FGPQPQNOPOb@a@n@i@@?n@g@LKNMTOPMRMPMPMd@Yb@YHEXQXOTMRKHCHEh@WTKHEHCh@UXMHC^O`@ORG^Mp@Sf@OVGREf@MNEZGj@MTERGZGNCRGXGh@Kf@Kj@MTETEREj@MTEJClAWv@QFAz@S|@UXITIRGDAb@ORIRIRGPIXMHC\\ORK^SNIRKf@Wj@_@l@_@FEJKNIPMPOROPMPQPMPOPQPONOPQPQNQPQPQNQNSNQNQNSHKFGLSJM`AwAr@kAn@eAj@aALUNSf@{@\\m@LULQd@y@R]\\k@LS`@q@HMZg@NULSNSNSNSLSJKBEPSPSFKJKJKRU\\]PQJKDEPQNOFEHGPQPMPORODEJGPMPMPMNIVSd@YRMv@g@TQPKf@[ROPKlAy@NIn@c@n@a@n@c@ZS\\Sd@[^WXQb@[tBuAn@a@j@a@PKx@i@\\U\\Uf@]NKx@i@DCl@a@NMXSb@Yf@]PMDEp@e@"
                     },
                     "start_location" : {
                        "lat" : 39.2502325,
                        "lng" : -76.67899299999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "25.5 mi",
                        "value" : 41007
                     },
                     "duration" : {
                        "text" : "23 mins",
                        "value" : 1392
                     },
                     "end_location" : {
                        "lat" : 39.5670465,
                        "lng" : -76.1412686
                     },
                     "html_instructions" : "Take exit \u003cb\u003e33\u003c/b\u003e to merge onto \u003cb\u003eI-95 N\u003c/b\u003e toward \u003cb\u003eNew York\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "{ffoFzd}qMVD@?nA{@VSVOXUp@e@TQDCTOd@_@`@YXULKtAeA^Yd@a@\\YLQnAeAZYHE~@y@TUdA}@n@k@`@]ZY`@[PMp@i@HGl@c@FENMHGDCDCJKJIFIFEHIJMFGDE@CHIJODEFKFKHMDIHMBI@AFKFMFODKDKDKDMHSFUBI@EDQFSFYDSBQD[@K@G@KBO?ID[Be@?C@I?O@[@Q?Y?S?U?OAQAa@A[?GAMAOAQCOC[EYE[?CEQEUCSIYGUCMEMI[Oc@KUIUAAISOYOUQ]]k@EIGKKOQYMUEGMUIOIOq@kAKSQ[[k@Uc@O[K]S]Q_@IQAAYo@EGGMWi@c@aAWg@Ym@KWMUKUMWKUMW?AKQMWKUMWKUCGIOKUMWKUKWMUKWKU]y@CGKUQc@[q@Ug@CGCEEOGMEI?AA?SAUk@Wo@Wm@Wo@Wo@o@}AeAoCWm@KWKWKWIQACKYKUMWKUAEIQKWKUGOCGMWKUIUc@_A]u@MUKUMUACISWe@EKKQYk@KSMWMUGKEIKUMUGKEIMUMUKU]k@MSMWMSMUGKEIMSMUMUGIEKMSMUMUMUIKCGMUMUMUMUEIGKMUKUMUMUMUGMCIMUMUKUMUKUMWKUGMCIMUKWMUKWKUIQAEMUKWKWKUKWKWKWKUKWWo@KUKWKWKWKWKWIUKWKWKWKUKWKWKWEIEMKYwAkDcCiGi@qAc@eAOc@]{@KWMWKWIUMYUm@Wo@Wm@c@gAo@_BWm@KW[w@Qg@_A{BGQWo@c@gAa@eAKSWs@Yo@a@eAc@gAc@gAWm@MYIUWo@m@}AYo@Qe@EIWm@KWKWMWKUKUMWKUMUQ]Uc@MWMUUc@Uc@CEEIMSWe@MSW_@e@u@e@q@a@i@]g@o@w@W[gAwAUY{@gAAC_AgAeAoAKOeAkA?As@w@y@_AIKY]WWq@u@sAyAGGe@g@UWaBeBq@s@CEqAuAgAkAqAwAoBuBIKQQ_@a@KK}@aAe@g@q@u@qBuBMQKKGKyA_Bw@y@w@y@a@c@IISUsBwBUWaBcBWYWY[Yg@e@u@w@s@u@MOuAwAOOc@e@_@_@QSi@i@[]Y[w@y@[[YYe@g@WWIIQQOQSQQSIGIKq@q@QQ[]u@s@gAiAa@c@SQMOQQAAMMECGISSIIYYQQOQOOMMMMYYi@i@q@q@i@i@}@{@e@e@e@c@[YGEy@w@WSw@q@QOWUa@]_@[IGSQ]YGGg@a@SQe@_@[WKKMIUQUO?A]YcAy@q@k@]Y]YGGiCwBSQWQi@e@_@[WSe@a@CCo@k@g@e@_@]UUWWMMWWY[[]i@m@EGY]IKOSW[W[[c@AAQWOSa@m@SYKQIMW_@U]IOGGi@y@EIIMMSMQOUOUk@{@OUMSS[MSc@o@EGk@{@g@u@AAu@iAMSU]IIi@y@g@u@Ya@MQACMQ[g@[c@MQACGIOUW]IMGM[c@OUg@u@q@cA_@i@OS]i@KMIMCEQW_@k@i@w@a@k@KOYc@o@_A_@i@_@k@i@w@i@w@S]MO[c@QSW_@S[IMU[_@k@[e@SY[e@[e@m@}@_@i@g@u@m@}@Yc@q@aA_@i@QWi@y@k@w@W_@EEMQSWMQUWSUKOWYKKQQSSUUKISSSQQOQOSQQOQMWSQMOKWQSMSMQMYQIEECOICAGEIEYQa@SSMIEaB}@kBaAIGUMQICCGEOGa@WWMe@YSIOKWMSKSKSMMG]Sg@Ww@e@UOQMKG[W[Uc@]GIQOGG[[AAUWOOOQQSACMMGIGIOQOSEGGKOSMUGIGIMUMSMS?AMUMUMUKUYo@KUKWKWIWKWKWIYIWKWGWIUACIWIYKYAIGOIYIWGWIW?AKWGYK[IUIWI[IYIUSq@IYIUACIYGWIWIYIYSm@IWIYIYIWIWIYIYIYKWI[Qm@KYIWIYIYK[GWKWI[CEEQSo@KYK[So@KWIYKWIYIUKYKWIWKWKWa@gAKYKUIWWo@KWKWMWIUMYKUKUKWMWKWKUKWMWGMg@iAQ_@IOSa@IOUe@[m@Ue@]o@Sa@c@u@Q]e@y@]k@g@}@[i@[g@a@m@Ye@_@k@]k@}@uAo@aAcA}Ag@w@S]OSk@}@c@o@CE_@k@]i@IOA?g@w@IOc@q@SYU_@]i@e@s@g@w@[e@GKg@u@QY]g@k@_Ag@w@GIy@oAYc@EG{@qA{@sAk@}@m@_A]i@SY[e@[i@{@qAWa@OWOS[g@EEOW[g@_@k@m@}@ACYa@_@m@GKQUWc@[g@S[GIEGOWe@s@[g@[g@OUEGCCS[MSU]W_@m@_A?Ae@u@GGMUm@}@OUi@y@[g@[e@}@uAk@}@IMOUQY_@k@[g@MSO[KQGICGOYKSMY_@w@ACUg@Sg@Uk@EKCICEEMISQe@K]CKEMQk@GUIWGUGSMk@Qs@AEOo@CSESOq@Im@Mq@AECUGc@CQCWEUC[AKEWAMAMEg@EYASGq@AYCYA[C[AWA_@CaAAa@Aa@AW?Y?E?w@?a@Aa@@eE?]?M?_@?o@@cE?kD?eB?q@@{@?_C@cE@mF@_J@uC@sA?w@?Q@wI@yA?w@?kC@sA?A?iCFcD?g@?_@?s@?I@sB?O?gA?q@?[?m@?CA}@A_@AO?KCw@A_@A]Eo@?EEo@K{AI}@E[C]AKIm@Ky@Ii@AKGYE[ScAKm@GYMk@ACG[Mc@Oo@CKMc@K_@Me@W{@?A[eAIYSu@GQ[iAg@gBGUGSEMCKCGOk@GSUy@GW{@wCYcAGWMc@Y_AmAmE}@_Dy@yCK]GQIYGWIUESIW?ACEAGCGI[K_@W}@Ma@AG]kAUw@_@wAc@{Aa@yAMa@[iA]iA_@kAk@gBOi@GMIYQg@IUM]Wu@ACUm@Si@Si@KWM]Qa@IUMYKWISKWMWc@gAYo@O]e@eAEI}@qBi@iAGMs@}Aq@}AMUg@iAyB}EiAeCMYs@}Aa@}@Wi@M[a@{@gBwDa@_AKSMYYm@Wm@k@uAc@eAq@aBWq@y@oBq@eBQc@Si@ACe@mAM[CGWs@Oa@Se@a@iA}@eCm@}Ae@oAu@wBYy@Oa@Yw@Us@Sk@Oe@M_@EMOa@IYu@{BSi@Sq@Wu@aBiF[cA[aAIYa@uA]gAg@eBGUK]Oi@IWGUWw@Oi@Oi@CG[kAa@wACGYcA?AUw@GWIUEOAGMa@GSw@oCI]EMGSW{@I[[gAa@yA_@qA]kASs@k@sBMe@K[EQK_@EMCI]oAOg@Oi@Oi@IUAECKOg@?AOi@Qk@Ok@[gAAEK[CMKYOk@EMc@{AK_@Uy@Ss@EOOg@_@sAK]CKEOAAGUK_@Ss@Oi@Oi@CICICGCMGQCISs@Mc@W_Ay@uCOg@Ka@u@eCYcAI[K[W}@Og@Uu@]eA_@oAO_@GQK[Ww@]}@Qg@c@kAYu@a@gAQc@Qg@KWGOM]KWO_@Yq@[w@s@yAq@sAc@y@Ua@e@y@S]}@yA]g@]g@e@o@_@g@cAqAMOa@g@Y[g@m@o@q@W[qB{BuA}AGGuA_Bu@y@u@{@GG}AoBi@s@_@k@EG_@k@g@}@KSi@aASa@MYIOGMWm@KUAEUi@ACg@sAOa@O]Sk@M[Yy@Sg@K[i@yACE[{@EMQg@Qa@y@{ByA}DAEc@kA[{@Yq@_@gASg@Ma@KYc@gAAG]_AGK]_Aw@wBISMa@k@{AWs@]cAKYIWIYCEYaASs@Sq@?AIWGYCIUaAGSI_@G[Os@EQIa@G[Ms@CMKg@EYG[EYCKCOMs@E[GYAEIk@ACMu@Mu@ESAGKs@[iBMu@AAEYGYk@gD[cBEYKe@Ki@Ke@Qw@S}@Qs@IYQs@Qq@Og@Mc@c@{AMa@KYIWIWIWKY?AKUIWIWKWKYa@cAu@iBc@_AM[i@iAe@cACCm@kAe@}@OWa@q@EGWe@OUe@u@e@s@k@{@m@{@m@w@GI}@iA_@e@UWo@u@WYOQcAcAo@o@g@e@eAaAg@e@i@i@SQq@u@AAm@s@QU]c@MQ]k@_@m@O[Uc@i@gAMWUg@k@iAaAoB_@w@k@kAO]Ue@c@{@i@kAg@cACEKUSc@e@_Ae@aACEUg@]s@Sa@Uc@Sa@ISs@uAa@w@?Ae@y@OYW_@IOOSCEMQMQMOW]Y]QQMOk@m@e@c@YWQOc@]MKk@a@w@g@m@a@w@i@q@e@YSc@][[YWa@c@OSMQc@i@EIMSIKQ[[k@Uc@MYMYKWWs@Wy@Ww@YmAU}@g@sBU_A]uAWeAg@sB?CQq@Sy@YoAQq@Sw@EUMe@Ka@GUWiAKa@Oi@AEMc@AEc@}AIWAEQk@Oa@Oe@AEKYCGSi@Si@GQQe@AASe@IUQ_@[s@O[Wi@Wi@OWg@aAKQ{@wA[g@]g@AAU]e@m@U[GKe@k@AAg@m@AA{@cAs@w@_@_@IKi@k@o@s@[]CA_@c@s@u@m@o@_AcAa@c@Y[q@u@c@e@_@a@a@e@cAgAcAeAAAcAgAAA}@aAEGm@q@QQcAgAe@g@[]UUa@c@QSm@q@AAa@a@QS]_@Y[KMq@u@IIa@a@KKUYSSi@k@k@o@gAkA_AcACC]_@_@a@AAq@u@i@k@WYWWACUU]]g@k@m@o@g@k@SUo@q@a@a@oAuAa@c@aDkDWY}@aAuAyAw@{@[]i@k@yA}AWWGI]_@WYe@g@}@aAQSMMuA{AQQOQQQMOOQQQQQY[i@m@SUEEGGIIWYOSOQOSMQOSOUOSMSOUKSOWMSMUKUMUMWQa@Q_@K[c@iA_@gAGSK[IYKWqAgESq@{A{EUs@u@}BSq@Uw@ISCKc@uAAEQg@AG_@iAi@eB{@oCUs@IWg@aBK[So@IWIYUq@IWIYIWK[_@gA?AUm@Uq@M]ACQe@KUKYKWKUEISe@KU[o@CKWg@k@gAMUMW[m@_@m@_@o@GMQUKQCGMQ]i@_@i@_@e@MSOSa@g@_@e@OQMOQUc@e@]a@GGGGSSQQCCKKa@a@u@s@c@_@QQc@]e@_@QMw@m@CAc@[OKSO_@WWOg@[SKEEMGQKSMQKMGEC[Os@_@sBgA}@e@SKQKQIWOmAo@g@Wg@W_Ag@MGKGGCIEQK]QUMw@a@[OSMa@S_Ag@_@S}@e@QK_@SWOWQGC[Ug@[_@W{@o@UOUQc@]o@i@}@y@e@c@][Y[w@y@UUEG[]UWu@}@_@e@g@m@k@w@w@cAkAyAMQKOY_@]c@SWy@eAUY{@iASWe@m@i@q@u@aAU[Y_@[a@[_@_@g@s@}@Y_@s@_As@}@s@_A[_@a@k@{@gAc@i@g@o@u@aA_AmAaAoAm@y@m@u@[c@_@e@W]eAyAW]y@mAQUYe@]g@Yc@]i@s@gAIMWa@ACAAu@kAYe@MQUa@Ya@e@u@c@q@Wc@eAaB}@wAAAw@mAo@cA]k@KOCCw@oAWa@uAwBWa@{@sAu@kAm@_Ao@eAKOWa@U_@ACc@o@Ye@Wa@Wa@Wa@k@}@g@y@AAc@q@e@u@]g@k@}@W]e@q@i@s@[_@Y_@a@e@[_@m@o@m@q@q@q@_@]YWm@i@k@g@g@c@yAmAmAcAy@q@KImB}A"
                     },
                     "start_location" : {
                        "lat" : 39.3586959,
                        "lng" : -76.5039767
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 mi",
                        "value" : 619
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 42
                     },
                     "end_location" : {
                        "lat" : 39.5704674,
                        "lng" : -76.13584809999999
                     },
                     "html_instructions" : "Take exit \u003cb\u003e89\u003c/b\u003e for \u003cb\u003eMD-155 W\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "a}npF|ivoMC][Yy@s@g@g@SSWWUUCE]_@Yc@S[S_@We@Sa@GOIQIUCIQc@M]ACIUESACSs@I[CIIa@Ki@E]O{@CUESGQGMSa@GMGIEGGIKIWKKKWQCA]U"
                     },
                     "start_location" : {
                        "lat" : 39.5670465,
                        "lng" : -76.1412686
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.9 mi",
                        "value" : 4652
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 230
                     },
                     "end_location" : {
                        "lat" : 39.5767591,
                        "lng" : -76.18684089999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMD-155 W\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mropF`huoMWr@iBfF]|@IVM^Ur@u@xBk@|AgA|C[|@m@fB{@bCCL]bAOd@ELYbAOj@a@zAYlAEJKh@U~@I`@AFUnACFSlACNMt@UzAQjAGd@ADE^Kz@SfBOjBIv@Ep@Ep@IlAEr@?BEl@A^ANEzAAFAd@An@CdAAr@?NAn@?l@?F?d@?h@?D?l@?b@@x@@l@?^D`CDzA@XFvADr@Dv@HnAJpAFz@N~AHv@^bDZfCZbC?DFf@Hh@VpBLdAD^BJb@pDBTJx@VrBNnADXHl@BPDXJ|@PzAVlBrA|KHj@?@Fj@Ff@NpAHv@Dn@LzA@VDl@@TBVBl@?FD~ADnA?@@`B@tAA~A?n@Ap@ElAGfBG~AIfAC\\El@Gp@K~@K|@ALOnAYlBQ`AIf@Kd@Or@CLMl@Oj@Or@]lAe@bBe@tAQf@O`@CD[|@_CzFCFcAbCeAjCq@jBEJo@fBADUr@Mb@a@pASx@m@~B"
                     },
                     "start_location" : {
                        "lat" : 39.5704674,
                        "lng" : -76.13584809999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "5.1 mi",
                        "value" : 8286
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 452
                     },
                     "end_location" : {
                        "lat" : 39.6456847,
                        "lng" : -76.2041232
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eMD-161 N\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wyppFvf_pM]Sa@Se@U[MOGOGSGuA[mDy@]Ig@K]IEAa@K]I_AUs@OUGA?kBc@_AUOEgAWKCsA[mAYa@KA?k@MkAUw@Ic@CA?a@AKAU?Q?_@?g@@a@@iA@s@@wAB{@Bw@Dg@BuAJc@Dk@Fo@Hu@LcAP}@PcATQFKBUJA?_@La@Nc@P_Bj@a@Na@NOFQF_@Na@PQFOFa@NeBn@UHm@RIDWHu@XOFOFQHOFMDQJKDQJC@MHOJMHQLIHSNCDSRCB[^Y\\W`@EDQZIH}@tAi@z@c@l@ABY^YXCBc@`@o@h@}@p@IFSNeAv@]VKHQN]VKFq@h@EDw@j@OJMHMH[P]L[HGBWDy@J_@D]DkBPU@MBa@DU@MBs@FS@SBO@E@M@s@Fa@D_@DYBG?i@Fc@DWBI@A?]BC@c@Ds@LQDYJGB[NCBKFSNW`@MPIPUb@Ub@Ud@Ub@Ud@Ub@Ub@Ud@Ub@Wb@OZCHIN[j@EHUd@Ub@KRKNQ\\CDW`@KNe@r@s@`AY^UXC@MLUTQN_@V_@TEBSLWJMHKBw@\\MFa@Nc@PWJ[JSD[HYFa@Hm@HQ@E@kAFI@c@BC?_@Ba@@A?c@BU@M@y@FK@a@@A@]BE?WBK@c@Fc@DG@YBc@FSBOBA?_@Fc@H]Hg@Jw@Na@Ha@HuAZSDc@Ha@HOBC@O@c@FA@M@Q@QBG@I?YBe@Fa@DI@WDIBIBEBKDIFIDOLSTaAfAc@h@_AhAKNOLQNKFC@MFGBGBC?SDKBA?E@M?M?A?OASAQE[KUMYQa@UCAOKm@_@s@e@s@a@WOSK[QWMWICAWIWE]GYEKACAWCa@AUAg@?e@?w@@]?o@?Y@O@I?M@K@I?MB]DE@OBC@MBKBG@YHG@A@e@L}@Xa@Jy@VC@A?_@LMBQFC?a@L_@Ja@JC@QDMDA?_@LA?a@J?@a@JMDUHQFo@XUJA?]PA@MHMHA@OJGB_@PE@C?QDG@E?A?SBO@S@OBS@A?K@c@Da@BA?YBI@]BE?a@DSBO@c@D[B_@Dg@Fa@Dc@DG@[Bm@FG?QBm@FUBM@]FC@OBSFE@UHE@MFQHQJQJEBMHMJIDKHu@f@o@^ULSJ[NE@[NE@[Le@Pg@N]J]JWDODS@UBU?E?OCI?ICG?GCIAYIECQISI]O_@OICc@QkAe@a@OKEYMGASKKESG]OQGME]MWIIE_@Mg@Sc@Mk@Q_@KYGSESGe@M_@KK?I?Q?C?Q@k@BeBLG@M@e@@m@@A?o@?i@@K?mB@w@@wB@g@?a@@_@?E?Y?I?a@@[@I?SBO@YDMDQFKBSFg@RUJSHk@b@[TQP]XYT"
                     },
                     "start_location" : {
                        "lat" : 39.5767591,
                        "lng" : -76.18684089999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 294
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 34
                     },
                     "end_location" : {
                        "lat" : 39.6482247,
                        "lng" : -76.2033761
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eMD-623\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "oh~pFvrbpMYSKIIGQKCACCIEGCCACAA?CAECMCGAGCQCSAOAEAEAA?EAGAKCECOESEAAOEQCKAMCA?KAE?KAOAOAW?g@Ag@@"
                     },
                     "start_location" : {
                        "lat" : 39.6456847,
                        "lng" : -76.2041232
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "11.8 mi",
                        "value" : 19066
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 916
                     },
                     "end_location" : {
                        "lat" : 39.7307361,
                        "lng" : -76.0257876
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eUS-1 N\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Pennsylvania\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kx~pFbnbpMg@eCw@gE{@aEw@kDa@cBAE?AAAEKa@cBeBsIAG]aBYwAWqAUkA_@aBYwAo@_DGYg@aCKk@YuAMk@ESSaAMk@Mi@Ka@YoAWgACMg@cCKi@YwAMk@Ki@UgAEOe@}B?CKg@GUm@uCk@oCUiAw@yDQ{@ESWqAKk@Kk@Kk@G_@GYO}@[sBC]Aa@?A?CEm@Ew@ASCk@EgB?C?cA?Y?}A@cA?{AAg@?OAO?IAICSAOEWEYIWEQEGEMWi@Yc@OQEEAAG@A?MMGGIE]SMIQGa@Q{CoAqAm@s@[GCWMa@QaBw@a@QaBu@mD_BiGoCaAc@oAi@wBaAkIsDWMGCeFcCkB{@WMaAe@KE{@W]EUAO?A?u@Dc@BUFMBQDk@L}@J_@D[@Q@c@?YAe@Co@Gk@Ig@My@W[MWMCA_@Qa@Wi@_@_@Ye@c@_@_@y@iA{AaCgAgBs@kAaAaBo@aA]i@S[w@qAmAsB_BgCo@cAo@eAi@_A[o@Ue@Uq@m@_Bi@{Ae@oAg@yAAAYy@Qk@IQYw@[{@KSa@gAYw@e@oAy@uBK[Sg@?Aa@cAe@uA]}@c@kAa@iAu@qB_BkEMYUk@AEOa@Oc@ACq@iBk@}AM[CKSg@Qe@KWGOQg@Oc@c@qAQm@Oi@ACKe@Oq@_AyEeCcMKk@_@oBS}@SkAa@mBUkAGYQ}@CMI]Mi@Mk@Mi@WkAa@_BWcAi@{BI[o@kCKa@CGa@_BWu@GOSk@[o@a@{@Wc@{@oAOSWc@eAaBkAiBYa@Wa@ACi@y@g@y@Ya@IKMU_@o@OUYe@MWUg@Ui@Uk@AAe@kASe@q@eBWs@M[g@mAQe@CGw@mBQg@Sg@Se@Qg@Sg@Se@Sg@Qg@GMKWSg@IUGQoAaDsCkH}@yBAESg@y@uBc@iAc@kAg@oAe@mAc@iAy@{BUy@GYGa@Ic@Ge@Gi@IkAIwAAaAAs@@o@B{@F}AHy@Fg@Jm@BMHe@dA}EVgAN{@Hc@@EBQDSDa@PkBBY?C@OBi@?[@o@@yAAi@AsBAmCAm@?m@Ao@?m@Am@?o@Am@?m@?o@AeAA}AAm@?G?e@E{G?k@?k@CgD?e@?IAqBC}DAqDAy@AkCAeAAkA?k@AkAAkCC{DAm@AcBAwAAuBEeACk@Eo@CYGi@Ig@QiAEs@Ig@G]Kk@Ie@EUQu@Om@a@gBIYSy@GS[eAW}@Wy@_@gAg@uAc@gAWk@O[Wk@ACa@y@i@cAGKa@u@c@s@c@s@KO_@k@k@y@W_@Ya@EGmAeBk@y@U_@Ya@GKg@w@KQg@o@Yc@W]U]u@gAA?c@q@}@sA]g@m@{@Wa@OS{@oAe@q@QWeA{Aq@_AmAiB}@sAIMIIc@o@QU[i@W]IM]g@AC_@i@a@m@a@m@IKq@eAc@s@ACYe@Yi@AAOWEKEIWe@Yk@CEEI?AMYMWYk@Wm@Wk@Oa@IO]}@CISg@M_@Um@Sq@Sm@GSGSIUEQEQQi@EQOm@Ka@K_@GYOo@I[GYEQG]WkAEWG[Mu@SmAKs@Ku@Kq@K{@MkAIu@I{@KiAKwAMkBCWEm@GaAIcAK_BO{B_@kFa@{FKaACa@OmAUmBQkAE[G_@CKE]WsAESWwA_@cBI[WeA]yA_@aBm@kCk@_Ca@eBs@}COo@iAcFYkAAGUcAOu@WsAQaAWyAQoAAGIe@Ky@_@sC_@eDGi@O{AUoBCUOwACYUyBMgAg@sEOqAUyBSgBS}AKs@Ms@WsA?AS}@Ia@CKQo@U}@[gA_@gAUq@[w@Ws@]w@CGeAyB}A}CUc@wCcGUe@k@iA_@s@KUUe@Uc@k@iACGc@{@MUO[Ym@g@_Ag@eAKUYk@Yk@_@u@EIUi@QYQa@i@aAm@iAKQWc@EGe@s@c@m@Yc@Y]W[Y]YYg@o@c@e@s@y@y@}@m@q@_@a@c@a@EEg@c@YWECIIMI_@Ua@Ug@WcA[iBk@eBg@{Bs@c@OkHyBmIiC_AYs@UgA]m@Q"
                     },
                     "start_location" : {
                        "lat" : 39.6482247,
                        "lng" : -76.2033761
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "23.5 mi",
                        "value" : 37842
                     },
                     "duration" : {
                        "text" : "24 mins",
                        "value" : 1415
                     },
                     "end_location" : {
                        "lat" : 39.8685973,
                        "lng" : -75.6622124
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eUS-1 N\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "c|nqFdx_oMeA]a@Mw@UaBe@c@O{@Wg@Ok@QOEw@SoAWA?g@Ks@KKAYEUC]Cc@Ek@Ei@CeACkBAW?_A?S?iAAs@@uB?Y?gC?sB@oA?cB?wA?S?uA?mC?iB?}@?mA?}@?eA@aA?mC?M?qB?[?e@?eB?yB?o@?kA?mAAm@A[A]A_@AYAk@EsAGcAIo@E{@IcAKcAM_@E_@EuAS_AQqB]yA[iAYaBa@EA[KcAYCAGAWI}@Yi@SKCo@UQIUI]Ma@Qg@Sk@Ui@Uw@]k@Wg@Wg@Ww@a@_Ae@y@e@i@[OIw@e@g@[m@_@_@UCAk@a@m@a@OKu@i@UQ_@WSQwAgAk@c@{@o@{AkA]Y{AiAyAkAYSeBuAYUc@]c@]e@_@UQk@e@c@[eA{@yAkAyAmAq@i@gA}@eBwAIGCCcAy@[Wk@e@]Wc@_@a@[WSUSMI[WgA{@KI_@[_@YUQQO_As@g@_@i@e@OKGGwAgAo@g@k@c@iA}@y@q@OM_As@II_BmAIGk@c@CCEEEC]Wu@m@{@q@w@m@w@m@[WWSmAaA_@YWSWSKIECoCwBe@_@IIMIs@k@_DeCkA}@c@_@QMe@_@kJmHSOQOg@a@_BmAGGm@e@WSc@_@SOQOg@_@QOSOYWKGSQc@]OMy@o@gA{@e@_@QOYUWSOMQOIKGESQACMKSQOMSSQOe@c@QQQOQOw@s@wAqASSOMSQOOQOQQSQOOyAqAeAaAo@k@ECQQOOQOi@e@[YOMQOOOOMOOcBsAc@a@OQQSQQOOQSOQQQOQOSOQOSKKEEOSOSAAMQMOOSKOECMSOQOSCCKMQUMQOSCCMOMQOSQSOSOSOQ]e@OSOSQSMQQSOSOSOQOSa@i@KOOSa@g@QSKQQU]c@CEKO[g@OUMSOUMUMUMUOWISOWACIOMWMUMUOWKSMUMUMWKUMUMUMUMUOYKQMUMWMUKSMUMWMWMSMUKUOYKQMUMWKSOUMWMUMWKSMUMUMWKSOWMUMWOYKSi@aAMUIO]q@IOOYMU[k@[k@[m@MUMWYk@i@aAy@{Aq@oAO[OWMUYk@k@cAMWKU]m@e@_Aw@wAcAoBi@cA[k@MUYk@[m@mA}BO]MU[k@[k@KWQYIQ[o@KUCAGQOYKUMUKUYm@Wm@e@cAKWWm@MWWo@KWKUKWWq@Wm@KYKWi@wAQc@Qi@M[Uq@KWI[KWAEIUUq@IYKYIWI[KYSs@IYIWK[AIGQEQCGMg@EMSu@GWI[IYI[[oAI[GYQu@G[IYG]Qu@GYGYG[G[Ou@G]GYOy@GYG]Ko@Q}@?EEUIi@Kk@O}@CSG[COOaAUuAMw@UuAG]E[GYE]G[i@eDE]GYMy@Km@kFg\\E[EYG]Mw@G[E]i@eDOy@AMCKE]G[G[E[Mw@Mw@UuAEYOw@E]EYOy@E[G]SqAIi@Kk@E[GYE[?Aq@eEc@iC[qBm@qDSuAo@_Ea@iCSoAM{@OaASoAUoAQgAKo@CSEOEYKm@Ki@CM?CO_AKg@AICSEYEWMw@O_AQcAg@aD{AmJ[kBMu@Ks@{CkRUsASqAMw@Km@M}@UqASmA[oBUuAEWO{@E[Ow@SqACKIe@UyAW{Ac@iCEYGYSoA[kBUqAKm@?CMw@G[GYSoAMu@g@{CAGKs@Mw@Ko@O_AKu@SoAESE]SqASoAG]QkAUsAO_A]wBkAoHUqAKs@G]i@}CKu@GYE[G_@ESAEEYG_@G]UqACSMs@COCOKq@G]Kq@G]Kq@O{@SoAMw@Ms@My@Kq@Mw@G[E[GYKy@Mq@Mw@E[My@GYKs@Mu@G]SqA[kBg@_DUuAGs@Cc@YeBi@gDQiAKu@Ig@Gg@AIIm@OoAKeAGo@ACEo@Gy@Ee@Eq@G}@Eu@Cy@Eu@C{@CaAAi@Ae@Cq@I_DGqBCgAE}ACcAAQE}BE_AEeBOiGQeHMcEg@qS{@u\\GcAG}@AYCwACw@A[A[?QAG?]A]A[A[AUCoAAg@A]A[?WAC?[A[A]A[A[A]?I?QA[AYA_@AYA]EoBA[A]A[AYA[Ae@?[AAEcCA]Ag@?ACq@?SCu@A{@?AAq@AmA?cA@y@?[?E?_@DeB@o@DuA@e@DeADeAJwAHyAFy@HkAPgCDm@HqAL}ALuBFs@HiATmDDm@n@qJDg@HgAF_ALoBDm@Dc@@WF{@Dk@BWLoBFs@Du@De@Di@JyADw@HaA?IHgAB]Dw@Bg@Du@@c@@YBw@@g@?_@@{@?k@?q@AM?}@Cu@CaACw@EeAAOO_CE}@Ee@E}@C[I{AS}CQuCMoBIyAG}@G_ACg@IeAKsBG{@MsBKaBKuBK}AEu@Es@I}AKeBEm@IiACm@Eu@G}@AYCa@C[G_AGqAIqACYCc@ASEu@CWGy@Gq@I}@Ea@Gm@AKAKE]EWK}@Gc@M}@Ig@Mu@EU?EGYEYG[GYEYEQAIGWG[GSSaAESGWIWGYI[IWGYIYIWIYIWIYIWIYIWKYIWIWKWKYIWKUKWIUKYGOCGKYKWGOO]ISACKWIWGMMYAEGOM[Si@g@kAKWKWIWKUKWKWKWIUMWKWKYKUKWKWGQKWM]KWIQAEKUKWIUISO]IUKWKWKWGQKWKWM[KWKWKWKWKWIUKWKWKWKWKUIWKWKWKWKWKWKWKWIWKWKWKUKWKYKUIWKWKWKWKWKWKWIUKWKWKYKUKWKWKWIWKSK[KWKUKYKUKWKWIWKUOc@GKIWKWIUMYCIGMKWIWKWKWKUKWIUAAKWIWKUKYKUGOCGKWKWKWKWIUKWKYKUIUAAKWIWKUKWKWGMCIKWKWIUMYIUKWKWKWKWIUMYIUKWMYAEGOKWKWAEIOiCwGuBmFUm@s@gBUm@Wm@Qe@c@iAi@uAQa@Qg@Si@]{@i@uAc@iA_AaCu@kBUm@i@uAQa@Oa@M_@O_@GOKWWq@GSM[GSGSSq@Ma@K]Sy@K]EWQq@GYG[Ms@Km@CKOy@Im@Ky@Gk@E_@I{@CWMwAc@eFKkAMuAKqAEk@Iu@Eo@SuBC_@KmAMuAEi@OeBM{AE_@AMCe@CSG_AE{@AQAOA[ASAW?YAYA_@A_@?[?_@As@?cA?a@?e@?_A?g@?{@AeC?{C?yAAmC?}CAwC?sB?C?}@A{A?e@?S?s@?kB?aCAy@?_A?w@?mBAqB?oB?W?{AAsA?UAy@C}@Ai@Co@Ew@Ce@CYCa@Ek@Eo@Ea@Iw@MmA_@eDEe@Gi@Ge@WyBAQCQE]C]CIAKEe@CUK}@Ea@Ge@OoAOwAQaBWwBEa@UsBYeCIw@MiAQeBGi@Iq@EYE]Gk@EQAMEYG]AEMs@G_@GWEWI]GYMk@Qu@Mg@I[I[Ok@Mg@Sy@Mg@U}@o@iCYgAOk@Qw@GUI[Qq@IYEUK]Oq@I]Kc@GWIc@Ow@Q{@O_AG_@G[Ie@Iq@Gc@COEYIo@Ec@Is@E]C[Ea@Gq@E_@M_BCWAICYI_AOoBKmAKcAKqAOaBWeDO_BKoAOaBC[Cc@Iy@C[I}@KoAMyAMsAM{A]mEUcCCUKoAC[C]CYAGCUCYCYCa@Iu@C]CWGy@WoCUmCs@uIGi@QyBS{BMwAKoAGk@KcAIw@OmAGg@Io@QmAQkAEWGc@SkAUsAUkAAG]iB]iBGa@o@iDScAMs@G]EYG]CKOaAE[M{@Ky@Ku@KiAEa@CUEe@CUCYEe@Ea@C[ASIy@KmAGs@AAEm@OiBI}@WsCOcBGw@I_AIu@I}@Cc@Gm@Gw@Ca@Ew@Ci@Cg@?YA]?k@?k@?a@?Y@]?U@g@@e@@i@@]@]@[?]Ba@@k@?UBm@B{@@c@?e@@a@@]@c@@Y@[@_@@c@@k@@_@@g@@YBs@@a@@s@?o@?_A?u@?A?k@As@Cu@A_@Cu@Ci@Ce@Ck@Gy@GaAIeAEc@Em@Eq@Ec@G_AGq@IaACi@Ca@Ea@KuAIqAKmACi@E_@Em@Eu@I_AG{@Eo@Gu@IaACi@Ei@A[Eu@A[Ce@Aw@Ac@Ak@?_@A_@?Q?i@?s@@o@@w@?M@[@k@?e@@]@[@{@@w@@s@@_A@c@@k@?a@@W@q@?o@?UA]Cy@Ea@AQEc@Iq@G]GWI[GWIYQg@M]Wk@_@w@OYg@eAq@wAUg@MWoAoCAAQc@Sc@a@_Am@wAAAg@mAiAuCy@uBm@_BK]K[K]IUMc@GWAAU_A_@yAc@cBa@_BCI]uAOi@K_@CIWeAMc@GWK][qAU{@Og@GUGUK]Sq@GUWw@q@sBCEMc@Oa@IWGSAAQe@IQQe@e@cA]s@IQGKCIQ[GOk@iAw@aBi@iACIq@uAq@yAo@oA}@aB_@s@QY_AgBIQq@mAEKMYO[o@wAUc@u@aB]y@_@}@[s@GWGQI]ESCMESGe@EYAQCOAQAKASAYAS?O?K?O?M?M?K?O@S@g@@k@@IJoDBoA?KFcBBo@@WBaA@w@FgCFyB@]"
                     },
                     "start_location" : {
                        "lat" : 39.7307361,
                        "lng" : -76.0257876
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 mi",
                        "value" : 1494
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 112
                     },
                     "end_location" : {
                        "lat" : 39.8809846,
                        "lng" : -75.6656074
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003ePA-52\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "wyirFxwxlMUCeG]iAS_E[o@I{BYUEy@I}@MA?_@EYCm@CM?{ALA?gAJa@FI?YDQBQBUBk@Ja@JIB]HEBYHYHE@a@JA?_@HC@_@FC@E@[Dw@Ls@Ju@HODa@H_@FC?_@FOBQFA?MDMDGDKBUJEBULA@A?MHQLWREBEDQPA@A@MLKLA@CDMRCBMRKTQ`@A@o@pAA@m@hAOXWb@OVGHCDOLGFC@OJ}@f@"
                     },
                     "start_location" : {
                        "lat" : 39.8685973,
                        "lng" : -75.6622124
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.9 mi",
                        "value" : 4620
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 275
                     },
                     "end_location" : {
                        "lat" : 39.9004377,
                        "lng" : -75.61990399999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003ePA-926 E\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cglrF`mylM]KKEKCg@sBCK[mAy@gDOk@?AQc@Oo@Oi@AE[oAMi@k@_CAGMc@Mi@AEKc@Ok@Mi@AEMc@AGMi@Mk@[qAC[YyA[wAUcAYmA]sA_@uAMi@Oi@GKk@aCMi@g@sBOo@Os@cAwEMq@Oo@WiA[sAi@_CGa@Mg@GW]uAK_@Uw@Mg@?AM_@Oc@GMKWMW[i@}@wA[e@cAeBEG]k@m@iAOY]m@aAaBEGo@cAWY{@gA}@w@YWo@k@g@g@w@w@UUg@i@WW[[CCs@u@KK_AaAOMEKEEKMAAeAgAMOQSY[i@q@MOUe@IOk@qAo@}AIQ]u@S_@EKWo@q@_BSg@GQ[s@CGa@cACICEAECGEOEO?AEOCQAIAGCOAOAQAUAg@Ac@?]ASAWAUCUEWESESIUISUe@[q@kA}B_CwEa@w@MYKS?AKSGOGOCKEMQi@Me@ACMe@a@wAOi@Ia@CIEQGYCGIa@ACEQGQ?AEKEMOa@Wk@Qe@CKOa@IQM]Ss@Uo@Qg@Yy@IWQc@AAYe@Uc@M[U_@EG]m@MSQ]ACGMEOCIEMKc@UiAGWQ}@[wAQw@AEEWCGEUG[AEEWG_@C]CY?EAEAEAGC_@I_ACc@Cs@Cu@Eo@AKCMAOCQCQCSAM?K?S@E?M@QBM?CBSBKBGR_ANm@Lk@Nk@Nu@D_@"
                     },
                     "start_location" : {
                        "lat" : 39.8809846,
                        "lng" : -75.6656074
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "8.3 mi",
                        "value" : 13428
                     },
                     "duration" : {
                        "text" : "16 mins",
                        "value" : 931
                     },
                     "end_location" : {
                        "lat" : 39.96472929999999,
                        "lng" : -75.48895970000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003ePA-926 E\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "w`prFjoplMwA_FWs@i@}AEMWs@k@_Be@oAc@oAe@oAe@sAEM_@cASg@CKMYQi@EKQe@?AM[Ws@K[EKK[EKK[EKM[EMKYCKSg@_@eACIAC]aAWs@M[CKQg@s@uBGKy@cCK[Sg@Oa@Sm@Qg@Qi@Qg@Qg@Qi@Qg@Qg@e@uAa@mAGSISGQ[_AK]u@wBaAmC}@iCw@aCUm@_AsCQi@kC{Hg@yAuA{DEMkAaD{AeEe@qAw@yBg@yAc@kA_@aAQg@Uo@k@}AmAmD_@cAOa@AEEKq@mBEIQg@M]Qi@KWSg@Qg@c@mASi@Qi@c@mAc@qAc@oAQg@w@yBQg@Qg@CGMa@Qg@IWGOYy@Qg@IWGOIYYw@IWi@aBG[IW?AGQIWc@oAeA{C_@aAWu@M_@g@qAGMGGgAaDo@mBg@}Ac@qA{@mCq@wBg@wAw@iCs@yBQi@Qc@EMACGc@IUm@gBQg@e@uA]eA?Ao@kBUk@m@}A_@_Au@kBCGKSSi@[w@[{@?Aw@uBYu@KYy@sBSi@mA_Dy@wBgAwCMe@Yy@IUGSk@cB{@cCs@yBMUe@wACIIYe@uACIQg@c@qAaAyCY{@Qi@CIM_@a@mAiBkFQg@c@qAQg@e@oAQg@Qg@Y{@KUQg@kAkD[aAGOQg@w@wBQg@Qg@Sg@CKM]gA_Dm@eBISEO_AmCe@uAeAaDQg@Qg@M[CIIUGQISGUISEKAGIUGQCIM_@KYKYYy@K]Oc@Oc@CIIS?C[w@AKKYIUy@{Ba@gAUo@Oa@a@eAk@cBGM]cAa@kAEMwAyDKUIG}@gC{AgEw@yBw@wBGQYs@]cAa@gASm@Uo@sAsDm@cBg@uAs@mBAC]_AYy@GOGQAEk@{AK[GOKWSm@Wq@Uo@GOGOc@oAKWGQ]_Ay@}B}@_C_BiEKYEMw@wBw@wBa@eAOa@[y@cAsCQg@GQKUiA_DSg@Yy@c@oAEMUm@ISiA_D[}@GQIQkAcDqAuDm@cBy@wB_BiEc@mAkA_Dk@{AUq@uAqD{EsM}AgEe@oAiAaDc@mAQg@Uo@Um@[{@e@oAKWM]e@oAIU[w@]cASi@]_A[q@IKe@m@qAeB[c@k@u@w@cAACGEGEEEKEIAICIAK?EAG?o@?A?{@@sA@c@?oBBW?q@?a@AOAI?EAGCKCGEKGGIIIACEEKSEGM[Ys@?AO]KSMUGKKOKOQW]a@W[A?Y[qA{AGI_@c@KOOQIM?AGMIMCGCGO]_@eAM]IUCGIYM_@q@sBQg@e@qAQg@KYEOQg@KYQi@Qi@u@yBa@kAK[c@qASm@s@yBOi@Qg@Mc@Um@Oi@[}@Y{@Qi@Og@Oe@ACQg@Qi@K[CKQi@IYQg@Qg@Qe@ISEKISIQ[u@MW[s@_@_AGOMUUi@Sa@_@y@q@sAWk@_@y@O_@ISISOa@IYCIOa@Oi@KUMWGOSk@Se@Si@Ui@Qe@M[MYKYGQGYKa@YcAK_@CICEKOIM"
                     },
                     "start_location" : {
                        "lat" : 39.9004377,
                        "lng" : -75.61990399999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "5.4 mi",
                        "value" : 8747
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 554
                     },
                     "end_location" : {
                        "lat" : 39.9850133,
                        "lng" : -75.39260829999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003ePA-3 E\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "qr|rF~|vkM}@}CY}BKu@Ii@?CQcAa@oBWaA]{Ay@eDy@kDgBsHYmAwAaGESaAcEESI]_AyDu@_DCIy@kDy@kDq@sCESgAuEI]CKc@kBYiAMm@GYAGOw@Ou@AMSgAEa@AKQoAMmAM{AS}BEc@G{@OwAGo@Go@MeAYqBSmAG_@G_@Ia@G[[wAIa@g@gCq@gDW_BWwACSMw@Kw@Gi@ACCUMeAGi@?COyAGk@?AOyAUkCQeBWiCg@cFUiCWiCy@qIUcCOsAUgCUgCCc@KoAAM?GMoBGcBCk@EuAEeCCyACuAAu@Au@Am@Ao@EgBGqDSsLIoFA_@CcAEmAIeAGq@Iq@K_AO{@Ko@WgAQw@Qm@AE_AcDw@mCaAaDq@yBQk@_@mA_BoFy@kC[iAoA}Dq@_C_AeDcAeDMa@s@wBIYa@iAm@aB}@{BoAaDuAqDIQg@wAeAmCg@qAaBgESi@eAkCo@aBe@mASg@M]{A{DO_@aBmEISg@sAWs@M[Wu@Oi@G[Kg@Ie@G[CU?AE_@C_@GwAC{@A[E}@?AIkBK}BAWEuAIqBEqAKiCG}AO{D?CEuAGwAI}BG{AQyFASA[IkCOaECcAKaCKmDCs@IkBCaAEgC?[@iA?a@Bi@@ADw@?CB_@F}@`@sCTyAb@iCL}@`@iCZoBVwAf@aDj@uDTyAV{A"
                     },
                     "start_location" : {
                        "lat" : 39.96472929999999,
                        "lng" : -75.48895970000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "4.7 mi",
                        "value" : 7510
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 597
                     },
                     "end_location" : {
                        "lat" : 40.0189255,
                        "lng" : -75.31999429999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBryn Mawr Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "iq`sFxbdkM[QWc@[g@e@w@o@cAAAUa@MUKQGKEKEG?ACGCGAGAEAG?CACASCU?GCe@K}AAQAQAG?ECMAKCK?ACKCOIUMa@ACOc@IWm@aB]}@Yy@KYOc@Q]QYW[AC[Y[YMKWSUSYSUOMI]UYUWSKIGEQQQSOQOQGIS]q@iAq@eAWa@Wc@AAU_@KQKOKOMQmA_Bs@aAOQo@y@i@s@c@k@]c@_@g@SYQSc@m@U[OQOQOMOOOMIG]UCA[Si@[_Ai@UOECMKIGIIEGGGGKGKIOAAGMKUAAQ_@KSKYO]AEISSk@WiAKa@?AI[EMKWISKUGKKSMUk@{@AAMQKM[]IIQS_@c@UW[]OSMOIKGICGAA?AGIGKEKACKQGOACEIa@}@Ui@Sc@Se@GMa@}@ACQa@g@mAg@iAsAwCi@iAk@iASe@IO[q@sAaDKc@Us@M[IWISACEKGSIOEKKQKQKMMOo@y@oA_BIKOSY][_@KOMO[_@IKgBuBY_@CEGICECEEICKEKCOCUAK?Q?I?S@O?O@_@@Y?O?OAKAM?GCME]I]I_@IYg@kBOi@AQ?AAC?Ak@_CUy@GSe@mAeAkCAAAACEe@oAM]w@yBm@_Be@oASg@Qg@e@oAe@oA[y@Uo@EKg@sAOa@KYIWGUIWEQKk@E_@AMCQC[AACi@?AEm@?ICc@Aa@AMCu@E}@C}@AUAQAc@AM?QC[C]Gi@Mi@COIYACKa@EM?AM_@Uu@M]AGY_AEIAGUs@[}@GQM_@}@sBSe@Sg@CE]y@yCgH{AkDiB{D]w@]o@AGc@y@c@}@kA}B}A{CaAoBy@_By@_BIQcAoBs@}Aa@}@Se@EIM_@gCkG}@aCm@{AM[KYGOGSESG_@Ie@G_@ESOaAIi@Mu@ASAECO?GEi@C]AS?M?I@i@Bk@Ba@Dm@BSD[J}@Ho@Da@?SAK?KGs@Gk@E]Iy@AE[gCOiAE_@wAeLQoAK_AEi@COA[Ca@C_@AWE}@G_B?AAm@M{CAa@AOAWCk@E_AA]A]AWAW?KC_AAKACA[CUOo@CKc@}@W[c@i@SSg@m@k@o@{AgB"
                     },
                     "start_location" : {
                        "lat" : 39.9850133,
                        "lng" : -75.39260829999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 286
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 44
                     },
                     "end_location" : {
                        "lat" : 40.0210381,
                        "lng" : -75.31808839999999
                     },
                     "html_instructions" : "Continue straight onto \u003cb\u003eS Bryn Mawr Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eSR 3038\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "iegsF||ujMGI[]kAsA{@o@WSA?]We@_@]YWSUS_Au@OK"
                     },
                     "start_location" : {
                        "lat" : 40.0189255,
                        "lng" : -75.31999429999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "486 ft",
                        "value" : 148
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 24
                     },
                     "end_location" : {
                        "lat" : 40.0206364,
                        "lng" : -75.3165789
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eLancaster Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "orgsF`qujMCWESCOI[Ti@h@wAf@sA"
                     },
                     "start_location" : {
                        "lat" : 40.0210381,
                        "lng" : -75.31808839999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 321
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 74
                     },
                     "end_location" : {
                        "lat" : 40.02303209999999,
                        "lng" : -75.315135
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMorris Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_pgsFrgujMUOc@[i@]y@u@K[COGKIIIEOIGEWQYSGCMAC?C?IDE@GFCBIHOV[SCCWM}@k@"
                     },
                     "start_location" : {
                        "lat" : 40.0206364,
                        "lng" : -75.3165789
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 mi",
                        "value" : 458
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 40
                     },
                     "end_location" : {
                        "lat" : 40.0209363,
                        "lng" : -75.3105075
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eMontgomery Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}~gsFr~tjMBKPg@v@wBRg@Pi@f@wAb@oA^eAd@wAb@oAvBiG"
                     },
                     "start_location" : {
                        "lat" : 40.02303209999999,
                        "lng" : -75.315135
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 mi",
                        "value" : 1142
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 120
                     },
                     "end_location" : {
                        "lat" : 40.0266546,
                        "lng" : -75.29962019999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eFishers Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{qgsFtatjMWQEEw@g@e@[UO_@U}@m@w@yBSg@w@wBQg@u@yBc@oAeA_Dq@mBwA{DwAkEc@qAc@oAWw@e@oAIUKWg@_BsB}FUs@_@eA"
                     },
                     "start_location" : {
                        "lat" : 40.0209363,
                        "lng" : -75.3105075
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "285 ft",
                        "value" : 87
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 19
                     },
                     "end_location" : {
                        "lat" : 40.0259458,
                        "lng" : -75.2991888
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eRose Ln\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "quhsFr}qjM\\Kb@Wf@Y`@W"
                     },
                     "start_location" : {
                        "lat" : 40.0266546,
                        "lng" : -75.29962019999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "466 ft",
                        "value" : 142
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 39
                     },
                     "end_location" : {
                        "lat" : 40.0259491,
                        "lng" : -75.29788479999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "eqhsF|zqjM[_AGOIWCSCIC_@?[@U?IBI@EBEBABABAB@H?FAB?@A@ABC"
                     },
                     "start_location" : {
                        "lat" : 40.0259458,
                        "lng" : -75.2991888
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "466 ft",
                        "value" : 142
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 36
                     },
                     "end_location" : {
                        "lat" : 40.0259458,
                        "lng" : -75.2991888
                     },
                     "html_instructions" : "Make a \u003cb\u003eU-turn\u003c/b\u003e",
                     "maneuver" : "uturn-left",
                     "polyline" : {
                        "points" : "eqhsFvrqjMCBA@A@C?G@I?CAC@C@C@CDADCH?HAT?ZB^BHBRHVFNZ~@"
                     },
                     "start_location" : {
                        "lat" : 40.0259491,
                        "lng" : -75.29788479999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "285 ft",
                        "value" : 87
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 17
                     },
                     "end_location" : {
                        "lat" : 40.0266546,
                        "lng" : -75.29962019999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eRose Ln\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "eqhsF|zqjMa@Vg@Xc@V]J"
                     },
                     "start_location" : {
                        "lat" : 40.0259458,
                        "lng" : -75.2991888
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 mi",
                        "value" : 409
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 42
                     },
                     "end_location" : {
                        "lat" : 40.0303055,
                        "lng" : -75.29906579999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eFishers Rd\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "quhsFr}qjMc@Cc@CkBM_@CC?qDYc@EaE]w@KGA[EOA"
                     },
                     "start_location" : {
                        "lat" : 40.0266546,
                        "lng" : -75.29962019999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "98 ft",
                        "value" : 30
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 4
                     },
                     "end_location" : {
                        "lat" : 40.0301848,
                        "lng" : -75.29875299999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eOld Gulph Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "mlisFdzqjMFUPi@"
                     },
                     "start_location" : {
                        "lat" : 40.0303055,
                        "lng" : -75.29906579999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 mi",
                        "value" : 1981
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 189
                     },
                     "end_location" : {
                        "lat" : 40.03964879999999,
                        "lng" : -75.2798246
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBlack Rock Rd\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "skisFdxqjM?m@@o@@aAA[AUCWE[COMm@_@eBIYK]CK_@{@Uc@IOGKWe@OUIOMQIKGKIKQSc@c@WWCCUQGG_Am@q@e@KG]WoAy@_@W[SAC]WAAQOEEGGKMEGEIQ_@?ASg@Qg@GMI[Oi@Oi@Oi@WaAOg@EMq@}BOi@oAeEAIW_AGSAAa@wAc@qAi@eBY_AGQGUQi@a@sAEQIUOi@a@sAQg@W{@IWOg@AEOc@Oi@ACOg@q@yBQk@Oe@?COe@ACOe@?AOg@c@uAi@kBu@w@m@gAKSS]a@s@Yg@"
                     },
                     "start_location" : {
                        "lat" : 40.0301848,
                        "lng" : -75.29875299999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 mi",
                        "value" : 2173
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 193
                     },
                     "end_location" : {
                        "lat" : 40.0309502,
                        "lng" : -75.2631114
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003ePA-23 E\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "yfksFzanjMZWRO`@Wb@[z@o@h@a@ROJIBCtAeA`@Yt@k@FENMn@g@RUJMFGHOx@qAr@kAZg@HMHMLUJQHMJO?ALSHQDKFMDI@CFOb@gAVo@Ti@\\m@FKHMDEBCFGHGLGHGXMRKFCDCLIHEFGHIHIHGHKHKFKBIN[BG@E@EBG@EJm@Hc@?CHYToAJWTo@f@y@h@m@h@i@BCZ]JKVWRS^g@RWP[Zm@Vc@Te@Tc@\\m@WWECGCGAGCKCI?K?Q?I@KBQBYD_@Fa@Hg@BC@K?KAMAMEICIGKCECECCEEGKSGWEQGc@Kw@Gc@MkAAUAGAg@@o@Fe@J{@J]Ts@Pc@P[HQj@u@r@_AhE{FDGxBsC"
                     },
                     "start_location" : {
                        "lat" : 40.03964879999999,
                        "lng" : -75.2798246
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 mi",
                        "value" : 1363
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 92
                     },
                     "end_location" : {
                        "lat" : 40.0397756,
                        "lng" : -75.2525768
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eHollow Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eState Rte 3050\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mpisFlyjjMUW[]UWSU}@_AwCgDEIACACa@g@a@e@q@u@EE[]AAW_@QWEGOWUa@GOACQa@Qe@s@_CSq@ACOg@EKWy@EOISCKACACEE[aAUo@Uu@Ma@IUEKWk@Q[GOIMMSKMY_@c@i@aAeAq@w@c@e@e@e@IKQMGEMKOMSMKEa@Sq@]OIk@YUK_@SQIAAmAq@OI]Sk@[SKeAi@"
                     },
                     "start_location" : {
                        "lat" : 40.0309502,
                        "lng" : -75.2631114
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 344
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 23
                     },
                     "end_location" : {
                        "lat" : 40.0388721,
                        "lng" : -75.2492329
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto the \u003cb\u003eI-76 E\u003c/b\u003e ramp",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "sgksFrwhjMAKEOGOGQEQAC?AAIC[AGCYEWAg@A_@?]@MFe@@E@I@G@E@G@E@G@EBI@EBEBG@EBE@EBEBEBEDGDEDGBC@AFGBCBCBEBCBCBCBEDCBEDEDEBEDCBEBC@ABEBABEDEDEDEDGDEDEBEHIDE@??ABU"
                     },
                     "start_location" : {
                        "lat" : 40.0397756,
                        "lng" : -75.2525768
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "7.7 mi",
                        "value" : 12335
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 614
                     },
                     "end_location" : {
                        "lat" : 39.9609521,
                        "lng" : -75.18215889999999
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eI-76\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "}aksFtbhjMNQPQPQPQNQPQNQRULOPSNSFIFINSJQJQDGLSLULWLWLU@EHQFOBIJWJWJWHYJYHWPk@BETs@HYTq@JWLa@FQHWBKFMHYJYHUJYJWJWJSNYJULWNSLWDGHKJQPUPUNQNSNQNORQNORQPOJIDEHIJGNMFGXUXULKPOPMRQPOPOPQPONORSNSPQNSNQNQNSNWNSNULSLULUNWJULWLUJWLWJWJWLWJWb@gALWJWJWJUFQP_@JWJWJWJULYJWJULWJWLWJULUFOR]LULULUNULUNSLULS@ANSLSNSNSn@{@TYhA_BJM@C`@i@LQNSPUNSNSNQ?ANSDGHKNSLSPULQNUNUNUZi@NUR_@b@y@Xk@DGXo@FMLWHULWHWPa@Pg@L]FQVs@Ts@@CHU?A^gAZaANa@Ts@HWHWL_@\\aADMDKd@yABKHWJYHU?AHWJYJWJY?ATm@JWHS?AXq@@EL[Ra@FMXm@Vi@N[JQN]Te@LWZo@JSHSLWN[LWRa@DIHOd@aAN]HQN[Xi@L[HQDEHQ@CLUVg@LUJQNWNULSNUNUNQLQHMVYJMZ]JMNQNMNO@ARQHIFGNMRQVSXSRO@AZSLIHGHEpAy@LIPKPKTO@?LIVQRMLIXQROBCLIPMPOPMROLKLMZWDEFG\\]NM@CVUDEHKLMBCPUPQDEX_@PSNQJQHIHKNSNSTYHK^g@NSNSLQLOBELO\\e@@ANQPWl@u@NS^g@NSPS\\e@PSNSp@{@Xa@f@m@^g@JMBCT]X]NQLQTYX_@NSNSPULOBCFIDGPUJOV_@HMLQR]Xi@PYJS\\q@Tg@N_@BENa@@EHOHUNc@DMJYNk@L]HYH[Pq@@GTeAHa@DWLq@DS@KDYF[DSDYVuABO@GNs@F]H[XgARu@T{@fAgE?An@cCRs@H[HYFYHYHYFYHWFYDOFQ@CFYHYHYHYHUJ_@JY?AJWHUJWJWBGFOJYBEHOJWHO@ELWLSLWBGHMFKJSDEFMNULSHMR[FIDGNSDEHKPSRSLOPQPOPMTQLIRMRMRK@APIRKRIRITIJCJEREVE\\EHAVC`@CPAVIf@C\\AVA^?B?T?f@@T@X@V@f@DVBB?d@F\\BVDD?`APRDj@Jf@JXHLBj@Nh@PZJLDh@PPHl@TJDDBRHf@TRHVJd@VLFj@Zf@VTLVNt@b@d@Zb@Zb@Zd@^JHVTRN`@^XTZZDDTRVXb@b@^b@VXX\\^d@^f@BBZb@^f@\\h@NVZf@Zf@LT\\l@PZLRR^R`@JRBDP`@N^P`@Th@N^N`@DJ?@FPJTHT@@L\\JXLXDLN\\Rh@LX@@HPLXLT@BXh@NXLRJPNVNTNTNTZ`@PTNPFHJLXXVVLNRRDDJHPP^ZRNPNXRLHRN@?PLTN\\PVNVL\\PLFRHf@RHD\\LPFB?PFl@PVFXFH@r@LNDH@XDVBVBVBJ@T@XBT@F?R?L@T?r@@|@Cj@AZCLAJAXCHAJAPCNCVEFAZIf@Kt@Uf@Sx@c@HEHEXS\\UVUHIPODEZ[LMFINSNSNSJMNUHMLUT_@NWJSNWP[HMJSNWJSNWNWLSLUZk@\\m@\\k@JSXi@LSXg@R]JSNULUR_@FKLUJO@EZk@LWJQN]HS@ATo@JWJ[J]HUZiAZsAH_@XeBJo@Hu@D_@D[De@JaAJaAL_AHu@@QNkABUJq@Pw@Nm@b@kAJUNULSLSHKTWRS^]BANKhAk@ZKRG@APE^Id@KXG^It@OHATGTEJChAUFA`@Kj@Kj@Mh@KrA[LCHA~@SXGb@MFA^KVKf@O?An@Y^OBCNI^UFETQ`@YXU^[Z[FGp@w@JK@CNUNU\\g@@CXg@HOBEf@gADIRg@To@Pk@La@HYTs@@CRk@La@FQNe@DIRk@Rg@FKh@eA`@o@FMZe@NQHKT[d@m@\\a@n@y@LQp@y@^e@^e@PQPSPQPQNMXWNOTQZY`@[t@m@h@c@`@]j@e@JIn@g@p@g@`@YROnAw@DCRKRMNKzAeA"
                     },
                     "start_location" : {
                        "lat" : 40.0388721,
                        "lng" : -75.2492329
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 263
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 15
                     },
                     "end_location" : {
                        "lat" : 39.9599811,
                        "lng" : -75.1794721
                     },
                     "html_instructions" : "Take exit \u003cb\u003e344\u003c/b\u003e on the \u003cb\u003eleft\u003c/b\u003e for \u003cb\u003eI-676 E\u003c/b\u003e toward \u003cb\u003eCentral Phila\u003c/b\u003e",
                     "maneuver" : "ramp-left",
                     "polyline" : {
                        "points" : "}z{rFn_{iMDO@CXW?CJKHKHIHM@ADIHMFMFMFQFOFODQBKDQBKBOF]BU?ABa@DeADe@FaA"
                     },
                     "start_location" : {
                        "lat" : 39.9609521,
                        "lng" : -75.18215889999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 mi",
                        "value" : 1096
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 58
                     },
                     "end_location" : {
                        "lat" : 39.9583983,
                        "lng" : -75.1667863
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eI-676\u003c/b\u003e",
                     "polyline" : {
                        "points" : "{t{rFtnziMF_AFw@H}@B_@Bm@Bm@?AFaADk@B[Bg@NwBBg@Fy@HmAF}@VcE@O@MJ_BHqAPsB?G@MJeABe@?A@E?ARoEBa@B[?ADi@Bk@RwCDm@B[FaA@_@J_B^}F"
                     },
                     "start_location" : {
                        "lat" : 39.9599811,
                        "lng" : -75.1794721
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 mi",
                        "value" : 1212
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 60
                     },
                     "end_location" : {
                        "lat" : 39.95694049999999,
                        "lng" : -75.15275989999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eI-676\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "_k{rFl_xiMFo@Dq@RqC@KZgFFm@@O`@oH?M@M@W@C?Eh@sI?APiCBm@HaAB_@D_@J{@Fm@FyAHyAZsEBQDm@B[@QJiA?A@ONcC@]@S@c@?a@?[?[?c@AYAS?EAYC[C[C[E["
                     },
                     "start_location" : {
                        "lat" : 39.9583983,
                        "lng" : -75.1667863
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 mi",
                        "value" : 716
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 33
                     },
                     "end_location" : {
                        "lat" : 39.95697010000001,
                        "lng" : -75.14461229999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to continue on \u003cb\u003eVine St Expy\u003c/b\u003e, follow signs for \u003cb\u003eInterstate 95\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eNew York\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eChester\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "{a{rFvguiMGc@G_@CQa@}BGWEUEUMs@QcACME[G[E]CYC[CYA]AWA_@AU?G?W?_@@W@]?K@SBW@YD_@Fs@B]D]BWB[D]B]D]BWD[D[BYD]B[@CFo@Fi@BWD]B[D[Hw@D_@"
                     },
                     "start_location" : {
                        "lat" : 39.95694049999999,
                        "lng" : -75.15275989999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "18.4 mi",
                        "value" : 29577
                     },
                     "duration" : {
                        "text" : "18 mins",
                        "value" : 1058
                     },
                     "end_location" : {
                        "lat" : 40.120425,
                        "lng" : -74.8878057
                     },
                     "html_instructions" : "Take the exit on the \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eI-95 N\u003c/b\u003e toward \u003cb\u003eNew York\u003c/b\u003e",
                     "maneuver" : "ramp-left",
                     "polyline" : {
                        "points" : "ab{rFxtsiMDYB[BYFc@BYD_@D]JaABUDa@@Q@Q@a@?[A]?SAMCYAGCUACIa@G[CEGWO_@?AMUISMOEISUGGIIWSWOSKUIYGYCUCUAWAW?[CYAWAK?M?WAUAIAM?UASAG?OASASAWCSAWCsAS?@MLk@Oi@M_A[]M[M}@_@e@WSKUKQMUKGGICQMSMSMUMQOSMQMQMSMQOQMQO[WQMGEOOSQIGGISQOOOMSSKKUU_@c@CCUWY[AAU[QUOWAAQWOUIOKQCGIMIOIOAEKSGQCEEKUo@CGKWOe@ESGSAAQw@Ia@k@yC]qBGY?A[gBIa@G[a@wBCWQaAMo@SmA_@oBk@oCKm@Ka@GYCKEMQq@GQ?AAEIYCGEOKYWq@GQWq@Qa@GK?AMWi@iAS_@IOEIKQEGGKGMEIMWCEeAgBWc@IM[k@]m@CCS]OYc@w@[k@a@q@Ua@IO_@s@_@q@]q@g@aAWg@Ug@Se@_@_AIUQa@]y@Qc@?ACECGCE?AAACEGQoAwCoBwEoBuE_CqFCI{BgF?AQc@M[Yq@Q_@}@_CSe@g@gAo@yAa@aAa@cACEKYo@yAIOKSKYw@wBc@uACKc@{Ac@mBc@yB[gBOs@Ms@WoAu@kDCG[mAAEQg@Oi@Qg@IWGQQg@e@wAO_@Qg@[}@Si@kA}CAEEO[{@{@yBcAmCq@mBw@uBKWSk@EMSi@o@iBOc@kAkDy@_CUk@Ys@m@_BEIk@wAmAsCUi@i@oASi@Yo@a@}@Si@GKUk@[w@c@aAKWACO]g@iAKWa@cAk@qAAA]q@q@qAs@mAS]]e@MSa@g@[_@MOc@g@u@s@i@e@[Ws@g@i@]o@_@SMw@c@UMeAk@[S_@SSKo@_@e@Y[Q}@g@o@a@QIQMc@WYQw@i@KG[So@_@SOSMSMSOUMACOISMQMQMSMQMSOQMSMQMSMOKSOUOOMMIOMKIUQKGCCOKOKUQOKCAg@]k@_@MK_@WSMCAII_@UMIGEq@a@UOs@c@MIm@_@EC]WOKmCgBqA}@[SWQ_@Wq@c@sA_AeAq@aBiAuA_AsBuAs@g@KGEESMQMSOMKIGQMQOQMCCOMSQOMMKQQMK?AQMOOOOIIEGOOOOGGWYMOQQOOOQEGWYMQ_@c@EGGIMQOSMQOQMQMSOSCEUa@MSCAIOMSMSKSMUKSCCIOKUMSEIEKMWIQAAKSKUGQACKUMWCGISISISu@kB{@iCUy@GUGUEQe@wBOw@EWK_Ak@sFGq@K_AQ_B?AEUGi@Gm@CQE[Mw@UmAMs@Os@YmAEOEUUy@Oc@Oi@Qg@Yy@u@iBQa@Yo@e@aAYq@Wi@Yi@wBuEo@uAk@oAy@kBEIy@mBe@eA_A_Ca@cA_@}@]}@q@cBy@wBCEw@qBe@kAKWy@qBCGu@oBgBqEm@aBg@mAe@iA?AiAoCu@iBy@uBKUQg@aBkEm@{Ak@wAy@{BQc@CKm@}Ay@yBy@}BYw@]cAc@wAQi@Oe@o@aCy@mDIWS{@[qAk@mCq@aDc@kBc@mBc@qBUeACOEQCMCKEYGYGYE[Kk@Ic@EYG[Ga@Ga@CMCOGc@GYE[EYG[EYMw@AGCQG[EYG[G]CWGYGYG[GYGYKc@Mi@GYIYIWIWMc@GQIUIWKWIWO]ISKUIUA?KYKUKUMUKWMWKWCEIOKWKUKWYk@KU?AMUKWQa@Sa@KWMWKUKUMWKUKU?AMUKWKUIOCGKUKWMUKUMWKWKUMWKWKUMWKWMUKWKUGKEIOYMUMUMSMSOUQSOSOSOQOOOQECKMQQQOIGGGQOSOQMCCOIQMIEIGSKQKWMUKQGSIUIUISGUISGSGUIUGSGUISGSGUISGQEWIUISGIE]MSKUISKOISMSKSMQKWSKISOQOQMIIGGQOQQWYY[MQOQQSOUMSMSMSMUOUKUMWMUMWKUEIEKMWKWKUKWKW?AIUKWGQCGIUKYIYIWKYCIEMIYIWIYAEGQIYOg@CIIYIYIYGWAAGWIYIYGYCIOg@EQKa@IYMg@CKIWI[GWIYIYIYGYIYIWI[Oo@K[GYIYIYIYGYIYIWGYIYIYGWI[IYGWI[IWIYMg@Me@IYGWIYQs@IYIWIYIYKYIWACSc@EIUk@IWMYYo@O[IQ[m@?AYg@[i@AE]g@]i@U]u@cASWKMA?QSOQc@e@IIEESSCC[[A?_Ay@YUQMSOSMAAECIGKG]Uw@c@KGGEg@Us@]]Ma@QYMi@SQIQGi@Wi@UUISK}@a@OK[QKGc@YCASMGEKIOKAAQMQOe@a@QOOOOO]]QSUWQSEI_@c@S[Yc@IKU]Uc@KSWg@_@y@Uk@CEIUGQKWOa@Og@EMMc@GYQq@I[G[G[Mu@GYIk@AKE[Gc@Gm@E]EY]yCc@qDOoAG]E[GYE[GYMw@GYGYUaAKg@IY_@uAYcAUq@Wu@_@cAAAUm@M[Wk@Ym@KUQ]IOMU[k@MUMUMSOWMSOSMSOSOUOSOQQWMO_@c@OSQQQQGIi@k@[YYYc@a@QOOOQQQOQQQOQOQQMKCCOO[Yk@i@OOMKWWa@_@WUYYe@a@MKc@c@][g@e@[YOOQOOOo@q@OOOOOQOQOQOQMO_@e@MQMQOQMSOQMSMQMSMSMSMSMSMSMSKSMUKSYk@MSKUKUKSMWISWk@KUKWUk@Um@IUa@eA_@cAUm@k@{AKWSm@Um@Uk@Uo@_@cAUk@Uo@k@{AUk@Um@Sm@Um@KWIUKWIUKUIWIUKWIWYu@Qc@KWIUIWSe@M]IUKWIWKUIWKUi@{ACEQg@Uk@Uo@Um@ISKWIWKUKUIUKWKUKUKSKW_@w@Ue@Wi@a@s@IOKSS]OYy@sAS[KOy@oAy@gAy@iAMOm@u@w@_A_@a@eAmAGI]c@QU]e@KOIKi@}@EG[g@KQKUMUSa@Q_@IQ]u@IUO]Oa@CKWq@Y_AGQOg@I[Oo@I]I[CMESSaAG]G]QmAa@}CG[CWG_@Iq@E[W_BCUUyAI_@EWUqA]eBo@yC_@}AWeAUy@Qq@K_@Sq@_A}CSk@Sm@Qe@Yw@Wq@EMM]Wm@IWm@yAa@}@Ym@GMUg@]u@Yk@Sa@A?Q]i@cAo@iA[m@EKEEsAeC}@cBQYCE]q@Yi@U_@S]g@}@g@_AAAYk@OUIOKUCCGO_@o@KUMS[i@o@oA{@{Ac@w@c@w@k@aAu@oAa@u@i@}@S[QWg@y@g@y@e@s@}AgCkCgEQYEG]g@_@o@c@s@m@_Ac@s@a@s@]o@a@w@k@iAa@{@u@eBgBaEc@aAs@aBq@{As@{Am@sAa@}@s@wAQ_@eAyBy@_B_AgBQ]]q@]o@m@iAu@wAs@qAa@}@[i@[k@[m@g@aAWc@CGMUCEIOKU[k@MUCEIOKSAAKUMUGKS]Q_@Ua@MUMUKSOWACS]S[MUOUMSMUEGIKMSOUMQMSGGU]MQOQMQOSOQMOOSOQOQY]_BeBUUQQQOOOGEYYq@k@YWYWMKeAaAIGGG_@[QOMMQOc@_@q@o@CAa@_@SOOOSQQOQQQQOOa@c@[[Y][]OQ_@e@_@g@_@g@k@y@OW]g@[i@Wc@[i@i@cAm@gAg@_ACE[k@_AcBCGi@cAs@oAEGa@y@i@aAi@aAOYe@{@sAcCEKc@u@Q]Q]QYYi@w@wAi@aAYk@EGGMMUMUKUMWKUKWKUKWKWIWKWIYMc@EMIWGYIWGYOs@G[GYEYG[Ks@Ms@G[Ku@c@eCSqAIg@CMGa@Ga@O_ACMQgAMw@SmASoA[iBCQIa@CMCMG[?AGWWeAAKEOK_@EQGSK]Oi@IWSo@Ma@Sg@Ws@M]KSISISMWKU?AKUMU[o@e@{@Yg@U_@_@k@IMMSOSOW]e@OSA?W[MQGIQQMOWYQQ[]SQOOSSOMOOQOQOQMMKWSSOOMe@[SMSMWQMGSKUMCCSIg@YIEME]QSIUIQIUISIUIA?QGSISGgAa@CAcCw@OEuAc@IEEAOEAAIAECOECAoAa@g@QUG}@YUISGSGUIUGSGUGSGSG_AU_AUm@MSGWEUESEUEUEUEUEUESCUESCA?UEUCUCSEUCq@GQCy@IK?QAMCWAUCQAC?SCy@GgAG"
                     },
                     "start_location" : {
                        "lat" : 39.95697010000001,
                        "lng" : -75.14461229999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "20.0 mi",
                        "value" : 32198
                     },
                     "duration" : {
                        "text" : "18 mins",
                        "value" : 1087
                     },
                     "end_location" : {
                        "lat" : 40.2851771,
                        "lng" : -74.6999022
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to continue on \u003cb\u003eI-295 E\u003c/b\u003e, follow signs for \u003cb\u003eTrenton\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering New Jersey\u003c/div\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "s_{sFxoahMOLA?_AC}@Au@?eA?[?Q?Y@a@@U?U@S?W@S@W@S@U@U@U@c@BK@SBU@UB_@Bu@HUBe@Dk@H_@D_@FyATYDQDi@JSDYDODSDSDSDYHSDSFSDWFQFWFSFSFUHSDUHSFA?SFUHUFSFSFk@Pi@PQDqA`@i@NWHg@NUFSFQF_@Ja@LUFSHUFi@Ng@Pk@Ne@NC@ODWHUFIBIBi@PUFUFg@Pi@Ni@NWHi@Ni@Pg@Ni@Ng@Ni@PUFWHSFUFi@PSFUFSFUHSFUFSFUFSFUHSFUFSFUH}@VUHSFUFSFUFSHUFSFSFQFWHSFUFUFSFSFUHUFQFUFUFSFUHUFSFIBIBSFUHSFUFSFSFWHSFSFUFSFWHi@P]HGBUFWHi@Pg@NA?QFSFSFUFSFUHUFUFUHUFSFQFSFYHSFi@Pi@NSFQFUFSFUFUHSFUFUFSFSHUFSFUFSFSHUFSFUFUHSFSFUFUFSFSHUFSFUFSFUFSHUFSFSFUHODE@SFSFUFSHUFSFSFWHSFUF}@XSFUFE@MDSFWHSFUFSFSFUHSFSFUFSFUFSFUFSFUFUFSFUFSDUFSFUDUFSD[Hy@PUDSFUDUDi@JUDi@JUDSDUDk@JUBSDUDUBUDSDUBWDSBUBUDSBUBUBUBUBUBUBSBUBUBUBSBS@C@U@SBU@c@DG?aAHM@G?UBU@U@U@U@U@S@U@U@U@U@c@BG?U@U@U?U@U@U?S?W@e@?[@U?i@?U@U?U?E?O?U?U?UAU?U?I?K?U?U?UAk@AUAS?WAS?WASAUAU?WAi@CUAUAUASAWASAA?SCG?MAUAUCUAIAKAUA]Ca@EUCUAUCSCkAKKAUCk@GSEUCUCUCUCSEc@GG?UEUCSEUCUEUESCUESEUEUEUESE[EOESEUESEKCGAUGSE]IOCSEUGUEUGSEAASESGIAKCSGGCOCQGUGSGWGQGUGSGUGSGUGSIUGSGSGUIUGSGUGSISGUGSGUIUGSGWI}@Y}@Yk@QQEy@WGASGSIC?QGQGEAQGUGQGUGCAOEUIA?SGg@Oi@QsAa@q@SEAUISGi@Oi@Qa@M[Ky@UEASISGUGUIQGA?SGUISGUISISGSKUIUKQISISKSKSKQKSMOICASMQMSKQMSMQOSMQOQMQOQOQOQOQOQOQQOQQOQQQQOQOQOSOQQSOQOSOSOUMQOSMUOSCEGKACMSOUMUMUOWMWYi@MYKWMUMYKYIQKUAAMYIUKSKWMYIUMWKYYo@IUMWKWKUWo@g@kAWm@GOQ]Sg@[m@Yk@AC[m@OYKSIOOWOWYg@QWMU]i@KOQWKOQW_@i@]g@_@e@UYIKSWY]i@k@]_@a@c@YYGIc@a@WW[]a@_@CA[[US_@]c@a@e@a@w@s@c@]c@_@WUKIw@o@a@[i@_@a@]OKg@a@OMQMCAOKQOUOa@Y[Ua@Wg@]e@[i@]eAq@m@_@u@e@ECMGQMUMe@WSMSKOKc@UmAq@[OSMGCKEQKUKSKa@SSKUKQIYMCAc@QECi@S_@OWIg@Qm@SQGg@Mi@Om@OKE[Gg@Mc@IOCu@Oo@KWEe@GSCk@IcAKy@G]Ci@CSAA?SAm@Ck@CW?kACk@Aq@?W?i@?U?qABG?i@@aABm@BU@S?cAFk@BO@YBm@DS@W@A@S@i@DUBUBU@UBUBUBSBUBUBUBUDUBi@HUBUBUDi@HUDUBSDUDUDUBSDUDUDi@LUDSDUDi@LUDi@Lk@LSFUFi@Li@NUFSFUFSFUFSFSFUHSFUFSHi@NUHg@Pi@RYHOFg@PSHUFGBi@RSFUHSFUHSHE@a@NUHg@Pi@Rg@Pi@Pi@Pi@R{@Zi@Pi@RSFSHMDE@UHSHSFUHg@PSFSHKBIBSHUFSFSFUHUFYHODSFUFUFQFUFUFSFSDUFSFUFSDUFUFSDC@QDSDA?SFSDUFUDSDUFUDSDUDODC?C@QBUDSDWDSDUDUDWDSDSDWDUDQBUDQBYDSBWDSBUDYBg@HC?QBSBUBUBSBWDS@UBQBC?SBUBSBWBC?QBU@SBUBU@UBU@SBG?M@WBU@O@s@DQ@YBG?S@Y@YB[@E?a@BU@W@S?U@W@S@U?U@Q?Y@U?A?Q@U?O@E?U?W@U?S?W?S@U?U?U?U?M?E?S?Y?U?U?SAU?U?U?WAS?Y?OAW?SAm@AMAY?[AI?IAUAU?m@COAC?WASAA?UAUASAC?OAWCK?IAOAC?UAEAOAUAG?MASCWAGAKAUAWCMAC?WCCAQAUCUCk@EGAMASCKAIAUCUCUCE?MCUCSCUCUEUCUCSEYEQCIAIAUEKAIAUEUEQCA?WEQEWCGCKAUEEAOCUESEUEIAIAUE?AUEUEQEC?i@MWGQEUEEAOEQGA?SGSESGUISGSGQGWISIUISGSISKSIUISISKSISKSKSISKSKSKQKSKSKSMQKSMSMQKSMe@[MICESMMICCQMQOSOQOQOQOQQOOQOQQOOQQOQQQOQOSQQOSOQGKEGOSOSOSOSMSOUMSMUMUOSMUMUMUKUMWKUMUKWMUKWKWO]GMM[KYKWIKGOKYIWKWM_@GQK]KWQk@Sq@GSGSCGGWIYIYIYGYIYIYGYGYIYG[GYGYACGWGYG[I[GWGYEWI[GYGYG[GYGYG[GYGYGYEYGYG[GYEYGYG[EYGYG[?AEWGYE[GYEYG[EYG[EYMu@Ms@GYE[GYE[GYEYG[EYG]EWG[EYG[E[GYE[GYAGCSUqA[kBE[G[Ia@Im@G[EYG]EYGYE[EYG[E[GYKs@G]E[GYE[E[G[EYEYG[EUAGEWG[E[GYG[EYGYGa@EUGYGYG[GYGYG[Ko@I]GWGYI[GYWcAEMEO]mA_@oAGMKYIWKYKWKWO_@GOKYIYKWKWMYACIQMUKUMSMUGMUa@_AmB{@eBa@{@S]Ue@Ue@iA_CqA{Ck@mAYq@g@aAy@eBUg@OWKUISKQIQIOKQACGKGOIQi@eAEKUe@Sa@MUMUMSMUMSMUOS_@g@]c@MO]e@SUIKKKIGoB_BCCQMSOQMSOQMSOUMcAq@EESKQMUMOKSMQMSMSKQMQMQMQKSMQMQMQMQKSOOKi@]UOSMUOOKSMSOQKCCOKQKg@[OMg@[]WEEe@[e@]QOQMe@_@c@]c@]SOQOc@_@e@_@a@_@c@a@c@_@IIWWc@a@[[EEc@c@q@s@c@c@a@c@a@c@_@c@a@e@KMUW_@e@_@c@_@e@_@g@_@e@_@g@Y_@GG]e@OSOSIIEGOSOSOSQSOSo@y@o@y@OSOSOSOQOSOSOS_@g@q@w@ACMOOSOSOQOUm@u@ACOQKOCC_@g@OSo@{@_@e@eA{A]c@SYgAwAEEW[g@s@m@u@IKa@i@cAoA_@c@Y]KMc@g@g@k@c@e@cAeAu@y@eAcAu@q@u@w@{@{@_@[iAiA}G}GEEUU{@u@ACaB}A_@_@]]_@_@[Y[]US_@_@]]OOWYq@o@IKcBcBSSQS]a@Y[GIo@y@[a@m@}@GIGKOUMUIMCGOUIS_@q@]q@Ue@KSMYSg@MYKWIQEKKYKWQg@K]K[Ma@Oi@Qo@I[GUI[GYI_@GWGYCQEUEQEYGWCUIa@CYEUE]G_@C[EWC[CQCWEe@AUCQAUASCUAUAYCk@Ca@A[A]AWA]?WAe@?G?O?OAa@?a@@]?s@?g@@u@@gADgBBiBDmC@e@@_@@g@@}@@}@@w@BkADqC@}@DcCH_FF_CBcB@w@?]@kA@U?O@wA?{@?IAgB?g@AgA?iAASA}ACy@?EE}BC_AIwBCo@AKQwD?ACc@GiAOyBMgBO_CIgAKaBCQWqDK_BO{BG_AGs@GaAIiA_@kFOaCm@yIIkAGy@GcAKsAOsBAQIsAUaDEk@WwDM_BMkBK}AEe@A[MoBIuAEk@Ck@Eu@Cw@A[Cg@Ak@A[?i@Ak@?y@?[?]?[@]@[Bw@@[Fy@Fu@D[Fm@Hg@BQF]Ls@H[Hc@BGT{@Ro@Vs@^aARi@Na@Vo@`@gAn@}A\\{@Tm@J[^aARo@Pe@b@qAZcADOZaARs@Rs@b@eBPs@XmAF]FWPu@P{@ZaBN}@TiAL{@F_@Fa@Fc@F[\\yCRaBVaCHaADc@H}@BY@WDi@Dk@HyABm@B_@Bi@Ba@Bs@DgABk@BaABkA@yA@m@?[@iA?iB?aA?SA{@AeACkBAg@GiCIcC?CMaFE_BCg@CeAAk@?UC{@?M?y@?a@A[?u@?S@i@?c@?_@?Q@_@@eA@i@@g@@C?EFyBFkA?MFeADm@Ba@LiBJoAH{@J{@H{@NuAHs@P_BRuBD[PeBJmAHeADk@Di@D{@@ABs@Bc@B[JeCBiAB{A@w@@[@}A@aA@a@@g@DaFBqBFyD@iBB_BBcCB}ABkC@]?]B_CBgB@g@@}B@yA?oA?Q?aAAsDAe@Aq@Au@CeBCaAEyA?UGcBKmECq@Ai@[sMAOAc@K}DCs@CcAKuD?[Cu@E{ACuACm@EyBG_CIaDCaACuAA]?WEuAAY?A?WA_@A[A[?]AY?I?S?WA]?u@?Y?_@@[?w@@Y?K@Q?[@[@[@Y@]@Y@Y?AB[Ba@@[@QB]BYBYBYB]D[B[Hq@D_@BYD[DYDYDY@GDUDWHg@Hg@Ns@Nu@DWFWHYF[FWFW"
                     },
                     "start_location" : {
                        "lat" : 40.120425,
                        "lng" : -74.8878057
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "15.1 mi",
                        "value" : 24269
                     },
                     "duration" : {
                        "text" : "21 mins",
                        "value" : 1241
                     },
                     "end_location" : {
                        "lat" : 40.438803,
                        "lng" : -74.5071775
                     },
                     "html_instructions" : "Take exit \u003cb\u003e67\u003c/b\u003e to merge onto \u003cb\u003eUS-1 N\u003c/b\u003e toward \u003cb\u003eNew Brunswick\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "ke{tFjy|fMVY@CDMHSHWJUHOLS@ARWJKJGFETKZKx@UXI\\MPGx@YVKNGRMFEDCHGDEFEDGHKHK@AHMLS?AHOHQ?ABEDMBIBG?A@ABKH[?AJi@?A@CFe@@??AB]BM?A@M@a@@W@O?M?S?Q?A?GAU?MC[AWCS?AEYCOCMGYACGUIQEKKWAAAAMSGMAAOQOMIIMKECYO[IICIAMCMAK?Q?K@K?K@Q?}@P_@DWBQ@Q?U?MAKCIAICICKCICKGWMQOIIKIMOQS[_@k@q@aBqBKKGCGESG_HaJkCmD}CcEe@k@uCqD_@g@sDwE]c@EIm@w@cC_DgDgEmA{AmEwFuAmBsBmCuBkCgAuAm@w@aAsAyAmBeC}C[_@a@g@qAeBaDcEiEsF}D_Fo@y@y@eAyEcGeAuAs@eAWYeAuA_AkAKMeCcDe@k@iB}BAEMQOOU[aBwBeAqAaAmA{@iAg@o@c@m@{@gAMOaAqAyD_FyBuCOSECQWoCmDCCIKCCCECCCEmHmJgEqFKKgFyGsAeBcBwBe@k@{@iAEE_AmAcAqAUUk@u@WYw@gAiAyACE_CyC}C_EsBkC_CwCwDaFo@y@[_@sBkCoA}AqAcBU[Y_@_DcEaD_E_AiAk@s@Y_@iL{Ns@aAY_@Ya@QWgBaC}AqBg@s@}@gAAAm@u@eAqA_AmAwBoC}C}D[_@s@_A[_@iDkEsCqDcC_DuBoCuBkC{AqBaC_D[a@[a@[c@_@c@Y_@uBwC{@eAY_@cC_DgByBu@aAu@gAcCaD_@_@s@}@k@w@o@_AqCoDGI[[{C_EiCeDm@}@oGiIa@e@gFuGg@o@e@o@oAgBa@g@]_@uFkH]i@o@y@U[mF_HwAiB}FsH}B{Co@y@QUOECCc@k@cByB}CaEeB{BmBcC}EkGIQkF_HoFcHIKi@s@s@_A}AoBkCiDmB_C}CaEsAcBYg@u@}@GIqAaBaByBW]o@y@c@i@sE}Fu@_Aa@g@cCaDY_@uFkHk@s@}@kAiBaCyC{D{C}DkDsEgAuAiHkJ_MaPoAaByAmB[g@QU[]Y]}AqBKMc@k@cCaDU[}@oAoAaB_EgFuAiBiEuFsAgBwC}Dk@u@{C_Ek@s@UYOS]c@mA}AwAkBm@w@}AoBAAs@_AyAkBaCaDsDwEY_@iB_CoBaCMSgF_Hm@y@_@e@{@eAiB}B}@kAgB_CiB_CqEaGm@{@}@gA[_@oBgCyAoB_DcEiBaCcBuBi@s@cAuAmBeCs@_A[_@QW{@eAsAgBaEkFY_@s@_Ao@y@Y_@u@aAgB}BW]y@eAY_@_@e@y@gAoA_BgB}Bk@u@]e@oA_BoA_Bs@_AmA_BoAaBeEsFsE_GmA_BoAaBoA_BY_@_AmAgBaC[_@kBcCQUQSgB_CmCkDaCaDoA_BcAuAoE}FiBaCs@_AY_@iBaCY_@Y_@oBiCk@y@oCqDW[]c@w@aAeAuAk@s@GIW_@{@gAW]W[uAiBQUKM[c@]c@oJaMoJaMEEc@i@Y_@SYY_@y@gAW[QSwBqCcEmFY_@QYuCwDc@i@kA}AUYOSs@}@iAyAqAcB_HaJwBoCeBcCuD}EIMmAcBwBmCc@g@_BwBoAcBY_@OOUYc@i@"
                     },
                     "start_location" : {
                        "lat" : 40.2851771,
                        "lng" : -74.6999022
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 mi",
                        "value" : 682
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 33
                     },
                     "end_location" : {
                        "lat" : 40.4433118,
                        "lng" : -74.50172169999999
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eUS-1 N\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "oeyuFzdweMsCsDmA_BiCgDy@cAuAiBiDmE_BsB_CwC"
                     },
                     "start_location" : {
                        "lat" : 40.438803,
                        "lng" : -74.5071775
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.6 mi",
                        "value" : 2556
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 142
                     },
                     "end_location" : {
                        "lat" : 40.4564376,
                        "lng" : -74.47802159999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eUS-1 N\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "uazuFvbveMaFqGOSaC{CaC}CuD}EaBwB_BqBm@y@CCqAkBwBoC_@a@mA_B[a@AEeC_Da@i@_AmA]c@i@s@W]o@y@sAgBk@u@KMQUc@o@KMEIMSOSKSA?MUMSMWMUMUMUMUKUO[Wo@o@{AKWIUKYKWKYGSK[GSK[IUI[KYGSAEIWCMEOIYG[I[EUI]EYEYGUEWG[E[GYEYG]E[AGCUCWAAC[EYE]C[CWE[C[E[C[SeBCWUiCQgBYwCW}BMoAAKCOEWE]CICME[E[GYEYQq@"
                     },
                     "start_location" : {
                        "lat" : 40.4433118,
                        "lng" : -74.50172169999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 mi",
                        "value" : 1494
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 79
                     },
                     "end_location" : {
                        "lat" : 40.4609907,
                        "lng" : -74.4614072
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eUS-1 N\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "ws|uFrnqeMIa@g@sCo@iDi@}CcAyFgCiNKo@]oBe@kCKg@qAgH[wBOu@UsAe@gCUiA_AeFwAaI]iBGm@kAgG"
                     },
                     "start_location" : {
                        "lat" : 40.4564376,
                        "lng" : -74.47802159999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "3.8 mi",
                        "value" : 6195
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 246
                     },
                     "end_location" : {
                        "lat" : 40.4967865,
                        "lng" : -74.41159100000002
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eUS-1 N\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "ep}uFxfneMGYSqAUgA_@wBUkAMu@_AkF_CsMKq@c@mCiAkGa@yBaAaFo@qDUuAQiAc@eCk@}Cc@cCk@_Ds@oDOy@k@_DUmA}@iFsB{KKo@O_AQaAIc@Ie@Ii@Ik@Ki@Ks@WyAUwAKm@Os@Os@Kg@G_@Kc@GWCGKa@?AOe@Mc@Oa@Oc@Sg@Se@Sc@Qa@uA}BMSSYOSOQOUQUQUUYi@u@wC}DqAcBoBgCc@k@Y_@mA_BuAgBw@gAoAaBY_@uAiBk@{@mA_BaAqAq@s@y@iAy@gAcAsAi@q@cByBuDeFaAiAyBsC_AqAo@y@eAyAa@c@a@e@a@c@a@a@c@c@c@_@c@a@c@_@c@_@m@g@KI_@WAAw@s@aAu@wBgBiAaA_CuBSQg@_@uAgAsAgAc@a@i@e@MKkC{BQO_Aw@u@m@gAw@A?gBqAaAs@oAu@k@W_@Qg@MkAWcAOw@I{@Io@Ak@Ec@CCAcAMsCWsC_@kCc@wCe@i@Mq@KOC_@G_AMm@I]GKCYG_@Kk@QKEUK_@SKGQKOIQKEC"
                     },
                     "start_location" : {
                        "lat" : 40.4609907,
                        "lng" : -74.4614072
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 213
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 10
                     },
                     "end_location" : {
                        "lat" : 40.4982121,
                        "lng" : -74.4099519
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eUS-1 N\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "}odvFlodeMOISMe@_@[[QQk@o@aAuAS[a@_A"
                     },
                     "start_location" : {
                        "lat" : 40.4967865,
                        "lng" : -74.41159100000002
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "4.2 mi",
                        "value" : 6749
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 446
                     },
                     "end_location" : {
                        "lat" : 40.5341808,
                        "lng" : -74.34622659999999
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eUS-1 N\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by Wendy's (on the right in 1.5 mi)\u003c/div\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "yxdvFdedeMuAaDe@kA{BeF_AyBAEIQAC?AISeAeCYm@c@cAqAeD}AqDi@iA}@qBwAkD_@{@{@qBa@w@sA_DO]aA}Bg@sAKQy@iBo@yA]{@KSy@oBiBiE_AwBwAgD_A}Bw@iBa@aAWm@Wi@]{@{@sBm@qA[u@M[g@iAWo@]{@cAeCGOWq@Qk@GOKYGSKWEO[cAi@aBK]IYGSGQc@qA[{@Qi@GY_@kAi@eBI_@Oa@]kAeAgDa@qAs@{BeByFc@qA[}@i@gBISa@sAISa@qA[eAs@uBM_@m@qBc@yA[aASu@g@{AACUw@a@qAm@mBY}@Y}@}CsJAEeBqFUo@c@kACGM[CEy@uBe@aAaAwBUi@cCgEwAcCcAwAMO]k@uEwGe@q@}@wAgA_Be@o@eA_BqBuCo@cAYa@a@k@KQ]a@wEaH_BgCEGiAeB{AyBaBeCaAuA_AwAqAqBQWWa@q@cAGIaA}ACC?ACCk@w@MSIMwB_Ds@cAqByC{FcJ{AaCy@mAwBgDYa@QY}@uAy@sAwAwB"
                     },
                     "start_location" : {
                        "lat" : 40.4982121,
                        "lng" : -74.4099519
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.1 mi",
                        "value" : 3310
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 187
                     },
                     "end_location" : {
                        "lat" : 40.5532154,
                        "lng" : -74.31621939999999
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eUS-1 N\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "sykvF|vwdMYa@iBqCMQYa@g@w@IKiAeBYa@Ya@e@u@g@s@S_@mAgBW_@gAaBo@_AWe@g@s@GKCGk@{@aBaCgBoC[e@a@o@g@s@g@s@u@iAgBoCa@k@wBcD{@qAmAiBU]sAoB_@k@IMKOS]{@wAm@eAc@{@oAiCO]kAeCw@gBKUi@kA}CwGs@wAuAyCq@yAa@}@oAqCcAwBoAsCiAaCoFoLaAwB{@gBM]cDuGgE}I{@iBSe@wA{C[o@"
                     },
                     "start_location" : {
                        "lat" : 40.5341808,
                        "lng" : -74.34622659999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "11.0 mi",
                        "value" : 17637
                     },
                     "duration" : {
                        "text" : "11 mins",
                        "value" : 634
                     },
                     "end_location" : {
                        "lat" : 40.6913108,
                        "lng" : -74.2672097
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e to merge onto \u003cb\u003eGarden State Pkwy\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "spovFj{qdM@S?E?AAICOEOCQCM?K?C?I?M@S?A?ABMBOBOFQFMHMFKJIHGJGLENELA@?H?J?F@JBLBFBLFLJHHHJFJDHDLDLBPBPBT?T?LATCPEXGXKX?@IREHGJEFGHEFGDCBQLGDGDEBSLc@RYNIDuAt@?@EXs@Zc@RSFIDMFa@N]Ny@Z_@Lc@Pa@Pk@RYJWJaA\\q@V{@Zy@XkAd@m@RYJy@\\sAh@g@PWLSHSJo@X[Nc@Ra@RiAj@WLm@Zy@b@cAj@mAp@_@RMHKDo@\\_ErBgAj@c@VSJSJy@b@_Af@g@VKDMFC@a@Ra@Vq@\\IDKFWJuBjA_Aj@aAl@cAp@s@d@MJ_Al@i@^{@n@cAr@e@\\q@d@g@`@YPUPc@\\eAv@WPKHkAz@sBxAy@j@SNUNUNiAr@m@^MFQJOHEBk@Vo@ZSHm@Vg@RA?SHQFWJE@}Af@i@NKDgAVUF_@JeARWFi@Hi@H}@Jy@J_AFM@s@Bc@Bs@@e@@o@?eAAs@AGAm@Ai@C?Ag@CaAIQCQAYCYEGAs@K}@OC?c@IMCOEQCAAMCm@OYIc@M]KKCe@QWIe@QA?}@_@o@W]Qs@]g@Yo@_@IEi@]WOQM{@k@y@i@k@a@iAq@QKc@Yg@YQK{@i@cAm@aAo@g@[c@WmAu@e@[eAq@GEGCiBkAwA}@GEk@]y@i@k@_@kCcBEAgAs@_BcAcAq@cAo@a@We@[{@i@m@_@KGcAq@cBeAkAu@w@g@s@e@aAm@WQa@Wy@g@_BcAk@_@qA{@IEiAu@aBeAOKo@c@OKMI]WiBkA{@k@sA{@cAm@aAi@}BwA[SuA{@iAs@sA{@yA_AkAu@o@c@[MQMQKSMKGGEe@[w@e@SMQMSKSKSMe@Si@YSIMGCAqAi@g@SWKw@Wm@SOEWGe@OUGSEUGSEUEEAa@KUE_AQi@KQCuAUi@IUESCi@IUCsAOy@IoAMa@Ga@EQC}AQ_AM_@E_@Es@Is@MKAIAUEOAYEo@Ie@Gs@Is@Ii@Im@Gw@Kg@G}AQUCoC]WCIAGAUEUCSCWEUCGA[EOCSEKCOCKCGACAQEUEq@QWG]IQEGCQEOCMEUISGYIA?MGg@OWKQGUIQIQGy@]oAi@KGQI_Ag@UKOIIE[Q]UIEQMSMk@]_@WSOk@a@eAw@a@][Ua@]MMOMUUSQOMg@g@CCAAAA{@}@qByBOSUWSUSWKK[_@UWOSSU_AgAGIWYi@o@i@m@KMEG[]OSa@e@A?KMIKUWOQSUgAmAa@g@sAaBGGmAwAgCwCgBsBa@c@[]c@i@e@i@q@w@c@i@a@i@u@cA]e@_@i@a@o@]e@Yc@a@k@Ye@[c@]i@Yc@W_@i@y@a@o@GKg@u@c@o@OUY_@[c@IKUY_@c@KKMO]_@IIk@k@AAu@s@e@c@CEk@e@KKKIe@a@k@e@m@g@a@[i@c@a@]k@a@USq@e@YUkBwASOKI[UMIGG]USOs@c@WQc@[MGGEMIYQKG]Sq@_@UKw@a@YMcAe@iAe@QGSIuAg@aBg@g@Ok@OA?QE[I_BY_@Ik@IUESEUCUEUCSCUCWESAUCUCWCSCUAUCk@CWAUAUAUAUASAWAU?WAi@AU?S?W?k@A_@?K?U?W@i@?aA?M?I?U?kCAq@?}A?i@?]?[?[?U?_AAQ?]?e@?k@?c@?c@?g@?iAAQ?k@?uBAqB?m@?}DAg@?g@AoA?k@?q@?eAAm@?k@?k@?g@?K?e@?KE[?I?cA?]?y@A{AAm@CYAm@C{@GqAKy@KKAaBUc@GoAUi@KyA]a@KYIGA_AYKEg@OWKc@O]Mw@YIEu@[YM_Ac@}@e@AAs@_@KG[QOIcAo@SOs@e@QKaBgAMIkBoAEESMmAy@SOc@Y]SYSg@]IGw@i@qDcCi@_@_Am@_Am@YSQIe@Y_@UQKGEg@WOIs@_@SIg@UQI]Q[MEAYMSIeA_@AACA_A[GAs@SMEk@QWGi@OiBa@sCi@s@MsAW_AOWE{@Q}AYkB]c@I[I]Ia@IYGWIUG_@KQIi@Si@U]QWMSMSM{@i@[SMICAe@[{AcAa@WOKe@[c@WMIKGOKgAm@YOo@]u@_@[QUMmAu@s@e@YSMKMKOMe@a@a@_@y@w@SQmAoAc@g@_@c@_@e@[a@GIi@s@_@g@_@k@c@s@KQ]m@]m@s@qA]u@Qa@Uc@Ui@[u@c@eAm@yAg@sAKYMYCG[{@"
                     },
                     "start_location" : {
                        "lat" : 40.5532154,
                        "lng" : -74.31621939999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 mi",
                        "value" : 966
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 56
                     },
                     "end_location" : {
                        "lat" : 40.6957092,
                        "lng" : -74.2576031
                     },
                     "html_instructions" : "Take exit \u003cb\u003e140\u003c/b\u003e to merge onto \u003cb\u003eUS-22 E\u003c/b\u003e toward \u003cb\u003eNJ-82\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eHillside\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "uojwF`ihdMBa@?CACKWGSG[E[AQAKCc@?IEq@?ACc@CWAECWG[AEIa@GW[oAUg@OYKSEEIMEIEIKMIMOSWYIICGEGEEEEQIk@_Aq@iAUa@_@o@OYMWe@eAYm@g@gAUi@ISCGGOACCGGQISIYo@_BY{@M]Ma@Oi@Uy@K_@EMAEOk@Uy@GYGU"
                     },
                     "start_location" : {
                        "lat" : 40.6913108,
                        "lng" : -74.2672097
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "4.3 mi",
                        "value" : 6861
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 326
                     },
                     "end_location" : {
                        "lat" : 40.7063119,
                        "lng" : -74.1828137
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eUS-22 E\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "ekkwF~lfdMa@kBK][}A]eBw@kEESG_@Mi@Oy@AMGUAI]iBKi@GWMq@Ii@i@uDEk@AQAUASAQ?CCi@Cs@EuACs@Ca@Cw@E{ACm@C_@EkA?GEwAIgBAc@Cs@ASAWEeAOkECaAC]C]AMAMCYGg@COCOAGCUMeAGc@Io@G_@AIACGc@c@_DQqAGYYeCIo@ACMoAM_AEm@AUAIAMA]A]ASAk@Ak@Aw@Ag@Ai@AmAA]A{@?KAo@CeC?GIiGCqB?}@@oA?K@a@DkABkAF}AH}ADoA?Q@[@O?ADkA@]Bk@?K@I@o@Fy@HcALcAPqAF_@Je@XmALc@FSZeAt@mCTy@HYBKNs@Jo@NcA\\gCd@qDPwADg@B_@Bq@Ba@?K@UDaADeBB_@HeCDaABcALkC@m@@S?U@E?M?Q?A?A?GAWAS?EASAQAQCQAQCOEUCSI[CKEOCKAAAEAAI[CCCIMU[q@]o@KSMW[e@S[IOKMQWU[Y_@mAcBs@gAY_@U_@AAS_@KWM]M[Me@ACI_@CKEYE_@G]Ce@C[IcAIcACOAIAKCKEUEOCIAEG[GOGQAGCIACEKEMCCGQSa@MUEGGK[g@CGU_@IOMWk@kAUa@aAoBAAuHkOUa@?AyAuCUe@oByDO[EIUc@_AmBAAUc@?Aa@u@yAyCi@cAyBmE{@kBS]Wm@IW]eAM_@GWIYESCM?AEQEYCMIe@Eg@Ga@Cc@Ek@AU?A?OCg@?c@Co@?o@C}AC}AA}@A_@OyH?SAi@IuGAcBC}@CmAG}B?S?C?C@EAw@Ay@?UAc@?a@?a@@Q?C?Y@O?G@Q@Q@S@SBUBUBK@ID_@F]@ADSH_@BKBKFUFMHSVq@LYr@gB\\w@h@kAHQJSh@kARe@P]"
                     },
                     "start_location" : {
                        "lat" : 40.6957092,
                        "lng" : -74.2576031
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 mi",
                        "value" : 807
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 41
                     },
                     "end_location" : {
                        "lat" : 40.7084111,
                        "lng" : -74.17433219999999
                     },
                     "html_instructions" : "Take the ramp on the \u003cb\u003eleft\u003c/b\u003e to \u003cb\u003eUS-1 Express N\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eUS-9 Express N\u003c/b\u003e",
                     "maneuver" : "ramp-left",
                     "polyline" : {
                        "points" : "mmmwFpywcM?G?E@C?EBGBIDS@IBM@G?EDY?K@C?E?G?G?KAK?AAICOCQEOEKGMKQEIEESYCCw@gAQWk@{@]k@KQYg@IMUc@]o@CCCGGKi@kAEICICGCICGCGCKAECGEQCMCOEY?ECM?CCW?GAY?M?K?Y?M?E@{C@mA@k@@aB@sA?gB?A?AAA?C?AAAEM"
                     },
                     "start_location" : {
                        "lat" : 40.7063119,
                        "lng" : -74.1828137
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "6.3 mi",
                        "value" : 10167
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 423
                     },
                     "end_location" : {
                        "lat" : 40.7390955,
                        "lng" : -74.0681455
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eUS-1 N\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eUS-9 N\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "qzmwFpdvcM@eADiEDwDBaCBwA?A@q@@{@@oA@c@@o@?u@@yA?}@?y@Au@C}BC_AAQM_EOyBK{ASmBSoBAMg@gEWoB]cBW_AYiAAAK[ISAC?AMWEKCGCEMYQ[GQEKAA?AA?CG?Ak@kA_AgB{@}AMS}@wAi@{@S[CE]e@EGw@eAm@u@CEu@y@W[ACkB{BIKa@g@Y]IM[]W][a@[_@[a@c@i@OOY_@[a@SWIM_@a@]a@MOc@e@SSe@e@MMMKQQSQs@m@SQc@_@AAu@m@_@Oa@Y_BgAkAy@y@m@wDoCg@a@QMMKCCc@]c@_@SQMMSQQOOOSQSQMMg@g@OQQQGIY[OQQQOSOSMO_AoAwAuBa@o@}@}AcBaDSe@[k@Se@iAaCMUi@iAo@sAQ]]s@GMe@aAeCoFoAiCAC]w@_@y@Ug@]u@q@uAAEa@}@a@w@k@oAq@yAcAwBu@}A?Ae@cAACSa@e@cA]s@ISCEcBqDw@cBoAkCSa@Q_@gA}B_@{@GOeAyBm@oAWi@yAyCYk@q@uAgAwBw@_BQ_@Q_@Q_@IOi@oASa@EIIWA?KYISGUQi@Oc@So@CKGUESMi@GYE[AG?AAECMMw@Ky@AIE[Gs@C[C[C[Ew@Ee@Ae@Cc@?UAK?O?AA]?[?[?G?K?k@@_@?q@@s@BaA@w@?[@C?_@@]FwE@a@@c@@}AB_BFcF?SB{AB{AByA@o@@m@B}AByCBaA@aA@e@@s@BoCB{A@s@@wA?]@Y?]?Y@uAB}@@w@ByAF{BBqA?W@W?_@@]?Y@_@@c@?S@c@@u@?C?YB}@@qA@Q?I?G?S?a@?M?O?[?W?Y?]Aq@?i@Au@A]?_@AK?SAWEcAAYCs@?_@ASAc@A]Ca@Aa@?CA[AOCc@AUA_@A]C_@AW?GIoBEy@A_@AUEaAAWCu@Ck@AKC_AASA[AACk@?QEu@AU?EA]AK?MC]?AAYAU?ECi@Cm@A]AQAIGwAAa@A[A]C]Cw@A[Ey@A]Cc@?UCo@AIA[A[Ew@G_AASCa@AMEm@C_@AQEs@Ie@Ec@Ec@E_@Ea@E_@E_@SuBGk@E[Gs@Ky@E]Eg@CKC[Iw@Ea@EY?E?CCSC[AUAGC]E_@AUA[C[C[Cg@CQKy@C[M{@Iy@Iq@E]Ge@I_@Ga@E]EW]_DAKAGAM]_DGe@i@sFa@gDQgBSgBW}BGo@CMCWOiAE_@K{@Ea@Ee@K_AGk@CYM}@K}@AOAQCQCQAOCQCWEa@C[?ECSEa@G{@AOCQCa@Cc@Ca@AWAe@Ca@Aa@Ac@Aq@CiAKyEEoB"
                     },
                     "start_location" : {
                        "lat" : 40.7084111,
                        "lng" : -74.17433219999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "1.7 mi",
                        "value" : 2771
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 356
                     },
                     "end_location" : {
                        "lat" : 40.7300025,
                        "lng" : -74.03974120000001
                     },
                     "html_instructions" : "Keep \u003cb\u003eleft\u003c/b\u003e to continue on \u003cb\u003eNJ-139 E\u003c/b\u003e",
                     "maneuver" : "keep-left",
                     "polyline" : {
                        "points" : "kzswF|lacMCYAs@CqAAq@Aa@?OEyA?ICmBAkA?e@?G?UBa@Be@Do@?S@M?S@c@@]?Y@Y@M?MBYHqA@SB]NyABSDa@D[F_@He@H]BIFSHWL[JWLYNYN[JSDIJQHQJOf@q@`AmAt@}@LQvBiCh@q@bAkAr@}@t@}@Z]LS`@g@NSNSNQNQNQPU\\a@|AmB|AmB`@e@`@g@PSpB}Bb@i@TYLMLOZc@JMT]HMNWJSLWJWFOBIFSBMDQDSBOBOBO@OBS@Q@O@Q?M?O@i@B_C@_@Bo@DuAJcCD{@Bq@Bq@D_AF{AHaBB_@@a@LcCJiBFq@BSBG@EBEDEBUBi@Bk@Bq@?AJcCBq@DmA@[@K@]@MB{@Dy@Ba@@Y@]Bc@@IB]LsBDc@"
                     },
                     "start_location" : {
                        "lat" : 40.7390955,
                        "lng" : -74.0681455
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "2.1 mi",
                        "value" : 3331
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 291
                     },
                     "end_location" : {
                        "lat" : 40.7209852,
                        "lng" : -74.0070508
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eHolland Tunnel\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eToll road\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003eParts of this road may be closed at certain times or days\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering New York\u003c/div\u003e",
                     "polyline" : {
                        "points" : "oarwFj{{bM@OPsB?CBuADeAB{@DeB@aC?a@@Q@OBWBWDY@IDc@Da@PeATwAJm@DUTyADUFYDWHe@XwADUZkB@CLu@Fu@@S@G?Y?ABmBx@sSLeDL}AFm@TkCh@uGFo@TiCTkCTkCfAoMFm@Fo@p@cIFo@Fm@Dm@L}APmBNyB@IJcCZyGBo@Ds@Dk@Fi@Je@@ENi@Tu@L]@CDMVg@\\g@^k@Va@|AaCT_@\\k@h@u@v@kAf@}@f@{@PYP[nCiE@?FKDEFIDEDC@?LGJA@?FAL?J@L@H@HBJBFDHDFHFHDFBHBHBHBL@J@@?J?L?B?h@?L@H?HBJBJBJFJFFFFDDFB@?FBF@F@H?FADAHCDEFEHIFKDI@G@A@E@M@K@KAK?IEQCOEICEMM"
                     },
                     "start_location" : {
                        "lat" : 40.7300025,
                        "lng" : -74.03974120000001
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "164 ft",
                        "value" : 50
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 14
                     },
                     "end_location" : {
                        "lat" : 40.7211308,
                        "lng" : -74.00655859999999
                     },
                     "html_instructions" : "Take exit \u003cb\u003e4\u003c/b\u003e toward \u003cb\u003eDowntown\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "eipwF`oubM@I?G?CAC?ACAECCCA?CECECC?CAA?E?A?G?I@K"
                     },
                     "start_location" : {
                        "lat" : 40.7209852,
                        "lng" : -74.0070508
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 320
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 74
                     },
                     "end_location" : {
                        "lat" : 40.7182888,
                        "lng" : -74.00712129999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eVarick St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ajpwF~kubM`@Dd@Fd@DPBFBvALl@Fz@Jj@HRBNDrAJhAP"
                     },
                     "start_location" : {
                        "lat" : 40.7211308,
                        "lng" : -74.00655859999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "256 ft",
                        "value" : 78
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 20
                     },
                     "end_location" : {
                        "lat" : 40.71768369999999,
                        "lng" : -74.00754460000002
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eW Broadway\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "ixowFnoubMJC`@ZXRPN^V"
                     },
                     "start_location" : {
                        "lat" : 40.7182888,
                        "lng" : -74.00712129999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 mi",
                        "value" : 446
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 165
                     },
                     "end_location" : {
                        "lat" : 40.7155837,
                        "lng" : -74.00303769999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at the 1st cross street onto \u003cb\u003eWorth St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "otowFbrubMPg@Rg@d@qAPi@Pg@FOfA{CLa@Zy@Vw@Pc@FS`@kA|@yBZy@JW"
                     },
                     "start_location" : {
                        "lat" : 40.71768369999999,
                        "lng" : -74.00754460000002
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 221
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 71
                     },
                     "end_location" : {
                        "lat" : 40.7136653,
                        "lng" : -74.00364089999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eFederal Plaza\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eLafayette St\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Lafayette St\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kgowF~utbM^@d@D`@DVBJ@D?XFn@Pf@L^JTHD@^LFBTP"
                     },
                     "start_location" : {
                        "lat" : 40.7155837,
                        "lng" : -74.00303769999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 166
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 60
                     },
                     "end_location" : {
                        "lat" : 40.7124771,
                        "lng" : -74.0048252
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eCentre St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "m{nwFvytbMXVJHFHv@t@`@^^\\RPXXDFDDBDFL"
                     },
                     "start_location" : {
                        "lat" : 40.7136653,
                        "lng" : -74.00364089999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "262 ft",
                        "value" : 80
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 22
                     },
                     "end_location" : {
                        "lat" : 40.7121273,
                        "lng" : -74.00565469999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003ePark Row\u003c/b\u003e",
                     "polyline" : {
                        "points" : "_tnwFdaubMB@FLJXDNHV?@DJBHBJBHJb@"
                     },
                     "start_location" : {
                        "lat" : 40.7124771,
                        "lng" : -74.0048252
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "220 ft",
                        "value" : 67
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 15
                     },
                     "end_location" : {
                        "lat" : 40.7124882,
                        "lng" : -74.00625260000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSteve Flanders Square\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eRestricted usage road\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "yqnwFhfubMWR?@A?C@A@?@A@?@A?W`AIRA@"
                     },
                     "start_location" : {
                        "lat" : 40.7121273,
                        "lng" : -74.00565469999999
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : [
                  {
                     "location" : {
                        "lat" : 40.5327223,
                        "lng" : -80.24371599999999
                     },
                     "step_index" : 46,
                     "step_interpolation" : 0.4503750026059003
                  },
                  {
                     "location" : {
                        "lat" : 38.9956819,
                        "lng" : -77.0801546
                     },
                     "step_index" : 73,
                     "step_interpolation" : 0.2742353134103059
                  },
                  {
                     "location" : {
                        "lat" : 40.025969,
                        "lng" : -75.29790199999999
                     },
                     "step_index" : 102,
                     "step_interpolation" : 0.981327479539589
                  }
               ]
            }
         ],
         "overview_polyline" : {
            "points" : "czjaG|zzyNwJvpDt|CxwDxjMpyRpxFn~EbzKtAb{Ipu@j~BluB~`HvsGh{HrsGn_K~cClyTbbQnrOxzD|rEzhAbaEafDn}DwkCcJuz|@nBueHpnCkt@h|HenMbcE{gIywAokK`h@_aIhtGiuCnoI}|One@mpPoAm`LteEauCrKw~LoyDo{Sad@_uRim@w_Qpm@_uIigAqkFq{CkhB}uCsoGay@cy`@mD_}Y|g@yxDtwD{|@~aCm^fc@moK}oAexH|o@koH`iGiD~_FqdD~oHu{KhqJyvQfgEk_EnzBc{IhuIe|JhsB{uKyDayHaCih_@axAwwS_QstB~jAkkBhwHi^j`MacDjgJk[lvGu`IhnB_mQd}S}~g@dfJjb@nvCagFf`Eim@lyDaSfoFa`ElqHwrBue@uvBhhApdBdwAhEncA|mAjtBi~BnjAyoEfpDopLloB}_H~kCyj@hmBw{@|hAxdBv}HhjEtvEvmC`gBau@tqBltDl~FtmHvgC`|@frBa}FbkHT`gK_{BrvEukAhiDrwAriKi_CbpKocFdfI_lEl~MkdFtvEcj@ncCw`B~lG{rEhsJudDyj@owGqsEmdDwhH{gIrsA{xD_N{kDz{@a_MshAsjIve@ygG}EwvQpW}_RmvCuaKavBeoIrJmqI`~AslFatAs_HpjAk_Zif@k|K|rDgrCh{C{fBed@cpHeEsdNsuBidLweCmbMaiE_kKtjB}{PrjDeuKp]yiEgjEiyDmf@atLqaBegEneAy}CaOkaIzaCwlOlyCabKdvFqiIooAsrJupAuaMngBysKlnDgiIjv@qeSnnCgwEltGgcC~xG_bJvzIsfJtbE{gJ~~HkgG|lFklGryTajOtjZ_cTd}H}xLn`A}XkkAmlAcg@grEs^guMwfGqqFc_JqtHkpI{tLqbOkmVqyBjtGuaIx}BccG`TujCssCc}DkmOfyEasUhjE}}CkmAaoDwwJicNugHucVgjKinRmoFuwDqHvtFigCli@qpDf`AsjDg`B{{F}dKmtBa`MsdDmkD}fEcwAykEaeFw|Cc~[chDgsUqfCybHkkCyiFkcKeuXwqCe~RsaCy~Ey`DkyOiDgkDzzBuoD`w@ojBzvAzr@`bDsvBb_@{xGysD}cIqtH}dNsmI}nP_kDulEqcEb_A{rDmRybEcwBqgDra@ieBwwCckE_vFq@}zLvXygIk~QcmU{yMakRstCmmJywDclEszG}tLybDllAikDwnB_yFs~CqwGc{CssBkrSckCwcJbUknHlsBgwG"
         },
         "summary" : "I-68 E",
         "warnings" : [],
         "waypoint_order" : []
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
