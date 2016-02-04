#### Test 575312431745da8_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3490): 
D/AndroidRuntime( 3490): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3490): CheckJNI is OFF
D/dalvikvm( 3490): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3490): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3490): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3490): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3490): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3490): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3490): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3490): failed to load memtrack module: -2
D/AndroidRuntime( 3490): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1022): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3490
D/AndroidRuntime( 3490): Shutting down VM
D/dalvikvm( 3490): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 1ms+0ms, total 3ms
,V/AlarmManager( 1022): sending alarm Alarm{430c7e68 type 2 com.google.android.gms}
,D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1022): sending alarm Alarm{431de288 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{431e2460 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{43288ba8 type 2 com.google.android.gms}
,E/global frequency( 1603): no tags to log
,D/Checkin ( 1603): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1603): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1603): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1603): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1603): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1603): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1603): BcsDSCheckin.events found events 2000
,D/Checkin ( 1603): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1603): GC_CONCURRENT freed 5449K, 32% free 11715K/17224K, paused 3ms+10ms, total 61ms
,I/BSUtils ( 1603): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1603): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1603): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1603): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1603): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1603): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1603): unknown error code mapping for: 0
I/global frequency( 1603): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1603): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1603): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1603): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 1603): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1603): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1603): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1603): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1603): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1603): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1603): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/MMApiWebService( 1603): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1603): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiBackOffService( 1603): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1603): MMApiWebService told us not to continue at the moment with this request: devices.json
,I/MMApiWebService( 1603): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1603): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1603): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
I/MMApiWebService( 1603): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1603): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1603): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1603): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1603): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1022): sending alarm Alarm{43216778 type 2 com.google.android.gms}
,I/VacuumService( 1220): Vacuum at: now=1454593118998 tag=VacuumService
,V/AlarmManager( 1022): sending alarm Alarm{4301bcb0 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4301c520 type 3 android}
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
,V/AlarmManager( 1022): sending alarm Alarm{4301d570 type 2 com.google.android.gms}
,D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1022): sending alarm Alarm{428d9400 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{43110fc8 type 3 android}
,V/GLSActivity( 2062): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2062): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1022): sending alarm Alarm{43225358 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{43113a70 type 3 android}
,I/MMApiBackOffService( 1603): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1603): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1603): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1603): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1603): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1603): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,I/MMApiWebService( 1603): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1603): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1603): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1603): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1603): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1603): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1603): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1603): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1603): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1603): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1603): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1603): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1603): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1022): sending alarm Alarm{431a7890 type 2 com.google.android.gms}
,D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1022): sending alarm Alarm{43008f10 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{43046980 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{43021cc0 type 2 com.motorola.ccc.cce},
I/PollingManager( 1603): alarm fired!
D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1022): sending alarm Alarm{430a6828 type 3 android}
,V/GLSActivity( 2062): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2062): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1022): sending alarm Alarm{430fd910 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{430bbb70 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4302b888 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{428a3f20 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4327ff48 type 3 android}
,V/GLSActivity( 2062): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2062): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 2062): GC_CONCURRENT freed 1855K, 41% free 10295K/17224K, paused 3ms+3ms, total 45ms
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1022): sending alarm Alarm{43021d70 type 2 android}
,V/AlarmManager( 1022): sending alarm Alarm{430c9060 type 2 com.google.android.gms}
,D/ConnectivityService( 1022): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1022): sending alarm Alarm{43033240 type 0 com.google.android.gms}
,D/ConnectivityService( 1022): Done.
,D/ConnectivityService( 1022): Setting timer for 720seconds
,D/ConnectivityService( 1022): handleInetConditionChange: no active default network - ignore
,I/EventLogService( 1689): Aggregate from 1454591800129 (log), 1454591800129 (data)
,D/dalvikvm( 1689): GC_CONCURRENT freed 1760K, 37% free 10951K/17224K, paused 4ms+4ms, total 31ms
,V/AlarmManager( 1022): sending alarm Alarm{431046d0 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4308bc88 type 3 android}
,I/MMApiBackOffService( 1603): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1603): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1603): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1603): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1603): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1603): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1603): ProvisionWS.Response: Missing mandatory message data in response from DM server...
I/MMApiWebService( 1603): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1603): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1603): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1603): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1603): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1603): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1603): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1603): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1603): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1603): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1603): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1603): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1603): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1022): sending alarm Alarm{43125948 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{431aa000 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{43263e60 type 3 android}
,V/GLSActivity( 2062): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2062): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1022): sending alarm Alarm{432147c0 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),V/AlarmManager( 1022): sending alarm Alarm{431f8b18 type 3 android}
D/AndroidRuntime( 3576): 
D/AndroidRuntime( 3576): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3576): CheckJNI is OFF
D/dalvikvm( 3576): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3576): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3576): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3576): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3576): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3576): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3576): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3576): failed to load memtrack module: -2
D/AndroidRuntime( 3576): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1022): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1022): WAIT_FOR_CONCURRENT_GC blocked 1ms
D/dalvikvm( 1022): GC_EXPLICIT freed 720K, 10% free 18354K/20176K, paused 7ms+8ms, total 97ms
D/AndroidRuntime( 3576): Shutting down VM
D/dalvikvm( 3576): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms

```
