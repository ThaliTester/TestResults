#### Test 58135655a1ee273_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3426): 
D/AndroidRuntime( 3426): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3426): CheckJNI is OFF
D/dalvikvm( 3426): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3426): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3426): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3426): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3426): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3426): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3426): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3426): failed to load memtrack module: -2
D/AndroidRuntime( 3426): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3426
D/AndroidRuntime( 3426): Shutting down VM
D/dalvikvm( 3426): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 1ms+0ms, total 3ms
,E/global frequency( 1577): no tags to log
,D/Checkin ( 1577): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1577): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1577): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1577): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1577): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1577): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1577): BcsDSCheckin.events found events 2000
,D/Checkin ( 1577): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1577): GC_CONCURRENT freed 5489K, 33% free 11686K/17224K, paused 3ms+5ms, total 55ms
,I/BSUtils ( 1577): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1577): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1577): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1577): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1577): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1577): AppWSProxy - sendAIDLWSResponse() sending reponse
I/ErrorTranslator( 1577): unknown error code mapping for: 0
I/global frequency( 1577): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1577): publish the event [tag = MOT_CHECKIN event name = LOG]
I/global frequency( 1577): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1577): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ClearcutLoggerApiImpl( 2062): disconnect managed GoogleApiClient
,V/AlarmManager( 1019): sending alarm Alarm{429a0e68 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{429504d0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{429a85e8 type 2 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{429b7998 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,I/VacuumService( 1209): Vacuum at: now=1454597283959 tag=VacuumService
,I/MMApiBackOffService( 1577): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1577): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1577): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1577): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1577): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1577): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1577): ProvisionWS.Response: Missing mandatory message data in response from DM server...
I/MMApiWebService( 1577): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1577): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1577): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1577): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1577): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1577): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1577): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1577): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1577): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1577): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1577): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1577): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{427070d8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42700a18 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4278e2f0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{426ff920 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,V/GLSActivity( 2062): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2062): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{427cd188 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{420bb4e0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{427690a8 type 3 android}
,I/MMApiBackOffService( 1577): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1577): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1577): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1577): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1577): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1577): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1577): ProvisionWS.Response: Missing mandatory message data in response from DM server...
I/MMApiWebService( 1577): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1577): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1577): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1577): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1577): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1577): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1577): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
I/MMApiWebService( 1577): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1577): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1577): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1577): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1577): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{427a9e28 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42750e90 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{427c0ca8 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,V/GLSActivity( 2062): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2062): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{427d27e8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42764510 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4278c5a0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42817bd8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{427b2138 type 3 android}
,V/GLSActivity( 2062): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2062): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{428093b8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42997888 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4277fcd0 type 3 android}
,I/MMApiBackOffService( 1577): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1577): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1577): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1577): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1577): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1577): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1577): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1577): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1577): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1577): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1577): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1577): MMApiWebService told us not to continue at the moment with this request: 
D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1577): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1577): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1577): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1577): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1577): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1577): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1577): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1577): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{42925d28 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{426f6b50 type 2 android}
,V/AlarmManager( 1019): sending alarm Alarm{427fcee0 type 2 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{426f4158 type 0 com.google.android.gms}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,I/EventLogService( 1660): Aggregate from 1454596125686 (log), 1454596125686 (data)
,V/AlarmManager( 1019): sending alarm Alarm{420f5988 type 3 android}
,V/GLSActivity( 2062): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2062): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{429c12f0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{429341b0 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3523): 
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
D/AndroidRuntime( 3523): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1019): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1019): GC_EXPLICIT freed 700K, 10% free 18323K/20164K, paused 3ms+7ms, total 83ms
D/AndroidRuntime( 3523): Shutting down VM
D/dalvikvm( 3523): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms

```
