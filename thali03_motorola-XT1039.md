#### Test 58135655e794d2c_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1020): sending alarm Alarm{42828888 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{429de728 type 2 com.google.android.gms}
--------- beginning of /dev/log/main
D/AndroidRuntime( 3453): 
D/AndroidRuntime( 3453): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3453): CheckJNI is OFF
D/dalvikvm( 3453): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3453): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3453): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3453): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3453): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3453): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3453): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3453): failed to load memtrack module: -2
D/AndroidRuntime( 3453): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3453
D/AndroidRuntime( 3453): Shutting down VM
D/dalvikvm( 3453): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+0ms, total 2ms
,E/global frequency( 1595): no tags to log
,D/Checkin ( 1595): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1595): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/BSUtils ( 1595): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 1595): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 1595): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 1595): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1595): BcsDSCheckin.events found events 2000
,D/Checkin ( 1595): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1595): GC_CONCURRENT freed 5455K, 33% free 11685K/17224K, paused 2ms+7ms, total 64ms
,I/BSUtils ( 1595): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1595): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1595): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1595): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1595): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 1595): AppWSProxy - sendAIDLWSResponse() sending reponse
I/ErrorTranslator( 1595): unknown error code mapping for: 0
I/global frequency( 1595): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1595): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1595): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1595): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 1595): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1595): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1595): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1595): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1595): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1595): doRequest(): polling manager says we're not connected, returning with an error: 
,E/MMApiProvisionService( 1595): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1595): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1595): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1595): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1595): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1595): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1595): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1595): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1595): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1595): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1595): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1595): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1595): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{42964d50 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42960188 type 2 com.google.android.gms}
,V/AlarmManager( 1020): sending alarm Alarm{42978390 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,I/VacuumService( 1214): Vacuum at: now=1454534174557 tag=VacuumService
,V/AlarmManager( 1020): sending alarm Alarm{427e0b08 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{427d4e68 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42135140 type 3 android}
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{427fc500 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{427cd7d0 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1020): sending alarm Alarm{427bc9d0 type 3 android}
,I/MMApiBackOffService( 1595): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1595): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1595): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1595): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1595): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1595): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1595): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1595): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1595): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1595): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1595): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1595): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1595): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1595): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1595): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1595): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1595): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1595): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1595): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{4278d0d0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{428a46c0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4284aad8 type 3 android}
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{4219e420 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4288ff18 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{428a4428 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1020): sending alarm Alarm{42a0fea8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4280d0d0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{41fc61d8 type 3 android}
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{42863d98 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{428479f8 type 3 android}
,I/MMApiBackOffService( 1595): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1595): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1595): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1595): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1595): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1595): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1595): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1595): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1595): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1595): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1595): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1595): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1595): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1595): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1595): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1595): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1595): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1595): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1595): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{42962d58 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42963a10 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{427b9b00 type 2 android}
,V/AlarmManager( 1020): sending alarm Alarm{427b0448 type 2 com.motorola.ccc.cce}
,D/ConnectivityService( 1020): Sampling interval elapsed, updating statistics ..
,I/PollingManager( 1595): alarm fired!
,D/Checkin ( 1595): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{427b0498 type 0 com.google.android.gms}
,D/ConnectivityService( 1020): Done.
,D/ConnectivityService( 1020): Setting timer for 720seconds
,I/EventLogService( 1702): Aggregate from 1454532670155 (log), 1454532670155 (data)
,V/AlarmManager( 1020): sending alarm Alarm{427c5318 type 3 android}
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1363): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{429ffc78 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{429c6288 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3539): 
D/AndroidRuntime( 3539): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3539): CheckJNI is OFF
D/dalvikvm( 3539): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3539): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3539): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3539): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3539): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3539): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3539): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3539): failed to load memtrack module: -2
D/AndroidRuntime( 3539): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1020): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1020): GC_EXPLICIT freed 658K, 9% free 18318K/19992K, paused 3ms+8ms, total 84ms
D/AndroidRuntime( 3539): Shutting down VM
D/dalvikvm( 3539): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms

```
