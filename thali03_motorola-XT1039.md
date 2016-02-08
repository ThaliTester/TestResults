#### Test 58380500962e22b_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1021): sending alarm Alarm{428c1968 type 2 com.google.android.gms}
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
--------- beginning of /dev/log/main
D/AndroidRuntime( 3329): 
D/AndroidRuntime( 3329): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3329): CheckJNI is OFF
D/dalvikvm( 3329): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3329): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3329): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3329): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3329): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3329): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3329): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3329): failed to load memtrack module: -2
D/AndroidRuntime( 3329): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1021): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3329
D/AndroidRuntime( 3329): Shutting down VM
D/dalvikvm( 3329): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 1ms+0ms, total 3ms
,V/AlarmManager( 1021): sending alarm Alarm{427cc910 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42817d00 type 2 com.google.android.gms}
,V/AlarmManager( 1021): sending alarm Alarm{428114a8 type 3 android}
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
,E/global frequency( 1584): no tags to log
,D/Checkin ( 1584): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1584): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1584): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 1584): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1584): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1584): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1584): BcsDSCheckin.events found events 2000
,D/Checkin ( 1584): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1584): GC_CONCURRENT freed 5476K, 32% free 11712K/17224K, paused 2ms+5ms, total 51ms
,D/dalvikvm( 1584): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/BSUtils ( 1584): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1584): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1584): AppWSProxy - sendAIDLWSResponse() sending reponse
I/ErrorTranslator( 1584): unknown error code mapping for: 0
I/global frequency( 1584): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1584): publish the event [tag = MOT_CHECKIN event name = LOG]
I/global frequency( 1584): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1584): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 1584): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1584): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
E/MMApiProvisionService( 1584): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1584): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: 
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: devices.json
,I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: 
D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1021): sending alarm Alarm{42052e10 type 2 com.google.android.gms}
,I/VacuumService( 1215): Vacuum at: now=1454973448845 tag=VacuumService
,V/AlarmManager( 1021): sending alarm Alarm{4272faa8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4272fb80 type 0 com.google.android.gms}
,I/EventLogService( 1682): Aggregate from 1454971586196 (log), 1454971586196 (data)
,V/AlarmManager( 1021): sending alarm Alarm{429837a0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{429a0400 type 2 com.google.android.gms}
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1021): sending alarm Alarm{428972d8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42074c18 type 3 android}
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1021): sending alarm Alarm{42090de0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4206ed00 type 3 android}
,I/MMApiBackOffService( 1584): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1584): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1584): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1584): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1021): sending alarm Alarm{4257d070 type 2 com.google.android.gms}
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1021): sending alarm Alarm{42818ce8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{429784f8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428c36f0 type 3 android}
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1021): sending alarm Alarm{42992458 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42977198 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428e0398 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428bfd30 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{429a2148 type 3 android}
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1021): sending alarm Alarm{429a04d8 type 2 android}
,D/ConnectivityService( 1021): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1021): sending alarm Alarm{427c2698 type 2 com.google.android.gms}
,V/AlarmManager( 1021): sending alarm Alarm{42807420 type 0 com.motorola.motocare}
,D/ConnectivityService( 1021): Done.
,D/ConnectivityService( 1021): Setting timer for 720seconds
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1021): sending alarm Alarm{427e7e40 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42811bf8 type 3 android}
,I/MMApiBackOffService( 1584): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1584): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1584): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1584): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: 
,D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1021): sending alarm Alarm{427fe380 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428d76f8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4288c4d0 type 3 android}
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1021): sending alarm Alarm{42807348 type 2 com.motorola.ccc.cce}
I/PollingManager( 1584): alarm fired!
D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1021): sending alarm Alarm{428f6018 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3418): 
D/AndroidRuntime( 3418): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3418): CheckJNI is OFF
D/dalvikvm( 3418): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3418): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3418): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3418): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3418): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3418): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3418): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3418): failed to load memtrack module: -2
D/AndroidRuntime( 3418): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1021): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1021): GC_EXPLICIT freed 844K, 9% free 18323K/20068K, paused 3ms+7ms, total 85ms
D/AndroidRuntime( 3418): Shutting down VM
D/dalvikvm( 3418): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms

```
