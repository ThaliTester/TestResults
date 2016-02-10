#### Test 58918757c0fcaf3_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1015): sending alarm Alarm{429502c0 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3421): 
D/AndroidRuntime( 3421): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3421): CheckJNI is OFF
D/dalvikvm( 3421): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3421): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3421): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3421): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3421): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3421): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3421): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3421): failed to load memtrack module: -2
D/AndroidRuntime( 3421): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1015): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3421
D/AndroidRuntime( 3421): Shutting down VM
D/dalvikvm( 3421): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+0ms, total 2ms
,E/global frequency( 1557): no tags to log
,D/Checkin ( 1557): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1557): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1557): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 1557): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1557): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1557): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1557): BcsDSCheckin.events found events 2000
,D/Checkin ( 1557): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1557): GC_CONCURRENT freed 5486K, 33% free 11686K/17224K, paused 3ms+6ms, total 54ms
,I/BSUtils ( 1557): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1557): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
D/MMApiWebService( 1557): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1557): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1557): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1557): AppWSProxy - sendAIDLWSResponse() sending reponse
I/ErrorTranslator( 1557): unknown error code mapping for: 0
I/global frequency( 1557): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1557): publish the event [tag = MOT_CHECKIN event name = LOG]
I/global frequency( 1557): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1557): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ClearcutLoggerApiImpl( 2031): disconnect managed GoogleApiClient
,V/AlarmManager( 1015): sending alarm Alarm{4281f520 type 3 android}
V/AlarmManager( 1015): sending alarm Alarm{42876828 type 2 com.google.android.gms}
,V/AlarmManager( 1015): sending alarm Alarm{4286ada8 type 2 com.google.android.gms}
,D/ConnectivityService( 1015): handleInetConditionChange: no active default network - ignore
,I/VacuumService( 1211): Vacuum at: now=1455124108201 tag=VacuumService
,I/MMApiBackOffService( 1557): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1557): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1557): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1557): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1557): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1557): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/MMApiWebService( 1557): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
E/MMApiProvisionService( 1557): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1557): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiBackOffService( 1557): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1557): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1557): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1557): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1557): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1557): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1557): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1557): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1557): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1557): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1015): sending alarm Alarm{42743438 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{4280b6a0 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{4204be38 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{42819370 type 2 com.google.android.gms}
,D/ConnectivityService( 1015): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1015): sending alarm Alarm{4226aa78 type 3 android}
,V/GLSActivity( 2031): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2031): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  270): write error (Broken pipe)
,V/AlarmManager( 1015): sending alarm Alarm{427f5bf8 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{42a06460 type 3 android}
,I/MMApiBackOffService( 1557): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1557): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1557): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1557): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1557): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1557): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1557): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1557): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1557): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1557): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1557): MMApiWebService told us not to continue at the moment with this request: devices.json
,I/MMApiWebService( 1557): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1557): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1557): MMApiWebService told us not to continue at the moment with this request: 
,D/MMApiWebService( 1557): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1557): doRequest(): polling manager says we're not connected, returning with an error: 
D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1557): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1557): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1557): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1015): sending alarm Alarm{420f2500 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{429a8e88 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{429e3850 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{42843c80 type 2 com.google.android.gms}
,D/ConnectivityService( 1015): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  270): write error (Broken pipe)
,V/GLSActivity( 2031): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2031): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  270): write error (Broken pipe)
,V/AlarmManager( 1015): sending alarm Alarm{42831a88 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{4299b040 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{4281b3a0 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{4282cc80 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{42772e38 type 3 android}
,V/GLSActivity( 2031): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2031): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  270): write error (Broken pipe)
,V/AlarmManager( 1015): sending alarm Alarm{42752260 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{42815288 type 3 android}
,I/MMApiBackOffService( 1557): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1557): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1557): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1557): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1557): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1557): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1557): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1557): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1557): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1557): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1557): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1557): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1557): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1557): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1557): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1557): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1557): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1557): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1557): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1557): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1015): sending alarm Alarm{4290f9d8 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{427b57e8 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{429a8700 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{42824258 type 2 android}
,V/AlarmManager( 1015): sending alarm Alarm{4298aa80 type 2 com.google.android.gms}
,D/ConnectivityService( 1015): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1015): Done.
,D/ConnectivityService( 1015): Setting timer for 720seconds
,D/ConnectivityService( 1015): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  270): write error (Broken pipe)
,V/GLSActivity( 2031): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2031): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  270): write error (Broken pipe)
,V/AlarmManager( 1015): sending alarm Alarm{42844260 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{428828c8 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3501): 
D/AndroidRuntime( 3501): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3501): CheckJNI is OFF
D/dalvikvm( 3501): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3501): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3501): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3501): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3501): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3501): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3501): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3501): failed to load memtrack module: -2
D/AndroidRuntime( 3501): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1015): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1015): GC_EXPLICIT freed 751K, 10% free 18343K/20208K, paused 9ms+8ms, total 100ms
D/AndroidRuntime( 3501): Shutting down VM
D/dalvikvm( 3501): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms

```
