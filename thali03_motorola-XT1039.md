#### Test 58380500c26a9ef_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1016): sending alarm Alarm{428b5350 type 2 com.google.android.gms}
D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
--------- beginning of /dev/log/main
D/dalvikvm( 2562): GC_CONCURRENT freed 1633K, 12% free 15188K/17228K, paused 3ms+2ms, total 67ms
D/AndroidRuntime( 3384): 
D/AndroidRuntime( 3384): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3384): CheckJNI is OFF
D/dalvikvm( 3384): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3384): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3384): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3384): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3384): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3384): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3384): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3384): failed to load memtrack module: -2
D/AndroidRuntime( 3384): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1016): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3384
D/AndroidRuntime( 3384): Shutting down VM
D/dalvikvm( 3384): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+0ms, total 2ms
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,E/global frequency( 1592): no tags to log
,D/Checkin ( 1592): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1592): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1592): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1592): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1592): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1592): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1592): BcsDSCheckin.events found events 2000
,D/Checkin ( 1592): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1592): GC_CONCURRENT freed 5498K, 33% free 11688K/17224K, paused 3ms+6ms, total 56ms
,I/BSUtils ( 1592): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1592): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
D/MMApiWebService( 1592): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1592): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1592): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1592): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1592): unknown error code mapping for: 0
,I/global frequency( 1592): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1592): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1592): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1592): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ClearcutLoggerApiImpl( 1347): disconnect managed GoogleApiClient
,V/AlarmManager( 1016): sending alarm Alarm{42960948 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4289e1d8 type 2 com.google.android.gms}
,V/AlarmManager( 1016): sending alarm Alarm{427c5300 type 0 com.google.android.gms}
,D/dalvikvm( 1687): GC_CONCURRENT freed 1888K, 37% free 10883K/17224K, paused 5ms+23ms, total 88ms
,I/EventLogService( 1687): Aggregate from 1454981862159 (log), 1454981862159 (data)
,I/VacuumService( 1213): Vacuum at: now=1454983662394 tag=VacuumService
,I/MMApiBackOffService( 1592): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1592): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1592): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1592): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1592): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1592): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/MMApiWebService( 1592): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1592): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,E/MMApiProvisionService( 1592): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiBackOffService( 1592): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1592): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1592): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1592): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1592): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1592): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1592): doRequest(): polling manager says we're not connected, returning with an error: 
D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1592): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1592): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1592): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{42139990 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4223bf08 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42139a68 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{421596c0 type 2 com.google.android.gms}
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1016): sending alarm Alarm{42010ac0 type 3 android}
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{4280c498 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{428d0e80 type 3 android}
,I/MMApiBackOffService( 1592): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1592): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1592): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1592): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1592): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
E/MMApiProvisionService( 1592): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1592): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1592): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/MMApiWebService( 1592): doRequest(): polling manager says we're not connected, returning with an error: 
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1592): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1592): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1592): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1592): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1592): MMApiWebService told us not to continue at the moment with this request: 
D/MMApiWebService( 1592): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1592): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1592): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1592): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1592): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{427d4b38 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{427f44c8 type 2 com.google.android.gms}
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1016): sending alarm Alarm{428283e0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{428febe0 type 3 android}
,D/dalvikvm( 1347): GC_EXPLICIT freed 1621K, 40% free 10345K/17224K, paused 3ms+4ms, total 36ms
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{427c5cf0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4280c970 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{428d19c8 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{428d5960 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{429897e0 type 3 android}
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{42940878 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42159710 type 2 android}
,V/AlarmManager( 1016): sending alarm Alarm{4282a8c8 type 2 com.google.android.gms}
,D/ConnectivityService( 1016): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1016): Done.
,D/ConnectivityService( 1016): Setting timer for 720seconds
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1016): sending alarm Alarm{4290f728 type 3 android}
,I/MMApiBackOffService( 1592): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1592): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1592): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1592): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1592): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1592): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1592): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1592): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,E/MMApiProvisionService( 1592): ProvisionWS.Response.setError: error RadioDownError
I/MMApiBackOffService( 1592): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1592): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1592): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1592): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1592): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1592): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1592): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1592): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1592): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1592): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{428239a8 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{428b3cd0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{428a8448 type 3 android}
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{428973d8 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4295fd88 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3468): 
D/AndroidRuntime( 3468): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3468): CheckJNI is OFF
D/dalvikvm( 3468): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3468): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3468): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3468): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3468): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3468): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3468): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3468): failed to load memtrack module: -2
D/AndroidRuntime( 3468): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1016): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1016): GC_EXPLICIT freed 830K, 9% free 18347K/19964K, paused 3ms+8ms, total 84ms
D/AndroidRuntime( 3468): Shutting down VM
D/dalvikvm( 3468): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms

```
