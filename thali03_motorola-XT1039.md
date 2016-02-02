#### Test 575312431f256a6_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1019): sending alarm Alarm{428b67b0 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3486): 
D/AndroidRuntime( 3486): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3486): CheckJNI is OFF
D/dalvikvm( 3486): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3486): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3486): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3486): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3486): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3486): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3486): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3486): failed to load memtrack module: -2
D/AndroidRuntime( 3486): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3486
D/AndroidRuntime( 3486): Shutting down VM
D/dalvikvm( 3486): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 1ms+0ms, total 3ms
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,E/global frequency( 1596): no tags to log
,D/Checkin ( 1596): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1596): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1596): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1596): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1596): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1596): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1596): BcsDSCheckin.events found events 1903
,D/Checkin ( 1596): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1596): GC_CONCURRENT freed 5496K, 32% free 11732K/17224K, paused 2ms+5ms, total 57ms
,I/BSUtils ( 1596): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1596): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1596): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1596): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1596): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1596): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1596): unknown error code mapping for: 0
I/global frequency( 1596): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1596): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1596): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1596): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{42159048 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42a4a768 type 2 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{42a2bf18 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,I/VacuumService( 1218): Vacuum at: now=1454434048523 tag=VacuumService
,I/MMApiBackOffService( 1596): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1596): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1596): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1596): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1596): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1596): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/MMApiWebService( 1596): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1596): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,E/MMApiProvisionService( 1596): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiBackOffService( 1596): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1596): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1596): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1596): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1596): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1596): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1596): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1596): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1596): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1596): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{4248cde0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42269d60 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4285d0a8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4215c078 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  273): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{427ab3d8 type 3 android}
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{427dcca0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42a04de0 type 3 android}
,I/MMApiBackOffService( 1596): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1596): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1596): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1596): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1596): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1596): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1596): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1596): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1596): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1596): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1596): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1596): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1596): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1596): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1596): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1596): doRequest(): polling manager says we're not connected, returning with an error: 
D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1596): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1596): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1596): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{4280e540 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{428be668 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{427c0350 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  273): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{427ebb88 type 3 android}
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  273): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{42766230 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{427a7a00 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{429438f8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4227dfc8 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{420f07b8 type 3 android}
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  273): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{42861a90 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42856fa0 type 3 android}
,I/MMApiBackOffService( 1596): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1596): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1596): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1596): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1596): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1596): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1596): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1596): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1596): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1596): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1596): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1596): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1596): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1596): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1596): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1596): doRequest(): polling manager says we're not connected, returning with an error: 
D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1596): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1596): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1596): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1596): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{429bc630 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42128ae0 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{427e2a70 type 2 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{4211faa8 type 0 com.google.android.gms}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,I/EventLogService( 1688): Aggregate from 1454432797753 (log), 1454432797753 (data)
,V/AlarmManager( 1019): sending alarm Alarm{42838a70 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{427f82b8 type 3 android}
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1342): GC_EXPLICIT freed 1635K, 41% free 10320K/17224K, paused 2ms+5ms, total 35ms
,V/AlarmManager( 1019): sending alarm Alarm{42801c48 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{428a1828 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3581): 
D/AndroidRuntime( 3581): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3581): CheckJNI is OFF
D/dalvikvm( 3581): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3581): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3581): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3581): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3581): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3581): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3581): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3581): failed to load memtrack module: -2
D/AndroidRuntime( 3581): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1019): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1019): GC_EXPLICIT freed 707K, 11% free 18323K/20388K, paused 3ms+7ms, total 89ms
D/AndroidRuntime( 3581): Shutting down VM
D/dalvikvm( 3581): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms

```
