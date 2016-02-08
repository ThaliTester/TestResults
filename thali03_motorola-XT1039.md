#### Test 581356550b07fff_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3456): 
D/AndroidRuntime( 3456): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3456): CheckJNI is OFF
D/dalvikvm( 3456): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3456): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3456): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3456): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3456): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3456): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3456): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3456): failed to load memtrack module: -2
D/AndroidRuntime( 3456): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1021): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3456
D/AndroidRuntime( 3456): Shutting down VM
D/dalvikvm( 3456): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 1ms+1ms, total 3ms
,E/global frequency( 1594): no tags to log
,D/Checkin ( 1594): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1594): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1594): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 1594): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1594): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1594): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1594): BcsDSCheckin.events found events 2000
,D/Checkin ( 1594): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1594): GC_CONCURRENT freed 5449K, 33% free 11679K/17224K, paused 3ms+7ms, total 53ms
,I/BSUtils ( 1594): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1594): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
D/MMApiWebService( 1594): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1594): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1594): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1594): AppWSProxy - sendAIDLWSResponse() sending reponse
I/ErrorTranslator( 1594): unknown error code mapping for: 0
I/global frequency( 1594): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1594): publish the event [tag = MOT_CHECKIN event name = LOG]
I/global frequency( 1594): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1594): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager( 1021): sending alarm Alarm{428b14f0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42841a88 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428cc728 type 2 com.google.android.gms}
,V/AlarmManager( 1021): sending alarm Alarm{428b2320 type 2 com.google.android.gms}
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
,I/VacuumService( 1215): Vacuum at: now=1454950445013 tag=VacuumService
,I/MMApiBackOffService( 1594): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1594): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1594): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1594): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1594): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1594): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/MMApiWebService( 1594): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
E/MMApiProvisionService( 1594): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1594): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiBackOffService( 1594): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1594): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1594): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1594): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1594): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1594): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1594): doRequest(): polling manager says we're not connected, returning with an error: 
D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1594): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1594): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1594): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1021): sending alarm Alarm{428cafb8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428df078 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4228a238 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428df150 type 2 com.google.android.gms}
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1021): sending alarm Alarm{428f9970 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{422207f8 type 2 com.motorola.ccc.cce}
I/PollingManager( 1594): alarm fired!
D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1021): sending alarm Alarm{420cda58 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428e71a0 type 3 android}
,I/MMApiBackOffService( 1594): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1594): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1594): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1594): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1594): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1594): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,D/MMApiWebService( 1594): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1594): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1594): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1594): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1594): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1594): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1594): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1594): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1594): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1594): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1594): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1594): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1594): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1021): sending alarm Alarm{421127e8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42a47fe8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428d1bf0 type 2 com.google.android.gms}
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1021): sending alarm Alarm{42851708 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{429b19d0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428a2070 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428f9d78 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428281e8 type 3 android}
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
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1021): sending alarm Alarm{428f22a8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428abf10 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428e56c0 type 3 android}
,I/MMApiBackOffService( 1594): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1594): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1594): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1594): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1594): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1594): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/MMApiWebService( 1594): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1594): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1594): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1594): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1594): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1594): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1594): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1594): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1594): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1594): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1594): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1594): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1594): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1021): sending alarm Alarm{42812138 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{422208d0 type 2 android}
,V/AlarmManager( 1021): sending alarm Alarm{428facd0 type 2 com.google.android.gms}
,D/ConnectivityService( 1021): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1021): sending alarm Alarm{42306dd0 type 0 com.google.android.gms}
,D/ConnectivityService( 1021): Done.
,D/ConnectivityService( 1021): Setting timer for 720seconds
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
,I/EventLogService( 1692): Aggregate from 1454949514319 (log), 1454949514319 (data)
,V/AlarmManager( 1021): sending alarm Alarm{42a165d0 type 3 android}
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2064): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1021): sending alarm Alarm{429a1340 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428212b8 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3544): 
D/AndroidRuntime( 3544): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3544): CheckJNI is OFF
D/dalvikvm( 3544): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3544): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3544): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3544): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3544): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3544): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3544): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3544): failed to load memtrack module: -2
D/AndroidRuntime( 3544): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1021): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1021): GC_EXPLICIT freed 810K, 9% free 18287K/19916K, paused 3ms+7ms, total 84ms
D/AndroidRuntime( 3544): Shutting down VM
D/dalvikvm( 3544): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms

```
