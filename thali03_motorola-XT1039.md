#### Test 57924002d5e0b14_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
E/global frequency( 1580): no tags to log
,D/Checkin ( 1580): publish the event [tag = MOT_CHECKIN event name = LOG]
I/BSUtils ( 1580): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/BSUtils ( 1580): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 1580): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 1580): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 1580): publish the event [tag = DEV_ATTRIBS event name = SW]
I/global frequency( 1580): BcsDSCheckin.events found events 1947
D/Checkin ( 1580): publish the event [tag = MOT_CHECKIN event name = LOG]
D/dalvikvm( 1580): GC_CONCURRENT freed 5484K, 32% free 11764K/17224K, paused 3ms+13ms, total 86ms
I/BSUtils ( 1580): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/AndroidRuntime( 3383): 
D/AndroidRuntime( 3383): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3383): CheckJNI is OFF
D/dalvikvm( 3383): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3383): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3383): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3383): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3383): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3383): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1580): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 1580): AppWSProxy - sendAIDLWSResponse() sending reponse
I/ErrorTranslator( 1580): unknown error code mapping for: 0
I/global frequency( 1580): BcsCore.status() called with error code=ERROR_FAIL
D/Checkin ( 1580): publish the event [tag = MOT_CHECKIN event name = LOG]
I/global frequency( 1580): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
D/Checkin ( 1580): publish the event [tag = MOT_CHECKIN event name = LOG]
E/memtrack( 3383): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3383): failed to load memtrack module: -2
D/AndroidRuntime( 3383): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1022): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3383
D/AndroidRuntime( 3383): Shutting down VM
D/dalvikvm( 3383): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+1ms, total 2ms
,V/AlarmManager( 1022): sending alarm Alarm{42a19fc8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42379b50 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42a54a70 type 2 com.google.android.gms}
,V/AlarmManager( 1022): sending alarm Alarm{42a69298 type 2 com.google.android.gms}
,D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
,I/VacuumService( 1211): Vacuum at: now=1454440740872 tag=VacuumService
,I/MMApiBackOffService( 1580): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1580): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1580): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1580): ProvisionWS.Response.setError: error RadioDownError
I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1022): sending alarm Alarm{4234b7d8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4232d1f0 type 3 android}
,W/SocketClient(  274): write error (Broken pipe)
,V/AlarmManager( 1022): sending alarm Alarm{42951478 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{422f4fa8 type 2 com.google.android.gms}
,D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  274): write error (Broken pipe)
,V/GLSActivity( 2049): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2049): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  274): write error (Broken pipe)
,V/AlarmManager( 1022): sending alarm Alarm{428faf40 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{428f27d8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{421787e0 type 3 android}
,I/MMApiBackOffService( 1580): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1580): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1580): ProvisionWS.Response: Missing mandatory message data in response from DM server...
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1580): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1022): sending alarm Alarm{4289ed98 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{428ccae8 type 2 com.google.android.gms}
,D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  274): write error (Broken pipe)
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1022): sending alarm Alarm{42973738 type 3 android}
,V/GLSActivity( 2049): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2049): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  274): write error (Broken pipe)
,V/AlarmManager( 1022): sending alarm Alarm{428c2d08 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42a6dde8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42960008 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4295fc80 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42958878 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{428cc808 type 3 android}
,V/GLSActivity( 2049): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2049): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1022): sending alarm Alarm{4245b580 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42a4d010 type 3 android}
,I/MMApiBackOffService( 1580): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1580): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1580): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1580): ProvisionWS.Response.setError: error RadioDownError
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: devices.json
,I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1022): sending alarm Alarm{422a4a18 type 2 android}
,V/AlarmManager( 1022): sending alarm Alarm{42864d20 type 2 com.google.android.gms}
,V/AlarmManager( 1022): sending alarm Alarm{4228b318 type 0 com.google.android.gms}
,D/ConnectivityService( 1022): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1022): Done.
,D/ConnectivityService( 1022): Setting timer for 720seconds
,D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
,I/EventLogService( 1677): Aggregate from 1454439278952 (log), 1454439278952 (data)
,V/AlarmManager( 1022): sending alarm Alarm{42a703d0 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42a5e1c8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4295bb18 type 3 android}
,V/GLSActivity( 2049): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2049): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  274): write error (Broken pipe)
,V/AlarmManager( 1022): sending alarm Alarm{42953960 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42957f48 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3479): 
D/AndroidRuntime( 3479): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3479): CheckJNI is OFF
D/dalvikvm( 3479): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3479): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3479): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3479): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3479): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3479): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3479): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3479): failed to load memtrack module: -2
D/AndroidRuntime( 3479): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1022): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1022): WAIT_FOR_CONCURRENT_GC blocked 1ms
D/dalvikvm( 1022): GC_EXPLICIT freed 703K, 8% free 18322K/19836K, paused 2ms+8ms, total 95ms
D/AndroidRuntime( 3479): Shutting down VM
D/dalvikvm( 3479): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms

```
