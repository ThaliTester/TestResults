#### Test 57924002a578a80_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1016): sending alarm Alarm{428d8988 type 2 com.google.android.gms}
D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
--------- beginning of /dev/log/main
D/AndroidRuntime( 3488): 
D/AndroidRuntime( 3488): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3488): CheckJNI is OFF
D/dalvikvm( 3488): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3488): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3488): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3488): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3488): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3488): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3488): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3488): failed to load memtrack module: -2
D/AndroidRuntime( 3488): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1016): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3488
D/AndroidRuntime( 3488): Shutting down VM
D/dalvikvm( 3488): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+0ms, total 2ms
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{42ad6438 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42ad5470 type 2 com.google.android.gms}
,E/global frequency( 1572): no tags to log
,D/Checkin ( 1572): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1572): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1572): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 1572): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1572): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1572): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1572): BcsDSCheckin.events found events 2000
,D/Checkin ( 1572): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1572): GC_CONCURRENT freed 5473K, 33% free 11685K/17224K, paused 3ms+6ms, total 57ms
,I/BSUtils ( 1572): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1572): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
D/MMApiWebService( 1572): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1572): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1572): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1572): AppWSProxy - sendAIDLWSResponse() sending reponse
I/ErrorTranslator( 1572): unknown error code mapping for: 0
I/global frequency( 1572): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1572): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1572): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1572): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{42ac4cd8 type 3 android}
,I/MMApiBackOffService( 1572): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1572): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1572): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1572): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1572): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1572): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1572): ProvisionWS.Response.setError: error RadioDownError
D/MMApiWebService( 1572): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1572): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1572): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1572): MMApiWebService told us not to continue at the moment with this request: devices.json
,I/MMApiWebService( 1572): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1572): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1572): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1572): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1572): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1572): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1572): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1572): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{42a70d20 type 2 com.google.android.gms}
,I/VacuumService( 1212): Vacuum at: now=1454460207425 tag=VacuumService
,V/AlarmManager( 1016): sending alarm Alarm{4260ee68 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{425f5038 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{425f2d48 type 2 com.google.android.gms}
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1016): sending alarm Alarm{420d2768 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42220608 type 3 android}
,V/GLSActivity( 2055): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2055): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{42812780 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{429b9de8 type 3 android}
,I/MMApiBackOffService( 1572): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1572): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1572): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1572): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1572): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1572): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1572): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1572): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,E/MMApiProvisionService( 1572): ProvisionWS.Response.setError: error RadioDownError
I/MMApiBackOffService( 1572): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1572): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1572): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1572): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1572): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1572): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1572): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1572): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1572): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1572): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{429ad2f8 type 2 com.google.android.gms}
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1016): sending alarm Alarm{421ce010 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{428ddfa0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42857d38 type 3 android}
,D/dalvikvm( 2055): GC_EXPLICIT freed 1561K, 41% free 10319K/17224K, paused 2ms+4ms, total 38ms
,V/GLSActivity( 2055): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2055): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{420e5288 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42935af0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42a6aec8 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{421660d0 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{42a66020 type 3 android}
,V/GLSActivity( 2055): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2055): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{42928360 type 2 com.google.android.gms}
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1016): sending alarm Alarm{4289c3a8 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42550c90 type 2 android}
,V/AlarmManager( 1016): sending alarm Alarm{4253b880 type 0 com.google.android.gms}
,D/ConnectivityService( 1016): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1016): Done.
,D/ConnectivityService( 1016): Setting timer for 720seconds
,I/EventLogService( 1673): Aggregate from 1454459277008 (log), 1454459277008 (data)
,V/AlarmManager( 1016): sending alarm Alarm{429abda0 type 3 android}
,I/MMApiBackOffService( 1572): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1572): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1572): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1572): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1572): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1572): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
E/MMApiProvisionService( 1572): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1572): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/MMApiWebService( 1572): doRequest(): polling manager says we're not connected, returning with an error: 
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1572): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1572): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1572): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1572): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1572): MMApiWebService told us not to continue at the moment with this request: 
D/MMApiWebService( 1572): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1572): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1572): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1572): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1572): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1572): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{428f1b40 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4299b520 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42908b60 type 3 android}
,V/GLSActivity( 2055): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2055): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{429b9b80 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3569): 
D/AndroidRuntime( 3569): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3569): CheckJNI is OFF
D/dalvikvm( 3569): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3569): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3569): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3569): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3569): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3569): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3569): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3569): failed to load memtrack module: -2
D/AndroidRuntime( 3569): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1016): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1016): GC_EXPLICIT freed 751K, 9% free 18351K/20120K, paused 3ms+8ms, total 84ms
D/AndroidRuntime( 3569): Shutting down VM
D/dalvikvm( 3569): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms

```
