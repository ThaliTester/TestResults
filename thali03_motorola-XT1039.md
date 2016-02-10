#### Test 58380500a584679_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1018): sending alarm Alarm{429d73b8 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 3435): 
D/AndroidRuntime( 3435): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3435): CheckJNI is OFF
D/dalvikvm( 3435): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3435): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3435): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3435): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3435): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3435): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3435): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3435): failed to load memtrack module: -2
D/AndroidRuntime( 3435): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3435
D/AndroidRuntime( 3435): Shutting down VM
D/dalvikvm( 3435): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+1ms, total 2ms
,I/ClearcutLoggerApiImpl( 1341): disconnect managed GoogleApiClient
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,E/global frequency( 1585): no tags to log
,D/Checkin ( 1585): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1585): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1585): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1585): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1585): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1585): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1585): BcsDSCheckin.events found events 2000
,D/Checkin ( 1585): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1585): GC_CONCURRENT freed 5479K, 33% free 11679K/17224K, paused 2ms+6ms, total 47ms
,I/BSUtils ( 1585): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1585): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1585): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1585): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1585): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1585): unknown error code mapping for: 0
I/global frequency( 1585): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1585): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1585): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1585): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{42a02018 type 3 android}
V/AlarmManager( 1018): sending alarm Alarm{4297ae20 type 2 com.google.android.gms}
,V/AlarmManager( 1018): sending alarm Alarm{429776d0 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,I/VacuumService( 1211): Vacuum at: now=1455067600237 tag=VacuumService
,I/MMApiBackOffService( 1585): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1585): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1585): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1585): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1585): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1585): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1585): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1585): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1585): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1585): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1585): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1585): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/MMApiWebService( 1585): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1585): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1585): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1585): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{425aab58 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{424780c0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42929688 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{421bcdd8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42468068 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): sending alarm Alarm{4283eb78 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42295be8 type 3 android}
,I/MMApiBackOffService( 1585): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1585): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1585): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1585): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1585): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1585): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1585): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1585): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1585): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1585): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1585): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
I/MMApiWebService( 1585): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1585): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1585): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1585): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1585): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{4297bec8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{429f5ac0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4290bee8 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1018): sending alarm Alarm{4299d308 type 3 android}
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): sending alarm Alarm{428359a0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{429113b8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{41f8ebf0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{423f2c08 type 2 android}
,V/AlarmManager( 1018): sending alarm Alarm{423417d0 type 0 com.android.vending}
,D/Finsky  ( 3058): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/ConnectivityService( 1018): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1018): Done.
,D/ConnectivityService( 1018): Setting timer for 720seconds
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3058): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3058): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3058): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 3058): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1018): sending alarm Alarm{429ca450 type 0 com.android.vending}
D/Finsky  ( 3058): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/WearableService( 1211): callingUid 10022, callindPid: 1211
,D/DeviceConnectionService( 1211): client connected with version: 8296000
,D/Finsky  ( 3058): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 3058): [263] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3058): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3058): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/dalvikvm( 1341): GC_EXPLICIT freed 1819K, 40% free 10344K/17224K, paused 4ms+5ms, total 36ms
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): sending alarm Alarm{429a9268 type 0 com.android.vending}
,D/Finsky  ( 3058): [249] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3058): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/AlarmManager( 1018): sending alarm Alarm{427b0460 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42a0bca0 type 3 android}
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): sending alarm Alarm{42927278 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{429479d0 type 3 android}
,I/MMApiBackOffService( 1585): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1585): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1585): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1585): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1585): ProvisionWS.Response.setError: error RadioDownError
D/MMApiWebService( 1585): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1585): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1585): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1585): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1585): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1585): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1585): MMApiWebService told us not to continue at the moment with this request: 
D/MMApiWebService( 1585): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1585): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1585): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1585): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{42a060f0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{428898e8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42864900 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1018): sending alarm Alarm{42943468 type 3 android}
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): sending alarm Alarm{42940af0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4284b310 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3520): 
D/AndroidRuntime( 3520): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3520): CheckJNI is OFF
D/dalvikvm( 3520): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3520): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3520): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3520): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3520): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3520): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3520): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3520): failed to load memtrack module: -2
D/AndroidRuntime( 3520): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1018): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1018): GC_EXPLICIT freed 872K, 9% free 18391K/20136K, paused 3ms+8ms, total 87ms
D/AndroidRuntime( 3520): Shutting down VM
D/dalvikvm( 3520): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms

```
