#### Test 57972094912017a_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
E/global frequency( 1576): no tags to log
,D/Checkin ( 1576): publish the event [tag = MOT_CHECKIN event name = LOG]
I/BSUtils ( 1576): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/BSUtils ( 1576): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 1576): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 1576): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 1576): publish the event [tag = DEV_ATTRIBS event name = SW]
I/global frequency( 1576): BcsDSCheckin.events found events 1779
D/Checkin ( 1576): publish the event [tag = MOT_CHECKIN event name = LOG]
I/BSUtils ( 1576): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/dalvikvm( 1576): GC_CONCURRENT freed 5486K, 33% free 11681K/17224K, paused 3ms+11ms, total 64ms
D/AndroidRuntime( 3380): 
D/AndroidRuntime( 3380): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3380): CheckJNI is OFF
D/dalvikvm( 3380): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3380): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3380): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3380): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3380): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3380): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1576): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 1576): AppWSProxy - sendAIDLWSResponse() sending reponse
I/ErrorTranslator( 1576): unknown error code mapping for: 0
I/global frequency( 1576): BcsCore.status() called with error code=ERROR_FAIL
D/Checkin ( 1576): publish the event [tag = MOT_CHECKIN event name = LOG]
I/global frequency( 1576): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
D/Checkin ( 1576): publish the event [tag = MOT_CHECKIN event name = LOG]
E/memtrack( 3380): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3380): failed to load memtrack module: -2
D/AndroidRuntime( 3380): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3380
D/AndroidRuntime( 3380): Shutting down VM
D/dalvikvm( 3380): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+0ms, total 2ms
,V/AlarmManager( 1019): sending alarm Alarm{43148f50 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4316fe38 type 2 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{43183438 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,I/VacuumService( 1214): Vacuum at: now=1454420862946 tag=VacuumService
,V/AlarmManager( 1019): sending alarm Alarm{430130f8 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MMApiBackOffService( 1576): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1576): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1576): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1576): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: 
D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{42ffa4f0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42f7a5d8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4281fb70 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42ff2700 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  271): write error (Broken pipe)
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{42f92c48 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42fe5790 type 2 com.motorola.ccc.cce}
I/PollingManager( 1576): alarm fired!
D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{4301c988 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4315d150 type 3 android}
,I/MMApiBackOffService( 1576): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1576): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1576): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1576): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{42718510 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42f2b650 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{430e95f0 type 3 android}
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{4301ba00 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43009f78 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4300be88 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43015008 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4302c360 type 3 android}
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{42f9d180 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42ffb4c8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{430bb8a0 type 3 android}
,I/MMApiBackOffService( 1576): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1576): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
E/MMApiProvisionService( 1576): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1576): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: 
D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{43122720 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{430c9560 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{431489e8 type 3 android}
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1336): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{42fddba8 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{42fba110 type 0 com.google.android.gms}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,I/EventLogService( 1665): Aggregate from 1454420149659 (log), 1454420149659 (data)
,V/AlarmManager( 1019): sending alarm Alarm{430c8e00 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{430aad60 type 3 android}
,I/ClearcutLoggerApiImpl( 1336): disconnect managed GoogleApiClient
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3475): 
D/AndroidRuntime( 3475): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3475): CheckJNI is OFF
D/dalvikvm( 3475): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3475): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3475): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3475): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3475): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3475): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3475): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3475): failed to load memtrack module: -2
D/AndroidRuntime( 3475): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1019): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1019): GC_EXPLICIT freed 712K, 10% free 18289K/20104K, paused 2ms+8ms, total 84ms
D/AndroidRuntime( 3475): Shutting down VM
D/dalvikvm( 3475): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms

```
