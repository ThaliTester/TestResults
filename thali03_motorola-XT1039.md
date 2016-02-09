#### Test 586983493da948e_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1019): sending alarm Alarm{427e0930 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
--------- beginning of /dev/log/main
D/AndroidRuntime( 3385): 
D/AndroidRuntime( 3385): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3385): CheckJNI is OFF
V/AlarmManager( 1019): sending alarm Alarm{425cef78 type 3 android}
D/dalvikvm( 3385): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3385): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3385): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3385): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3385): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3385): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3385): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3385): failed to load memtrack module: -2
D/AndroidRuntime( 3385): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3385
D/AndroidRuntime( 3385): Shutting down VM
D/dalvikvm( 3385): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+0ms, total 2ms
,I/ClearcutLoggerApiImpl( 1359): disconnect managed GoogleApiClient
,V/AlarmManager( 1019): sending alarm Alarm{42452468 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42d5aa38 type 2 com.google.android.gms}
,E/global frequency( 1586): no tags to log
,D/Checkin ( 1586): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1586): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1586): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1586): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1586): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1586): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1586): BcsDSCheckin.events found events 2000
,D/Checkin ( 1586): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1586): GC_CONCURRENT freed 5474K, 33% free 11710K/17224K, paused 2ms+6ms, total 58ms
,I/BSUtils ( 1586): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1586): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1586): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1586): unknown error code mapping for: 0
I/global frequency( 1586): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1586): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1586): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1586): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 1586): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1586): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1586): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1586): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{42bcdae8 type 2 com.google.android.gms}
,I/VacuumService( 1217): Vacuum at: now=1454986367809 tag=VacuumService
,V/AlarmManager( 1019): sending alarm Alarm{42c8bf18 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42cb2140 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42cb21f0 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{42bb08f0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42c943f0 type 3 android}
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{42ca3de0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42d37030 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42dd4f98 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  271): write error (Broken pipe)
,I/MMApiBackOffService( 1586): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1586): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1586): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1586): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{424e0f18 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42cc77b0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42c8c938 type 3 android}
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{42b8eae8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42cd6ea0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42e2e408 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42bc75b8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42de3dd0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42cb7f50 type 2 android}
,V/AlarmManager( 1019): sending alarm Alarm{42cb7d88 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  271): write error (Broken pipe)
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{42d39878 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42dd5498 type 3 android}
,I/MMApiBackOffService( 1586): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1586): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1586): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1586): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: devices.json
,I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{42cc1f20 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42cbd9c0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42d8c460 type 3 android}
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{42e06488 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42d7bdd8 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3462): 
D/AndroidRuntime( 3462): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3462): CheckJNI is OFF
D/dalvikvm( 3462): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3462): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3462): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3462): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3462): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3462): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
V/AlarmManager( 1019): sending alarm Alarm{42cb8010 type 2 com.motorola.ccc.cce}
V/AlarmManager( 1019): sending alarm Alarm{42cc4140 type 0 com.google.android.gms}
I/PollingManager( 1586): alarm fired!
D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
I/EventLogService( 1682): Aggregate from 1454985701085 (log), 1454985701085 (data)
E/memtrack( 3462): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3462): failed to load memtrack module: -2
D/AndroidRuntime( 3462): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1019): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1019): GC_EXPLICIT freed 793K, 9% free 18310K/20012K, paused 3ms+7ms, total 85ms
D/AndroidRuntime( 3462): Shutting down VM
D/dalvikvm( 3462): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms

```
