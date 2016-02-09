#### Test 583805004251330_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,D/AndroidRuntime( 3523): 
D/AndroidRuntime( 3523): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3523): CheckJNI is OFF
D/dalvikvm( 3523): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3523): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3523): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3523): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3523): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3523): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3523): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3523): failed to load memtrack module: -2
D/AndroidRuntime( 3523): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1012): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3523
D/AndroidRuntime( 3523): Shutting down VM
D/dalvikvm( 3523): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 1ms+0ms, total 3ms
,V/AlarmManager( 1012): sending alarm Alarm{428e1c88 type 3 android}
,V/AlarmManager( 1012): sending alarm Alarm{4290dbf8 type 2 com.google.android.gms}
,E/global frequency( 1599): no tags to log
,D/Checkin ( 1599): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1599): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1599): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 1599): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 1599): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 1599): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1599): BcsDSCheckin.events found events 2000
,D/Checkin ( 1599): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1599): GC_CONCURRENT freed 5487K, 33% free 11686K/17224K, paused 3ms+6ms, total 54ms
,I/BSUtils ( 1599): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1599): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
D/MMApiWebService( 1599): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1599): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1599): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 1599): AppWSProxy - sendAIDLWSResponse() sending reponse
I/ErrorTranslator( 1599): unknown error code mapping for: 0
I/global frequency( 1599): BcsCore.status() called with error code=ERROR_FAIL
D/Checkin ( 1599): publish the event [tag = MOT_CHECKIN event name = LOG]
I/global frequency( 1599): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1599): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 1599): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1599): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1599): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1599): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1599): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
I/MMApiWebService( 1599): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1599): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1599): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1599): ProvisionWS.Response.setError: error RadioDownError
I/MMApiBackOffService( 1599): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1599): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1599): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1599): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1599): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
I/MMApiWebService( 1599): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1599): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1599): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1599): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1599): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,I/ClearcutLoggerApiImpl( 1329): disconnect managed GoogleApiClient
,V/AlarmManager( 1012): sending alarm Alarm{41fdaaa8 type 3 android}
,V/AlarmManager( 1012): sending alarm Alarm{424a5958 type 2 com.google.android.gms}
,V/AlarmManager( 1012): sending alarm Alarm{42884628 type 2 com.google.android.gms}
,D/ConnectivityService( 1012): handleInetConditionChange: no active default network - ignore
,I/VacuumService( 1214): Vacuum at: now=1455034086460 tag=VacuumService
,V/AlarmManager( 1012): sending alarm Alarm{429da398 type 3 android}
,V/AlarmManager( 1012): sending alarm Alarm{42066a90 type 3 android}
,V/AlarmManager( 1012): sending alarm Alarm{4290f620 type 3 android}
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1012): sending alarm Alarm{42066b40 type 2 com.google.android.gms}
,D/ConnectivityService( 1012): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1012): sending alarm Alarm{422863b8 type 3 android}
,V/AlarmManager( 1012): sending alarm Alarm{4291e868 type 3 android}
,I/MMApiBackOffService( 1599): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1599): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1599): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1599): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1599): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1599): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
E/MMApiProvisionService( 1599): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1599): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/MMApiWebService( 1599): doRequest(): polling manager says we're not connected, returning with an error: 
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1599): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1599): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1599): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1599): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1599): MMApiWebService told us not to continue at the moment with this request: 
D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1599): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1599): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1599): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1599): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1599): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1012): sending alarm Alarm{4291bae8 type 3 android}
,V/AlarmManager( 1012): sending alarm Alarm{428f5410 type 3 android}
,V/AlarmManager( 1012): sending alarm Alarm{428dcc20 type 3 android}
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1012): sending alarm Alarm{42047598 type 3 android}
,V/AlarmManager( 1012): sending alarm Alarm{42873f10 type 2 com.google.android.gms}
,D/ConnectivityService( 1012): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1012): sending alarm Alarm{429000b8 type 3 android}
,V/AlarmManager( 1012): sending alarm Alarm{4286d588 type 3 android}
,V/AlarmManager( 1012): sending alarm Alarm{4206cdf0 type 2 android}
,V/AlarmManager( 1012): sending alarm Alarm{42181b58 type 0 com.android.vending}
,D/Finsky  ( 2423): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/ConnectivityService( 1012): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1012): Done.
,D/ConnectivityService( 1012): Setting timer for 720seconds
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1329): GC_EXPLICIT freed 1553K, 40% free 10350K/17224K, paused 2ms+4ms, total 33ms
,W/Finsky  ( 2423): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2423): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2423): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 2423): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1012): sending alarm Alarm{4278f790 type 0 com.android.vending}
D/Finsky  ( 2423): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,D/WearableService( 1214): callingUid 10022, callindPid: 1214
,D/DeviceConnectionService( 1214): client connected with version: 8296000
,D/Finsky  ( 2423): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 2423): [214] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2423): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 2423): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1012): sending alarm Alarm{4299a988 type 0 com.android.vending}
,D/Finsky  ( 2423): [198] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2423): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/AlarmManager( 1012): sending alarm Alarm{42867388 type 3 android}
,V/AlarmManager( 1012): sending alarm Alarm{429a05c0 type 3 android}
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1012): sending alarm Alarm{42757430 type 3 android}
,V/AlarmManager( 1012): sending alarm Alarm{428885a0 type 3 android}
,I/MMApiBackOffService( 1599): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1599): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1599): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1599): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1599): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1599): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1599): ProvisionWS.Response: Missing mandatory message data in response from DM server...
I/MMApiWebService( 1599): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1599): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1599): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1599): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1599): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1599): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1599): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1599): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1599): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1599): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1599): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1599): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1599): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1012): sending alarm Alarm{429ca2e8 type 3 android}
,V/AlarmManager( 1012): sending alarm Alarm{429ad818 type 3 android}
,V/AlarmManager( 1012): sending alarm Alarm{429a1198 type 3 android}
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1329): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1012): sending alarm Alarm{429c3660 type 3 android}
,V/AlarmManager( 1012): sending alarm Alarm{429c7e40 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3622): 
D/AndroidRuntime( 3622): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3622): CheckJNI is OFF
D/dalvikvm( 3622): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3622): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3622): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3622): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3622): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3622): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3622): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3622): failed to load memtrack module: -2
D/AndroidRuntime( 3622): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1012): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1012): GC_EXPLICIT freed 895K, 9% free 18363K/19976K, paused 3ms+8ms, total 92ms
D/AndroidRuntime( 3622): Shutting down VM
D/dalvikvm( 3622): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms

```
