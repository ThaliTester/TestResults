#### Test 579720943a29850_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,D/AndroidRuntime( 3452): 
D/AndroidRuntime( 3452): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3452): CheckJNI is OFF
D/dalvikvm( 3452): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3452): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3452): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3452): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3452): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3452): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3452): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3452): failed to load memtrack module: -2
D/AndroidRuntime( 3452): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1017): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3452
D/AndroidRuntime( 3452): Shutting down VM
D/dalvikvm( 3452): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 0ms+1ms, total 2ms
,V/AlarmManager( 1017): sending alarm Alarm{4279c4e8 type 2 com.google.android.gms}
D/ConnectivityService( 1017): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1017): sending alarm Alarm{429862f8 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4205e838 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4297bc18 type 2 com.google.android.gms}
,E/global frequency( 1576): no tags to log
,D/Checkin ( 1576): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1576): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1576): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1576): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1576): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1576): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1576): BcsDSCheckin.events found events 1659
,D/Checkin ( 1576): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1576): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/dalvikvm( 1576): GC_CONCURRENT freed 5536K, 33% free 11597K/17224K, paused 3ms+5ms, total 49ms
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1576): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1576): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1576): unknown error code mapping for: 0
I/global frequency( 1576): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1576): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1576): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1576): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 1576): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1576): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1576): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1576): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1017): sending alarm Alarm{4285c9f0 type 2 com.google.android.gms}
,I/VacuumService( 1213): Vacuum at: now=1454414911296 tag=VacuumService
,V/AlarmManager( 1017): sending alarm Alarm{4280a068 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42878888 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42064fa0 type 2 com.google.android.gms}
,D/ConnectivityService( 1017): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1017): sending alarm Alarm{427ca840 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4275aad8 type 3 android}
,V/GLSActivity( 2072): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2072): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1017): sending alarm Alarm{42852718 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{427d75e8 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42778b78 type 2 com.google.android.gms}
,D/ConnectivityService( 1017): handleInetConditionChange: no active default network - ignore
,I/MMApiBackOffService( 1576): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1576): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1576): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1576): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1017): sending alarm Alarm{4279ba60 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42817a10 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42988808 type 3 android}
,V/GLSActivity( 2072): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2072): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1017): sending alarm Alarm{429dba70 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{428024b0 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{429f41a8 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4286f5c0 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4287d470 type 2 com.google.android.gms}
,D/ConnectivityService( 1017): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1017): sending alarm Alarm{4281daa0 type 3 android}
,V/GLSActivity( 2072): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2072): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1017): sending alarm Alarm{42080220 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{422a05c0 type 3 android}
,I/MMApiBackOffService( 1576): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1576): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1576): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1576): ProvisionWS.Response.setError: error RadioDownError
I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1017): sending alarm Alarm{42917128 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42850e38 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{420baf20 type 2 android}
,V/AlarmManager( 1017): sending alarm Alarm{420c3418 type 2 com.motorola.ccc.cce}
,D/ConnectivityService( 1017): Sampling interval elapsed, updating statistics ..
,I/PollingManager( 1576): alarm fired!
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1017): sending alarm Alarm{420c3468 type 0 com.google.android.gms}
,D/ConnectivityService( 1017): Done.
,D/ConnectivityService( 1017): Setting timer for 720seconds
,I/EventLogService( 1658): Aggregate from 1454413584380 (log), 1454413584380 (data)
,V/AlarmManager( 1017): sending alarm Alarm{42888710 type 3 android}
,V/GLSActivity( 2072): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2072): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1017): sending alarm Alarm{42838f80 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3549): 
D/AndroidRuntime( 3549): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3549): CheckJNI is OFF
D/dalvikvm( 3549): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3549): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3549): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3549): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3549): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3549): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3549): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3549): failed to load memtrack module: -2
D/AndroidRuntime( 3549): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1017): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1017): GC_EXPLICIT freed 683K, 9% free 18266K/19968K, paused 3ms+7ms, total 84ms
D/AndroidRuntime( 3549): Shutting down VM
D/dalvikvm( 3549): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms

```
