#### Test 58135655a685cd3_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3475): 
D/AndroidRuntime( 3475): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3475): CheckJNI is OFF
D/dalvikvm( 3475): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3475): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3475): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3475): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3475): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3475): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3475): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3475): failed to load memtrack module: -2
D/AndroidRuntime( 3475): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3475
D/AndroidRuntime( 3475): Shutting down VM
D/dalvikvm( 3475): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+0ms, total 2ms
,V/AlarmManager( 1019): sending alarm Alarm{42f109f8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{430821a0 type 2 com.google.android.gms}
,E/global frequency( 1591): no tags to log
,D/Checkin ( 1591): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1591): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1591): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1591): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1591): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1591): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1591): BcsDSCheckin.events found events 2000
,D/Checkin ( 1591): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1591): GC_CONCURRENT freed 5478K, 33% free 11658K/17224K, paused 2ms+7ms, total 51ms
,I/BSUtils ( 1591): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1591): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1591): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1591): unknown error code mapping for: 0
I/global frequency( 1591): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1591): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1591): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1591): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ClearcutLoggerApiImpl( 2061): disconnect managed GoogleApiClient
,V/AlarmManager( 1019): sending alarm Alarm{4303c1a8 type 3 android}
,I/MMApiBackOffService( 1591): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1591): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1591): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1591): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{42fa8c00 type 2 com.google.android.gms}
,I/VacuumService( 1217): Vacuum at: now=1454591179980 tag=VacuumService
,V/AlarmManager( 1019): sending alarm Alarm{4289a368 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4282d550 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1019): sending alarm Alarm{4282d5a0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42ef79a8 type 3 android}
,V/GLSActivity( 2061): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2061): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{42e79160 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42eb10e8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42f7d720 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{42e5e2f0 type 3 android}
,I/MMApiBackOffService( 1591): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1591): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1591): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: 
,E/MMApiProvisionService( 1591): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{42e76e80 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42f15838 type 3 android}
,V/GLSActivity( 2061): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2061): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{43079d00 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4280c7e8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42fab9a8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42e6aff0 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{42815530 type 2 android}
,V/AlarmManager( 1019): sending alarm Alarm{427d12b0 type 0 com.google.android.gms}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,I/EventLogService( 1683): Aggregate from 1454589430024 (log), 1454589430024 (data)
,V/AlarmManager( 1019): sending alarm Alarm{4303b540 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42e5e6b8 type 3 android}
,V/GLSActivity( 2061): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2061): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{4303ae60 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42e2f800 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42fa5638 type 3 android}
,I/MMApiBackOffService( 1591): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1591): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1591): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1591): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{42f9ee90 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42ef6050 type 3 android}
,V/GLSActivity( 2061): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2061): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{42efcee8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43083b20 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3573): 
D/AndroidRuntime( 3573): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3573): CheckJNI is OFF
D/dalvikvm( 3573): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3573): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3573): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3573): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3573): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3573): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3573): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3573): failed to load memtrack module: -2
D/AndroidRuntime( 3573): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1019): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1019): GC_EXPLICIT freed 683K, 10% free 18365K/20300K, paused 3ms+7ms, total 91ms
D/AndroidRuntime( 3573): Shutting down VM
D/dalvikvm( 3573): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms

```
