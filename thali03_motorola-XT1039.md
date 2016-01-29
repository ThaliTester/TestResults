#### Test 57659382b63fd0b_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1018): sending alarm Alarm{42995380 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3625): 
D/AndroidRuntime( 3625): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3625): CheckJNI is OFF
D/dalvikvm( 3625): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3625): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3625): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3625): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3625): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3625): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3625): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3625): failed to load memtrack module: -2
D/AndroidRuntime( 3625): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3625
D/AndroidRuntime( 3625): Shutting down VM
D/dalvikvm( 3625): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+0ms, total 2ms
,E/global frequency( 1583): no tags to log
,D/Checkin ( 1583): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1583): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1583): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1583): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1583): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1583): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1583): BcsDSCheckin.events found events 1103
,D/Checkin ( 1583): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1583): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/dalvikvm( 1583): GC_CONCURRENT freed 5779K, 35% free 11313K/17224K, paused 2ms+5ms, total 46ms
,D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1583): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1583): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1583): unknown error code mapping for: 0
I/global frequency( 1583): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1583): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1583): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1583): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{42996360 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42998250 type 2 com.google.android.gms}
,V/AlarmManager( 1018): sending alarm Alarm{429bbd58 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,I/VacuumService( 1214): Vacuum at: now=1454082681617 tag=VacuumService
,I/MMApiBackOffService( 1583): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1583): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1583): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,E/MMApiProvisionService( 1583): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{4236d010 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{421b7858 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4286a660 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{420916b0 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1018): sending alarm Alarm{427ebd08 type 3 android}
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): sending alarm Alarm{42992ca0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4280fab0 type 3 android}
,I/MMApiBackOffService( 1583): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1583): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1583): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1583): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{42840538 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42799a38 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4286deb0 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1018): sending alarm Alarm{428541e8 type 3 android}
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): sending alarm Alarm{429454b8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{429ae728 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{428cd7b0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{427f6f80 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4293a1a8 type 3 android}
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): sending alarm Alarm{4297bf98 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{428587b0 type 3 android}
,I/MMApiBackOffService( 1583): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1583): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1583): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1583): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: 
,D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: 
D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{429945d0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{428318c0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4207bd00 type 2 android}
,V/AlarmManager( 1018): sending alarm Alarm{428cc6d0 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1018): sending alarm Alarm{4206adb8 type 0 com.google.android.gms}
,D/ConnectivityService( 1018): Done.
,D/ConnectivityService( 1018): Setting timer for 720seconds
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,I/EventLogService( 1681): Aggregate from 1454081039630 (log), 1454081039630 (data)
,V/AlarmManager( 1018): sending alarm Alarm{42896628 type 3 android}
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
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  272): write error (Broken pipe)
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
,V/AlarmManager( 1018): sending alarm Alarm{42905f18 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42999fb0 type 3 android}
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
D/dalvikvm( 1018): GC_EXPLICIT freed 660K, 9% free 18326K/20044K, paused 3ms+7ms, total 83ms
D/AndroidRuntime( 3709): Shutting down VM
D/dalvikvm( 3709): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms

```
