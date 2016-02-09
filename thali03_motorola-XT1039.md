#### Test 58380500306a2c5_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1019): sending alarm Alarm{42311818 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
--------- beginning of /dev/log/main
D/AndroidRuntime( 3494): 
D/AndroidRuntime( 3494): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3494): CheckJNI is OFF
D/dalvikvm( 3494): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3494): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3494): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3494): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3494): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3494): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3494): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3494): failed to load memtrack module: -2
D/AndroidRuntime( 3494): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3494
D/AndroidRuntime( 3494): Shutting down VM
D/dalvikvm( 3494): GC_CONCURRENT freed 97K, 15% free 602K/704K, paused 1ms+0ms, total 3ms
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
,V/AlarmManager( 1019): sending alarm Alarm{428222b8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{429c9e28 type 2 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{4295c1e0 type 3 android}
,I/ClearcutLoggerApiImpl( 2041): disconnect managed GoogleApiClient
,E/global frequency( 1576): no tags to log
,D/Checkin ( 1576): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1576): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1576): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1576): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1576): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1576): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 1576): BcsDSCheckin.events found events 2000
,D/Checkin ( 1576): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/dalvikvm( 1576): GC_CONCURRENT freed 5451K, 33% free 11679K/17224K, paused 3ms+6ms, total 53ms
,I/BSUtils ( 1576): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
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
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1576): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1576): ProvisionWS.Response.setError: error RadioDownError
,D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: devices.json
,I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: 
,D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{425fa358 type 2 com.google.android.gms}
,I/VacuumService( 1213): Vacuum at: now=1455058289058 tag=VacuumService
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42890700 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4289e0a0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{428b1460 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1019): sending alarm Alarm{4258cde8 type 3 android}
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{42a4ae70 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42b04d38 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{427de8b8 type 3 android}
,I/MMApiBackOffService( 1576): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1576): MMApiBackOffService told us it's okay to retry the waiting requests: 3,
D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1576): ProvisionWS.Response: Missing mandatory message data in response from DM server...
I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1576): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{4281e868 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1019): sending alarm Alarm{42aca9a0 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{4285a500 type 3 android}
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{42adf298 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42130518 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{420cc258 type 0 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{420f9560 type 0 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{420e3c90 type 1 com.motorola.context}
,I/LaunchCheckinHandler( 1019): cleanup(): cleared. Last call was 557364 ms ago
,I/ActivityManager( 1019): Start proc com.motorola.context for service com.motorola.context/com.motorola.analytics.DailyCheckinService: pid=3551 uid=10011 gids={50011, 3003, 3002, 3001}
,V/AlarmManager( 1019): sending alarm Alarm{420e3c40 type 1 com.android.calendar}
,V/AlarmManager( 1019): sending alarm Alarm{420e3bf0 type 1 com.motorola.motocare}
,I/EventLogService( 1639): Aggregate from 1455056860164 (log), 1455056860164 (data)
,I/ActivityManager( 1019): Killing 2929:android.process.media/u0a18 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Checkin ( 3551): publish the event [tag = CONTEXT_ENGINE event name = INTERNAL]
,D/Checkin ( 3551): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 3551): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 3551): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 3551): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 3551): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 3551): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 3551): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 3551): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 3551): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 3551): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 3551): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 3551): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 3551): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 3551): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 3551): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,I/ActivityManager( 1019): Start proc com.google.android.gm for content provider com.google.android.gm/.provider.MailProvider: pid=3586 uid=10064 gids={50064, 3003, 1028, 1015}
,D/ActivityThread( 3586): Loading provider com.android.gmail.ui: com.google.android.gm.provider.GmailProvider
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2434 
E/MC_LineReader( 2189): Error opening /sys/module/pm8921_bms/parameters/bms_chrg_capacity
E/MC_LineReader( 2189): java.io.FileNotFoundException: /sys/module/pm8921_bms/parameters/bms_chrg_capacity: open failed: ENOENT (No such file or directory)
E/MC_LineReader( 2189): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/MC_LineReader( 2189): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
E/MC_LineReader( 2189): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
E/MC_LineReader( 2189): 	at java.io.FileReader.<init>(FileReader.java:66)
E/MC_LineReader( 2189): 	at com.motorola.motocare.util.LineReader.<init>(LineReader.java:20)
E/MC_LineReader( 2189): 	at com.motorola.motocare.util.LineReader$1.<init>(LineReader.java:53)
E/MC_LineReader( 2189): 	at com.motorola.motocare.util.LineReader.firstLineReader(LineReader.java:53)
E/MC_LineReader( 2189): 	at com.motorola.motocare.action.BatteryHealthAction.appendBatteryHealthReport(BatteryHealthAction.java:77)
E/MC_LineReader( 2189): 	at com.motorola.motocare.action.BatteryHealthAction.onReceiveImpl(BatteryHealthAction.java:57)
E/MC_LineReader( 2189): 	at com.motorola.motocare.util.BackgroundReceiver$1.run(BackgroundReceiver.java:14)
E/MC_LineReader( 2189): 	at android.os.Handler.handleCallback(Handler.java:733)
E/MC_LineReader( 2189): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/MC_LineReader( 2189): 	at android.os.Looper.loop(Looper.java:136)
E/MC_LineReader( 2189): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/MC_LineReader( 2189): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
E/MC_LineReader( 2189): 	at libcore.io.Posix.open(Native Method)
E/MC_LineReader( 2189): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/MC_LineReader( 2189): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/MC_LineReader( 2189): 	... 13 more
E/MC_BatteryHealthAction( 2189): Invalid cycle_count 0
E/MC_MmcStatsAction( 2189): Unable to find mmc block stat files.
W/System.err( 2189): java.io.FileNotFoundException: /sys/block/mmcblk1/stat: open failed: ENOENT (No such file or directory)
W/System.err( 2189): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2189): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 2189): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err( 2189): 	at java.io.FileReader.<init>(FileReader.java:66)
W/System.err( 2189): 	at com.motorola.motocare.action.MmcStatsAction.readMmcSectorWrites(MmcStatsAction.java:87)
W/System.err( 2189): 	at com.motorola.motocare.action.MmcStatsAction.appendMmcStatsReport(MmcStatsAction.java:70)
W/System.err( 2189): 	at com.motorola.motocare.action.MmcStatsAction.onReceiveImpl(MmcStatsAction.java:49)
W/System.err( 2189): 	at com.motorola.motocare.util.BackgroundReceiver$1.run(BackgroundReceiver.java:14)
W/System.err( 2189): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2189): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2189): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2189): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 2189): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 2189): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2189): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2189): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2189): 	... 11 more
,W/GAV2    ( 3586): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/dalvikvm( 1639): GC_CONCURRENT freed 1729K, 36% free 11068K/17224K, paused 4ms+5ms, total 33ms
,I/Gmail   ( 3586): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3586): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3586): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3586): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager( 1019): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=3624 uid=10019 gids={50019, 3003, 1028, 1015}
,D/ActivityThread( 3624): Loading provider com.android.email.provider;com.android.email.notifier: com.android.email.provider.EmailProvider
,D/dalvikvm( 3624): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41ffa6c8, skipping init
,I/com.android.email.cryptography.CryptographicModeHelper( 3624): Cryptographic modes supported!
I/openssl ( 3624): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3624): Crypto mode 0 already enabled
,W/ActivityManager( 1019): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.SmsCallsAction.onReceiveImpl:64 com.motorola.motocare.internal.SmsCallsAction.access$000:21 
,I/ActivityManager( 1019): Killing 3187:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,I/Email   ( 3624): Observing account changes for notifications
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ActivityManager( 1019): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/dalvikvm( 1019): GC_CONCURRENT freed 2138K, 11% free 18413K/20640K, paused 6ms+6ms, total 104ms
,D/dalvikvm( 1019): GC_CONCURRENT freed 2489K, 13% free 18251K/20780K, paused 2ms+5ms, total 92ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,I/GAV2    ( 3586): Thread[GAThread,5,main]: No campaign data found.
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_L1 event name = EventLogs]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L2 event name = DC_SDCARD]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/dalvikvm( 2189): GC_CONCURRENT freed 7100K, 42% free 10012K/17224K, paused 2ms+4ms, total 38ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/dalvikvm( 2189): GC_CONCURRENT freed 2255K, 44% free 9804K/17224K, paused 2ms+4ms, total 23ms
,D/dalvikvm( 2189): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/dalvikvm( 2189): GC_CONCURRENT freed 1899K, 43% free 9953K/17224K, paused 1ms+6ms, total 25ms
,D/dalvikvm( 2189): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/dalvikvm( 2189): GC_CONCURRENT freed 2213K, 44% free 9720K/17224K, paused 2ms+6ms, total 30ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/dalvikvm( 2189): GC_CONCURRENT freed 1908K, 43% free 9860K/17224K, paused 3ms+5ms, total 28ms
,D/dalvikvm( 2189): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/dalvikvm( 2189): GC_CONCURRENT freed 2040K, 44% free 9787K/17224K, paused 1ms+5ms, total 25ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/dalvikvm( 2189): GC_CONCURRENT freed 2150K, 45% free 9588K/17224K, paused 3ms+3ms, total 29ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/dalvikvm( 2189): GC_CONCURRENT freed 1717K, 43% free 9918K/17224K, paused 2ms+5ms, total 25ms
,D/dalvikvm( 2189): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/dalvikvm( 2189): GC_CONCURRENT freed 2133K, 44% free 9766K/17224K, paused 2ms+6ms, total 29ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,V/AlarmManager( 1019): sending alarm Alarm{4289e350 type 2 com.motorola.ccc.cce}
I/PollingManager( 1576): alarm fired!
D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/dalvikvm( 2189): GC_CONCURRENT freed 1906K, 43% free 9883K/17224K, paused 3ms+5ms, total 32ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/dalvikvm( 2189): GC_CONCURRENT freed 2046K, 44% free 9777K/17224K, paused 2ms+5ms, total 30ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/dalvikvm( 2189): GC_CONCURRENT freed 2060K, 44% free 9664K/17224K, paused 2ms+4ms, total 27ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/dalvikvm( 1019): GC_CONCURRENT freed 2189K, 13% free 18252K/20780K, paused 2ms+5ms, total 81ms
,D/dalvikvm( 2189): GC_CONCURRENT freed 1894K, 44% free 9756K/17224K, paused 1ms+5ms, total 27ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/dalvikvm( 2189): GC_CONCURRENT freed 1937K, 44% free 9794K/17224K, paused 1ms+5ms, total 39ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/dalvikvm( 2189): GC_CONCURRENT freed 2130K, 45% free 9608K/17224K, paused 3ms+3ms, total 26ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/dalvikvm( 2189): GC_CONCURRENT freed 1853K, 44% free 9713K/17224K, paused 2ms+5ms, total 28ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/dalvikvm( 2189): GC_CONCURRENT freed 1911K, 44% free 9801K/17224K, paused 1ms+5ms, total 27ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/dalvikvm( 2189): GC_CONCURRENT freed 2151K, 45% free 9625K/17224K, paused 2ms+3ms, total 25ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/dalvikvm( 2189): GC_CONCURRENT freed 1619K, 42% free 10017K/17224K, paused 2ms+6ms, total 26ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/dalvikvm( 2189): GC_CONCURRENT freed 2302K, 44% free 9689K/17224K, paused 2ms+5ms, total 29ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/dalvikvm( 2189): GC_CONCURRENT freed 1927K, 44% free 9729K/17224K, paused 1ms+4ms, total 26ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = DataSizes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = RadioTypes]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = SignalStrengths]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = PhoneTimeStats]
,I/ActivityManager( 1019): Killing 3205:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 1249): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = PerUidStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/dalvikvm( 2189): GC_CONCURRENT freed 1958K, 43% free 9819K/17224K, paused 2ms+4ms, total 30ms
,D/dalvikvm( 2189): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = AppUsage]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L1 event name = DC_ACCOUNT]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L1 event name = DC_SIGNALSTRENGTH]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L3 event name = DC_NETWORK]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L1 event name = DC_BATTERY]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = EventLogs]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_L1 event name = EventLogs]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_L3 event name = EventLogs]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_L3 event name = EventLogs]
,D/dalvikvm( 2189): GC_CONCURRENT freed 1733K, 42% free 10015K/17224K, paused 3ms+5ms, total 29ms
,W/ResourceType( 2189): Failure getting entry for 0x7f050000 (t=4 e=0) in package 0 (error -75)
W/PackageManager( 2189): Failure retrieving text 0x7f050000 in package com.android.keyguard
W/PackageManager( 2189): android.content.res.Resources$NotFoundException: String resource ID #0x7f050000
W/PackageManager( 2189): 	at android.content.res.Resources.getText(Resources.java:244)
W/PackageManager( 2189): 	at android.app.ApplicationPackageManager.getText(ApplicationPackageManager.java:994)
W/PackageManager( 2189): 	at android.content.pm.PackageItemInfo.loadLabel(PackageItemInfo.java:115)
W/PackageManager( 2189): 	at android.app.ApplicationPackageManager.getApplicationLabel(ApplicationPackageManager.java:1038)
W/PackageManager( 2189): 	at com.motorola.motocare.action.report.AppInfoReport.getAppInfoList(AppInfoReport.java:162)
W/PackageManager( 2189): 	at com.motorola.motocare.action.report.AppInfoReport.report(AppInfoReport.java:186)
W/PackageManager( 2189): 	at com.motorola.motocare.action.DailyReportAction.runDailyReports(DailyReportAction.java:128)
W/PackageManager( 2189): 	at com.motorola.motocare.action.DailyReportAction.onReceiveImpl(DailyReportAction.java:44)
W/PackageManager( 2189): 	at com.motorola.motocare.util.BackgroundReceiver$1.run(BackgroundReceiver.java:14)
W/PackageManager( 2189): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager( 2189): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager( 2189): 	at android.os.Looper.loop(Looper.java:136)
W/PackageManager( 2189): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ResourceType( 2189): Failure getting entry for 0x7f050000 (t=4 e=0) in package 0 (error -75)
,W/PackageManager( 2189): Failure retrieving text 0x7f050000 in package com.android.keyguard
W/PackageManager( 2189): android.content.res.Resources$NotFoundException: String resource ID #0x7f050000
W/PackageManager( 2189): 	at android.content.res.Resources.getText(Resources.java:244)
W/PackageManager( 2189): 	at android.app.ApplicationPackageManager.getText(ApplicationPackageManager.java:994)
W/PackageManager( 2189): 	at android.content.pm.PackageItemInfo.loadLabel(PackageItemInfo.java:115)
W/PackageManager( 2189): 	at android.app.ApplicationPackageManager.getApplicationLabel(ApplicationPackageManager.java:1038)
W/PackageManager( 2189): 	at com.motorola.motocare.action.report.AppInfoReport.getAppInfoList(AppInfoReport.java:163)
W/PackageManager( 2189): 	at com.motorola.motocare.action.report.AppInfoReport.report(AppInfoReport.java:186)
W/PackageManager( 2189): 	at com.motorola.motocare.action.DailyReportAction.runDailyReports(DailyReportAction.java:128)
W/PackageManager( 2189): 	at com.motorola.motocare.action.DailyReportAction.onReceiveImpl(DailyReportAction.java:44)
W/PackageManager( 2189): 	at com.motorola.motocare.util.BackgroundReceiver$1.run(BackgroundReceiver.java:14)
W/PackageManager( 2189): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager( 2189): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager( 2189): 	at android.os.Looper.loop(Looper.java:136)
W/PackageManager( 2189): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L2 event name = DC_APPINFO]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L2 event name = DC_APPINFO]
,D/Checkin ( 2189): publish the event [tag = MOT_CA_STATS_L2 event name = DC_APPINFO]
,D/dalvikvm( 2189): GC_CONCURRENT freed 2385K, 44% free 9677K/17224K, paused 3ms+2ms, total 32ms
,D/dalvikvm( 2189): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 2189): GC_CONCURRENT freed 2024K, 44% free 9671K/17224K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 2189): GC_CONCURRENT freed 2067K, 45% free 9633K/17224K, paused 1ms+2ms, total 21ms
,D/dalvikvm( 2189): GC_CONCURRENT freed 2026K, 44% free 9648K/17224K, paused 1ms+2ms, total 20ms
,D/dalvikvm( 2189): GC_CONCURRENT freed 2011K, 44% free 9679K/17224K, paused 1ms+2ms, total 21ms
,D/dalvikvm( 2189): GC_CONCURRENT freed 2101K, 45% free 9619K/17224K, paused 1ms+2ms, total 19ms
,D/dalvikvm( 2189): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 2189): GC_CONCURRENT freed 2040K, 45% free 9621K/17224K, paused 2ms+2ms, total 21ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = MMCStats]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_L1 event name = EventLogs]
,D/dalvikvm( 2189): GC_CONCURRENT freed 1557K, 42% free 10005K/17224K, paused 1ms+5ms, total 25ms
,D/dalvikvm( 2189): GC_CONCURRENT freed 1934K, 42% free 10024K/17224K, paused 2ms+5ms, total 34ms
,D/dalvikvm( 2189): GC_CONCURRENT freed 1954K, 42% free 10025K/17224K, paused 2ms+6ms, total 40ms
,D/dalvikvm( 2189): GC_CONCURRENT freed 1955K, 42% free 10025K/17224K, paused 2ms+6ms, total 27ms
,D/dalvikvm( 2189): GC_CONCURRENT freed 1954K, 42% free 10024K/17224K, paused 1ms+5ms, total 27ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MM event name = DC_MM]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MM event name = DC_MM]
,D/dalvikvm( 2189): GC_CONCURRENT freed 2062K, 43% free 9983K/17224K, paused 1ms+5ms, total 30ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MM event name = DC_MM]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MM event name = DC_MM]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MM event name = DC_MM]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MM event name = DC_MM]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MM event name = DC_MM]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MM event name = DC_MM]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MM event name = DC_MM]
,D/dalvikvm( 2189): GC_CONCURRENT freed 2189K, 44% free 9808K/17224K, paused 1ms+4ms, total 29ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MM event name = DC_MM]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MM event name = DC_MM]
,I/dalvikvm( 2189): Jit: resizing JitTable from 4096 to 8192
,D/dalvikvm( 2189): GC_CONCURRENT freed 1777K, 42% free 10022K/17224K, paused 3ms+4ms, total 29ms
,D/dalvikvm( 2189): GC_CONCURRENT freed 1869K, 42% free 10089K/17224K, paused 2ms+5ms, total 30ms
,D/Checkin ( 1019): publish the event [tag = MOT_APP_STATS event name = APPLAUNCH]
,D/Checkin ( 1019): publish the event [tag = MOT_APP_STATS event name = APPLAUNCH]
,D/dalvikvm( 2189): GC_CONCURRENT freed 1942K, 42% free 10088K/17224K, paused 2ms+5ms, total 30ms
,D/dalvikvm( 2189): GC_CONCURRENT freed 1978K, 42% free 10103K/17224K, paused 1ms+5ms, total 30ms
,D/dalvikvm( 2189): GC_CONCURRENT freed 1991K, 42% free 10103K/17224K, paused 3ms+5ms, total 31ms
,D/dalvikvm( 2189): GC_CONCURRENT freed 1938K, 42% free 10085K/17224K, paused 3ms+4ms, total 27ms
,D/dalvikvm( 2189): GC_CONCURRENT freed 1944K, 42% free 10095K/17224K, paused 3ms+5ms, total 31ms
,D/dalvikvm( 2189): GC_CONCURRENT freed 1985K, 42% free 10106K/17224K, paused 1ms+6ms, total 33ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/dalvikvm( 2189): GC_CONCURRENT freed 2107K, 42% free 10003K/17224K, paused 2ms+5ms, total 33ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/dalvikvm( 2189): GC_CONCURRENT freed 2046K, 43% free 9928K/17224K, paused 3ms+4ms, total 28ms
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = STORAGESTATS]
,D/Checkin ( 2189): publish the event [tag = MOT_DEVICE_STATS event name = PMaps]
,V/AlarmManager( 1019): sending alarm Alarm{4289e428 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4289e500 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,V/AlarmManager( 1019): sending alarm Alarm{428f7bc8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{428c3fe8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{420d5f70 type 3 android}
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{428b04d0 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1019): sending alarm Alarm{428fb680 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42ab2fa0 type 3 android}
,I/MMApiBackOffService( 1576): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1576): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1576): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1576): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1576): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1576): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1576): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1576): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1576): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1576): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{42af57b0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42a4d500 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42aa14f0 type 3 android}
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2041): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{42a42668 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3692): 
D/AndroidRuntime( 3692): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3692): CheckJNI is OFF
D/dalvikvm( 3692): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3692): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3692): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3692): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3692): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3692): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3692): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3692): failed to load memtrack module: -2
D/AndroidRuntime( 3692): Calling main entry com.android.commands.pm.Pm
W/PackageManager( 1019): Package named 'com.test.thalitest' doesn't exist.
D/dalvikvm( 1019): GC_EXPLICIT freed 1491K, 12% free 18260K/20640K, paused 3ms+7ms, total 84ms
D/AndroidRuntime( 3692): Shutting down VM
D/dalvikvm( 3692): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms

```
