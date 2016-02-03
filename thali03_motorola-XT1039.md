#### Test 58135655c662d33_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/ClearcutLoggerApiImpl( 2088): disconnect managed GoogleApiClient
,D/AndroidRuntime( 3495): 
D/AndroidRuntime( 3495): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3495): CheckJNI is OFF
D/dalvikvm( 3495): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3495): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3495): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3495): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3495): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3495): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3495): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3495): failed to load memtrack module: -2
D/AndroidRuntime( 3495): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3495
D/AndroidRuntime( 3495): Shutting down VM
D/dalvikvm( 3495): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 1ms+0ms, total 3ms
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
,V/AlarmManager( 1019): sending alarm Alarm{42c8e290 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42e963a0 type 2 com.google.android.gms}
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
,E/global frequency( 1582): no tags to log
,D/Checkin ( 1582): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1582): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1582): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1582): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1582): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1582): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1582): BcsDSCheckin.events found events 2000
,D/Checkin ( 1582): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1582): GC_CONCURRENT freed 5476K, 33% free 11682K/17224K, paused 3ms+5ms, total 52ms
,I/BSUtils ( 1582): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1582): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1582): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1582): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1582): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1582): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1582): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1582): unknown error code mapping for: 0
I/global frequency( 1582): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1582): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 1582): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1582): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1582): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1582): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1582): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1582): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
I/MMApiWebService( 1582): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/MMApiWebService( 1582): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/Checkin ( 1582): publish the event [tag = MOT_CCE event name = LOG]
E/MMApiProvisionService( 1582): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1582): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiBackOffService( 1582): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1582): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1582): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1582): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1582): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1582): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1582): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1582): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1582): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1582): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1582): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1582): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1582): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1582): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1582): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1582): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1582): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1582): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{42e211f0 type 2 com.google.android.gms}
,I/VacuumService( 1212): Vacuum at: now=1454523235797 tag=VacuumService
,V/AlarmManager( 1019): sending alarm Alarm{42c06798 type 3 android}
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42c04258 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42c03910 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1019): sending alarm Alarm{42c92390 type 3 android}

```
