#### Test 58135655812b57f_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1016): sending alarm Alarm{427bfce8 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3401): 
D/AndroidRuntime( 3401): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3401): CheckJNI is OFF
D/dalvikvm( 3401): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3401): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3401): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3401): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3401): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3401): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
V/AlarmManager( 1016): sending alarm Alarm{429d4810 type 2 com.google.android.gms}
D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
E/memtrack( 3401): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3401): failed to load memtrack module: -2
D/AndroidRuntime( 3401): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1016): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3401
D/AndroidRuntime( 3401): Shutting down VM
D/dalvikvm( 3401): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+0ms, total 3ms
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
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{4295e428 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{429ef368 type 2 com.google.android.gms}
,E/global frequency( 1560): no tags to log
,D/Checkin ( 1560): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1560): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1560): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1560): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1560): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1560): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/ClearcutLoggerApiImpl( 1316): disconnect managed GoogleApiClient
,I/global frequency( 1560): BcsDSCheckin.events found events 2000
,D/Checkin ( 1560): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1560): GC_CONCURRENT freed 5474K, 33% free 11678K/17224K, paused 2ms+5ms, total 42ms
,I/BSUtils ( 1560): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1560): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1560): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1560): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1560): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1560): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1560): unknown error code mapping for: 0
I/global frequency( 1560): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1560): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1560): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1560): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 1560): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1560): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1560): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1560): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1560): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1560): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/MMApiWebService( 1560): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
E/MMApiProvisionService( 1560): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1560): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiBackOffService( 1560): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1560): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1560): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1560): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1560): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1560): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1560): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1560): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1560): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1560): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{429a0a28 type 2 com.google.android.gms}
,I/VacuumService( 1210): Vacuum at: now=1454948745586 tag=VacuumService
,V/AlarmManager( 1016): sending alarm Alarm{42169360 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{420b68a8 type 3 android}
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
,V/AlarmManager( 1016): sending alarm Alarm{4207c740 type 2 com.google.android.gms}
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1016): sending alarm Alarm{4210aed8 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42868188 type 3 android}
,V/GLSActivity( 1316): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1316): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{4280c918 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{429761b8 type 3 android}
,I/MMApiBackOffService( 1560): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1560): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1560): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1560): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1560): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1560): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1560): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1560): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1560): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1560): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1560): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1560): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1560): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1560): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1560): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1560): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1560): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1560): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1560): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{429ec6a8 type 2 com.google.android.gms}
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1016): sending alarm Alarm{42822778 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42806190 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{427c6ee0 type 3 android}
,V/GLSActivity( 1316): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1316): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{42a19bd8 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{428213f8 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4299ffe0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42321cb0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42947c20 type 3 android}
,V/GLSActivity( 1316): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1316): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{4205f6c8 type 2 android}
,D/ConnectivityService( 1016): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1016): sending alarm Alarm{427a3258 type 2 com.google.android.gms},
,V/AlarmManager( 1016): sending alarm Alarm{41fca280 type 0 com.google.android.gms}
,D/ConnectivityService( 1016): Done.
,D/ConnectivityService( 1016): Setting timer for 720seconds
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
,I/EventLogService( 1635): Aggregate from 1454947133474 (log), 1454947133474 (data)
,V/AlarmManager( 1016): sending alarm Alarm{4207e190 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4279db80 type 3 android}
,I/MMApiBackOffService( 1560): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1560): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1560): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1560): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1560): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1560): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1560): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,I/MMApiWebService( 1560): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1560): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1560): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1560): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1560): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1560): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1560): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1560): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1560): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1560): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1560): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1560): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1560): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{42a00ae8 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42856e50 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{427ccc18 type 3 android}
,V/GLSActivity( 1316): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1316): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{429ec9b8 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4282e2d0 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3483): 
D/AndroidRuntime( 3483): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3483): CheckJNI is OFF
D/dalvikvm( 3483): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3483): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3483): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3483): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3483): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3483): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3483): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3483): failed to load memtrack module: -2
D/AndroidRuntime( 3483): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1016): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1016): GC_EXPLICIT freed 771K, 10% free 18311K/20124K, paused 3ms+8ms, total 91ms
D/AndroidRuntime( 3483): Shutting down VM
D/dalvikvm( 3483): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms

```
