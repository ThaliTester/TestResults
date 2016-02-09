#### Test 58135655e9e7eb8_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1022): sending alarm Alarm{42a89398 type 2 com.google.android.gms}
,D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
--------- beginning of /dev/log/main
D/AndroidRuntime( 3394): 
D/AndroidRuntime( 3394): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3394): CheckJNI is OFF
D/dalvikvm( 3394): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3394): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3394): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3394): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3394): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3394): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3394): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3394): failed to load memtrack module: -2
D/AndroidRuntime( 3394): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1022): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3394
D/AndroidRuntime( 3394): Shutting down VM
D/dalvikvm( 3394): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+0ms, total 3ms
,V/AlarmManager( 1022): sending alarm Alarm{421fda48 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{429d2580 type 2 com.google.android.gms}
,E/global frequency( 1583): no tags to log
,D/Checkin ( 1583): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1583): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1583): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1583): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1583): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1583): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1583): BcsDSCheckin.events found events 2000
,D/Checkin ( 1583): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1583): GC_CONCURRENT freed 5451K, 33% free 11679K/17224K, paused 2ms+5ms, total 43ms
,I/BSUtils ( 1583): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1583): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1583): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1583): unknown error code mapping for: 0
I/global frequency( 1583): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1583): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1583): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1583): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager( 1022): sending alarm Alarm{429bcba8 type 3 android}
,I/MMApiBackOffService( 1583): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1583): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1583): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
E/MMApiProvisionService( 1583): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: devices.json
,I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: 
D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1022): sending alarm Alarm{42813470 type 2 com.google.android.gms}
,I/VacuumService( 1216): Vacuum at: now=1455021564065 tag=VacuumService
,V/AlarmManager( 1022): sending alarm Alarm{428b4e40 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4290e700 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4290e790 type 2 com.google.android.gms}
,D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1022): sending alarm Alarm{427deb70 type 3 android}
,V/GLSActivity( 2032): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2032): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1022): sending alarm Alarm{428fc698 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42a2d1a8 type 2 com.motorola.ccc.cce}
I/PollingManager( 1583): alarm fired!
D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1022): sending alarm Alarm{429dd6f8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{428bdac8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{427e0a38 type 2 com.google.android.gms}
,D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  272): write error (Broken pipe)
,I/MMApiBackOffService( 1583): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1583): MMApiBackOffService told us it's okay to retry the waiting requests: 3
D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
E/MMApiProvisionService( 1583): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1583): ProvisionWS.Response.setError: error RadioDownError
I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1022): sending alarm Alarm{428fe798 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42a4b540 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/GLSActivity( 2032): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2032): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1022): sending alarm Alarm{42a1ce18 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{428f91d8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42a464a8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42159c48 type 2 android}
,V/AlarmManager( 1022): sending alarm Alarm{42159d20 type 0 com.android.vending}
,D/Finsky  ( 3058): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/ConnectivityService( 1022): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1022): Done.
,D/ConnectivityService( 1022): Setting timer for 720seconds
,V/GLSActivity( 2032): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2032): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3058): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/SocketClient(  272): write error (Broken pipe)
,V/GLSActivity( 2032): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2032): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2032): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2032): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3058): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 2032): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2032): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3058): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 3058): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1022): sending alarm Alarm{42983d78 type 0 com.android.vending}
D/Finsky  ( 3058): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/WearableService( 1216): callingUid 10022, callindPid: 1216
,D/DeviceConnectionService( 1216): client connected with version: 8296000
,D/Finsky  ( 3058): [266] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3058): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 3058): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3058): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 2032): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2032): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1022): sending alarm Alarm{42a3c870 type 0 com.android.vending}
,D/Finsky  ( 3058): [252] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3058): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/AlarmManager( 1022): sending alarm Alarm{428bfa40 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{429cf400 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42a87ee8 type 2 com.google.android.gms}
,D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  272): write error (Broken pipe)
,V/GLSActivity( 2032): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2032): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1022): sending alarm Alarm{42999c68 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{429163c8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{428e9190 type 3 android}
,I/MMApiBackOffService( 1583): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1583): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
E/MMApiProvisionService( 1583): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1583): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: devices.json
,I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: 
,D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1022): sending alarm Alarm{428ea6c8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{428ede08 type 3 android}
,V/GLSActivity( 2032): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2032): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1022): sending alarm Alarm{428ef2d8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{428d0df0 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3492): 
D/AndroidRuntime( 3492): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3492): CheckJNI is OFF
D/dalvikvm( 3492): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3492): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3492): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3492): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3492): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3492): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3492): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3492): failed to load memtrack module: -2
D/AndroidRuntime( 3492): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1022): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1022): GC_EXPLICIT freed 948K, 9% free 18415K/20152K, paused 3ms+8ms, total 86ms
D/AndroidRuntime( 3492): Shutting down VM
D/dalvikvm( 3492): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms

```
