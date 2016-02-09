#### Test 583805004f2b042_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3415): 
D/AndroidRuntime( 3415): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3415): CheckJNI is OFF
D/dalvikvm( 3415): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3415): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3415): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3415): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3415): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3415): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3415): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3415): failed to load memtrack module: -2
D/AndroidRuntime( 3415): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3415
D/AndroidRuntime( 3415): Shutting down VM
D/dalvikvm( 3415): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+1ms, total 2ms
,V/AlarmManager( 1018): sending alarm Alarm{4278b4e0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4299dd88 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{428054a0 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1018): sending alarm Alarm{427f8208 type 2 com.google.android.gms}
,E/global frequency( 1570): no tags to log
,D/Checkin ( 1570): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1570): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1570): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1570): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1570): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1570): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1570): BcsDSCheckin.events found events 2000
,D/Checkin ( 1570): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1570): GC_CONCURRENT freed 5452K, 33% free 11705K/17224K, paused 2ms+11ms, total 59ms
,I/BSUtils ( 1570): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1570): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1570): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1570): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1570): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1570): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1570): unknown error code mapping for: 0
I/global frequency( 1570): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1570): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1570): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1570): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 1570): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1570): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1570): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1570): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1570): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
E/MMApiProvisionService( 1570): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1570): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1570): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/MMApiWebService( 1570): doRequest(): polling manager says we're not connected, returning with an error: 
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1570): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1570): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1570): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1570): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1570): MMApiWebService told us not to continue at the moment with this request: 
D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1570): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1570): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1570): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1570): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1570): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{42408c80 type 2 com.google.android.gms}
,I/VacuumService( 1215): Vacuum at: now=1455035860317 tag=VacuumService
,V/AlarmManager( 1018): sending alarm Alarm{420bb4e8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{420bb5c0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4280dbd8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4277d028 type 2 com.google.android.gms}
,W/SocketClient(  272): write error (Broken pipe)
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1018): sending alarm Alarm{427a10e0 type 3 android}
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
,V/GLSActivity( 2079): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2079): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1018): sending alarm Alarm{4281e780 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{427b7dc0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4277d100 type 2 com.motorola.ccc.cce}
I/PollingManager( 1570): alarm fired!
D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1570): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1570): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1570): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1570): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1570): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1570): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1570): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1570): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1570): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1570): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1570): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1570): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1570): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1570): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1570): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1570): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1570): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1570): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1570): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{42045bd8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{428a6f48 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1018): sending alarm Alarm{427ffb20 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4297d678 type 3 android}
,V/GLSActivity( 2079): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2079): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1018): sending alarm Alarm{429a3420 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4294b410 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42975070 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4218f2e8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42827850 type 3 android}
,V/GLSActivity( 2079): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2079): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1018): sending alarm Alarm{42961898 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{425756c8 type 2 android}
,V/AlarmManager( 1018): sending alarm Alarm{428289a0 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): Sampling interval elapsed, updating statistics ..,
,D/ConnectivityService( 1018): Done.
,D/ConnectivityService( 1018): Setting timer for 720seconds
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1018): sending alarm Alarm{4295d178 type 3 android}
,I/MMApiBackOffService( 1570): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1570): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1570): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1570): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1570): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1570): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1570): ProvisionWS.Response: Missing mandatory message data in response from DM server...
I/MMApiWebService( 1570): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1570): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1570): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1570): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1570): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1570): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1570): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1570): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1570): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1570): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1570): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1570): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1570): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{42818d48 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{429a1238 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{427ebdd8 type 3 android}
,D/dalvikvm( 2079): GC_EXPLICIT freed 1768K, 41% free 10281K/17224K, paused 3ms+5ms, total 36ms
,V/GLSActivity( 2079): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2079): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1018): sending alarm Alarm{427dfbc8 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3499): 
D/AndroidRuntime( 3499): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3499): CheckJNI is OFF
D/dalvikvm( 3499): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3499): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3499): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3499): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3499): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3499): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3499): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3499): failed to load memtrack module: -2
D/AndroidRuntime( 3499): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1018): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1018): GC_EXPLICIT freed 762K, 9% free 18348K/20048K, paused 10ms+8ms, total 101ms
D/AndroidRuntime( 3499): Shutting down VM
D/dalvikvm( 3499): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms

```
