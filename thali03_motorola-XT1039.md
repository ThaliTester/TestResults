#### Test 5838050069f842e_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1020): sending alarm Alarm{42267620 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 3479): 
D/AndroidRuntime( 3479): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3479): CheckJNI is OFF
D/dalvikvm( 3479): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3479): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3479): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3479): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3479): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3479): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3479): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3479): failed to load memtrack module: -2
D/AndroidRuntime( 3479): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3479
D/AndroidRuntime( 3479): Shutting down VM
D/dalvikvm( 3479): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 1ms+0ms, total 3ms
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{42806f70 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42968f80 type 2 com.google.android.gms}
,E/global frequency( 1580): no tags to log
,D/Checkin ( 1580): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1580): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1580): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1580): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1580): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1580): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1580): BcsDSCheckin.events found events 2000
,D/Checkin ( 1580): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1580): GC_CONCURRENT freed 5484K, 33% free 11685K/17224K, paused 4ms+6ms, total 60ms
,I/BSUtils ( 1580): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1580): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1580): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1580): unknown error code mapping for: 0
I/global frequency( 1580): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1580): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1580): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1580): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 1580): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1580): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
E/MMApiProvisionService( 1580): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1580): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: devices.json
,I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{4214d550 type 2 com.google.android.gms}
,V/AlarmManager( 1020): sending alarm Alarm{4290dad8 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,I/VacuumService( 1217): Vacuum at: now=1454701255727 tag=VacuumService
,V/AlarmManager( 1020): sending alarm Alarm{42855da8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4291d6f8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42865c40 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42052c00 type 3 android}
,V/GLSActivity( 2065): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2065): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{4291d7a8 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1020): sending alarm Alarm{4294c290 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{41f417e0 type 3 android}
,I/MMApiBackOffService( 1580): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1580): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1580): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1580): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{429f2148 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{429f1438 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{427c73c0 type 3 android}
,V/GLSActivity( 2065): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2065): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{4281cf58 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4280cff8 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1020): sending alarm Alarm{428655e0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4291e598 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4292e1e8 type 2 android}
,D/ConnectivityService( 1020): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1020): Done.
,D/ConnectivityService( 1020): Setting timer for 720seconds
,V/AlarmManager( 1020): sending alarm Alarm{427c48f8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{421606b0 type 3 android}
,V/GLSActivity( 2065): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2065): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{429208a0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42978340 type 3 android}
,I/MMApiBackOffService( 1580): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1580): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1580): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1580): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{4293f858 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42994428 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4292fd98 type 3 android}
,V/GLSActivity( 2065): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2065): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{428079b0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4229a198 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3554): 
D/AndroidRuntime( 3554): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3554): CheckJNI is OFF
D/dalvikvm( 3554): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3554): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3554): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3554): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3554): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3554): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3554): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3554): failed to load memtrack module: -2
D/AndroidRuntime( 3554): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1020): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1020): GC_EXPLICIT freed 644K, 9% free 18354K/20116K, paused 3ms+8ms, total 101ms
D/AndroidRuntime( 3554): Shutting down VM
D/dalvikvm( 3554): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms

```
