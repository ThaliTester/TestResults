#### Test 5797209499148df_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3547): 
D/AndroidRuntime( 3547): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3547): CheckJNI is OFF
D/dalvikvm( 3547): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3547): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3547): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3547): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3547): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3547): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3547): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3547): failed to load memtrack module: -2
D/AndroidRuntime( 3547): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3547
D/AndroidRuntime( 3547): Shutting down VM
D/dalvikvm( 3547): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 1ms+1ms, total 3ms
,V/AlarmManager( 1020): sending alarm Alarm{42837108 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4294ad10 type 2 com.google.android.gms}
,E/global frequency( 1586): no tags to log
,D/Checkin ( 1586): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1586): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1586): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 1586): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1586): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1586): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1586): BcsDSCheckin.events found events 1699
,D/Checkin ( 1586): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1586): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/dalvikvm( 1586): GC_CONCURRENT freed 5545K, 33% free 11617K/17224K, paused 2ms+6ms, total 57ms
,D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1586): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1586): AppWSProxy - sendAIDLWSResponse() sending reponse
I/ErrorTranslator( 1586): unknown error code mapping for: 0
I/global frequency( 1586): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1586): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1586): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1586): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{4293ebe0 type 3 android}
,I/MMApiBackOffService( 1586): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1586): MMApiBackOffService told us it's okay to retry the waiting requests: 3
D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1586): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1586): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{42701668 type 2 com.google.android.gms}
,I/VacuumService( 1215): Vacuum at: now=1454416635028 tag=VacuumService
,V/AlarmManager( 1020): sending alarm Alarm{4275ee20 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{42727710 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42724a48 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1020): sending alarm Alarm{427abec8 type 3 android}
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1020): sending alarm Alarm{422c58a0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42705430 type 2 com.motorola.ccc.cce}
I/PollingManager( 1586): alarm fired!
D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{423d2ea8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{41fecbd0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42812a98 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  272): write error (Broken pipe)
,I/MMApiBackOffService( 1586): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1586): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1586): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,E/MMApiProvisionService( 1586): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{42775310 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{427d5998 type 3 android}
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1020): sending alarm Alarm{42777288 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{41efc120 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{427e2e10 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4291ecb8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{427980b8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{426fd0d8 type 2 android}
,V/AlarmManager( 1020): sending alarm Alarm{4274d6e0 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1020): Done.
,D/ConnectivityService( 1020): Setting timer for 720seconds
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  272): write error (Broken pipe)
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1020): sending alarm Alarm{41f42c48 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{427f9788 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4281c270 type 3 android}
,I/MMApiBackOffService( 1586): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1586): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1586): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1586): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: 
D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{4280dc60 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{427d0cf8 type 3 android}
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2063): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1020): sending alarm Alarm{42782830 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42929e08 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3618): 
D/AndroidRuntime( 3618): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3618): CheckJNI is OFF
D/dalvikvm( 3618): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3618): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3618): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3618): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3618): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3618): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3618): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3618): failed to load memtrack module: -2
D/AndroidRuntime( 3618): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1020): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1020): GC_EXPLICIT freed 740K, 8% free 18290K/19852K, paused 3ms+7ms, total 83ms
D/AndroidRuntime( 3618): Shutting down VM
D/dalvikvm( 3618): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms

```
