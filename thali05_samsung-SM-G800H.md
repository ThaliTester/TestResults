#### Test 58380500962e22b_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 3512): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3512):  
--------- beginning of /dev/log/system
I/ActivityManager(  736): Killing 2658:com.sec.android.app.shealth/u0a35 (adj 15): empty #43
I/SELinux ( 3512): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3512):  
I/SELinux ( 3512):  
I/SELinux ( 3512): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3512): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3512): >>>>> Normal User
E/dalvikvm( 3512): >>>>> tv.peel.smartremote [ userId:0 | appId:10163 ]
E/SELinux ( 3512): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/BadgeProvider( 1339): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
D/BadgeProvider( 1339): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1339): sendNotify, [notify] : null
D/BadgeProvider( 1339): update, [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 1252): reloadBadges entered.
D/BadgeProvider( 1339): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1339): update, [UpdateCount] : 1
I/Process ( 3446): Sending signal. PID: 3446 SIG: 9
D/RCPManagerService(  736): exchangeData() failure , invalid userId
D/TimaKeyStoreProvider( 3512): in addTimaSignatureService
D/TimaKeyStoreProvider( 3512): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3512): Added TimaKesytore provider
I/ActivityManager(  736): Process com.android.exchange (pid 3446) (adj 11) has died.
W/ActivityManager(  736): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=3512, uid=10163 requires android.permission.INTERACT_ACROSS_USERS
V/AlarmManager(  736): waitForAlarm result :4
V/AlarmManager(  736): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
V/AlarmManager(  736): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
V/AlarmManager(  736): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
I/ActivityManager(  736): Waited long enough for: ServiceRecord{43166498 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
I/iu.UploadsManager( 1649): End new media; added: 0, uploading: 0, time: 36 ms
D/BatteryService(  736): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:14, charge type:1, power sharing:false
D/BatteryService(  736): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
V/HeadsetService( 1932): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1932): Disconnected process message: 10
D/UiModeManager(  736): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
D/NotiRemoteService( 3512): action com.peel.widget.notification.SETUP_SERVICE_CONNECTION
D/NotiRemoteService( 3512): connectToPeelService 0
W/ContextImpl( 3512): Implicit intents with startService are not safe: Intent { act=tv.peel.samsung.widget.service.IPeelService } android.content.ContextWrapper.bindService:529 tv.peel.samsung.widget.a.c.<init>:-1 tv.peel.samsung.widget.NotiRemoteService.a:-1 
I/SELinux ( 3540): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3540):  
D/NotiRemoteService( 3512): onServiceOn() mServiceState = 1
D/NotiRemoteService( 3512): Send action to self com.peel.widget.notification.SERVICE_BINDED
D/NotiRemoteService( 3512): action com.peel.widget.notification.SERVICE_BINDED
D/NotiRemoteService( 3512): feature is Off. Stop service
D/NotiRemoteService( 3512): Send action to self com.peel.widget.notification.STOP_PROCESS
D/NotiRemoteService( 3512): action com.peel.widget.notification.STOP_PROCESS
D/NotiRemoteService( 3512): onDestroy()
D/NotiRemoteService( 3512): mOrientationChangeReceier was not registered
I/SELinux ( 3540): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3540):  
I/SELinux ( 3540):  
I/SELinux ( 3540): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3540): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3540): >>>>> Normal User
E/dalvikvm( 3540): >>>>> org.simalliance.openmobileapi.service [ userId:0 | appId:1101 ]
E/SELinux ( 3540): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3540): in addTimaSignatureService
D/TimaKeyStoreProvider( 3540): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3540): Added TimaKesytore provider
E/Watchdog(  736): !@Sync 1
V/SmartcardService( 3540): main Received broadcast
V/SmartcardService( 3540): Starting smartcard service after boot completed
W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=3540, uid=1101 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 3552): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3552):  
E/STK2    ( 1240): onReceive android.intent.action.BOOT_COMPLETED
I/SELinux ( 3552): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3552):  
I/SELinux ( 3552):  
I/SELinux ( 3552): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/SELinux ( 3558): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3558):  
E/SELinux ( 3552): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3552): >>>>> Normal User
E/dalvikvm( 3552): >>>>> org.simalliance.openmobileapi.service:remote [ userId:0 | appId:1101 ]
E/SELinux ( 3552): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3552): in addTimaSignatureService
D/TimaKeyStoreProvider( 3552): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3552): Added TimaKesytore provider
I/SELinux ( 3558): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3558):  
I/SELinux ( 3558):  
I/SELinux ( 3558): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3558): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3558): >>>>> Normal User
E/dalvikvm( 3558): >>>>> com.sec.android.app.sysscope [ userId:0 | appId:1000 ]
E/SELinux ( 3558): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=3552, uid=1101 requires android.permission.INTERACT_ACROSS_USERS
D/TimaKeyStoreProvider( 3558): in addTimaSignatureService
D/TimaKeyStoreProvider( 3558): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3558): Added TimaKesytore provider
W/ContextImpl( 3558): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 3583): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3583):  
W/ContextImpl(  736): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/SELinux ( 3583): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3583):  
I/SELinux ( 3583):  
I/SELinux ( 3583): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3583): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3583): >>>>> Normal User
E/dalvikvm( 3583): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10166 ]
E/SELinux ( 3583): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3583): in addTimaSignatureService
D/TimaKeyStoreProvider( 3583): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3583): Added TimaKesytore provider
D/SSRMv2:SIOP(  736): SIOP:: AP = 330, Delta = 10
W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=3583, uid=10166 requires android.permission.INTERACT_ACROSS_USERS
I/SELinux ( 3595): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3595):  
I/ActivityManager(  736): Killing 2056:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 3595): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3595):  
I/SELinux ( 3595):  
I/SELinux ( 3595): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3595): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 3595): >>>>> Normal User
E/dalvikvm( 3595): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
E/SELinux ( 3595): [DEBUG] seapp_context_lookup: seinfoCategory = shared
D/TimaKeyStoreProvider( 3595): in addTimaSignatureService
D/TimaKeyStoreProvider( 3595): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3595): Added TimaKesytore provider
I/Intent to TravelDirActivity( 3595): inside TravelBroadcastReceiver
W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=3595, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
I/ActivityManager(  736): Killing 2768:com.policydm/1000 (adj 15): empty #43
D/daemonapp( 1471): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1471): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1471): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1471): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1471): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
D/comsamsunglog( 1471): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1471): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1471): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1471): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1471): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 1471): [MSC_Daemon]>>> WDSM:87 [0:0] ABOOTCOPLD
D/AndroidRuntime( 3579): 
D/AndroidRuntime( 3579): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3579): CheckJNI is OFF
D/AndroidRuntime( 3579): setted country_code = Poland
D/AndroidRuntime( 3579): setted countryiso_code = PL
D/AndroidRuntime( 3579): setted sales_code = XEO
D/AndroidRuntime( 3579): readGMSProperty: start
D/AndroidRuntime( 3579): readGMSProperty: already setted!!
D/AndroidRuntime( 3579): readGMSProperty: end
D/AndroidRuntime( 3579): addProductProperty: start
D/daemonapp( 1471): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
W/BackupManagerService(  736): dataChanged but no participant pkg='com.android.providers.settings' uid=10172
D/daemonapp( 1471): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
D/daemonapp( 1471): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1471): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1471): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
D/daemonapp( 1471): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/dalvikvm( 3579): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3579): Added shared lib libjavacore.so 0x0
D/daemonapp( 1471): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
D/dalvikvm( 3579): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3579): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3579): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/daemonapp( 1471): [MSC_Daemon]>>> WU:1761 [0:0] [boot]now           :1454973326949
D/daemonapp( 1471): [MSC_Daemon]>>> WU:1762 [0:0] [boot]NUT :1454994900000
D/daemonapp( 1471): [MSC_Daemon]>>> WU:1763 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1471): [MSC_Daemon]>>> WU:1764 [0:0] [boot]NUT - now :true
D/SensorService(  736):   -0.0 -0.1 9.5
D/daemonapp( 1471): [MSC_Daemon]>>> WDBH:2157 [0:0] ud NT1454994900000
D/daemonapp( 1471): [MSC_Daemon]>>> WCP:1212 [0:0] cp update : count : 1, pt : 3
D/daemonapp( 1471): [MSC_Daemon]>>> WU:1774 [0:0] Boot set AR_nexttime :1454994900000
D/comdaemonstockapp( 1471): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1471): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
I/SELinux ( 3614): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3614):  
I/SELinux ( 3614): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3614):  
I/SELinux ( 3614):  
I/SELinux ( 3614): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3614): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3614): >>>>> Normal User
E/dalvikvm( 3614): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
E/SELinux ( 3614): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 3614): in addTimaSignatureService
D/TimaKeyStoreProvider( 3614): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3614): Added TimaKesytore provider
E/memtrack( 3579): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3579): failed to load memtrack module: -2
D/dalvikvm( 3579): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
E/SMD     (  240): DCD ON
D/AndroidRuntime( 3579): Calling main entry com.android.commands.am.Am
W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=3614, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
D/AndroidRuntime( 3579): Shutting down VM
D/dalvikvm( 3579): GC_CONCURRENT freed 99K, 13% free 717K/820K, paused 0ms+0ms, total 2ms
E/YouTube ( 3614): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
I/ActivityManager(  736): Waited long enough for: ServiceRecord{432f40c0 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
D/YouTube ( 3614): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 3614): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,D/YouTube ( 3614): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
,D/YouTube ( 3614): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
,D/YouTube ( 3614): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,D/YouTube ( 3614): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,D/WifiDisplayAdapter(  736): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  736): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/AudioService(  736): getStreamVolume 3 index 0
I/MediaRouter( 3614): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/YouTube ( 3614): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,I/GoogleConversionPing( 3614): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=pCM2fjXErR9Rqcj2Pcnofw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.2&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1454973327&data=screen_name%3D%3CAndroid_YT_Open_App%3E
,I/System.out( 3614): Thread-358(HTTPLog):isShipBuild true
,I/System.out( 3614): Thread-358(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/cutils  (  227): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 3614): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,D/YouTube ( 3614): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  227): Returning OperationFailed - no handler for errno 30
,D/YouTube ( 3614): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
,D/YouTube ( 3614): apps.youtube.common.f.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.a.a
,D/YouTube ( 3614): apps.youtube.datalib.offline.a.a.a:35 Network change detected, dispatch offline http requests.
D/WifiDisplayAdapter(  736): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/YouTube ( 3614): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
,D/YouTube ( 3614): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,D/YouTube ( 3614): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
,D/YouTube ( 3614): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
,I/SELinux ( 3666): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3666):  
,I/ActivityManager(  736): Killing 2791:com.sec.spp.push/u0a38 (adj 15): empty #43
,I/SELinux ( 3666): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3666):  
I/SELinux ( 3666):  
,I/SELinux ( 3666): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3666): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3666): >>>>> Normal User
,E/dalvikvm( 3666): >>>>> com.qualcomm.atfwd [ userId:0 | appId:1000 ]
,E/SELinux ( 3666): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3666): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3666): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3666): Added TimaKesytore provider
,I/GoogleConversionPing( 3614): Ping responded with response code 200
,D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
,D/STATUSBAR-NetworkController_dual( 1067): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm(  736): GC_EXPLICIT freed 978K, 14% free 23325K/27068K, paused 5ms+10ms, total 125ms
,W/ContextImpl( 3666): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2698 
E/AtFwd AutoBoot( 3666): AtFwd Auto Boot Started Successfully
D/AtFwdService( 3666): onCreate method
,I/AtFwdService( 3666): Instantiate AtCmdFwd Service
D/AtCkpdCmdHandler( 3666): De-queing command
W/ContextImpl(  736): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.qualcomm.location.LocationServiceReceiver.onReceive:41 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 3689): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3689):  
,D/dalvikvm(  247): GC_EXPLICIT freed 45K, 50% free 9507K/18864K, paused 3ms+4ms, total 40ms
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9507K/18864K, paused 3ms+3ms, total 25ms
,I/SELinux ( 3689): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3689):  
I/SELinux ( 3689):  
,I/SELinux ( 3689): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3689): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3689): >>>>> Normal User
,E/dalvikvm( 3689): >>>>> com.android.vending [ userId:0 | appId:10030 ]
,E/SELinux ( 3689): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm(  247): GC_EXPLICIT freed <1K, 50% free 9507K/18864K, paused 2ms+4ms, total 24ms
,D/TimaKeyStoreProvider( 3689): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3689): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3689): Added TimaKesytore provider
,D/AmoledAdjustTimer(  736): prevTemp = 288, currTemp = 290, prevStep = 4, currStep = 4
,I/dalvikvm( 3689): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
,W/dalvikvm( 3689): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3689): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 3689): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 3689): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 3689): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 3689): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 3689): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 3689): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 3689): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 3689): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 3689): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 3689): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 3689): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 3689): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3689): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 3689): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3689): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 3689): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 3689): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3689): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 3689): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 3689): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 3689): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 3689): VFY: replacing opcode 0x6e at 0x0385
,I/dalvikvm( 3689): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 3689): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 3689): VFY: replacing opcode 0x6e at 0x0019
,D/Volley  ( 3689): [354] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3689): [347] DiskBasedCache.clear: Cache cleared.
,D/Finsky  ( 3689): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Ads     ( 3689): Skipping gmscore version check
,D/Finsky  ( 3689): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3689): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 3689): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/dalvikvm( 1649): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,W/dalvikvm( 1649): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1649): VFY: replacing opcode 0x62 at 0x0012
D/dalvikvm( 1649): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
W/dalvikvm( 1649): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1649): VFY: replacing opcode 0x62 at 0x0021
,D/dalvikvm( 1649): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 1649): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1649): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1649): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1649): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1649): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1649): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
I/dalvikvm( 1649): DexOpt: unable to optimize static field ref 0x0077 at 0x17 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 1649): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
I/dalvikvm( 1649): DexOpt: unable to optimize static field ref 0x0076 at 0x26 in Lcom/google/android/chimera/container/j;.a
,D/dalvikvm( 1649): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,I/dalvikvm( 1649): DexOpt: unable to optimize static field ref 0x0077 at 0x0d in Lcom/google/android/chimera/container/j;.b
,W/InstanceID/Rpc( 1649): Found 10011
,D/FileApkUtils( 1649): Spent 71ms computing apk sha1.
,D/FileApkUtils( 1649): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 1649): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1649): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/ChimeraCfgMgr( 1649): Reading stored module config
,D/GmsModuleFndr( 1649): Beginning GMS chimera module scan
,D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1067): refreshSignalCluster - setNWBoosterIndicators(false)
,D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
,D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
,D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/ChimeraCfgMgr( 1649): Beginning module configuration check
,D/ChimeraCfgMgr( 1649): Module APKs unchanged, check complete
,E/dalvikvm( 1649): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1649): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 1649): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 1649): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1649): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1649): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1649): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 1649): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 1649): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 1649): VFY: replacing opcode 0x6e at 0x0021
,D/dalvikvm( 1649): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
W/dalvikvm( 1649): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1649): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 1649): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,E/dalvikvm( 1219): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
,W/dalvikvm( 1219): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
D/dalvikvm( 1219): VFY: replacing opcode 0x22 at 0x00af
,W/dalvikvm( 1219): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1219): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1219): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1219): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 1219): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 1219): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 1219): VFY: replacing opcode 0x6e at 0x0021
E/dalvikvm( 1649): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 1649): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
D/dalvikvm( 1649): VFY: replacing opcode 0x1f at 0x000e
,D/dalvikvm( 1219): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,W/dalvikvm( 1219): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1219): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 1219): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,E/dalvikvm( 1649): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 1649): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,D/dalvikvm( 1649): VFY: replacing opcode 0x1f at 0x00f6
,W/dalvikvm( 1649): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
I/dalvikvm( 1649): Could not find method android.telephony.SubscriptionManager.getActiveSubscriptionInfoList, referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1649): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,D/dalvikvm( 1649): VFY: replacing opcode 0x6e at 0x0004
D/dalvikvm( 1649): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1649): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1649): VFY: replacing opcode 0x62 at 0x0008
,D/dalvikvm( 1649): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,I/dalvikvm( 1649): DexOpt: unable to optimize static field ref 0x00e5 at 0x0c in Lcom/google/android/gms/checkin/d;.a
,D/GCM     ( 1649): COMPAT: Multi user not supported
,D/GCM     ( 1309): COMPAT: Multi user not supported
,I/CheckinService( 1649): Checkin interval check for package: unspecified last checkin: 1454573756466 min interval config: 0 actual interval: 399572625
,I/dalvikvm( 1309): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.nts.a.c.b
W/dalvikvm( 1309): VFY: unable to resolve virtual method 1473: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1309): VFY: replacing opcode 0x6e at 0x000f
,D/dalvikvm( 1649): GC_CONCURRENT freed 2295K, 41% free 11247K/18864K, paused 4ms+6ms, total 48ms
,I/GCoreUlr( 1649): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/dalvikvm( 1309): GC_EXPLICIT freed 773K, 45% free 10381K/18864K, paused 4ms+5ms, total 33ms
,I/GCoreUlr( 1219): DispatchingService.onCreate()
,I/CheckinService( 1649): Disabling old GoogleServicesFramework version
,I/dalvikvm( 1309): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
,W/dalvikvm( 1309): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,D/dalvikvm( 1309): VFY: replacing opcode 0x6e at 0x0010
,W/dalvikvm( 1649): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1649): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/ChimeraCfgMgr( 1649): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/EnterpriseDeviceManagerService(  736): Creating context as user 0
,D/BootCompletedReceiver( 1649): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 1649): Got an BootCompleted event.
,D/BootCompletedReceiver( 1649): Will NOT schedule AdAttestation signal task because it's disabled.
,D/SystemUpdateService( 1649): onCreate
,I/GCoreUlr( 1219): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/CheckinService( 1649): Checking schedule, now: 1454973329228 next: 1455161282380
,I/CheckinService( 1649): active receiver: disabled
,D/SystemUpdateService( 1649): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/dalvikvm( 1649): Could not find method android.app.Notification$Builder.setCategory, referenced from method com.google.android.gms.update.t.a
,W/dalvikvm( 1649): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,D/dalvikvm( 1649): VFY: replacing opcode 0x6e at 0x0409
,W/dalvikvm( 1309): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/dalvikvm( 1219): GC_CONCURRENT freed 1601K, 40% free 11425K/18864K, paused 6ms+4ms, total 48ms
,W/dalvikvm( 1309): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1309): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1309): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1309): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 1309): VFY: replacing opcode 0x6e at 0x00bb
V/AuthZen ( 1649): Handling intent: android.intent.action.BOOT_COMPLETED
,I/dalvikvm( 1649): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
,W/dalvikvm( 1649): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 1649): VFY: replacing opcode 0x6e at 0x002b
D/dalvikvm( 1309): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
W/dalvikvm( 1309): VFY: unable to resolve instance field 161
,D/dalvikvm( 1309): VFY: replacing opcode 0x52 at 0x0006
,I/SystemUpdateService( 1649): cancelUpdate (empty URL)
,I/SystemUpdateService( 1649): active receiver: disabled
,W/dalvikvm( 1649): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/EnterpriseDeviceManagerService(  736): Creating context as user 0
,D/dalvikvm( 1649): Trying to load lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x4265a348
,I/GCoreUlr( 1219): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1219): Unbound from all location providers
,I/GCoreUlr( 1219): Place inference reporting - stopped
,D/SystemUpdateService( 1649): onDestroy
I/dalvikvm( 1309): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.cb.onReceive
W/dalvikvm( 1309): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1309): VFY: replacing opcode 0x6e at 0x0059
I/GCoreUlr( 1219): DispatchingService.onDestroy()
,I/GCoreUlr( 1219): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1219): Unbound from all location providers
,I/GCoreUlr( 1219): Place inference reporting - stopped
,I/dalvikvm( 1309): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.e.c
W/dalvikvm( 1309): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1309): VFY: replacing opcode 0x6e at 0x0022
,D/AuthZenEventHandler( 1649): Handling event: android.intent.action.BOOT_COMPLETED
,D/dalvikvm( 1649): Added shared lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x4265a348
,D/dalvikvm( 1649): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x4265a348, skipping init
,D/GCM     ( 1309): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/dalvikvm( 1309): Could not find method android.accounts.AccountManager.removeAccount, referenced from method com.google.android.gms.auth.o.a
W/dalvikvm( 1309): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1309): VFY: replacing opcode 0x6e at 0x001c
,W/BaseAppContext( 1649): Using Auth Proxy for data requests.
,W/dalvikvm( 1649): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1649): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1649): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1649): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1649): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1649): VFY: replacing opcode 0x6e at 0x00bb
,V/GLSActivity( 1309): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BaseAppContext( 1649): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,V/GLSActivity( 1309): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 1309): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1309): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1309): VFY: replacing opcode 0x6e at 0x0053
I/dalvikvm( 1649): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
W/dalvikvm( 1649): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
,D/dalvikvm( 1649): VFY: replacing opcode 0x6e at 0x002f
,I/AuthZen ( 1649): Fetching signing key...
,W/Auth    ( 1309): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/AuthZen ( 1649): Signing key fetched successfully!
,V/GLSActivity( 1309): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1649): Using Auth Proxy for data requests.
,D/LockPatternUtils( 1067): isPcwEnable = null
,D/PersistentNotificationBroadcastReceiver( 1219): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/AuthZenTransactionCache( 1649): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1649): Clearing transaction cache
,I/dalvikvm( 1309): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.be.p.a
W/dalvikvm( 1309): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,D/dalvikvm( 1309): VFY: replacing opcode 0x6e at 0x001f
,I/GCM     ( 1309): GCM config loaded
,V/GLSActivity( 1309): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 1309): Could not find method android.accounts.AccountManager.notifyAccountAuthenticated, referenced from method com.google.android.gms.auth.be.s.a
W/dalvikvm( 1309): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,D/dalvikvm( 1309): VFY: replacing opcode 0x6e at 0x0041
,D/WearableService( 1219): callingUid 10011, callindPid: 1219
,E/MDM     ( 1219): [94] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1649): Restart initialization of location
,D/AuthorizationBluetoothService( 1309): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1309): Proximity feature is not enabled.
,V/GLSActivity( 1309): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1219): No location to return for getLastLocation()
,W/FusedLocationProvider( 1219): location=null
,V/AlarmManager(  736): waitForAlarm result :8
,V/AlarmManager(  736): waitForAlarm result :8
,E/MDM     ( 1219): [96] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1649): Restart initialization of location
,D/AuthorizationBluetoothService( 1309): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1309): Proximity feature is not enabled.
,W/GCoreFlp( 1219): No location to return for getLastLocation()
,W/FusedLocationProvider( 1219): location=null
,V/GLSActivity( 1309): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AlarmManager(  736): waitForAlarm result :8
,D/dalvikvm( 1649): GC_CONCURRENT freed 1679K, 40% free 11490K/18864K, paused 3ms+3ms, total 29ms
,D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
,D/STATUSBAR-NetworkController_dual( 1067): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,I/SELinux ( 3804): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3804):  
,D/Mms/Contact( 1738): sContactsObserver.onChange(),selfUpdate=false
D/QuickConnect[1.1][2] ( 3351): PreDiscoveryHelper.mContentObserver - Contact Data changed
,V/QuickConnect[1.1][2] ( 3351): CONTACT_Info.getMyMobileNumber - 
,D/Mms/Contact( 1738): performUpdate:widgetCount=0
,D/ContactProvider( 2495): getAllContactInfoList Start
,D/QuickConnect[1.1][2] ( 3351): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3351): CONTACT_Info.getMyMobileNumber - null 
,D/ContactProvider( 2495): getAllContactInfoList End
,I/syncContacts( 2495): thread: 179, onChange
,I/SELinux ( 3804): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3804):  
I/SELinux ( 3804):  
,I/SELinux ( 3804): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3804): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3804): >>>>> Normal User
,E/dalvikvm( 3804): >>>>> com.sec.android.widgetapp.activeapplicationwidget [ userId:0 | appId:10152 ]
,E/SELinux ( 3804): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3804): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3804): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3804): Added TimaKesytore provider
,D/QuickConnect[1.1][2] ( 3351): PreDiscoveryHelper.mContentObserver - Contact Data changed
,V/QuickConnect[1.1][2] ( 3351): CONTACT_Info.getMyMobileNumber - 
,W/ActivityManager(  736): Permission Denial: getCurrentUser() from pid=3804, uid=10152 requires android.permission.INTERACT_ACROSS_USERS
V/TaskCloserActivity( 3804): TaskCloserActivity enter()
D/Mms/Contact( 1738): sContactsObserver.onChange(),selfUpdate=false
,I/SELinux ( 3820): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3820):  
,D/ContactProvider( 2495): getAllContactInfoList Start
,D/QuickConnect[1.1][2] ( 3351): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3351): CONTACT_Info.getMyMobileNumber - null 
,D/ContactProvider( 2495): getAllContactInfoList End
,I/syncContacts( 2495): thread: 180, onChange
,I/SELinux ( 3820): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3820):  
I/SELinux ( 3820):  
,I/SELinux ( 3820): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3820): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3820): >>>>> Normal User
,E/dalvikvm( 3820): >>>>> com.sec.factory [ userId:0 | appId:1000 ]
,E/SELinux ( 3820): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3820): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3820): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3820): Added TimaKesytore provider
,D/FactoryTestApp( 3820): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.SECPHONE_READY
,I/FactoryTestApp( 3820): [FactoryTestBroadcastReceiver$onReceive] android.intent.action.SECPHONE_READY
,D/FactoryTest( 3820): User mode
,I/ActivityManager(  736): Killing 2815:com.osp.app.signin/u0a43 (adj 15): empty #43
,I/knox    ( 3287): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,I/knox    ( 3287): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3287): KNOXAgentService : onCreate()
D/knox    ( 3287): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3287): KNOXAgentService. startJobThread() start
,D/knox    ( 3287): KNOXAgentService. JobThread()
D/knox    ( 3287): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3287): KNOXAgentService. startJobThread() wait
W/ContextImpl( 3287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,E/SMD     (  240): DCD ON
,I/SELinux ( 3833): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3833):  
D/knox    ( 3287): KNOXAgentService : onDestroy().
,D/knox    ( 3287): ModuleBase.cancelAllAlarmManageModule()
D/ConnectivityService(  736): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/STATUSBAR-NetworkController_dual( 1067): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,I/SELinux ( 3833): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3833):  
I/SELinux ( 3833):  
,I/SELinux ( 3833): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3833): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3833): >>>>> Normal User
,E/dalvikvm( 3833): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
,E/SELinux ( 3833): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3833): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3833): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3833): Added TimaKesytore provider
,D/SensorService(  736):   -0.1 -0.1 9.6
,D/dalvikvm(  736): GC_EXPLICIT freed 2146K, 14% free 23445K/27068K, paused 6ms+10ms, total 129ms
,E/MTPRx   ( 3833): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,E/MTPRx   ( 3833): check value of boot_completed is1
,E/MTPRx   ( 3833): check booting is completed_sys.boot_completed
,E/MTPRx   ( 3833): Sd-Card path/storage/extSdCard
E/MTPRx   ( 3833): Status for mount/Unmount :removed
,E/MTPRx   ( 3833): SDcard is not available
,W/MTPRx   ( 3833): value of connected istrue
W/MTPRx   ( 3833): value of configured istrue
,W/MTPRx   ( 3833): value of mtpEnabled istrue
,W/MTPRx   ( 3833): value of ptpEnabled isfalse
,E/MTPRx   ( 3833): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 3833): mFirstTime: false
,D/        ( 3833): MTP: reading debug level property
,E/MTPRx   ( 3833):  String obtained from jar = 0b1e96db05d64ea4
E/MTPJNIInterface( 3833): Getting CryptionKey from JAVA
,E/MTPRx   ( 3833): currentUserId is 0
,E/MTPRx   ( 3833): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 3833): usbMode is 0200
,E/MTPRx   ( 3833): is_secretmode is NOT 1
,W/MTPRx   ( 3833): Phone is lockedtrue
,D/LockPatternUtils( 1067): isPcwEnable = null
,D/MTPRx   ( 3833):  inside checkKnoxStatus
,D/MTPRx   ( 3833):  inside checkKnoxStatus_isKnoxModeActive : false
,E/MTPRx   ( 3833): Sending NORMAL_BOOT to stack
,E/MTPJNIInterface( 3833): noti = 17
,E/MTPRx   ( 3833): sending MTP_ICON_ENABLED to stack
,E/MTPRx   ( 3833): else part ... so first time!!!
,E/MTPPlaObsrvr( 3833): inside setContext()
,E/MTPPlaObsrvr( 3833):  inside createplafiles
,E/MTPPlaObsrvr( 3833): playlist count is0
,E/MTPPlaObsrvr( 3833):  inside try branch createplafiles
,E/MTPPlaObsrvr( 3833):  inside deleteing plas createplafiles
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,E/MTPPlaObsrvr( 3833): Inside registerContentObserver
,E/MtpAdbObserver( 3833): inside setContext()
E/MtpAdbObserver( 3833): Inside registerContentObserver
,W/Settings( 3833): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,E/MtpService( 3833): onCreate.
,E/MtpService( 3833): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 3833): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 3833): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 3833): onStartCommand.
W/MTPRx   ( 3833): calling native method
,E/MTPJNIInterface( 3833): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 3833): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 3833): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 3833): noti = 10
,E/MtpService( 3833): onStartCommand.
,W/MTPRx   ( 3833): calling native method
E/MTPRx   ( 3833): Checking the driver time out
E/MTPJNIInterface( 3833): noti = 2
,D/        ( 3833): deleting sockets before message queue initialization
D/        ( 3833): event handler thread is created, so set the flag
E/MTPRx   ( 3833): called native method
,E/MTPJNIInterface( 3833): setting Media scanner status0
,E/MTPJNIInterface( 3833): After setting Media scanner status0
,E/MTPJNIInterface( 3833): Getting media scanner status0
W/MTPRx   ( 3833): notification from stack 1
,E/MTPJNIInterface( 3833): DeviceName is Galaxy S5-2
,E/MtpService( 3833): handleMessage. msg= { when=-5ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,D/daemonapp( 1471): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1471): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1471): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1471): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1471): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1471): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1471): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1471): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1471): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1471): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1471): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1471): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1471): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1471): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1454994900000
,D/daemonapp( 1471): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1454973330591
,D/daemonapp( 1471): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1471): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,D/daemonapp( 1471): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1471): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1471): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 1471): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/BluetoothNotiBroadcastReceiver( 1320): onReceive
,D/AuthorizationBluetoothService( 1309): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/knox    ( 3287): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,I/knox    ( 3287): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3287): KNOXAgentService : onCreate()
,D/knox    ( 3287): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 3287): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
,D/knox    ( 3287): GSLBThreadManager.NetworkStateChanged : Wifi is connected.
,D/knox    ( 3287): KNOXAgentService. startJobThread() start
,D/knox    ( 3287): KNOXAgentService. JobThread()
,D/knox    ( 3287): KNOXAgentService. JobThread. notifyAll().
,W/ContextImpl( 3287): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3287): KNOXAgentService. startJobThread() wait
,D/knox    ( 3287): KNOXAgentService : onDestroy().
,D/knox    ( 3287): ModuleBase.cancelAllAlarmManageModule()
,I/knox    ( 3287): RedirectionDataManager.isProductShip() is true. GSLB goes to Production Server.
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
,D/FileShare-Server( 3030): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Server( 3030): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,I/SELinux ( 3858): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3858):  
,I/SELinux ( 3858): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3858):  
I/SELinux ( 3858):  
,I/SELinux ( 3858): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3858): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3858): >>>>> Normal User
,E/dalvikvm( 3858): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 3858): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 3858): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3858): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3858): Added TimaKesytore provider
,D/dalvikvm( 3858): WAIT_FOR_CONCURRENT_GC blocked 1ms
,I/System.out( 3858): Inside WakeupProvider
,I/System.out( 3858): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 3858): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 3858): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 3858): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
,D/STATUSBAR-NetworkController_dual( 1067): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
,D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
,D/DialogFlow( 3858): initQueue()
W/ContextImpl( 1320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/LocalBluetoothProfileManager( 1320): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1320): Adding local HEADSET profile
W/ContextImpl( 1320): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,E/BluetoothHeadset( 1320): BTStateChangeCB is registed
,E/BluetoothHeadset( 1320): BluetoothHeadset service is binded
,D/Bluetoothsap( 1320): bindService called to Bluetooth SAP Service
W/ContextImpl( 1320): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
W/ContextImpl( 1320): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
W/ContextImpl( 1320): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,I/Atfwd_Daemon(  289): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/Atfwd_Daemon(  289): ATFWD --> QMI Port : rmnet1
,I/Atfwd_Daemon(  289): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 16844800
I/Atfwd_Daemon(  289): Trying to register 8 commands:
,I/Atfwd_Daemon(  289): cmd0: +CKPD
I/Atfwd_Daemon(  289): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  289): cmd1: +CTSA
I/Atfwd_Daemon(  289): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  289): cmd2: +CFUN
I/Atfwd_Daemon(  289): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  289): cmd3: +CMAR
I/Atfwd_Daemon(  289): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  289): cmd4: +CDIS
I/Atfwd_Daemon(  289): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  289): cmd5: +CRSL
I/Atfwd_Daemon(  289): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  289): cmd6: +CSS
D/LocalBluetoothProfileManager( 1320): PANU : true
,D/LocalBluetoothProfileManager( 1320): Adding local MAP profile
I/Atfwd_Daemon(  289): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  289): cmd7: $QCPWRDN
I/Atfwd_Daemon(  289): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  289): Registered AT Commands event handler
W/ContextImpl( 1320): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
,D/BluetoothMap( 1320): Create BluetoothMap proxy object
W/ContextImpl( 1320): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,W/ContextImpl( 1320): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/Bluetoothsap( 1320): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1320): LocalBluetoothProfileManager construction complete
W/ContextImpl( 1320): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/DockEventReceiver( 1320): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1320): onReceive
,D/BluetoothA2dp( 1320): Proxy object connected
,D/BtConfig.SecureMode( 1932): isSecureModeOn:false
,D/AuthorizationBluetoothService( 1309): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1309): Proximity feature is not enabled.
,D/A2dpProfile( 1320): Bluetooth service connected
,D/dalvikvm( 1320): GC_CONCURRENT freed 7593K, 47% free 10092K/18864K, paused 6ms+2ms, total 123ms
,W/BluetoothAdapter( 1932): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1932): SOCK FLAG = 0 ***********************
,D/GKI_LINUX( 1932): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtOppRfcommListener( 1932): Accept thread started.
,D/HeadsetProfile( 1320): Bluetooth service connected
,D/BluetoothInputDevice( 1320): Proxy object connected
,D/HidProfile( 1320): Bluetooth service connected
,D/BluetoothPan( 1320): BluetoothPAN Proxy object connected
,D/PanProfile( 1320): Bluetooth service connected
,D/BluetoothMap( 1320): Proxy object connected
,D/MapProfile( 1320): Bluetooth service connected
,D/BluetoothPbap( 1320): Proxy object connected
,D/PbapServerProfile( 1320): Bluetooth service connected
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
,D/Toast   ( 1320):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1320): showing allowed
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
,D/GKI_LINUX( 1932): release_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:1
,I/SurfaceFlinger(  246): id=15 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,I/SELinux ( 3893): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3893):  
D/PowerManagerService(  736): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=736
D/DisplayPowerController(  736): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService(  736): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/lights  (  736): lcd : 8 +
D/RampAnimator(  736): Light Animator Finished currentValue=8
,D/dalvikvm( 1207): GC_EXPLICIT freed 3899K, 47% free 10046K/18864K, paused 4ms+6ms, total 48ms
,D/lights  (  736): lcd : 8 -
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
E/MTPJNIInterface( 3833): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3833): SDcard is not available
I/SELinux ( 3893): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3893):  
I/SELinux ( 3893):  
,I/SELinux ( 3893): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3893): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3893): >>>>> Normal User
,E/dalvikvm( 3893): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
,E/SELinux ( 3893): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,I/dalvikvm( 3893): Enabling JNI app bug workarounds for target SDK version 8...
,D/TimaKeyStoreProvider( 3893): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3893): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3893): Added TimaKesytore provider
,E/MTPJNIInterface( 3833): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3833): SDcard is not available
E/SQLiteLog( 3833): (21) API call with NULL database connection pointer
E/SQLiteLog( 3833): (21) misuse at line 96833 of [00bb9c9ce4]
E/SQLiteLog( 3833): (21) API call with NULL database connection pointer
E/SQLiteLog( 3833): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3833): (21) API call with NULL database connection pointer
E/SQLiteLog( 3833): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3833): (21) API call with NULL database connection pointer
,E/SQLiteLog( 3833): (21) misuse at line 96833 of [00bb9c9ce4]
,W/MTPRx   ( 3833): notification from stack 2
D/        ( 3833): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 3833): [mtp_init_device]  After open the MTP fd = 60 and line = 678...
D/        ( 3833): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,D/        ( 3833): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
I/PowerManagerService(  736): [PWL] On : 0 (54361 ms ago)
I/PowerManagerService(  736): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
I/PowerManagerService(  736): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1067, ws=null) (elapsedTime=16773)
I/PowerManagerService(  736): [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=736, ws=WorkSource{1000}) (elapsedTime=84)

```
