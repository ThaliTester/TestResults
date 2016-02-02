#### Test 575312438097721_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3388): 
D/AndroidRuntime( 3388): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3388): CheckJNI is OFF
D/dalvikvm( 3388): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3388): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3388): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3388): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3388): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3388): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3388): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3388): failed to load memtrack module: -2
D/AndroidRuntime( 3388): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1015): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3388
D/AndroidRuntime( 3388): Shutting down VM
D/dalvikvm( 3388): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+0ms, total 2ms
,E/global frequency( 1580): no tags to log
,D/Checkin ( 1580): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1580): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1580): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1580): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1580): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1580): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1580): BcsDSCheckin.events found events 1863
,D/Checkin ( 1580): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1580): GC_CONCURRENT freed 5474K, 33% free 11620K/17224K, paused 3ms+4ms, total 44ms
,I/BSUtils ( 1580): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1580): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1580): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1580): unknown error code mapping for: 0
I/global frequency( 1580): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1580): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1580): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1580): publish the event [tag = MOT_CHECKIN event name = LOG]
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
,V/AlarmManager( 1015): sending alarm Alarm{42a09940 type 3 android}
,I/MMApiBackOffService( 1580): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1580): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
E/MMApiProvisionService( 1580): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1580): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1015): sending alarm Alarm{4288fee8 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{42a0d4a8 type 2 com.google.android.gms}
,V/AlarmManager( 1015): sending alarm Alarm{42a0b978 type 2 com.google.android.gms}
,D/ConnectivityService( 1015): handleInetConditionChange: no active default network - ignore
,I/VacuumService( 1208): Vacuum at: now=1454429766302 tag=VacuumService
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1015): sending alarm Alarm{4283c500 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{428c95d8 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{4258bd90 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{428c9688 type 2 com.google.android.gms}
,D/ConnectivityService( 1015): handleInetConditionChange: no active default network - ignore
,V/GLSActivity( 1327): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1327): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1015): sending alarm Alarm{4283ff20 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{42524960 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{429a66b8 type 3 android}
,I/MMApiBackOffService( 1580): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1580): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1580): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,E/MMApiProvisionService( 1580): ProvisionWS.Response.setError: error RadioDownError
I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1015): sending alarm Alarm{4208a8f0 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{4278ee30 type 3 android}
,V/GLSActivity( 1327): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1327): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1015): sending alarm Alarm{42882ea8 type 2 com.google.android.gms}
,D/ConnectivityService( 1015): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1015): sending alarm Alarm{429d5ff8 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{428ba658 type 3 android}
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
,V/AlarmManager( 1015): sending alarm Alarm{427e3670 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{4278e1a8 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{420e89b0 type 3 android}
,V/GLSActivity( 1327): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1327): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1015): sending alarm Alarm{421135a0 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{4242d450 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{428b3080 type 3 android}
,I/MMApiBackOffService( 1580): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1580): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1580): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1580): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1580): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1580): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1580): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1580): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1580): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1580): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1015): sending alarm Alarm{4289cc10 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{429e1668 type 3 android}
,V/GLSActivity( 1327): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1327): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1015): sending alarm Alarm{429fb848 type 3 android}
,V/AlarmManager( 1015): sending alarm Alarm{429893d0 type 2 android}
,V/AlarmManager( 1015): sending alarm Alarm{428b55b0 type 2 com.google.android.gms}
,V/AlarmManager( 1015): sending alarm Alarm{42105228 type 0 com.google.android.gms}
,D/ConnectivityService( 1015): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1015): Done.
,D/ConnectivityService( 1015): Setting timer for 720seconds
,D/ConnectivityService( 1015): handleInetConditionChange: no active default network - ignore
,I/EventLogService( 1677): Aggregate from 1454428789353 (log), 1454428789353 (data)
,V/AlarmManager( 1015): sending alarm Alarm{42a278e8 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3477): 
D/AndroidRuntime( 3477): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3477): CheckJNI is OFF
D/dalvikvm( 3477): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3477): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3477): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3477): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3477): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3477): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3477): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3477): failed to load memtrack module: -2
D/AndroidRuntime( 3477): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1015): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1015): GC_EXPLICIT freed 689K, 9% free 18321K/20004K, paused 3ms+7ms, total 91ms
D/AndroidRuntime( 3477): Shutting down VM
D/dalvikvm( 3477): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms

```
