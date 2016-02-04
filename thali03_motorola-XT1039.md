#### Test 58259810381ca4f_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1024): sending alarm Alarm{42910bf0 type 2 com.google.android.gms}
D/ConnectivityService( 1024): handleInetConditionChange: no active default network - ignore
--------- beginning of /dev/log/main
D/AndroidRuntime( 3459): 
D/AndroidRuntime( 3459): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3459): CheckJNI is OFF
D/dalvikvm( 3459): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3459): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3459): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3459): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3459): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3459): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3459): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3459): failed to load memtrack module: -2
D/AndroidRuntime( 3459): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1024): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3459
D/AndroidRuntime( 3459): Shutting down VM
D/dalvikvm( 3459): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+0ms, total 3ms
,V/AlarmManager( 1024): sending alarm Alarm{42ac8fe8 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1024): sending alarm Alarm{42a6c908 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{42abefa8 type 2 com.google.android.gms}
,E/global frequency( 1604): no tags to log
,D/Checkin ( 1604): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1604): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1604): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1604): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1604): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1604): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1604): BcsDSCheckin.events found events 2000
,D/Checkin ( 1604): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1604): GC_CONCURRENT freed 5489K, 33% free 11635K/17224K, paused 3ms+4ms, total 45ms
,I/BSUtils ( 1604): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1604): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1604): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1604): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1604): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1604): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1604): unknown error code mapping for: 0
I/global frequency( 1604): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1604): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 1604): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1604): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1604): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1604): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1604): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
I/MMApiWebService( 1604): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/MMApiWebService( 1604): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1604): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,E/MMApiProvisionService( 1604): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiBackOffService( 1604): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1604): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1604): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1604): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1604): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/MMApiWebService( 1604): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1604): doRequest(): polling manager says we're not connected, returning with an error: 
D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1604): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1604): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1604): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1024): sending alarm Alarm{4295d270 type 2 com.google.android.gms}
,I/VacuumService( 1215): Vacuum at: now=1454579011544 tag=VacuumService
,V/AlarmManager( 1024): sending alarm Alarm{42905458 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{428fc6a0 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{428f5508 type 2 com.google.android.gms}
,D/ConnectivityService( 1024): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  274): write error (Broken pipe)
,V/AlarmManager( 1024): sending alarm Alarm{428e4a80 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{42a94be0 type 3 android}
,V/GLSActivity( 1317): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1317): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  274): write error (Broken pipe)
,V/AlarmManager( 1024): sending alarm Alarm{428b9180 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{42848d68 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{42343dd8 type 2 com.google.android.gms}
,D/ConnectivityService( 1024): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  274): write error (Broken pipe)
,I/MMApiBackOffService( 1604): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1604): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1604): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1604): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1604): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1604): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1604): ProvisionWS.Response: Missing mandatory message data in response from DM server...
I/MMApiWebService( 1604): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1604): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1604): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1604): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1604): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1604): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1604): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1604): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1604): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1604): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1604): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1604): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1024): sending alarm Alarm{42ac0268 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{428e7310 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{4288eaf0 type 3 android}
,V/GLSActivity( 1317): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1317): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  274): write error (Broken pipe)
,V/AlarmManager( 1024): sending alarm Alarm{428d4c90 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{428f6478 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{428e5b78 type 2 android}
,V/AlarmManager( 1024): sending alarm Alarm{428e5a10 type 0 com.android.vending}
,D/Finsky  ( 2930): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ConnectivityService( 1024): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1024): Done.
,D/ConnectivityService( 1024): Setting timer for 720seconds
,V/GLSActivity( 1317): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1317): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2930): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/SocketClient(  274): write error (Broken pipe)
,V/GLSActivity( 1317): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1317): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1317): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1317): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2930): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1317): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1317): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2930): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 2930): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager( 1024): sending alarm Alarm{42904fa0 type 0 com.android.vending}
,D/Finsky  ( 2930): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/WearableService( 1215): callingUid 10022, callindPid: 1215
,D/DeviceConnectionService( 1215): client connected with version: 8296000
,D/Finsky  ( 2930): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 2930): [259] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2930): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 2930): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1317): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1317): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1024): sending alarm Alarm{42884610 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{420bf5e0 type 0 com.android.vending}
,D/Finsky  ( 2930): [243] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2930): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/AlarmManager( 1024): sending alarm Alarm{42aba018 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{42a66ef8 type 2 com.google.android.gms}
,D/ConnectivityService( 1024): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  274): write error (Broken pipe)
,V/AlarmManager( 1024): sending alarm Alarm{42965c70 type 3 android}
,V/GLSActivity( 1317): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1317): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  274): write error (Broken pipe)
,V/AlarmManager( 1024): sending alarm Alarm{42a40138 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{42a5b3e0 type 3 android}
,I/MMApiBackOffService( 1604): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1604): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1604): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1604): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1604): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1604): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1604): ProvisionWS.Response.setError: error RadioDownError
,D/MMApiWebService( 1604): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1604): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1604): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1604): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1604): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1604): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1604): MMApiWebService told us not to continue at the moment with this request: 
D/MMApiWebService( 1604): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1604): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1604): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1604): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1604): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1604): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1024): sending alarm Alarm{42a4c758 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{42947728 type 3 android}
,V/AlarmManager( 1024): sending alarm Alarm{429125f0 type 3 android}
,V/GLSActivity( 1317): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1317): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  274): write error (Broken pipe)
,V/AlarmManager( 1024): sending alarm Alarm{4295b6a0 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3550): 
D/AndroidRuntime( 3550): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3550): CheckJNI is OFF
D/dalvikvm( 3550): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3550): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3550): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3550): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3550): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3550): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3550): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3550): failed to load memtrack module: -2
D/AndroidRuntime( 3550): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1024): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1024): GC_EXPLICIT freed 870K, 9% free 18422K/20108K, paused 3ms+8ms, total 85ms
D/AndroidRuntime( 3550): Shutting down VM
D/dalvikvm( 3550): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms

```
