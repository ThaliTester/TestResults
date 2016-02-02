#### Test 5753124305d96c2_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1016): sending alarm Alarm{4306b2e8 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43177480 type 2 com.google.android.gms}
D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
--------- beginning of /dev/log/main
D/AndroidRuntime( 3432): 
D/AndroidRuntime( 3432): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3432): CheckJNI is OFF
D/dalvikvm( 3432): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3432): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3432): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3432): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3432): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3432): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3432): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3432): failed to load memtrack module: -2
D/AndroidRuntime( 3432): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1016): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3432
D/AndroidRuntime( 3432): Shutting down VM
D/dalvikvm( 3432): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+1ms, total 2ms
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{43138460 type 2 com.google.android.gms}
,E/global frequency( 1601): no tags to log
,D/Checkin ( 1601): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1601): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1601): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1601): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1601): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1601): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1601): BcsDSCheckin.events found events 1819
,D/Checkin ( 1601): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1601): GC_CONCURRENT freed 5461K, 33% free 11688K/17224K, paused 2ms+5ms, total 53ms
,I/BSUtils ( 1601): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1601): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1601): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1601): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1601): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1601): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1601): unknown error code mapping for: 0
I/global frequency( 1601): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1601): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1601): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1601): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 1601): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1601): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1601): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1601): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1601): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/MMApiWebService( 1601): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1601): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
E/MMApiProvisionService( 1601): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1601): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiBackOffService( 1601): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1601): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1601): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1601): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1601): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1601): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1601): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1601): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1601): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1601): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{430c2df8 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{430b1498 type 2 com.google.android.gms}
,I/VacuumService( 1216): Vacuum at: now=1454422625733 tag=VacuumService
,V/AlarmManager( 1016): sending alarm Alarm{42f135b0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42ef4de0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42ec44c8 type 2 com.google.android.gms}
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
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
,V/AlarmManager( 1016): sending alarm Alarm{42ed1480 type 3 android}
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{4295d288 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42c2fe08 type 2 com.motorola.ccc.cce}
,I/PollingManager( 1601): alarm fired!
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{42fadb38 type 3 android}
,I/MMApiBackOffService( 1601): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1601): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1601): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1601): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1601): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1601): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1601): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1601): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1601): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1601): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1601): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1601): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1601): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1601): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1601): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1601): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1601): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1601): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1601): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{42ff84e8 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42909830 type 2 com.google.android.gms}
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1016): sending alarm Alarm{428b2788 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42ff9950 type 3 android}
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{430735f8 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42eda738 type 3 android}
,I/ClearcutLoggerApiImpl( 1371): disconnect managed GoogleApiClient
,V/AlarmManager( 1016): sending alarm Alarm{42ed4768 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{429fa6a8 type 2 android}
,V/AlarmManager( 1016): sending alarm Alarm{428737c0 type 0 com.android.vending}
,D/Finsky  ( 3053): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/ConnectivityService( 1016): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1016): Done.
,D/ConnectivityService( 1016): Setting timer for 720seconds
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3053): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3053): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3053): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 3053): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1016): sending alarm Alarm{42fb4710 type 0 com.android.vending}
,D/dalvikvm( 1371): GC_CONCURRENT freed 1840K, 41% free 10322K/17224K, paused 3ms+7ms, total 42ms
,D/Finsky  ( 3053): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/WearableService( 1216): callingUid 10022, callindPid: 1216
,D/DeviceConnectionService( 1216): client connected with version: 8296000
,D/Finsky  ( 3053): [263] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3053): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 3053): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3053): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{4315ffc8 type 0 com.android.vending}
,D/Finsky  ( 3053): [249] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3053): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/AlarmManager( 1016): sending alarm Alarm{42fb1c50 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43099f38 type 3 android}
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{43058a30 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43146a20 type 2 com.google.android.gms}
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1016): sending alarm Alarm{42fbc3d0 type 3 android}
,I/MMApiBackOffService( 1601): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1601): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1601): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1601): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1601): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1601): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1601): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1601): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1601): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1601): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1601): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1601): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1601): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1601): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1601): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1601): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1601): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1601): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1601): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1601): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{43098340 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43075208 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{430766f8 type 3 android}
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1371): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{43077be8 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43065690 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3524): 
D/AndroidRuntime( 3524): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3524): CheckJNI is OFF
D/dalvikvm( 3524): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3524): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3524): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3524): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3524): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3524): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3524): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3524): failed to load memtrack module: -2
D/AndroidRuntime( 3524): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1016): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1016): GC_EXPLICIT freed 880K, 10% free 18385K/20212K, paused 3ms+8ms, total 84ms
D/AndroidRuntime( 3524): Shutting down VM
D/dalvikvm( 3524): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms

```
