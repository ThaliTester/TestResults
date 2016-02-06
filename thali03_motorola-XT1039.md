#### Test 58380500fccea7e_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1020): sending alarm Alarm{4293fd80 type 3 android}
V/AlarmManager( 1020): sending alarm Alarm{4293a7f0 type 2 com.google.android.gms}
--------- beginning of /dev/log/main
D/AndroidRuntime( 3423): 
D/AndroidRuntime( 3423): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3423): CheckJNI is OFF
D/dalvikvm( 3423): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3423): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3423): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3423): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3423): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3423): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3423): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3423): failed to load memtrack module: -2
D/AndroidRuntime( 3423): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3423
D/AndroidRuntime( 3423): Shutting down VM
D/dalvikvm( 3423): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 1ms+0ms, total 3ms
,E/global frequency( 1588): no tags to log
,D/Checkin ( 1588): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1588): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1588): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1588): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1588): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1588): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/ClearcutLoggerApiImpl( 1327): disconnect managed GoogleApiClient
I/global frequency( 1588): BcsDSCheckin.events found events 2000
,D/Checkin ( 1588): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1588): GC_CONCURRENT freed 5450K, 33% free 11684K/17224K, paused 3ms+4ms, total 63ms
,I/BSUtils ( 1588): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1588): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
D/MMApiWebService( 1588): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1588): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1588): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1588): AppWSProxy - sendAIDLWSResponse() sending reponse
I/ErrorTranslator( 1588): unknown error code mapping for: 0
I/global frequency( 1588): BcsCore.status() called with error code=ERROR_FAIL
D/Checkin ( 1588): publish the event [tag = MOT_CHECKIN event name = LOG]
I/global frequency( 1588): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
D/Checkin ( 1588): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{42456868 type 3 android}
,I/MMApiBackOffService( 1588): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1588): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1588): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1588): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1588): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1588): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
E/MMApiProvisionService( 1588): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1588): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1588): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiBackOffService( 1588): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1588): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1588): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1588): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1588): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
I/MMApiWebService( 1588): MMApiWebService told us not to continue at the moment with this request: 
,D/MMApiWebService( 1588): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1588): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1588): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1588): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{423ea250 type 2 com.google.android.gms}
,I/VacuumService( 1212): Vacuum at: now=1454717710358 tag=VacuumService
,V/AlarmManager( 1020): sending alarm Alarm{41ffc410 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{41fe7ea0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{41f6d4c8 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1020): sending alarm Alarm{42063b50 type 3 android}
,V/GLSActivity( 1327): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1327): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1327): GC_EXPLICIT freed 1437K, 41% free 10311K/17224K, paused 3ms+4ms, total 35ms
,V/AlarmManager( 1020): sending alarm Alarm{42426c50 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42914780 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42942c68 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1020): sending alarm Alarm{423d0748 type 3 android}
,I/MMApiBackOffService( 1588): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1588): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1588): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1588): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1588): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1588): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1588): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1588): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1588): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1588): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1588): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1588): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1588): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1588): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
I/MMApiWebService( 1588): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1588): doRequest(): polling manager says we're not connected, returning with an error: 
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1588): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1588): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1588): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{427b4240 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42091c38 type 3 android}
,V/GLSActivity( 1327): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1327): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{428d5a48 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{41f25d90 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42800698 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{427e8e98 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{427a97f0 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1020): sending alarm Alarm{41f3bfe0 type 2 android}
,V/AlarmManager( 1020): sending alarm Alarm{41f3bb90 type 0 com.google.android.gms}
,D/ConnectivityService( 1020): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1020): Done.
,D/ConnectivityService( 1020): Setting timer for 720seconds
,I/Icing   ( 1683): Performing maintenance.
,I/Icing   ( 1683): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1683): GC_CONCURRENT freed 1744K, 35% free 11226K/17224K, paused 4ms+4ms, total 33ms
,I/Icing   ( 1683): Performing maintenance usage 2130186 budget 1732472965 free 99.877% index free 99.963% purge? false target 1212731075
,I/Icing   ( 1683): Query from com.google.android.gms package restrict com.google.android.gms start 0 num 100
,V/AlarmManager( 1020): sending alarm Alarm{42842508 type 3 android}
,V/GLSActivity( 1327): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1327): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{42840c60 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42945d70 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{429c0288 type 3 android}
,I/MMApiBackOffService( 1588): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1588): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1588): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1588): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1588): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1588): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1588): ProvisionWS.Response.setError: error RadioDownError
D/MMApiWebService( 1588): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1588): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1588): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1588): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1588): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1588): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1588): MMApiWebService told us not to continue at the moment with this request: 
D/MMApiWebService( 1588): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1588): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1588): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1588): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1588): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1588): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{429be508 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{427f52d8 type 3 android}
,V/GLSActivity( 1327): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1327): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{427f1738 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42809d48 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3507): 
D/AndroidRuntime( 3507): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3507): CheckJNI is OFF
D/dalvikvm( 3507): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3507): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3507): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3507): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3507): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3507): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3507): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3507): failed to load memtrack module: -2
D/AndroidRuntime( 3507): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1020): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1020): GC_EXPLICIT freed 823K, 10% free 18340K/20224K, paused 3ms+8ms, total 96ms
D/AndroidRuntime( 3507): Shutting down VM
D/dalvikvm( 3507): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms

```
