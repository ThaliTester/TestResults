#### Test 587523534d3a10e_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1021): sending alarm Alarm{42a46648 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428b33c8 type 2 com.google.android.gms}
--------- beginning of /dev/log/main
D/AndroidRuntime( 3336): 
D/AndroidRuntime( 3336): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3336): CheckJNI is OFF
D/dalvikvm( 3336): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3336): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3336): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3336): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3336): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3336): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3336): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3336): failed to load memtrack module: -2
D/AndroidRuntime( 3336): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1021): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3336
D/AndroidRuntime( 3336): Shutting down VM
D/dalvikvm( 3336): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 1ms+1ms, total 3ms
,E/global frequency( 1585): no tags to log
,D/Checkin ( 1585): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1585): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1585): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1585): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1585): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1585): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1585): BcsDSCheckin.events found events 2000
,D/Checkin ( 1585): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1585): GC_CONCURRENT freed 5448K, 33% free 11685K/17224K, paused 3ms+6ms, total 60ms
,I/BSUtils ( 1585): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1585): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1585): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
D/CCE     ( 1585): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1585): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1585): unknown error code mapping for: 0
I/global frequency( 1585): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1585): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1585): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 1585): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager( 1021): sending alarm Alarm{428c7218 type 3 android}
,I/MMApiBackOffService( 1585): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1585): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1585): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
I/MMApiWebService( 1585): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1585): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1585): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1585): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiBackOffService( 1585): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1585): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1585): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1585): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1585): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1585): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1585): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1585): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1585): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1021): sending alarm Alarm{428151c8 type 2 com.google.android.gms}
,V/AlarmManager( 1021): sending alarm Alarm{428a2ed8 type 2 com.google.android.gms}
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
,I/VacuumService( 1213): Vacuum at: now=1455029488192 tag=VacuumService
,V/AlarmManager( 1021): sending alarm Alarm{428b29c0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428d1e40 type 0 com.google.android.gms}
,I/EventLogService( 1681): Aggregate from 1455027621613 (log), 1455027621613 (data)
,V/AlarmManager( 1021): sending alarm Alarm{428dc6d0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428705a0 type 3 android}
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
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1021): sending alarm Alarm{429e7dc0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428dc7a8 type 2 com.google.android.gms}
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1021): sending alarm Alarm{42a06ca0 type 2 com.motorola.ccc.cce}
I/PollingManager( 1585): alarm fired!
D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1021): sending alarm Alarm{428d2450 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42888f40 type 3 android}
,I/MMApiBackOffService( 1585): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1585): MMApiBackOffService told us it's okay to retry the waiting requests: 3,
,D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1585): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1585): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
E/MMApiProvisionService( 1585): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1585): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/MMApiWebService( 1585): doRequest(): polling manager says we're not connected, returning with an error: 
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1585): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1585): MMApiWebService told us not to continue at the moment with this request: devices.json
,I/MMApiWebService( 1585): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1585): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1585): MMApiWebService told us not to continue at the moment with this request: 
D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1585): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1585): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1585): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1585): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1021): sending alarm Alarm{42a38a58 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42875738 type 3 android}
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1021): sending alarm Alarm{428cde90 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42a08058 type 2 com.google.android.gms}
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1021): sending alarm Alarm{42812888 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428c1778 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42a06d78 type 2 android}
,D/ConnectivityService( 1021): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1021): Done.
,D/ConnectivityService( 1021): Setting timer for 720seconds
,V/AlarmManager( 1021): sending alarm Alarm{42858268 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428d8848 type 3 android}
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1021): sending alarm Alarm{42838d88 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428bb748 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42a02b98 type 3 android}
,I/MMApiBackOffService( 1585): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1585): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1585): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1585): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/MMApiWebService( 1585): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1585): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1585): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1585): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1585): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1585): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1585): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1585): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1585): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1585): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1585): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1585): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1585): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1585): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1021): sending alarm Alarm{429ca930 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{429d9918 type 3 android}
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1021): sending alarm Alarm{429f5b78 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42a25ce0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{428ce7f0 type 2 com.google.android.gms}
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3407): 
D/AndroidRuntime( 3407): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3407): CheckJNI is OFF
D/dalvikvm( 3407): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3407): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3407): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3407): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3407): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3407): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3407): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3407): failed to load memtrack module: -2
D/AndroidRuntime( 3407): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1021): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1021): GC_EXPLICIT freed 807K, 9% free 18327K/20016K, paused 3ms+8ms, total 89ms
D/AndroidRuntime( 3407): Shutting down VM
D/dalvikvm( 3407): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms

```
