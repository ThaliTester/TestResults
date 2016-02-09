#### Test 5841644866d9c0e_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,D/AndroidRuntime( 3380): 
D/AndroidRuntime( 3380): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3380): CheckJNI is OFF
D/dalvikvm( 3380): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3380): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3380): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3380): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3380): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3380): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3380): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3380): failed to load memtrack module: -2
D/AndroidRuntime( 3380): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1022): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3380
D/AndroidRuntime( 3380): Shutting down VM
D/dalvikvm( 3380): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+0ms, total 2ms
,E/global frequency( 1595): no tags to log
,D/Checkin ( 1595): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1595): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1595): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1595): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 1595): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1595): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1595): BcsDSCheckin.events found events 2000
,D/Checkin ( 1595): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1595): GC_CONCURRENT freed 5481K, 33% free 11679K/17224K, paused 3ms+6ms, total 49ms
,I/BSUtils ( 1595): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1595): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1595): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1595): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1595): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1595): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1595): unknown error code mapping for: 0
I/global frequency( 1595): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1595): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1595): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1595): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager( 1022): sending alarm Alarm{428cde10 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{427455f0 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4293a4c8 type 2 com.google.android.gms}
,V/AlarmManager( 1022): sending alarm Alarm{4298da48 type 2 com.google.android.gms}
,D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
,I/VacuumService( 1212): Vacuum at: now=1455019862645 tag=VacuumService
,I/MMApiBackOffService( 1595): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1595): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1595): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1595): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1595): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1595): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,E/MMApiProvisionService( 1595): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1595): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1595): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiBackOffService( 1595): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1595): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1595): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1595): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1595): MMApiWebService told us not to continue at the moment with this request: 
D/MMApiWebService( 1595): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1595): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1595): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1595): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1595): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1022): sending alarm Alarm{42250260 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4217c9f8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{427cc278 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{421779d8 type 2 com.google.android.gms}
,D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1022): sending alarm Alarm{429a1518 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42957768 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{427723d8 type 3 android}
,I/MMApiBackOffService( 1595): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1595): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1595): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1595): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1595): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1595): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1595): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
E/MMApiProvisionService( 1595): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1595): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiBackOffService( 1595): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1595): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1595): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1595): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1595): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1595): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1595): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1595): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1595): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1595): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1022): sending alarm Alarm{42249560 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42795f90 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4270e6e0 type 2 com.google.android.gms}
,D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1022): sending alarm Alarm{41f39e68 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{428c55e8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{428c4108 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42164db8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{429a0fd8 type 3 android}
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1022): sending alarm Alarm{427c40c0 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{427559a0 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{428fc878 type 3 android}
,I/MMApiBackOffService( 1595): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1595): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1595): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1595): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1595): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1595): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1595): ProvisionWS.Response: Missing mandatory message data in response from DM server...
I/MMApiWebService( 1595): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1595): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1595): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1595): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1595): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1595): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1595): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1595): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1595): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1595): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1595): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1595): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1022): sending alarm Alarm{429792e0 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42174ae0 type 2 android}
,V/AlarmManager( 1022): sending alarm Alarm{42840188 type 2 com.google.android.gms}
,D/ConnectivityService( 1022): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1022): Done.
,D/ConnectivityService( 1022): Setting timer for 720seconds
,D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  270): write error (Broken pipe)
,V/AlarmManager( 1022): sending alarm Alarm{427f1d10 type 3 android}
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1326): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1022): sending alarm Alarm{42947470 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{427018d8 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3466): 
D/AndroidRuntime( 3466): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3466): CheckJNI is OFF
D/dalvikvm( 3466): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3466): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3466): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3466): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3466): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3466): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3466): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3466): failed to load memtrack module: -2
D/AndroidRuntime( 3466): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1022): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1022): GC_EXPLICIT freed 635K, 10% free 18313K/20292K, paused 2ms+8ms, total 94ms
D/AndroidRuntime( 3466): Shutting down VM
D/dalvikvm( 3466): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms
I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''

```
