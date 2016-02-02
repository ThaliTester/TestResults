#### Test 575312435db8e90_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main,
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
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3631): 
D/AndroidRuntime( 3631): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3631): CheckJNI is OFF
D/dalvikvm( 3631): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3631): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3631): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3631): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3631): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3631): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3631): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3631): failed to load memtrack module: -2
D/AndroidRuntime( 3631): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3631
D/AndroidRuntime( 3631): Shutting down VM
D/dalvikvm( 3631): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+0ms, total 3ms
,V/AlarmManager( 1018): sending alarm Alarm{429ba420 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42d7b890 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1018): sending alarm Alarm{43280058 type 2 com.google.android.gms}
,E/global frequency( 1602): no tags to log
,D/Checkin ( 1602): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1602): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1602): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1602): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1602): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1602): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1602): BcsDSCheckin.events found events 1619
,D/Checkin ( 1602): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1602): GC_CONCURRENT freed 5542K, 33% free 11586K/17224K, paused 3ms+5ms, total 56ms
,I/BSUtils ( 1602): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1602): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1602): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1602): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1602): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1602): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1602): unknown error code mapping for: 0
,I/global frequency( 1602): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1602): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{4327c250 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MMApiBackOffService( 1602): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1602): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1602): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1602): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1602): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1602): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1602): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1602): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1602): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1602): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1602): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1602): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1602): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1602): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1602): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1602): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1602): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1602): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1602): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{431d07b0 type 2 com.google.android.gms}
,I/VacuumService( 1215): Vacuum at: now=1454412383821 tag=VacuumService
,V/AlarmManager( 1018): sending alarm Alarm{4320e780 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4320e7f8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{431c59a8 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1018): sending alarm Alarm{43159ca0 type 3 android}
,V/GLSActivity( 2113): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2113): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): sending alarm Alarm{431394c8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{431fc950 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42a2d9a8 type 3 android}
,I/MMApiBackOffService( 1602): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1602): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1602): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1602): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1602): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1602): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,D/MMApiWebService( 1602): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1602): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1602): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1602): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1602): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1602): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1602): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1602): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/MMApiWebService( 1602): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1602): doRequest(): polling manager says we're not connected, returning with an error: 
D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1602): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1602): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1602): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{431b4fe0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42ad9da0 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1018): sending alarm Alarm{431d4f00 type 3 android}
,V/GLSActivity( 2113): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2113): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1018): sending alarm Alarm{430bf890 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43156fd0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{432476b8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4311e5a8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42a5a5c0 type 3 android}
,V/GLSActivity( 2113): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2113): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): sending alarm Alarm{43077e40 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43140330 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4316ee58 type 2 android}
,V/AlarmManager( 1018): sending alarm Alarm{430d7868 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1018): Done.
,D/ConnectivityService( 1018): Setting timer for 720seconds
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1018): sending alarm Alarm{4326e820 type 3 android}
,I/MMApiBackOffService( 1602): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1602): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1602): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1602): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1602): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1602): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1602): ProvisionWS.Response: Missing mandatory message data in response from DM server...
I/MMApiWebService( 1602): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1602): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1602): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1602): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1602): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1602): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1602): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1602): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1602): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1602): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1602): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1602): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1602): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{431d1738 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4314ccd8 type 3 android}
,V/GLSActivity( 2113): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2113): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): sending alarm Alarm{4317b030 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{429eed48 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3709): 
D/AndroidRuntime( 3709): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3709): CheckJNI is OFF
D/dalvikvm( 3709): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3709): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3709): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3709): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3709): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3709): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3709): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3709): failed to load memtrack module: -2
D/AndroidRuntime( 3709): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1018): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1018): GC_EXPLICIT freed 616K, 9% free 18315K/19936K, paused 3ms+7ms, total 83ms
D/AndroidRuntime( 3709): Shutting down VM
D/dalvikvm( 3709): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms

```
