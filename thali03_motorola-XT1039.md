#### Test 586024278176cca_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1020): sending alarm Alarm{42d3ad30 type 3 android}
V/AlarmManager( 1020): sending alarm Alarm{42de1aa0 type 2 com.google.android.gms}
--------- beginning of /dev/log/main
D/AndroidRuntime( 3549): 
D/AndroidRuntime( 3549): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3549): CheckJNI is OFF
D/dalvikvm( 3549): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3549): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3549): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3549): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3549): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3549): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3549): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3549): failed to load memtrack module: -2
D/AndroidRuntime( 3549): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3549
D/AndroidRuntime( 3549): Shutting down VM
D/dalvikvm( 3549): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+0ms, total 2ms
,I/ClearcutLoggerApiImpl( 2063): disconnect managed GoogleApiClient
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,E/global frequency( 1578): no tags to log
,D/Checkin ( 1578): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1578): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1578): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1578): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1578): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1578): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1578): BcsDSCheckin.events found events 2000
,D/Checkin ( 1578): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1578): GC_CONCURRENT freed 5496K, 33% free 11684K/17224K, paused 3ms+6ms, total 60ms
,I/BSUtils ( 1578): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1578): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1578): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1578): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1578): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1578): unknown error code mapping for: 0
I/global frequency( 1578): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1578): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{42df0b98 type 3 android}
,I/MMApiBackOffService( 1578): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1578): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1578): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
I/MMApiWebService( 1578): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1578): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1578): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1578): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiBackOffService( 1578): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1578): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1578): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1578): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1578): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1578): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1578): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1578): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1578): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{42da2f28 type 2 com.google.android.gms}
,V/AlarmManager( 1020): sending alarm Alarm{42dd5358 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,I/VacuumService( 1215): Vacuum at: now=1454935120331 tag=VacuumService
,V/AlarmManager( 1020): sending alarm Alarm{42ce3be8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42ce3c60 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42e999c8 type 3 android}
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{4277c268 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42a12c00 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1020): sending alarm Alarm{42d5fc20 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42f492a8 type 3 android}
,I/MMApiBackOffService( 1578): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1578): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1578): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1578): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1578): ProvisionWS.Response.setError: error RadioDownError
D/MMApiWebService( 1578): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1578): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1578): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1578): MMApiWebService told us not to continue at the moment with this request: devices.json
,I/MMApiWebService( 1578): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1578): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1578): MMApiWebService told us not to continue at the moment with this request: 
D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1578): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1578): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1578): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1578): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{42cf9c90 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42d4f8a0 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  273): write error (Broken pipe)
,V/AlarmManager( 1020): sending alarm Alarm{42cc3788 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42d50690 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42583cc8 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  273): write error (Broken pipe)
,V/AlarmManager( 1020): sending alarm Alarm{42806490 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42996da0 type 2 android}
,V/AlarmManager( 1020): sending alarm Alarm{42809d40 type 0 com.google.android.gms}
,V/AlarmManager( 1020): sending alarm Alarm{427f5630 type 0 com.android.vending}
,D/ConnectivityService( 1020): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1020): Done.
,D/Finsky  ( 3093): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/ConnectivityService( 1020): Setting timer for 720seconds
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1640): Aggregate from 1454933701389 (log), 1454933701389 (data)
,W/Finsky  ( 3093): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3093): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3093): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 3093): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1020): sending alarm Alarm{42f45b80 type 0 com.android.vending}
D/Finsky  ( 3093): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/WearableService( 1215): callingUid 10022, callindPid: 1215
,D/DeviceConnectionService( 1215): client connected with version: 8296000
,D/Finsky  ( 3093): [270] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3093): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 3093): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3093): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/dalvikvm( 2063): GC_EXPLICIT freed 1822K, 40% free 10353K/17224K, paused 2ms+4ms, total 34ms
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{42d69258 type 0 com.android.vending}
,D/Finsky  ( 3093): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3093): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/AlarmManager( 1020): sending alarm Alarm{42d69308 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42e88da8 type 3 android}
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  273): write error (Broken pipe)
,V/AlarmManager( 1020): sending alarm Alarm{42ea9c28 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42f47130 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42f401c8 type 3 android}
,I/MMApiBackOffService( 1578): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1578): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1578): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1578): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1578): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1578): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1578): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiBackOffService( 1578): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1578): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1578): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1578): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1578): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1578): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1578): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1578): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1578): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{42debaa8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42ec1d40 type 3 android}
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1020): GC_EXPLICIT freed 1032K, 8% free 18439K/19996K, paused 3ms+8ms, total 92ms
,V/AlarmManager( 1020): sending alarm Alarm{42ec3210 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42f4d940 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42f49538 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3656): 
D/AndroidRuntime( 3656): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3656): CheckJNI is OFF
D/dalvikvm( 3656): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3656): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3656): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3656): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3656): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3656): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3656): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3656): failed to load memtrack module: -2
D/AndroidRuntime( 3656): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1020): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1020): GC_EXPLICIT freed 152K, 9% free 18320K/19996K, paused 3ms+6ms, total 81ms
D/AndroidRuntime( 3656): Shutting down VM
D/dalvikvm( 3656): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms

```
