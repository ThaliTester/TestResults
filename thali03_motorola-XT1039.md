#### Test 58380500055030c_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1019): sending alarm Alarm{42f47fc0 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
--------- beginning of /dev/log/main
D/AndroidRuntime( 3413): 
D/AndroidRuntime( 3413): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3413): CheckJNI is OFF
D/dalvikvm( 3413): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3413): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3413): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3413): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3413): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3413): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3413): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3413): failed to load memtrack module: -2
D/AndroidRuntime( 3413): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3413
D/AndroidRuntime( 3413): Shutting down VM
D/dalvikvm( 3413): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+0ms, total 2ms
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42e98f50 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43031030 type 2 com.google.android.gms}
,E/global frequency( 1591): no tags to log
,D/Checkin ( 1591): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1591): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1591): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1591): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1591): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1591): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1591): BcsDSCheckin.events found events 2000
,D/Checkin ( 1591): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1591): GC_CONCURRENT freed 5475K, 33% free 11684K/17224K, paused 3ms+5ms, total 59ms
,I/BSUtils ( 1591): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1591): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1591): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1591): unknown error code mapping for: 0
I/global frequency( 1591): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1591): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1591): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1591): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ClearcutLoggerApiImpl( 1360): disconnect managed GoogleApiClient
,V/AlarmManager( 1019): sending alarm Alarm{42fd1240 type 3 android}
,I/MMApiBackOffService( 1591): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1591): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1591): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1591): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{42f4d430 type 2 com.google.android.gms}
,I/VacuumService( 1217): Vacuum at: now=1454970855025 tag=VacuumService
,V/AlarmManager( 1019): sending alarm Alarm{42ed3668 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42ed1ea0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42ecf320 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{42e8b690 type 3 android}
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{42ba8c60 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42eaf680 type 3 android}
,I/ClearcutLoggerApiImpl( 1360): disconnect managed GoogleApiClient
,V/AlarmManager( 1019): sending alarm Alarm{426d0ff8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42ed7a50 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  272): write error (Broken pipe)
,I/MMApiBackOffService( 1591): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1591): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1591): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1591): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: devices.json
,I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{42fc0110 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42db9538 type 3 android}
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{4302d368 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42ed4978 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43001e88 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42f54ea0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42fa1f80 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42ec2ea0 type 2 android}
V/AlarmManager( 1019): sending alarm Alarm{42f5f9d0 type 2 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{42ebad38 type 0 com.google.android.gms}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,I/EventLogService( 1692): Aggregate from 1454969682700 (log), 1454969682700 (data)
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{42f62ef8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42f95fd8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43030850 type 3 android}
,I/MMApiBackOffService( 1591): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1591): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1591): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1591): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{42ec1698 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42fa6eb0 type 3 android}
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1360): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{42dbc8f8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42f5d6c0 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3487): 
D/AndroidRuntime( 3487): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3487): CheckJNI is OFF
D/dalvikvm( 3487): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3487): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3487): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3487): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3487): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3487): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3487): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3487): failed to load memtrack module: -2
D/AndroidRuntime( 3487): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1019): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1019): GC_EXPLICIT freed 740K, 9% free 18325K/20080K, paused 11ms+7ms, total 108ms
D/AndroidRuntime( 3487): Shutting down VM
D/dalvikvm( 3487): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms

```
