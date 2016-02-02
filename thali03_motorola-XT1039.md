#### Test 575312431be71d2_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1018): sending alarm Alarm{428a3be8 type 3 android}
V/AlarmManager( 1018): sending alarm Alarm{42a1f170 type 2 com.google.android.gms}
V/AlarmManager( 1018): sending alarm Alarm{42a1f440 type 2 com.google.android.gms}
D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
--------- beginning of /dev/log/main
I/VacuumService( 1211): Vacuum at: now=1454419126743 tag=VacuumService
D/AndroidRuntime( 3417): 
D/AndroidRuntime( 3417): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3417): CheckJNI is OFF
D/dalvikvm( 3417): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3417): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3417): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3417): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3417): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3417): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3417): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3417): failed to load memtrack module: -2
D/AndroidRuntime( 3417): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3417
D/AndroidRuntime( 3417): Shutting down VM
D/dalvikvm( 3417): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+0ms, total 2ms
,E/global frequency( 1578): no tags to log
,D/Checkin ( 1578): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1578): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1578): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1578): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1578): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1578): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1578): BcsDSCheckin.events found events 1739
,D/Checkin ( 1578): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1578): GC_CONCURRENT freed 5488K, 33% free 11620K/17224K, paused 3ms+5ms, total 44ms
,I/BSUtils ( 1578): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1578): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1578): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1578): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1578): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1578): unknown error code mapping for: 0
I/global frequency( 1578): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1578): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1578): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1578): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{4253edd8 type 3 android}
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MMApiBackOffService( 1578): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1578): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1578): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1578): doRequest(): polling manager says we're not connected, returning with an error: 
,E/MMApiProvisionService( 1578): ProvisionWS.Response: Missing mandatory message data in response from DM server...
I/MMApiWebService( 1578): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1578): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1578): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1578): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1578): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1578): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1578): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1578): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1578): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1578): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1578): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{42522e20 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{427bc270 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42489400 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  274): write error (Broken pipe)
,V/AlarmManager( 1018): sending alarm Alarm{42896c18 type 3 android}
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  274): write error (Broken pipe)
,V/AlarmManager( 1018): sending alarm Alarm{428acf60 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{429f3908 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42891ef8 type 3 android}
,I/MMApiBackOffService( 1578): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1578): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1578): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1578): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1578): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1578): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1578): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1578): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1578): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1578): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1578): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1578): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1578): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1578): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1578): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1578): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{42805738 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4297e3d8 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  274): write error (Broken pipe)
,V/AlarmManager( 1018): sending alarm Alarm{42827bb8 type 3 android}
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  274): write error (Broken pipe)
,V/AlarmManager( 1018): sending alarm Alarm{429e6b40 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42949400 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4288c6c0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42807188 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42805968 type 3 android}
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  274): write error (Broken pipe)
,V/AlarmManager( 1018): sending alarm Alarm{4295a248 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4210fa48 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42801d80 type 3 android}
,I/MMApiBackOffService( 1578): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1578): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1578): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1578): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1578): ProvisionWS.Response: Missing mandatory message data in response from DM server...
I/MMApiWebService( 1578): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1578): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1578): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1578): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1578): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1578): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1578): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1578): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1578): doRequest(): polling manager says we're not connected, returning with an error: 
D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1578): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1578): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1578): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{428271f8 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  274): write error (Broken pipe)
,V/AlarmManager( 1018): sending alarm Alarm{42a1dc80 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4243a460 type 2 android}
V/AlarmManager( 1018): sending alarm Alarm{423bfcc8 type 2 com.motorola.ccc.cce}
,V/AlarmManager( 1018): sending alarm Alarm{4238d170 type 0 com.google.android.gms}
,D/ConnectivityService( 1018): Sampling interval elapsed, updating statistics ..
,I/PollingManager( 1578): alarm fired!
,D/Checkin ( 1578): publish the event [tag = MOT_CCE event name = LOG]
,D/ConnectivityService( 1018): Done.
,D/ConnectivityService( 1018): Setting timer for 720seconds
,I/EventLogService( 1687): Aggregate from 1454417857121 (log), 1454417857121 (data)
,V/AlarmManager( 1018): sending alarm Alarm{42a11128 type 3 android}
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  274): write error (Broken pipe)
,V/AlarmManager( 1018): sending alarm Alarm{4283ecb0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42879e08 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3505): 
D/AndroidRuntime( 3505): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3505): CheckJNI is OFF
D/dalvikvm( 3505): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3505): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3505): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3505): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3505): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3505): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3505): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3505): failed to load memtrack module: -2
D/AndroidRuntime( 3505): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1018): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1018): GC_EXPLICIT freed 699K, 10% free 18300K/20144K, paused 3ms+7ms, total 90ms
D/AndroidRuntime( 3505): Shutting down VM
D/dalvikvm( 3505): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms

```
