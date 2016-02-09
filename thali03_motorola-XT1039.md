#### Test 583805003a0697c_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1014): sending alarm Alarm{42a1bf08 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{428e2c28 type 2 com.google.android.gms}
--------- beginning of /dev/log/main
D/AndroidRuntime( 3448): 
D/AndroidRuntime( 3448): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3448): CheckJNI is OFF
D/dalvikvm( 3448): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3448): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3448): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3448): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3448): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3448): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3448): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3448): failed to load memtrack module: -2
D/AndroidRuntime( 3448): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1014): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3448
D/AndroidRuntime( 3448): Shutting down VM
D/dalvikvm( 3448): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+1ms, total 2ms
,E/global frequency( 1580): no tags to log
,D/Checkin ( 1580): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1580): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1580): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 1580): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1580): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1580): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1580): BcsDSCheckin.events found events 2000
,D/Checkin ( 1580): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1580): GC_CONCURRENT freed 5478K, 33% free 11638K/17224K, paused 4ms+4ms, total 52ms
,I/BSUtils ( 1580): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1580): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1580): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1580): unknown error code mapping for: 0
I/global frequency( 1580): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1580): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1580): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1580): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager( 1014): sending alarm Alarm{428f0f10 type 3 android}
,I/MMApiBackOffService( 1580): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1580): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1580): ProvisionWS.Response: Missing mandatory message data in response from DM server...
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1580): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1014): sending alarm Alarm{428d6c28 type 2 com.google.android.gms}
,V/AlarmManager( 1014): sending alarm Alarm{428dbb60 type 2 com.google.android.gms}
,D/ConnectivityService( 1014): handleInetConditionChange: no active default network - ignore
,I/VacuumService( 1212): Vacuum at: now=1455056249175 tag=VacuumService
,V/AlarmManager( 1014): sending alarm Alarm{4247fb00 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{4246f8f0 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{429b8db8 type 3 android}
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1014): sending alarm Alarm{42905190 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{423d1b40 type 2 com.google.android.gms}
,D/ConnectivityService( 1014): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  273): write error (Broken pipe)
,V/AlarmManager( 1014): sending alarm Alarm{42296080 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{42873488 type 3 android}
,I/MMApiBackOffService( 1580): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1580): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1580): ProvisionWS.Response: Missing mandatory message data in response from DM server...
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1580): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1014): sending alarm Alarm{42314868 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{42818ab0 type 3 android}
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  273): write error (Broken pipe)
,V/AlarmManager( 1014): sending alarm Alarm{428d2a28 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{4288aa20 type 2 com.google.android.gms}
,D/ConnectivityService( 1014): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1014): sending alarm Alarm{4298a2b8 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{42841768 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{420d3e48 type 2 android}
,V/AlarmManager( 1014): sending alarm Alarm{4203b1e8 type 0 com.android.vending}
,D/Finsky  ( 3095): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager( 1014): sending alarm Alarm{4203b238 type 0 com.google.android.gms}
D/ConnectivityService( 1014): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1014): Done.
,D/ConnectivityService( 1014): Setting timer for 720seconds
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1651): Aggregate from 1455055047524 (log), 1455055047524 (data)
,W/Finsky  ( 3095): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3095): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3095): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 3095): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1014): sending alarm Alarm{42992bf8 type 0 com.android.vending}
D/Finsky  ( 3095): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/WearableService( 1212): callingUid 10022, callindPid: 1212
,D/DeviceConnectionService( 1212): client connected with version: 8296000
D/Finsky  ( 3095): [263] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3095): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 3095): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3095): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1014): sending alarm Alarm{428f0530 type 0 com.android.vending}
,D/Finsky  ( 3095): [249] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3095): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/AlarmManager( 1014): sending alarm Alarm{428f0608 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{429e4088 type 3 android}
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1014): sending alarm Alarm{42a8d798 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{429c75d8 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{42975a60 type 3 android}
,I/MMApiBackOffService( 1580): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1580): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1580): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,E/MMApiProvisionService( 1580): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1014): sending alarm Alarm{42976f70 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{42a14ab8 type 3 android}
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1014): GC_EXPLICIT freed 959K, 9% free 18406K/20136K, paused 3ms+8ms, total 89ms
,W/SocketClient(  273): write error (Broken pipe)
,V/AlarmManager( 1014): sending alarm Alarm{42a15f88 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{428f06e0 type 2 com.google.android.gms}
,D/ConnectivityService( 1014): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1014): sending alarm Alarm{42a6b4e8 type 3 android}
,V/AlarmManager( 1014): sending alarm Alarm{429ee808 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3542): 
D/AndroidRuntime( 3542): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3542): CheckJNI is OFF
D/dalvikvm( 3542): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3542): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3542): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3542): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3542): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3542): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3542): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3542): failed to load memtrack module: -2
D/AndroidRuntime( 3542): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1014): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1014): GC_EXPLICIT freed 126K, 10% free 18317K/20136K, paused 3ms+7ms, total 82ms
D/AndroidRuntime( 3542): Shutting down VM
D/dalvikvm( 3542): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms

```
