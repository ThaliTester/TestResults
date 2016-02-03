#### Test 5813565532fb33b_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3513): 
D/AndroidRuntime( 3513): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3513): CheckJNI is OFF
--------- beginning of /dev/log/system
V/AlarmManager( 1020): sending alarm Alarm{42e28030 type 3 android}
V/AlarmManager( 1020): sending alarm Alarm{42e4eb80 type 2 com.google.android.gms}
D/dalvikvm( 3513): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3513): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3513): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3513): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3513): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3513): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3513): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3513): failed to load memtrack module: -2
D/AndroidRuntime( 3513): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3513
D/AndroidRuntime( 3513): Shutting down VM
D/dalvikvm( 3513): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+1ms, total 2ms
,I/ClearcutLoggerApiImpl( 2048): disconnect managed GoogleApiClient
,E/global frequency( 1590): no tags to log
,D/Checkin ( 1590): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1590): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1590): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1590): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1590): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1590): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1590): BcsDSCheckin.events found events 2000
,D/Checkin ( 1590): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1590): GC_CONCURRENT freed 5496K, 33% free 11687K/17224K, paused 2ms+5ms, total 54ms
,I/BSUtils ( 1590): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1590): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1590): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1590): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1590): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1590): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1590): unknown error code mapping for: 0
I/global frequency( 1590): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1590): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1590): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1590): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{42eb07c0 type 3 android}
,I/MMApiBackOffService( 1590): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1590): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1590): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1590): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1590): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1590): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,I/MMApiWebService( 1590): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1590): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1590): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1590): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1590): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1590): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1590): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1590): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1590): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1590): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1590): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1590): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1590): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{42e1e110 type 2 com.google.android.gms}
,V/AlarmManager( 1020): sending alarm Alarm{42e33740 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,I/VacuumService( 1213): Vacuum at: now=1454527891487 tag=VacuumService
,V/AlarmManager( 1020): sending alarm Alarm{42e18bf0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42e17288 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42967628 type 3 android}
,V/GLSActivity( 2048): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2048): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{42d07a20 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42e12d20 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1020): sending alarm Alarm{42d060b8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42cae830 type 3 android}
,I/MMApiBackOffService( 1590): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1590): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1590): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1590): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1590): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1590): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1590): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1590): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1590): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1590): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1590): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1590): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1590): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1590): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1590): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1590): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1590): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1590): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1590): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{42d2a358 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42e16cd0 type 3 android}
,V/GLSActivity( 2048): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2048): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  269): write error (Broken pipe)
,V/AlarmManager( 1020): sending alarm Alarm{42cbf918 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42d72150 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1020): sending alarm Alarm{425487b0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42e459a8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42ded0e0 type 2 android}
,V/AlarmManager( 1020): sending alarm Alarm{42decc98 type 0 com.google.android.gms}
,D/ConnectivityService( 1020): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1020): Done.
,D/ConnectivityService( 1020): Setting timer for 720seconds
,I/EventLogService( 1658): Aggregate from 1454526687167 (log), 1454526687167 (data)
,V/AlarmManager( 1020): sending alarm Alarm{42dae4c0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42cd0a58 type 3 android}
,V/GLSActivity( 2048): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2048): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  269): write error (Broken pipe)
,V/AlarmManager( 1020): sending alarm Alarm{42dd5f38 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42d3a5c8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42d83c50 type 3 android}
,I/MMApiBackOffService( 1590): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1590): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1590): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1590): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1590): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1590): doRequest(): polling manager says we're not connected, returning with an error: 
,E/MMApiProvisionService( 1590): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1590): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1590): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1590): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1590): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1590): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1590): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1590): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/MMApiWebService( 1590): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1590): doRequest(): polling manager says we're not connected, returning with an error: 
D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1590): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1590): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1590): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1590): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{42c8c920 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42cfc658 type 3 android}
,D/dalvikvm( 2048): GC_EXPLICIT freed 1527K, 40% free 10336K/17224K, paused 3ms+5ms, total 38ms
,V/GLSActivity( 2048): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2048): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  269): write error (Broken pipe)
,V/AlarmManager( 1020): sending alarm Alarm{42dbbf80 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42d4e340 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42d6d360 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42e3d420 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  269): write error (Broken pipe)
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3601): 
D/AndroidRuntime( 3601): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3601): CheckJNI is OFF
D/dalvikvm( 3601): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3601): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3601): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3601): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3601): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3601): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3601): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3601): failed to load memtrack module: -2
D/AndroidRuntime( 3601): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1020): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1020): GC_EXPLICIT freed 824K, 9% free 18292K/19968K, paused 2ms+8ms, total 84ms
D/AndroidRuntime( 3601): Shutting down VM
D/dalvikvm( 3601): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms

```
