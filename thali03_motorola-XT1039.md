#### Test 584164489c56086_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1019): sending alarm Alarm{42d7e228 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 3407): 
D/AndroidRuntime( 3407): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3407): CheckJNI is OFF
D/dalvikvm( 3407): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3407): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3407): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3407): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3407): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3407): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3407): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3407): failed to load memtrack module: -2
D/AndroidRuntime( 3407): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3407
D/AndroidRuntime( 3407): Shutting down VM
D/dalvikvm( 3407): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+0ms, total 2ms
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,E/global frequency( 1563): no tags to log
,D/Checkin ( 1563): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1563): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1563): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1563): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1563): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1563): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1563): BcsDSCheckin.events found events 2000
,D/Checkin ( 1563): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1563): GC_CONCURRENT freed 5491K, 33% free 11684K/17224K, paused 3ms+6ms, total 58ms
,I/BSUtils ( 1563): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1563): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1563): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1563): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1563): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1563): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1563): unknown error code mapping for: 0
I/global frequency( 1563): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1563): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ClearcutLoggerApiImpl( 1318): disconnect managed GoogleApiClient
,V/AlarmManager( 1019): sending alarm Alarm{42e4d978 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42dd4b18 type 2 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{42dd4778 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,I/VacuumService( 1211): Vacuum at: now=1455009691383 tag=VacuumService
,I/MMApiBackOffService( 1563): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1563): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1563): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1563): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1563): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1563): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1563): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1563): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1563): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1563): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1563): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1563): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1563): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1563): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1563): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1563): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1563): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1563): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1563): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{42c0ffa0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42bdb5b0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42d7d2d0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42dd7468 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42bcc250 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  271): write error (Broken pipe)
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{42c94df8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42e256c0 type 3 android}
,I/MMApiBackOffService( 1563): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1563): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1563): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1563): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1563): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1563): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1563): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1563): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1563): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1563): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1563): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1563): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1563): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1563): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
I/MMApiWebService( 1563): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1563): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1563): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1563): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1563): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42dac940 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42e34f88 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42542ba8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42e62e90 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  271): write error (Broken pipe)
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{42e53470 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42cc14d8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42d9b8d8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42bc9318 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{42bc3608 type 0 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{42bc3658 type 0 com.android.vending}
,D/Finsky  ( 3060): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1658): Aggregate from 1455008245622 (log), 1455008245622 (data)
,W/Finsky  ( 3060): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/dalvikvm( 1318): GC_EXPLICIT freed 1732K, 40% free 10354K/17224K, paused 2ms+4ms, total 31ms
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3060): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3060): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 3060): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1019): sending alarm Alarm{42de6d68 type 0 com.android.vending}
D/Finsky  ( 3060): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,D/WearableService( 1211): callingUid 10022, callindPid: 1211
,D/DeviceConnectionService( 1211): client connected with version: 8296000
,D/Finsky  ( 3060): [260] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3060): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 3060): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3060): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{42d94f28 type 0 com.android.vending}
,D/Finsky  ( 3060): [246] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3060): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/AlarmManager( 1019): sending alarm Alarm{42d95000 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42e49198 type 3 android}
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{42e4a688 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42e5a9f8 type 3 android}
,I/MMApiBackOffService( 1563): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1563): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1563): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1563): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1563): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1563): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1563): ProvisionWS.Response.setError: error RadioDownError
D/MMApiWebService( 1563): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1563): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1563): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1563): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1563): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1563): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1563): MMApiWebService told us not to continue at the moment with this request: 
D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1563): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1563): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1563): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1563): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1563): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1563): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{42e5bf80 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42e3b450 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42e3c920 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42d950d8 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  271): write error (Broken pipe)
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1318): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1019): GC_EXPLICIT freed 1002K, 9% free 18377K/20028K, paused 3ms+8ms, total 89ms
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{42e3e3d8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42e31a20 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3518): 
D/AndroidRuntime( 3518): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3518): CheckJNI is OFF
D/dalvikvm( 3518): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3518): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3518): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3518): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3518): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3518): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3518): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3518): failed to load memtrack module: -2
D/AndroidRuntime( 3518): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1019): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1019): GC_EXPLICIT freed 142K, 9% free 18251K/20028K, paused 3ms+7ms, total 80ms
D/AndroidRuntime( 3518): Shutting down VM
D/dalvikvm( 3518): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms

```
