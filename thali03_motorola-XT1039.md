#### Test 58497659c9ea290_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1019): sending alarm Alarm{42120428 type 3 android}
V/AlarmManager( 1019): sending alarm Alarm{42a75ac0 type 2 com.google.android.gms}
V/AlarmManager( 1019): sending alarm Alarm{428e0cb8 type 2 com.google.android.gms}
D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
--------- beginning of /dev/log/main
D/AndroidRuntime( 3371): 
D/AndroidRuntime( 3371): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3371): CheckJNI is OFF
D/dalvikvm( 3371): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3371): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3371): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3371): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3371): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3371): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3371): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3371): failed to load memtrack module: -2
D/AndroidRuntime( 3371): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3371
D/AndroidRuntime( 3371): Shutting down VM
D/dalvikvm( 3371): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+0ms, total 3ms
,E/global frequency( 1597): no tags to log
,D/Checkin ( 1597): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1597): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1597): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1597): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 1597): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1597): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1597): BcsDSCheckin.events found events 2000
,D/Checkin ( 1597): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1597): GC_CONCURRENT freed 5470K, 33% free 11658K/17224K, paused 3ms+4ms, total 45ms
,I/BSUtils ( 1597): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1597): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
D/MMApiWebService( 1597): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1597): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1597): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 1597): AppWSProxy - sendAIDLWSResponse() sending reponse
I/ErrorTranslator( 1597): unknown error code mapping for: 0
I/global frequency( 1597): BcsCore.status() called with error code=ERROR_FAIL
D/Checkin ( 1597): publish the event [tag = MOT_CHECKIN event name = LOG]
I/global frequency( 1597): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
D/Checkin ( 1597): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MMApiBackOffService( 1597): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1597): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1597): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1597): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1597): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,E/MMApiProvisionService( 1597): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1597): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1597): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/MMApiWebService( 1597): doRequest(): polling manager says we're not connected, returning with an error: 
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1597): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1597): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1597): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1597): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1597): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1597): MMApiWebService told us not to continue at the moment with this request: 
,D/MMApiWebService( 1597): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1597): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1597): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1597): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{429be568 type 2 com.google.android.gms}
,I/VacuumService( 1212): Vacuum at: now=1454714939102 tag=VacuumService
,V/AlarmManager( 1019): sending alarm Alarm{427e0050 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{427cf568 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{427de8e8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42555398 type 2 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{42301bf8 type 0 com.motorola.motocare}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1019): sending alarm Alarm{4299da50 type 3 android}
,V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{42a7c738 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{427e5688 type 3 android}
,I/MMApiBackOffService( 1597): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1597): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1597): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1597): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1597): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1597): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1597): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1597): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,E/MMApiProvisionService( 1597): ProvisionWS.Response.setError: error RadioDownError
I/MMApiBackOffService( 1597): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1597): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1597): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1597): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1597): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1597): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1597): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1597): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1597): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1597): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{4287d760 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{428a94b8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{428e18c8 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1019): sending alarm Alarm{428a4fc0 type 3 android}
,V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{42102fd0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{428ab2c8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{428a46d0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{429d1c40 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42a75350 type 3 android}
,V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{428dd468 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{428d79d8 type 3 android}
,I/MMApiBackOffService( 1597): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1597): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1597): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1597): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1597): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1597): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1597): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1597): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1597): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1597): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1597): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1597): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1597): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1597): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1597): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1597): doRequest(): polling manager says we're not connected, returning with an error: 
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1597): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1597): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1597): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{42301c48 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{4282a658 type 2 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{42301700 type 0 com.google.android.gms}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,I/EventLogService( 1689): Aggregate from 1454713618693 (log), 1454713618693 (data)
,V/AlarmManager( 1019): sending alarm Alarm{428c1208 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{429cc610 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{428ecff8 type 3 android}
,V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2052): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{429cd810 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{428c30e8 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3451): 
D/AndroidRuntime( 3451): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3451): CheckJNI is OFF
D/dalvikvm( 3451): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3451): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3451): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3451): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3451): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3451): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3451): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3451): failed to load memtrack module: -2
D/AndroidRuntime( 3451): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1019): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1019): GC_EXPLICIT freed 702K, 10% free 18287K/20188K, paused 2ms+8ms, total 84ms
D/AndroidRuntime( 3451): Shutting down VM
D/dalvikvm( 3451): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms

```
