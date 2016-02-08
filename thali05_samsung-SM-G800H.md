#### Test 58135655812b57f_thali05_samsung-SM-G800H Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 3522): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3522):  
I/SELinux ( 3522):  
I/SELinux ( 3522): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3522): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3522): >>>>> Normal User
E/dalvikvm( 3522): >>>>> tv.peel.smartremote [ userId:0 | appId:10163 ]
E/SELinux ( 3522): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/BadgeProvider( 1342): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
I/Process ( 3461): Sending signal. PID: 3461 SIG: 9
D/Launcher.Model( 1252): reloadBadges entered.
D/BadgeProvider( 1342): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1342): sendNotify, [notify] : null
D/BadgeProvider( 1342): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1342): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1342): update, [UpdateCount] : 1
D/TimaKeyStoreProvider( 3522): in addTimaSignatureService
D/RCPManagerService(  693): exchangeData() failure , invalid userId
D/TimaKeyStoreProvider( 3522): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3522): Added TimaKesytore provider
--------- beginning of /dev/log/system
W/ActivityManager(  693): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/ActivityManager(  693): Process com.android.exchange (pid 3461) (adj 11) has died.
,W/ActivityManager(  693): Permission Denial: getCurrentUser() from pid=3522, uid=10163 requires android.permission.INTERACT_ACROSS_USERS
D/NotiRemoteService( 3522): action com.peel.widget.notification.SETUP_SERVICE_CONNECTION
D/NotiRemoteService( 3522): connectToPeelService 0
W/ContextImpl( 3522): Implicit intents with startService are not safe: Intent { act=tv.peel.samsung.widget.service.IPeelService } android.content.ContextWrapper.bindService:529 tv.peel.samsung.widget.a.c.<init>:-1 tv.peel.samsung.widget.NotiRemoteService.a:-1 
I/SELinux ( 3555): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3555):  
E/Watchdog(  693): !@Sync 1
D/NotiRemoteService( 3522): onServiceOn() mServiceState = 1
D/NotiRemoteService( 3522): Send action to self com.peel.widget.notification.SERVICE_BINDED
D/NotiRemoteService( 3522): action com.peel.widget.notification.SERVICE_BINDED
D/NotiRemoteService( 3522): feature is Off. Stop service
D/NotiRemoteService( 3522): Send action to self com.peel.widget.notification.STOP_PROCESS
D/NotiRemoteService( 3522): action com.peel.widget.notification.STOP_PROCESS
D/NotiRemoteService( 3522): onDestroy()
D/NotiRemoteService( 3522): mOrientationChangeReceier was not registered
I/SELinux ( 3555): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3555):  
I/SELinux ( 3555):  
I/SELinux ( 3555): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3555): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3555): >>>>> Normal User
E/dalvikvm( 3555): >>>>> org.simalliance.openmobileapi.service [ userId:0 | appId:1101 ]
E/SELinux ( 3555): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3555): in addTimaSignatureService
D/TimaKeyStoreProvider( 3555): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3555): Added TimaKesytore provider
V/AlarmManager(  693): waitForAlarm result :4
V/AlarmManager(  693): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
V/AlarmManager(  693): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
V/AlarmManager(  693): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/AndroidRuntime( 3543): 
D/AndroidRuntime( 3543): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3543): CheckJNI is OFF
D/AndroidRuntime( 3543): setted country_code = Poland
D/AndroidRuntime( 3543): setted countryiso_code = PL
D/AndroidRuntime( 3543): setted sales_code = XEO
D/AndroidRuntime( 3543): readGMSProperty: start
D/AndroidRuntime( 3543): readGMSProperty: already setted!!
D/AndroidRuntime( 3543): readGMSProperty: end
D/AndroidRuntime( 3543): addProductProperty: start
I/iu.UploadsManager( 1760): End new media; added: 0, uploading: 0, time: 37 ms
D/dalvikvm( 3543): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3543): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3543): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3543): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3543): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
V/SmartcardService( 3555): main Received broadcast
V/SmartcardService( 3555): Starting smartcard service after boot completed
W/ActivityManager(  693): Permission Denial: getCurrentUser() from pid=3555, uid=1101 requires android.permission.INTERACT_ACROSS_USERS
D/BatteryService(  693): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:17, charge type:1, power sharing:false
D/BatteryService(  693): Sending ACTION_BATTERY_CHANGED.
I/SELinux ( 3576): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3576):  
D/KeyguardUpdateMonitor( 1067): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1067): handleBatteryUpdate
D/UiModeManager(  693): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 1067):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
D/BatteryMeterView( 1067): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
V/HeadsetService( 1944): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 1944): Disconnected process message: 10
I/SELinux ( 3576): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3576):  
I/SELinux ( 3576):  
I/SELinux ( 3576): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3576): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3576): >>>>> Normal User
E/dalvikvm( 3576): >>>>> org.simalliance.openmobileapi.service:remote [ userId:0 | appId:1101 ]
E/SELinux ( 3576): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3576): in addTimaSignatureService
D/TimaKeyStoreProvider( 3576): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3576): Added TimaKesytore provider
W/ActivityManager(  693): Permission Denial: getCurrentUser() from pid=3576, uid=1101 requires android.permission.INTERACT_ACROSS_USERS
E/memtrack( 3543): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3543): failed to load memtrack module: -2
W/ContextImpl(  693): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/dalvikvm( 3543): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
E/STK2    ( 1241): onReceive android.intent.action.BOOT_COMPLETED
I/SELinux ( 3596): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3596):  
I/ActivityManager(  693): Waited long enough for: ServiceRecord{437dfb80 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
D/AndroidRuntime( 3543): Calling main entry com.android.commands.am.Am
I/SELinux ( 3596): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3596):  
I/SELinux ( 3596):  
I/SELinux ( 3596): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3596): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3596): >>>>> Normal User
E/dalvikvm( 3596): >>>>> com.sec.android.app.sysscope [ userId:0 | appId:1000 ]
E/SELinux ( 3596): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3596): in addTimaSignatureService
D/TimaKeyStoreProvider( 3596): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3596): Added TimaKesytore provider
D/AndroidRuntime( 3543): Shutting down VM
D/dalvikvm( 3543): GC_CONCURRENT freed 99K, 13% free 717K/820K, paused 0ms+0ms, total 3ms
W/ContextImpl( 3596): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2698 
D/SensorService(  693):   -0.1 -0.1 9.6
I/SELinux ( 3615): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3615):  
I/SELinux ( 3615): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3615):  
I/SELinux ( 3615):  
I/SELinux ( 3615): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3615): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3615): >>>>> Normal User
E/dalvikvm( 3615): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10166 ]
E/SELinux ( 3615): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 3615): in addTimaSignatureService
D/TimaKeyStoreProvider( 3615): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3615): Added TimaKesytore provider
D/SSRMv2:SIOP(  693): SIOP:: AP = 330, Delta = 10
W/ActivityManager(  693): Permission Denial: getCurrentUser() from pid=3615, uid=10166 requires android.permission.INTERACT_ACROSS_USERS
E/SMD     (  242): DCD ON
I/SELinux ( 3630): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3630):  
I/ActivityManager(  693): Killing 2054:com.sec.android.service.health/u0a16 (adj 15): empty #43
,I/SELinux ( 3630): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3630):  
I/SELinux ( 3630):  
I/SELinux ( 3630): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3630): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 3630): >>>>> Normal User
E/dalvikvm( 3630): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10169 ]
E/SELinux ( 3630): [DEBUG] seapp_context_lookup: seinfoCategory = shared
D/TimaKeyStoreProvider( 3630): in addTimaSignatureService
D/TimaKeyStoreProvider( 3630): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3630): Added TimaKesytore provider
I/Intent to TravelDirActivity( 3630): inside TravelBroadcastReceiver
W/ActivityManager(  693): Permission Denial: getCurrentUser() from pid=3630, uid=10169 requires android.permission.INTERACT_ACROSS_USERS
I/ActivityManager(  693): Killing 2764:com.policydm/1000 (adj 15): empty #43
D/daemonapp( 1463): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1463): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
D/comsamsunglog( 1463): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1463): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1463): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1463): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:87 [0:0] ABOOTCOPLD
W/BackupManagerService(  693): dataChanged but no participant pkg='com.android.providers.settings' uid=10172
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
D/daemonapp( 1463): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 1463): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1761 [0:0] [boot]now           :1454948620867
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1762 [0:0] [boot]NUT :1454970180000
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1763 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1764 [0:0] [boot]NUT - now :true
D/daemonapp( 1463): [MSC_Daemon]>>> WDBH:2157 [0:0] ud NT1454970180000
D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1212 [0:0] cp update : count : 1, pt : 2
D/daemonapp( 1463): [MSC_Daemon]>>> WU:1774 [0:0] Boot set AR_nexttime :1454970180000
D/comdaemonstockapp( 1463): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1463): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
I/SELinux ( 3642): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3642):  
I/SELinux ( 3642): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3642):  
I/SELinux ( 3642):  
I/SELinux ( 3642): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 3642): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3642): >>>>> Normal User
E/dalvikvm( 3642): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
E/SELinux ( 3642): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 3642): in addTimaSignatureService
D/TimaKeyStoreProvider( 3642): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3642): Added TimaKesytore provider
W/ActivityManager(  693): Permission Denial: getCurrentUser() from pid=3642, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
E/YouTube ( 3642): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
I/ActivityManager(  693): Waited long enough for: ServiceRecord{437e1ea0 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
D/YouTube ( 3642): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 3642): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
,D/YouTube ( 3642): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
,D/YouTube ( 3642): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.2; en_US; SM-G800H Build/KOT49H)
,D/YouTube ( 3642): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,D/YouTube ( 3642): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,D/WifiDisplayAdapter(  693): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  693): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService(  693): getStreamVolume 3 index 0
,I/MediaRouter( 3642): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/YouTube ( 3642): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,I/GoogleConversionPing( 3642): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=pCM2fjXErR9Rqcj2Pcnofw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.2&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1454948621&data=screen_name%3D%3CAndroid_YT_Open_App%3E
,I/System.out( 3642): Thread-358(HTTPLog):isShipBuild true
,I/System.out( 3642): Thread-358(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/cutils  (  229): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 3642): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,D/YouTube ( 3642): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  229): Returning OperationFailed - no handler for errno 30
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837934
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/STATUSBAR-NetworkController_dual( 1067): refreshSignalCluster - setNWBoosterIndicators(false)
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
D/SignalClusterView_dual( 1067): wifi: VISIBLE sig=2130837979 act=2130837936
D/SignalClusterView_dual( 1067): mMobileDataState=0 mMobileDataState2=0
D/SignalClusterView_dual( 1067): apply() mSeparateMobileGroup=8
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
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/YouTube ( 3642): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
,D/YouTube ( 3642): apps.youtube.common.f.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.a.a
,D/YouTube ( 3642): apps.youtube.datalib.offline.a.a.a:35 Network change detected, dispatch offline http requests.
D/STATUSBAR-IconMerger( 1067): checkOverflow(288), More:false, Req:false Child:2
,D/WifiDisplayAdapter(  693): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/YouTube ( 3642): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
,D/YouTube ( 3642): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,D/YouTube ( 3642): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
,D/YouTube ( 3642): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
,I/SELinux ( 3692): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3692):  
,I/ActivityManager(  693): Killing 2781:com.sec.spp.push/u0a38 (adj 15): empty #43
,I/SELinux ( 3692): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3692):  
I/SELinux ( 3692):  
,I/SELinux ( 3692): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3692): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3692): >>>>> Normal User
,E/dalvikvm( 3692): >>>>> com.qualcomm.atfwd [ userId:0 | appId:1000 ]
,E/SELinux ( 3692): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3692): in addTimaSignatureService
D/TimaKeyStoreProvider( 3692): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 3692): Added TimaKesytore provider
,I/GoogleConversionPing( 3642): Ping responded with response code 200
W/ContextImpl( 3692): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2698 
,D/dalvikvm(  693): GC_EXPLICIT freed 1031K, 14% free 23314K/26868K, paused 5ms+12ms, total 128ms
,E/AtFwd AutoBoot( 3692): AtFwd Auto Boot Started Successfully
D/AtFwdService( 3692): onCreate method
,I/AtFwdService( 3692): Instantiate AtCmdFwd Service
,D/AtCkpdCmdHandler( 3692): De-queing command
W/ContextImpl(  693): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.qualcomm.location.LocationServiceReceiver.onReceive:41 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 3719): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3719):  
,D/dalvikvm(  250): GC_EXPLICIT freed 44K, 51% free 9507K/19140K, paused 2ms+3ms, total 24ms
,D/dalvikvm(  250): GC_EXPLICIT freed <1K, 51% free 9507K/19140K, paused 2ms+2ms, total 18ms
,I/SELinux ( 3719): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3719):  
I/SELinux ( 3719):  
,I/SELinux ( 3719): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3719): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 3719): >>>>> Normal User
,E/dalvikvm( 3719): >>>>> com.android.vending [ userId:0 | appId:10030 ]
,E/SELinux ( 3719): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm(  250): GC_EXPLICIT freed <1K, 51% free 9507K/19140K, paused 2ms+3ms, total 18ms
,D/TimaKeyStoreProvider( 3719): in addTimaSignatureService
D/TimaKeyStoreProvider( 3719): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3719): Added TimaKesytore provider
,D/AmoledAdjustTimer(  693): prevTemp = 289, currTemp = 292, prevStep = 4, currStep = 4
,I/dalvikvm( 3719): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 3719): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3719): VFY: replacing opcode 0x6e at 0x000e
,D/Finsky  ( 3719): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 3719): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
,W/dalvikvm( 3719): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 3719): VFY: replacing opcode 0x6e at 0x01d3
,I/dalvikvm( 3719): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
,W/dalvikvm( 3719): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 3719): VFY: replacing opcode 0x6e at 0x000a
,D/Finsky  ( 3719): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/dalvikvm( 3719): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 3719): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 3719): VFY: replacing opcode 0x6e at 0x0032
,W/Settings( 3719): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3719): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 3719): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3719): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 3719): VFY: replacing opcode 0x6e at 0x013c
,I/dalvikvm( 3719): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3719): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 3719): VFY: replacing opcode 0x6e at 0x037f
,I/dalvikvm( 3719): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 3719): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 3719): VFY: replacing opcode 0x6e at 0x0385
,I/dalvikvm( 3719): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
,W/dalvikvm( 3719): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 3719): VFY: replacing opcode 0x6e at 0x0019
,D/Volley  ( 3719): [354] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3719): [347] DiskBasedCache.clear: Cache cleared.
,D/Ads     ( 3719): Skipping gmscore version check
,D/Finsky  ( 3719): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3719): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3719): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 3719): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/dalvikvm( 1760): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,W/dalvikvm( 1760): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1760): VFY: replacing opcode 0x62 at 0x0012
D/dalvikvm( 1760): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
W/dalvikvm( 1760): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1760): VFY: replacing opcode 0x62 at 0x0021
D/dalvikvm( 1760): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
W/dalvikvm( 1760): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
D/dalvikvm( 1760): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1760): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1760): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 1760): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1760): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
I/dalvikvm( 1760): DexOpt: unable to optimize static field ref 0x0077 at 0x17 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 1760): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_32_BIT_ABIS
I/dalvikvm( 1760): DexOpt: unable to optimize static field ref 0x0076 at 0x26 in Lcom/google/android/chimera/container/j;.a
D/dalvikvm( 1760): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_64_BIT_ABIS
,I/dalvikvm( 1760): DexOpt: unable to optimize static field ref 0x0077 at 0x0d in Lcom/google/android/chimera/container/j;.b
,W/InstanceID/Rpc( 1760): Found 10011
,D/FileApkUtils( 1760): Spent 62ms computing apk sha1.
,D/FileApkUtils( 1760): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 1760): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 1760): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
D/ChimeraCfgMgr( 1760): Reading stored module config
,D/GmsModuleFndr( 1760): Beginning GMS chimera module scan
,D/ChimeraCfgMgr( 1760): Beginning module configuration check
,D/ChimeraCfgMgr( 1760): Module APKs unchanged, check complete
E/dalvikvm( 1760): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1760): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 1760): VFY: replacing opcode 0x22 at 0x00af
,W/dalvikvm( 1760): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1760): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,W/dalvikvm( 1760): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1760): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 1760): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 1760): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
D/dalvikvm( 1760): VFY: replacing opcode 0x6e at 0x0021
D/dalvikvm( 1760): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
W/dalvikvm( 1760): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1760): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 1760): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,E/dalvikvm( 1219): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1219): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,D/dalvikvm( 1219): VFY: replacing opcode 0x22 at 0x00af
W/dalvikvm( 1219): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1219): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1219): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1219): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/dalvikvm( 1219): Could not find method android.net.ConnectivityManager.unregisterNetworkCallback, referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onDestroy
W/dalvikvm( 1219): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,D/dalvikvm( 1219): VFY: replacing opcode 0x6e at 0x0021
,D/dalvikvm( 1219): DexOpt: unable to opt direct call 0x03f7 at 0xb1 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
W/dalvikvm( 1219): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1219): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,D/dalvikvm( 1219): DexOpt: unable to opt direct call 0x4245 at 0xd3 in Lcom/google/android/gms/common/stats/GmsCoreStatsService;.onCreate
,E/dalvikvm( 1760): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 1760): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
,D/dalvikvm( 1760): VFY: replacing opcode 0x1f at 0x000e
,E/dalvikvm( 1760): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 1760): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,D/dalvikvm( 1760): VFY: replacing opcode 0x1f at 0x00f6
,W/dalvikvm( 1760): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
I/dalvikvm( 1760): Could not find method android.telephony.SubscriptionManager.getActiveSubscriptionInfoList, referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1760): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,D/dalvikvm( 1760): VFY: replacing opcode 0x6e at 0x0004
D/dalvikvm( 1760): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1760): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 1760): VFY: replacing opcode 0x62 at 0x0008
,D/dalvikvm( 1760): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,I/dalvikvm( 1760): DexOpt: unable to optimize static field ref 0x00e5 at 0x0c in Lcom/google/android/gms/checkin/d;.a
,D/dalvikvm( 1296): GC_EXPLICIT freed 755K, 46% free 10364K/19140K, paused 2ms+3ms, total 33ms
,I/CheckinService( 1760): Checkin interval check for package: unspecified last checkin: 1454573756466 min interval config: 0 actual interval: 374866540
,D/GCM     ( 1760): COMPAT: Multi user not supported
,I/CheckinService( 1760): Disabling old GoogleServicesFramework version
,D/GCM     ( 1296): COMPAT: Multi user not supported
,I/dalvikvm( 1296): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.nts.a.c.b
,W/dalvikvm( 1296): VFY: unable to resolve virtual method 1473: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/dalvikvm( 1296): VFY: replacing opcode 0x6e at 0x000f
,W/dalvikvm( 1760): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1760): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/ChimeraCfgMgr( 1760): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/dalvikvm( 1296): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
W/dalvikvm( 1296): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,D/dalvikvm( 1296): VFY: replacing opcode 0x6e at 0x0010
,D/BootCompletedReceiver( 1760): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 1760): Got an BootCompleted event.
,D/BootCompletedReceiver( 1760): Will NOT schedule AdAttestation signal task because it's disabled.
,D/SystemUpdateService( 1760): onCreate
,D/dalvikvm( 1760): GC_CONCURRENT freed 2326K, 42% free 11288K/19140K, paused 3ms+7ms, total 47ms
,I/CheckinService( 1760): Checking schedule, now: 1454948623086 next: 1455161282380
,I/CheckinService( 1760): active receiver: disabled
,D/SystemUpdateService( 1760): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/GCoreUlr( 1760): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1219): DispatchingService.onCreate()
,I/dalvikvm( 1760): Could not find method android.app.Notification$Builder.setCategory, referenced from method com.google.android.gms.update.t.a
W/dalvikvm( 1760): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,D/dalvikvm( 1760): VFY: replacing opcode 0x6e at 0x0409
,V/AuthZen ( 1760): Handling intent: android.intent.action.BOOT_COMPLETED
I/SystemUpdateService( 1760): cancelUpdate (empty URL)
,I/SystemUpdateService( 1760): active receiver: disabled
,W/dalvikvm( 1760): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1760): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
W/dalvikvm( 1760): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 1760): VFY: replacing opcode 0x6e at 0x002b
,W/dalvikvm( 1296): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1296): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1296): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1296): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1296): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 1296): VFY: replacing opcode 0x6e at 0x00bb
D/dalvikvm( 1296): DexOpt: couldn't find field Landroid/os/Message;.sendingUid
W/dalvikvm( 1296): VFY: unable to resolve instance field 161
,D/dalvikvm( 1296): VFY: replacing opcode 0x52 at 0x0006
,D/EnterpriseDeviceManagerService(  693): Creating context as user 0
,D/dalvikvm( 1760): Trying to load lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x42c34d08
,I/GCoreUlr( 1219): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/SystemUpdateService( 1760): onDestroy
,D/dalvikvm( 1760): Added shared lib /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x42c34d08
,D/dalvikvm( 1760): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libAppDataSearch.so 0x42c34d08, skipping init
,I/dalvikvm( 1296): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.cb.onReceive
,W/dalvikvm( 1296): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1296): VFY: replacing opcode 0x6e at 0x0059
D/dalvikvm( 1219): GC_CONCURRENT freed 1689K, 41% free 11453K/19140K, paused 3ms+6ms, total 77ms
,D/dalvikvm( 1219): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/EnterpriseDeviceManagerService(  693): Creating context as user 0
,D/AuthZenEventHandler( 1760): Handling event: android.intent.action.BOOT_COMPLETED
,I/dalvikvm( 1296): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.gms.gcm.e.c
W/dalvikvm( 1296): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/dalvikvm( 1296): VFY: replacing opcode 0x6e at 0x0022
,W/BaseAppContext( 1760): Using Auth Proxy for data requests.
,I/GCoreUlr( 1219): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/dalvikvm( 1760): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1760): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/GCM     ( 1296): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,W/dalvikvm( 1760): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1760): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1760): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1760): VFY: replacing opcode 0x6e at 0x00bb
,I/GCoreUlr( 1219): Unbound from all location providers
,I/GCoreUlr( 1219): Place inference reporting - stopped
I/dalvikvm( 1296): Could not find method android.accounts.AccountManager.removeAccount, referenced from method com.google.android.gms.auth.o.a
W/dalvikvm( 1296): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/dalvikvm( 1296): VFY: replacing opcode 0x6e at 0x001c
,E/BaseAppContext( 1760): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
I/GCoreUlr( 1219): DispatchingService.onDestroy()
,I/GCoreUlr( 1219): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1219): Unbound from all location providers
,I/GCoreUlr( 1219): Place inference reporting - stopped
,I/dalvikvm( 1760): Could not find method android.os.UserManager.isManagedProfile, referenced from method com.google.android.gms.auth.be.proximity.authorization.bt.b.a
W/dalvikvm( 1760): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
,D/dalvikvm( 1760): VFY: replacing opcode 0x6e at 0x002f
,V/GLSActivity( 1296): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1296): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 1296): Could not find method android.app.admin.DevicePolicyManager.getProfileOwner, referenced from method com.google.android.gms.auth.WorkAccountAuthenticatorInitializer.a
W/dalvikvm( 1296): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/dalvikvm( 1296): VFY: replacing opcode 0x6e at 0x0053
,I/AuthZen ( 1760): Fetching signing key...
,W/Auth    ( 1296): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/GLSActivity( 1296): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtils( 1067): isPcwEnable = null
,I/AuthZen ( 1760): Signing key fetched successfully!
,D/PersistentNotificationBroadcastReceiver( 1219): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,W/BaseAppContext( 1760): Using Auth Proxy for data requests.
,I/dalvikvm( 1296): Could not find method android.accounts.AccountManager.removeAccountExplicitly, referenced from method com.google.android.gms.auth.be.p.a
W/dalvikvm( 1296): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,D/dalvikvm( 1296): VFY: replacing opcode 0x6e at 0x001f
,I/BootupListener( 1241): mPendingNetworkManualSelection : false
,D/StatusChecker( 3350): onReceive : android.intent.action.SERVICE_STATE
,D/StatusChecker( 3350): Service state changed : 3
,V/GLSActivity( 1296): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dalvikvm( 1296): Could not find method android.accounts.AccountManager.notifyAccountAuthenticated, referenced from method com.google.android.gms.auth.be.s.a
W/dalvikvm( 1296): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,D/dalvikvm( 1296): VFY: replacing opcode 0x6e at 0x0041
,I/GCM     ( 1296): GCM config loaded
,D/AuthZenTransactionCache( 1760): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1760): Clearing transaction cache
,D/WearableService( 1219): callingUid 10011, callindPid: 1219
,E/MDM     ( 1219): [93] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1760): Restart initialization of location
,D/AuthorizationBluetoothService( 1296): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1296): Proximity feature is not enabled.
,V/GLSActivity( 1296): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1219): No location to return for getLastLocation()
,W/FusedLocationProvider( 1219): location=null
V/AlarmManager(  693): waitForAlarm result :8
,E/MDM     ( 1219): [95] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1760): Restart initialization of location
V/AlarmManager(  693): waitForAlarm result :8
,D/AuthorizationBluetoothService( 1296): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1296): Proximity feature is not enabled.
W/GCoreFlp( 1219): No location to return for getLastLocation()
,W/FusedLocationProvider( 1219): location=null
,E/SMD     (  242): DCD ON
V/AlarmManager(  693): waitForAlarm result :8
,V/GLSActivity( 1296): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SensorService(  693):   -0.0 -0.1 9.6
,I/SELinux ( 3834): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3834):  
,D/QuickConnect[1.1][2] ( 3370): PreDiscoveryHelper.mContentObserver - Contact Data changed
,V/QuickConnect[1.1][2] ( 3370): CONTACT_Info.getMyMobileNumber - 
,D/Mms/Contact( 1671): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact( 1671): performUpdate:widgetCount=0
,D/ContactProvider( 2324): getAllContactInfoList Start
D/QuickConnect[1.1][2] ( 3370): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3370): CONTACT_Info.getMyMobileNumber - null 
,D/ContactProvider( 2324): getAllContactInfoList End
,I/syncContacts( 2324): thread: 152, onChange
,I/SELinux ( 3834): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3834):  
I/SELinux ( 3834):  
,I/SELinux ( 3834): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3834): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3834): >>>>> Normal User
,E/dalvikvm( 3834): >>>>> com.sec.android.widgetapp.activeapplicationwidget [ userId:0 | appId:10152 ]
,E/SELinux ( 3834): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3834): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3834): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3834): Added TimaKesytore provider
,D/Mms/Contact( 1671): sContactsObserver.onChange(),selfUpdate=false
D/QuickConnect[1.1][2] ( 3370): PreDiscoveryHelper.mContentObserver - Contact Data changed
,V/QuickConnect[1.1][2] ( 3370): CONTACT_Info.getMyMobileNumber - 
,D/ContactProvider( 2324): getAllContactInfoList Start
D/QuickConnect[1.1][2] ( 3370): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 3370): CONTACT_Info.getMyMobileNumber - null 
,W/ActivityManager(  693): Permission Denial: getCurrentUser() from pid=3834, uid=10152 requires android.permission.INTERACT_ACROSS_USERS
V/TaskCloserActivity( 3834): TaskCloserActivity enter()
,I/SELinux ( 3850): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3850):  
,D/ContactProvider( 2324): getAllContactInfoList End
,I/syncContacts( 2324): thread: 153, onChange
,I/SELinux ( 3850): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3850):  
I/SELinux ( 3850):  
,I/SELinux ( 3850): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3850): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3850): >>>>> Normal User
,E/dalvikvm( 3850): >>>>> com.sec.factory [ userId:0 | appId:1000 ]
,E/SELinux ( 3850): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3850): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3850): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3850): Added TimaKesytore provider
,D/ConnectivityService(  693): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController_dual( 1067): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews start
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews set mobileLabel[SIM_0] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews GONE
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 set mobileLabel[SIM_1] =
D/StatusBar.NetworkController_dual( 1067): mMobileLabelViews2 GONE
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set : simMode = 0
,D/StatusBar.NetworkController_dual( 1067): mSingleMobileLabelViews set as slot1`s
,D/FactoryTestApp( 3850): [FactoryTestBroadcastReceiver$onReceive] onReceive action=android.intent.action.SECPHONE_READY
,I/FactoryTestApp( 3850): [FactoryTestBroadcastReceiver$onReceive] android.intent.action.SECPHONE_READY
,D/FactoryTest( 3850): User mode
,I/SELinux ( 3862): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3862):  
I/ActivityManager(  693): Killing 2797:com.osp.app.signin/u0a43 (adj 15): empty #43
,I/SELinux ( 3862): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3862):  
I/SELinux ( 3862):  
,I/SELinux ( 3862): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3862): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3862): >>>>> Normal User
,E/dalvikvm( 3862): >>>>> com.samsung.android.MtpApplication [ userId:0 | appId:1000 ]
,E/SELinux ( 3862): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 3862): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3862): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3862): Added TimaKesytore provider
,D/dalvikvm(  693): GC_EXPLICIT freed 2139K, 14% free 23433K/27132K, paused 4ms+10ms, total 121ms
,E/MTPRx   ( 3862): In MtpReceiverandroid.hardware.usb.action.USB_STATE
E/MTPRx   ( 3862): check value of boot_completed is1
,E/MTPRx   ( 3862): check booting is completed_sys.boot_completed
,E/MTPRx   ( 3862): Sd-Card path/storage/extSdCard
E/MTPRx   ( 3862): Status for mount/Unmount :removed
,E/MTPRx   ( 3862): SDcard is not available
W/MTPRx   ( 3862): value of connected istrue
W/MTPRx   ( 3862): value of configured istrue
W/MTPRx   ( 3862): value of mtpEnabled istrue
,W/MTPRx   ( 3862): value of ptpEnabled isfalse
E/MTPRx   ( 3862): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 3862): mFirstTime: false
,D/        ( 3862): MTP: reading debug level property
E/MTPRx   ( 3862):  String obtained from jar = 0b1e96db05d64ea4
,E/MTPJNIInterface( 3862): Getting CryptionKey from JAVA
,E/MTPRx   ( 3862): currentUserId is 0
,E/MTPRx   ( 3862): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 3862): usbMode is 0200
,E/MTPRx   ( 3862): is_secretmode is NOT 1
,W/MTPRx   ( 3862): Phone is lockedtrue
,D/LockPatternUtils( 1067): isPcwEnable = null
,D/MTPRx   ( 3862):  inside checkKnoxStatus
,D/MTPRx   ( 3862):  inside checkKnoxStatus_isKnoxModeActive : false
,E/MTPRx   ( 3862): Sending NORMAL_BOOT to stack
,E/MTPJNIInterface( 3862): noti = 17
,E/MTPRx   ( 3862): sending MTP_ICON_ENABLED to stack
,E/MTPRx   ( 3862): else part ... so first time!!!
E/MTPPlaObsrvr( 3862): inside setContext()
,E/MTPPlaObsrvr( 3862):  inside createplafiles
E/MTPPlaObsrvr( 3862): playlist count is0
,E/MTPPlaObsrvr( 3862):  inside try branch createplafiles
,E/MTPPlaObsrvr( 3862):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 3862): Inside registerContentObserver
E/MtpAdbObserver( 3862): inside setContext()
,E/MtpAdbObserver( 3862): Inside registerContentObserver
,W/Settings( 3862): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/KeyguardViewMediator( 1067): handleKeyguardDoneDrawing
,E/MtpService( 3862): onCreate.
,E/MtpService( 3862): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 3862): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 3862): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 3862): onStartCommand.
,E/MtpService( 3862): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
W/MTPRx   ( 3862): calling native method
,E/MTPJNIInterface( 3862): < MTP > Registering BroadCast receiver :::::
,E/MTPJNIInterface( 3862): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 3862): noti = 10
,I/knox    ( 3304): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
E/MtpService( 3862): onStartCommand.
W/MTPRx   ( 3862): calling native method
E/MTPRx   ( 3862): Checking the driver time out
,E/MTPJNIInterface( 3862): noti = 2
D/        ( 3862): deleting sockets before message queue initialization
,D/        ( 3862): event handler thread is created, so set the flag
E/MTPRx   ( 3862): called native method
E/MTPJNIInterface( 3862): setting Media scanner status0
,E/MTPJNIInterface( 3862): After setting Media scanner status0
,E/MTPJNIInterface( 3862): Getting media scanner status0
,E/MtpService( 3862): handleMessage. msg= { when=-2ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
W/MTPRx   ( 3862): notification from stack 1
,E/MTPJNIInterface( 3862): DeviceName is Galaxy S5-2
,W/ContextImpl( 3304): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
I/knox    ( 3304): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 3304): KNOXAgentService : onCreate()
,D/knox    ( 3304): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3304): KNOXAgentService. startJobThread() start
,D/knox    ( 3304): KNOXAgentService. JobThread()
D/knox    ( 3304): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 3304): KNOXAgentService. startJobThread() wait
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/knox    ( 3304): KNOXAgentService : onDestroy().
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/knox    ( 3304): ModuleBase.cancelAllAlarmManageModule()
,D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 1463): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1463): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 1463): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1463): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1454970180000
,D/daemonapp( 1463): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1454948624542
,D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 2
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 1463): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
I/Atfwd_Daemon(  290): result : 0 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/Atfwd_Daemon(  290): ATFWD --> QMI Port : rmnet1
,D/daemonapp( 1463): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
I/Atfwd_Daemon(  290): qmi_atcop_srvc_init_client - QMI Err code 0 , handle 16844800
I/Atfwd_Daemon(  290): Trying to register 8 commands:
I/Atfwd_Daemon(  290): cmd0: +CKPD
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
I/Atfwd_Daemon(  290): cmd1: +CTSA
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): cmd2: +CFUN
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): cmd3: +CMAR
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): cmd4: +CDIS
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): cmd5: +CRSL
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): cmd6: +CSS
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): cmd7: $QCPWRDN
I/Atfwd_Daemon(  290): qmi_atcop_reg_at_command_fwd_req: 0
,I/Atfwd_Daemon(  290): Registered AT Commands event handler
,D/BluetoothNotiBroadcastReceiver( 1317): onReceive
,D/AuthorizationBluetoothService( 1296): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/knox    ( 3304): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3304): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
I/knox    ( 3304): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 3304): GSLBThreadManager.NetworkStateChanged : Wifi is connected.
D/knox    ( 3304): KNOXAgentService : onCreate()
W/ContextImpl( 3304): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 3304): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 3304): KNOXAgentService. startJobThread() start
D/knox    ( 3304): KNOXAgentService. JobThread()
D/knox    ( 3304): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 3304): KNOXAgentService. startJobThread() wait
I/knox    ( 3304): RedirectionDataManager.isProductShip() is true. GSLB goes to Production Server.
D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/knox    ( 3304): KNOXAgentService : onDestroy().
D/knox    ( 3304): ModuleBase.cancelAllAlarmManageModule()
V/NearbySettings( 1317): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1317): MountReceiver.onReceive - Keep current state
D/FileShare-Server( 3029): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/FileShare-Server( 3029): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,I/SELinux ( 3901): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3901):  
,I/SELinux ( 3901): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3901):  
I/SELinux ( 3901):  
,I/SELinux ( 3901): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3901): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 3901): >>>>> Normal User
,E/dalvikvm( 3901): >>>>> com.vlingo.midas [ userId:0 | appId:10033 ]
,E/SELinux ( 3901): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 3901): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3901): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3901): Added TimaKesytore provider
,I/System.out( 3901): Inside WakeupProvider
,I/System.out( 3901): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 3901): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=XEO
,D/VlingoApplication( 3901): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 3901): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1317): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1317): MountReceiver.onReceive - Keep current state
,D/DialogFlow( 3901): initQueue()
,D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1317): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1317): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1317): MountReceiver.onReceive - Keep current state
,D/Toast   ( 1317):  checkMirrorLinkEnabled returns : false
,D/Toast   ( 1317): showing allowed
,D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1317): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=4, Uoast
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/PowerManagerService(  693): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=693
,D/DisplayPowerController(  693): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService(  693): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/lights  (  693): lcd : 8 +
D/RampAnimator(  693): Light Animator Finished currentValue=8
W/ContextImpl( 1317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/lights  (  693): lcd : 8 -
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/KeyguardUpdateMonitor( 1067): sendKeyguardVisibilityChanged(true)
,D/KeyguardUpdateMonitor( 1067): handleKeyguardVisibilityChanged(1)
,D/dalvikvm( 1317): GC_CONCURRENT freed 7515K, 48% free 10055K/19140K, paused 6ms+8ms, total 60ms
,D/LocalBluetoothProfileManager( 1317): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1317): Adding local HEADSET profile
W/ContextImpl( 1317): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,E/BluetoothHeadset( 1317): BTStateChangeCB is registed
,E/BluetoothHeadset( 1317): BluetoothHeadset service is binded
W/ContextImpl( 1317): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
,W/ContextImpl( 1317): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/Bluetoothsap( 1317): bindService called to Bluetooth SAP Service
,W/ContextImpl( 1317): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,W/ContextImpl( 1317): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
,D/LocalBluetoothProfileManager( 1317): PANU : true
,D/LocalBluetoothProfileManager( 1317): Adding local MAP profile
,D/BluetoothMap( 1317): Create BluetoothMap proxy object
W/ContextImpl( 1317): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,W/ContextImpl( 1317): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/Bluetoothsap( 1317): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1317): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1317): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1317): onReceive
W/ContextImpl( 1317): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/BluetoothA2dp( 1317): Proxy object connected
,D/BtConfig.SecureMode( 1944): isSecureModeOn:false
,D/A2dpProfile( 1317): Bluetooth service connected
,D/AuthorizationBluetoothService( 1296): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1296): Proximity feature is not enabled.
,D/HeadsetProfile( 1317): Bluetooth service connected
,D/BluetoothInputDevice( 1317): Proxy object connected
I/SELinux ( 3923): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 3923):  
,D/dalvikvm( 1207): GC_EXPLICIT freed 3900K, 48% free 10045K/19140K, paused 5ms+7ms, total 56ms
,I/PowerManagerService(  693): [PWL] On : 0 (54743 ms ago)
I/PowerManagerService(  693): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
,I/PowerManagerService(  693): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=1067, ws=null) (elapsedTime=17232)
,I/PowerManagerService(  693): [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=693, ws=WorkSource{1000}) (elapsedTime=271)
,D/HidProfile( 1317): Bluetooth service connected
W/ContextImpl(  693): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BluetoothPan( 1317): BluetoothPAN Proxy object connected
,D/PanProfile( 1317): Bluetooth service connected
E/MTPJNIInterface( 3862): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3862): SDcard is not available
I/SELinux ( 3923): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800H_4.4.2_0046
I/SELinux ( 3923):  
I/SELinux ( 3923):  
,I/SELinux ( 3923): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 3923): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 3923): >>>>> Normal User
,E/dalvikvm( 3923): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
,E/SELinux ( 3923): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/BluetoothMap( 1317): Proxy object connected
,W/BluetoothAdapter( 1944): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 1944): SOCK FLAG = 0 ***********************
,D/GKI_LINUX( 1944): acquire_my_wake_lock(), g_wake_lock_fd:91, g_wake_unlock_fd:92, wake_lock_acquired:0
,I/BtOppRfcommListener( 1944): Accept thread started.
,D/MapProfile( 1317): Bluetooth service connected
,D/BluetoothPbap( 1317): Proxy object connected
,D/PbapServerProfile( 1317): Bluetooth service connected
,I/dalvikvm( 3923): Enabling JNI app bug workarounds for target SDK version 8...
,D/TimaKeyStoreProvider( 3923): in addTimaSignatureService
,D/TimaKeyStoreProvider( 3923): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 3923): Added TimaKesytore provider
E/MTPJNIInterface( 3862): Status for mount/Unmount :removed
,E/MTPJNIInterface( 3862): SDcard is not available
E/SQLiteLog( 3862): (21) API call with NULL database connection pointer
E/SQLiteLog( 3862): (21) misuse at line 96833 of [00bb9c9ce4]
E/SQLiteLog( 3862): (21) API call with NULL database connection pointer
E/SQLiteLog( 3862): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3862): (21) API call with NULL database connection pointer
E/SQLiteLog( 3862): (21) misuse at line 93298 of [00bb9c9ce4]
E/SQLiteLog( 3862): (21) API call with NULL database connection pointer
,E/SQLiteLog( 3862): (21) misuse at line 96833 of [00bb9c9ce4]
,W/MTPRx   ( 3862): notification from stack 2
D/        ( 3862): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 3862): [mtp_init_device]  After open the MTP fd = 60 and line = 678...
D/        ( 3862): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,D/        ( 3862): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
