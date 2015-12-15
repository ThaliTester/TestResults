#### Test 50388019385b4d9_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
I/SELinux ( 3582): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3582): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ContextImpl( 3046): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
I/KLMS-2.5.183: ( 3535): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
--------- beginning of system
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3046): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/ContextImpl( 3046): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
I/KLMS-2.5.183: ( 3535): KLMSIntentService(): BOOT_COMPLETED
D/TimaKeyStoreProvider( 3582): TimaSignature is unavailable
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
D/ActivityThread( 3582): Added TimaKeyStore provider
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/libprocessgroup( 1015): failed to open /acct/uid_10159/pid_2843/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10048/pid_2804/cgroup.procs: No such file or directory
D/ActivityManager( 1015): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
D/FileShare-Server( 3555): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3622 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 3622): MountEmulatedStorage()
E/Zygote  ( 3622): v2
I/libpersona( 3622): KNOX_SDCARD checking this for 1000
I/libpersona( 3622): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Killing 2877:com.sec.usbsettings/1000 (adj 15): empty #31
I/SELinux ( 3622): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ActivityManager( 1015): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
I/SELinux ( 3622): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/KLMS-2.5.183: ( 3535): KLMSIntentService(): onDestroy()
E/SELinux ( 3622): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 2828:com.sec.dsm.system/1000 (adj 15): empty #31
D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/DBG_DM  ( 2948): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
D/TimaKeyStoreProvider( 3622): TimaSignature is unavailable
D/ActivityThread( 3622): Added TimaKeyStore provider
E/MTPRx   ( 3622): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
D/SecContentProvider2( 1015): uri = 14 selection = getSealedState
D/SecContentProvider2( 1015): mCursor = null
D/SecContentProvider2( 1015): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1015): mCursor = null
V/MTPRx   ( 3622): sealedState: false
V/MTPRx   ( 3622): sealedUsbMassStorageState: false
D/SettingsProvider( 1015): name = mtp_usb_connection_status
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2877/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2828/cgroup.procs: No such file or directory
D/ActivityManager( 1015): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/ActivityManager( 1015): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/ActivityManager( 1015): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/ActivityManager( 1015): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
W/ContextImpl( 1953): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1015): startService callerProcessName:com.qualcomm.qti.services.secureui, calleePkgName: com.qualcomm.qti.services.secureui
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
D/SecUISvc( 1953): Service started flags 0 startId 1
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
D/SecUISvc( 1953): Thread created.
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3649): MountEmulatedStorage()
E/Zygote  ( 3649): v2
I/libpersona( 3649): KNOX_SDCARD checking this for 10028
I/libpersona( 3649): KNOX_SDCARD not a persona
I/SELinux ( 3649): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3649): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3649 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 3649): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/SettingsProvider( 1015): name = media_player_mode
I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
I/ActivityManager( 1015): Killing 2776:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
I/ActivityManager( 1015): Killing 2897:com.sec.android.app.factorykeystring/1000 (adj 15): empty #32
D/TimaKeyStoreProvider( 3649): TimaSignature is unavailable
D/ActivityThread( 3649): Added TimaKeyStore provider
D/SettingsProvider( 1015): name = mtp_usb_conditions_met
I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
D/SettingsProvider( 1015): name = mtp_running_status
I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
W/libprocessgroup( 1015): failed to open /acct/uid_10085/pid_2776/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2897/cgroup.procs: No such file or directory
D/SettingsProvider( 1015): name = media_mount_count
I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
D/SettingsProvider( 1015): name = mtp_sync_alive
I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
D/SettingsProvider( 1015): name = sdcard_launch
D/SettingsProvider( 1015): name = boot_time_connected
I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
D/SettingsProvider( 1015): name = mtp_open_session
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
W/ContextImpl( 1015): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3679): MountEmulatedStorage()
I/libpersona( 3679): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3679): v2
I/libpersona( 3679): KNOX_SDCARD not a persona
I/SELinux ( 3679): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3679 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/Gmail   ( 3518): getAccountsCursor
I/SELinux ( 3679): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3679): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TimaKeyStoreProvider( 3679): TimaSignature is unavailable
D/ActivityThread( 3679): Added TimaKeyStore provider
I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
I/PCWCLIENTTRACE_PushUtil( 3258): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3258): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3258): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3258): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3258): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3258): ACTION_BOOTUP - Push type: [SPP, GCM]
D/Finsky  ( 3649): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/PCWCLIENTTRACE_PCWHandler( 3258): [ensureRegistration] - netwrok is not available. action ignored
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/GAV2    ( 3518): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/SMD     (  287): DCD OFF
E/Zygote  ( 3701): MountEmulatedStorage()
E/Zygote  ( 3701): v2
I/libpersona( 3701): KNOX_SDCARD checking this for 10031
I/libpersona( 3701): KNOX_SDCARD not a persona
I/SELinux ( 3701): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3701): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3701): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3701 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 2938:com.sec.android.diagmonagent/1000 (adj 15): empty #31
D/TimaKeyStoreProvider( 3701): TimaSignature is unavailable
D/ActivityThread( 3701): Added TimaKeyStore provider
W/ResourcesManager( 3701): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/ServiceManager(  314): Waiting for service AtCmdFwd...
W/ContextImpl( 3679): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2938/cgroup.procs: No such file or directory
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3720): MountEmulatedStorage()
E/Zygote  ( 3720): v2
I/libpersona( 3720): KNOX_SDCARD checking this for 1000
I/libpersona( 3720): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3720 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3720): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3720): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3720): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/art     (  304): Explicit concurrent mark sweep GC freed 8751(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 640us total 26.483ms
D/TimaKeyStoreProvider( 3720): TimaSignature is unavailable
D/ActivityThread( 3720): Added TimaKeyStore provider
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 20.143ms
W/ResourcesManager( 3720): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 679us total 23.881ms
D/FactoryTestApp( 2537): [DummyFtClient$onDestroy](2537) Destroy DummyFtClient service
D/FactoryTestApp( 2537): [Support$Values.getString](2537) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2537): [ModuleCommon$isConnectionModeNone](2537) mConnectionMode = gsm
I/FactoryTestApp( 2537): [ModuleCommon$isRunningFtClient](2537) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2537): [DummyFtClient$onDestroy](2537) kill process
I/Process ( 2537): Sending signal. PID: 2537 SIG: 9
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/Gmail   ( 3518): getAccountsCursor
E/Gmail   ( 3518): Error finding the version of the Email provider.....
E/Gmail   ( 3518): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3518): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3518): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 3518): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3518): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3518): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3518): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3518): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 3518): We do not support migrating this version of the Email provider.
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/ActivityManager( 1015): Process com.sec.factory (pid 2537)(adj 0) has died(254,1042)
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3754): MountEmulatedStorage()
E/Zygote  ( 3754): v2
I/libpersona( 3754): KNOX_SDCARD checking this for 10104
I/libpersona( 3754): KNOX_SDCARD not a persona
I/SELinux ( 3754): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3754 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/SELinux ( 3754): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3754): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/GoogleHttpClient( 1626): GMS http client unavailable, use old client
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/TimaKeyStoreProvider( 3754): TimaSignature is unavailable
D/ActivityThread( 3754): Added TimaKeyStore provider
V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/VlingoApplication( 3701): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
E/SQLiteLog( 3518): (283) recovered 42 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
D/Finsky  ( 3649): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/DBG_DM  ( 2948): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
D/TimaService( 1015): TIMA: in getTimaVersion
D/TimaService( 1015): TIMA3: KeyStore3_init
D/TimaService( 1015): TIMA: in getTimaVersion
E/TLC_TZ_KEYSTORE: ( 1015): Inside TZ_KEYSTORE_initialize()
I/TLC_TZ_KEYSTORE: ( 1015): creating new keystore context...
I/TLC_TZ_KEYSTORE: ( 1015): initializing ccm context...
I/TLC_TZ_KEYSTORE: ( 1015): root = /firmware/image, root_strlen = 15
I/TLC_TZ_KEYSTORE: ( 1015): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1015): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): aligned max_sendmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1015): aligned max_recvmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1015): max_message_size = 2176 = 0x880
D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x880
D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
D/QSEECOMAPI: ( 1015): Loaded image: APP id = 8
I/TZ: qc_tlc_communication( 1015): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
I/TLC_TZ_KEYSTORE: ( 1015): ctx = 0xb93d4dd8, comm = 0xb942d8b0, sendmsg = 0xa0682000, recvmsg = 0xa0682440
I/TZ_init: ( 1015): TZ_init: sending initialization request...
E/TZ_init: ( 1015): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 1015): trustlet initialization failed
I/TZ_init: ( 1015): TZ_init_START...
W/Settings( 3649): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/TZ_init: ( 1015): TZ_init_with_data: sending initialization request...
I/TZ_init: ( 1015): TZ_init: successful initialization
D/QSEECOMAPI: ( 1015): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1015): QSEECom_shutdown_app, app_id = 8
E/TLC_TZ_KEYSTORE: ( 1015): Count : 1, Ret : 0
W/Settings( 3649): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/art     ( 1015): Explicit concurrent mark sweep GC freed 32419(1739KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 26MB/39MB, paused 2.437ms total 160.937ms
D/BluetoothAdapter( 3701): 225332699: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3701): 225332699: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3701): 225332699: getState() :  mService = null. Returning STATE_OFF
I/VlingoAndroidCore( 3701): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ResourcesManager( 3754): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 3518): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@17343bec that was originally bound here
E/ActivityThread( 3518): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@17343bec that was originally bound here
E/ActivityThread( 3518): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3518): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3518): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3518): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3518): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3518): 	at com.android.emailcommon.service.ah.a(SourceFile:181)
E/ActivityThread( 3518): 	at com.android.emailcommon.service.ah.e(SourceFile:224)
E/ActivityThread( 3518): 	at com.android.email.service.n.c(SourceFile:161)
E/ActivityThread( 3518): 	at com.android.email.provider.b.a(SourceFile:173)
E/ActivityThread( 3518): 	at com.android.email.provider.b.a(SourceFile:117)
E/ActivityThread( 3518): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
E/ActivityThread( 3518): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
E/ActivityThread( 3518): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3518): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3518): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3518): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1015): Unbind failed: could not find connection for android.os.BinderProxy@12c2ffc6
I/Gmail   ( 3518): Observing account changes for notifications
I/ActivityManager( 1015): Killing 2967:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Volley  ( 3649): [553] DiskBasedCache.clear: Cache cleared.
D/Finsky  ( 3649): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3649): [1] Libraries$2.run: Finished loading 1 libraries.
D/Volley  ( 3649): [546] DiskBasedCache.clear: Cache cleared.
D/Ads     ( 3649): Skipping gmscore version check
D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
D/VlingoApplication( 3701): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 3701): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
D/DialogFlow( 3701): initQueue()
W/libprocessgroup( 1015): failed to open /acct/uid_10150/pid_2967/cgroup.procs: No such file or directory
I/ActivityManager( 1015): Waited long enough for: ServiceRecord{1100568a u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3679): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3679): Resource data:2131165186
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
W/ResourcesManager( 3679): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3679): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3679): getResourceTypeNamexml
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3786 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/Zygote  ( 3786): MountEmulatedStorage()
E/Zygote  ( 3786): v2
I/libpersona( 3786): KNOX_SDCARD checking this for 10032
I/libpersona( 3786): KNOX_SDCARD not a persona
I/SELinux ( 3786): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3786): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3786): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 2859:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
D/TimaKeyStoreProvider( 3786): TimaSignature is unavailable
D/ActivityThread( 3786): Added TimaKeyStore provider
I/AMMetaDataParserService( 3679): Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
D/Finsky  ( 3649): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
I/AMMetaDataParserService( 3679): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
I/AMMetaDataParserService( 3679): Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
W/libprocessgroup( 1015): failed to open /acct/uid_10072/pid_2859/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
W/ContextImpl( 3679): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
W/art     ( 3701): Suspending all threads took: 8.181ms
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:assistant
I/AMMetaDataParserService( 3679): Resource data:2131034113
W/ResourcesManager( 3679): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3679): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3679): getResourceTypeNamexml
E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX construct_block_size_descriptor_2d second part( 3679): took 2.178803ms for 0*0 texture 0
I/GFX generate_partition_tables( 3679): took 6.120522ms for 0*0 texture 0
I/GFX raster( 3679): took 9.518022ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb905c5f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb905c980 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3679): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3806): MountEmulatedStorage()
I/ActivityManager( 1015): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3806 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/Zygote  ( 3806): v2
I/libpersona( 3806): KNOX_SDCARD checking this for 10033
I/SELinux ( 3806): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 3806): KNOX_SDCARD not a persona
I/SELinux ( 3806): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3806): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3806): TimaSignature is unavailable
D/ActivityThread( 3806): Added TimaKeyStore provider
D/Finsky  ( 3649): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
E/File    ( 3518): fail readDirectory() errno=2
I/Gmail   ( 3518): notifyAccountChanged
W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
I/Gmail   ( 3518): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 3518): getAccountsCursor
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 3518): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ActivityManager( 1015): Killing 2994:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
W/ContextImpl( 3720): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.bcservice, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/FileApkUtils( 1923): Spent 50ms computing apk sha1.
D/FileApkUtils( 1923): Module already staged or being staged:chimera-modules/MapsModule.apk
I/Gmail   ( 3518): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/art     ( 1923): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-ca8b2a9144773fc3650c54ed299f2d4558171b12@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
I/ActivityManager( 1015): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3831 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 3831): MountEmulatedStorage()
I/libpersona( 3831): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3831): v2
I/libpersona( 3831): KNOX_SDCARD not a persona
I/SELinux ( 3831): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/DexOptUtils( 1923): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk appears to be unoptimized.
D/DexOptUtils( 1923): Lollipop platform, using <isa> directory.
D/DexOptUtils( 1923): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 1923): Primary ABI of odexing process is armeabi-v7a
I/SELinux ( 3831): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3831): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3831): TimaSignature is unavailable
I/Gmail   ( 3518): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/ActivityThread( 3831): Added TimaKeyStore provider
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2994/cgroup.procs: No such file or directory
W/ResourcesManager( 3831): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
I/Babel   ( 3754): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3754): MmsConfig.loadMmsSettings
I/Babel   ( 3754): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 3754): MmsConfig.loadFromDatabase
E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3679): took 0.818334ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb905c5f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9064a10 counterpartCT=4 counterpartW=96 counterparth=96
I/dex2oat ( 3842): ----------------------------------------------------
I/dex2oat ( 3842): <SS>: S T A R T I N G . . .
I/dex2oat ( 3842): <SS>: Zip is absent. Canceled.
I/dex2oat ( 3842): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk --oat-fd=41 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
W/ResourcesManager( 3806): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3806): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3806): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3679): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
W/ContextImpl( 3831): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
D/ActivityManager( 1015): startService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.bcservice
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
W/ResourcesManager( 3806): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3806): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3806): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/F_PHONE ( 3831): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
W/ContextImpl( 3831): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
D/AndroidRuntime( 3826): 
D/AndroidRuntime( 3826): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/ActivityManager( 1015): bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
D/AndroidRuntime( 3826): CheckJNI is OFF
D/AndroidRuntime( 3826): readGMSProperty: start
D/AndroidRuntime( 3826): readGMSProperty: already setted!!
D/AndroidRuntime( 3826): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3826): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3826): readGMSProperty: end
D/AndroidRuntime( 3826): addProductProperty: start
W/SEAMService( 1015):  hashset_to_int_array returning null
W/SEAMService( 1015):  hashset_to_int_array returning null
E/Babel   ( 3754): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3754): MmsConfig.loadFromResources
E/SQLiteLog( 3720): (284) automatic index on seams_container_info(seams_container_id)
E/SQLiteLog( 3720): (284) automatic index on seams_container_info(sp_id)
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
E/Babel   ( 3754): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3754): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
W/Settings( 3754): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX construct_block_size_descriptor_2d second part( 3679): took 2.125573ms for 0*0 texture 0
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/GFX generate_partition_tables( 3679): took 7.455779ms for 0*0 texture 0
I/GFX raster( 3679): took 10.659165ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9061218 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9061380 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3679): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
W/SEAMService( 1015):  hashset_to_int_array returning null
I/DBG_DM  ( 2948): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
D/F_PHONE ( 3831): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 3831): default registerAction()
I/F_PHONE ( 3831): [[com.sec.bcservice]] sendPendingMessage()
W/ResourcesManager( 3806): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3806): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 3806): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/InstanceID/Rpc( 1923): Found 10012
W/art     ( 3701): Suspending all threads took: 58.166ms
E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3679): took 0.746146ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9065be8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9065d50 counterpartCT=4 counterpartW=96 counterparth=96
E/AffinityControl( 3826): AffinityControl: registerfunction enter
W/art     ( 3754): Suspending all threads took: 20.498ms
I/AMMetaDataParserService( 3679): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/AndroidRuntime( 3826): Calling main entry com.android.commands.am.Am
E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3679): took 0.971823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb90626e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9062850 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/AMMetaDataParserService( 3679): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/CustomFrequencyManagerService( 1015): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1015): mDVFSHelper.acquire()
E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3679): took 0.625625ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb90619f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9061b58 counterpartCT=4 counterpartW=96 counterparth=96
I/SurfaceFlinger(  257): id=8 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  257): id=9 createSurf (16x16),-1 flag=20004, EimLayer(An
I/AMMetaDataParserService( 3679): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
I/Babel_StickerModule( 3754): App launched.
D/FocusedStackFrame( 1015): Set to : 0
D/Launcher.HomeView( 1466): onPause
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus left window: 1466
D/Launcher( 1466): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
W/art     ( 3754): Suspending all threads took: 7.241ms
D/AndroidRuntime( 3826): Shutting down VM
E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3679): took 0.706667ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9061080 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9060f30 counterpartCT=4 counterpartW=96 counterparth=96
D/PhoneWindow( 1015): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1015): *FMB* installDecor flags : 25362712
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=10 createSurf (1x1),1 flag=404, iello
I/AMMetaDataParserService( 3679): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3874 uid=10177 gids={50177, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/Zygote  ( 3874): MountEmulatedStorage()
E/Zygote  ( 3874): v2
I/libpersona( 3874): KNOX_SDCARD checking this for 10177
I/libpersona( 3874): KNOX_SDCARD not a persona
I/SELinux ( 3874): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3874): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3874): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
V/ActivityThread( 1466): updateVisibility : ActivityRecord{13855fee token=android.os.BinderProxy@dcd0d1b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
I/GFX raster( 3679): took 0.593177ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064ab0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9064bd0 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3679): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
D/TimaKeyStoreProvider( 3874): TimaSignature is unavailable
D/ActivityThread( 3874): Added TimaKeyStore provider
V/WindowOrientationListener( 1015): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1015): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1015): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1466): onStop
V/ActivityThread( 1466): updateVisibility : ActivityRecord{13855fee token=android.os.BinderProxy@dcd0d1b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:assistant
I/AMMetaDataParserService( 3679): Resource data:2131034113
I/AMMetaDataParserService( 3679): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3679): getResourceTypeNamexml
E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3679): took 0.816719ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9044590 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb903c490 counterpartCT=4 counterpartW=96 counterparth=96
D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1015): isKioskContainerExistOnDevice
I/AMMetaDataParserService( 3679): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
V/Babel   ( 3754): babel boot account: SMS
I/art     ( 1923): WaitForGcToComplete blocked for 5.041ms for cause DisableMovingGc
W/Babel   ( 3754): EsDatabaseHelper.static should not be called on main thread [called on main thread]
D/Launcher( 1466): onTrimMemory. Level: 20
W/Babel   ( 3754): java.lang.Exception
W/Babel   ( 3754): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3754): 	at aes.<clinit>(SourceFile:95)
W/Babel   ( 3754): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3754): 	at ckh.a(SourceFile:67)
W/Babel   ( 3754): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3754): 	at bhn.a(SourceFile:301)
W/Babel   ( 3754): 	at bhn.a(SourceFile:137)
W/Babel   ( 3754): 	at bhn.a(SourceFile:126)
W/Babel   ( 3754): 	at bhn.a(SourceFile:159)
W/Babel   ( 3754): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3754): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3754): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3754): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3754): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3754): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3754): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3754): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3754): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3754): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3754): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/WindowOrientationListener( 1015):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1015): [SO] activate (ident=0xb95abcd0, enabled=0)
I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
W/Babel   ( 3754): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
W/Babel   ( 3754): java.lang.Exception
W/Babel   ( 3754): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3754): 	at aes.a(SourceFile:145)
W/Babel   ( 3754): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3754): 	at ckh.a(SourceFile:67)
W/Babel   ( 3754): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3754): 	at bhn.a(SourceFile:301)
W/Babel   ( 3754): 	at bhn.a(SourceFile:137)
W/Babel   ( 3754): 	at bhn.a(SourceFile:126)
W/Babel   ( 3754): 	at bhn.a(SourceFile:159)
W/Babel   ( 3754): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3754): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3754): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3754): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3754): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3754): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3754): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3754): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3754): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3754): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3754): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/art     ( 3826): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/SensorManager( 1015): unregisterListener ::   
I/Sensors ( 1015): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1015): [SO] changed settle time [1]
D/SensorService( 1015): [SO] setDelay [66000000]
D/SensorService( 1015): [SO] activate (ident=0xb95abcd0, enabled=1)
D/SensorService( 1015): [SO] AR_init
I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SensorManager( 1015): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.829063ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9044590 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9064cd0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/SensorService( 1015): [SO] Reset Rotation Old [100], Init [1]
,I/WebViewFactory( 3874): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.598177ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064a18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb90436a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/LibraryLoader( 3874): Time to load native libraries: 2 ms (timestamps 9597-9599)
,I/LibraryLoader( 3874): Expected native library version number "",actual native library version number ""
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
V/Babel   ( 3754): babel boot account: thalitester@gmail.com
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.616510ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9027c78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9064b00 counterpartCT=4 counterpartW=96 counterparth=96
,D/SensorService( 1015): [SO] 0.192 0.134 10.132
,D/SensorService( 1015): [SO] [100 -> 255]
,I/AMMetaDataParserService( 3679): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,V/WebViewChromiumFactoryProvider( 3874): Binding Chromium to main looper Looper (main, tid 1) {29c93eb}
,I/LibraryLoader( 3874): Expected native library version number "",actual native library version number ""
,I/chromium( 3874): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
W/Babel   ( 3754): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 3754): java.lang.Exception
W/Babel   ( 3754): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3754): 	at aes.a(SourceFile:145)
W/Babel   ( 3754): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3754): 	at ckh.a(SourceFile:67)
W/Babel   ( 3754): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3754): 	at bhn.a(SourceFile:301)
W/Babel   ( 3754): 	at bhn.a(SourceFile:137)
W/Babel   ( 3754): 	at bhn.a(SourceFile:126)
W/Babel   ( 3754): 	at bhn.a(SourceFile:159)
W/Babel   ( 3754): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3754): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3754): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3754): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3754): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3754): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3754): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3754): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3754): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3754): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3754): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/BrowserStartupController( 3874): Initializing chromium process, singleProcess=true
,W/art     ( 3874): Attempt to remove local handle scope entry from IRT, ignoring
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.821718ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9061950 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb90436a8 counterpartCT=4 counterpartW=96 counterparth=96
,E/SysUtils( 3874): ApplicationContext is null in ApplicationStatus
,W/chromium( 3874): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/AMMetaDataParserService( 3679): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/chromium( 3874): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 3874): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 3874): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk,
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,I/Adreno-EGL( 3874): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3874): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3874): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3874): Local Branch: 
I/Adreno-EGL( 3874): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3874): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3874):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.640469ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064c50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9064b00 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/Zygote  ( 3906): MountEmulatedStorage()
I/libpersona( 3906): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3906): v2
I/libpersona( 3906): KNOX_SDCARD not a persona
,I/SELinux ( 3906): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3906): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3906 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 3906): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Process ( 3806): Sending signal. PID: 3806 SIG: 9
E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3679): took 0.708177ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9061080 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb90246c0 counterpartCT=4 counterpartW=96 counterparth=96
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  282): getCameraInfo: X
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  282): getCameraInfo: X
D/BluetoothAdapter( 3874): 295950621: getState() :  mService = null. Returning STATE_OFF
,D/TimaKeyStoreProvider( 3906): TimaSignature is unavailable
,D/ActivityThread( 3906): Added TimaKeyStore provider
,W/VideoCapabilities( 3754): Unrecognized profile 2130706433 for video/avc
,I/AMMetaDataParserService( 3679): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/AudioCapabilities( 3754): Unsupported mime audio/evrc
,I/SurfaceFlinger(  257): id=6 Removed Mauncher (5/8)
I/SurfaceFlinger(  257): id=6 Removed Mauncher (-2/8)
W/AudioCapabilities( 3754): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3754): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3754): Unsupported mime audio/mpeg-L2
,I/ActivityManager( 1015): Process com.sec.android.app.sns3 (pid 3806)(adj 0) has died(198,1072)
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/chromium( 3874): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.684740ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064ab0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c8e3a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/ActivityManager( 1015): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=3934 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,W/AudioCapabilities( 3754): Unsupported mime audio/x-ms-wma
,E/Zygote  ( 3934): MountEmulatedStorage()
I/libpersona( 3934): KNOX_SDCARD checking this for 10034
E/Zygote  ( 3934): v2
I/libpersona( 3934): KNOX_SDCARD not a persona
,I/SELinux ( 3934): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/AudioCapabilities( 3754): Unsupported mime audio/x-ima,
,I/SELinux ( 3934): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3934): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
W/AudioCapabilities( 3754): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3754): Unsupported mime audio/evrc
,D/TimaKeyStoreProvider( 3934): TimaSignature is unavailable
,D/ActivityThread( 3934): Added TimaKeyStore provider
,I/art     ( 1626): Explicit concurrent mark sweep GC freed 4341(188KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 25.544ms total 744.154ms
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3679): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3679): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3679): getResourcePackageName:assistant
I/AMMetaDataParserService( 3679): Resource data:2131034112
,W/art     ( 3874): Attempt to remove local handle scope entry from IRT, ignoring
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/SQLiteConnectionPool( 1626): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/AMMetaDataParserService( 3679): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3679): getResourceTypeNamexml
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.730834ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9027c78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb90246c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2948): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec,
,E/Zygote  ( 3949): MountEmulatedStorage(),
I/libpersona( 3949): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3949): v2
I/libpersona( 3949): KNOX_SDCARD not a persona
W/AwContents( 3874): onDetachedFromWindow called when already detached. Ignoring,
I/SELinux ( 3949): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3949): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1015): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3949 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,E/SELinux ( 3949): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 3010:com.google.android.configupdater/u0a86 (adj 15): empty #31
,W/VideoCapabilities( 3754): Unsupported mime video/wvc1
,W/VideoCapabilities( 3754): Unsupported mime video/x-ms-wmv
,D/PhoneWindow( 3874): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3874): *FMB* installDecor flags : 8456448
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SystemWebViewEngine( 3874): CordovaWebView is running on device made by: samsung
,W/art     ( 3874): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3874): Attempt to remove local handle scope entry from IRT, ignoring
,D/TimaKeyStoreProvider( 3949): TimaSignature is unavailable
,D/ActivityThread( 3949): Added TimaKeyStore provider
,W/VideoCapabilities( 3754): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 3754): Unsupported mime video/wvc1
,W/VideoCapabilities( 3754): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 3754): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 3754): Unsupported mime video/x-ms-wmv8
,D/OpenGLRenderer( 3874): Render dirty regions requested: true
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,D/PhoneWindow( 3874): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3874): *FMB* isFloatingMenuEnabled return false
,W/VideoCapabilities( 3754): Unsupported mime video/mp43
,I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, NainActivit
,W/VideoCapabilities( 3754): Unsupported mime video/sorenson
,W/VideoCapabilities( 3754): Unsupported mime video/mp4v-esdp
,W/ResourcesManager( 3786): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/InputDispatcher( 1015): Focus entered window: 3874
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/SRIB_DCS( 3874): log_dcs ThreadedRenderer::initialize entered! 
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
I/OpenGLRenderer( 3874): Initialized EGL, version 1.4
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
D/OpenGLRenderer( 3874): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3874): Enabling debug mode 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/VideoCapabilities( 3754): Unsupported profile 4 for video/mp4v-es
,D/GCM     ( 1923): COMPAT: Multi user not supported
,W/libprocessgroup( 1015): failed to open /acct/uid_10086/pid_3010/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
I/CheckinService( 1923): Checkin interval check for package: unspecified last checkin: 1450010279118 min interval config: 0 actual interval: 179027150
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1746): COMPAT: Multi user not supported
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/KnoxSetupWizardDbHelper( 3949): dbMigrationFlag : false
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ResourcesManager( 3786): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3786): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3786): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1923): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline( 3874): Timeline: Activity_idle id: android.os.BinderProxy@2b1d07b6 time:40319
,D/PanelView( 1178): There is/are notification(s) 
,D/ShortcutReceiver( 3949):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.703855ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9027c78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9064b00 counterpartCT=4 counterpartW=96 counterparth=96
,I/SamsungIME( 1764): getCurrentCandidateView
,I/AMMetaDataParserService( 3679): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,I/ActivityManager( 1015): Displayed Component not be shown by security: +1s28ms
,D/CustomFrequencyManagerService( 1015): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  tag : ACTIVITY_RESUME_BOOSTER@7
,D/CustomFrequencyManagerService( 1015): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  pkgName : ACTIVITY_RESUME_BOOSTER@11
,W/ActivityManager( 1015): mDVFSHelper.release()
I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{146fea2d u0 com.example.hello/.MainActivity t2} time:40344
,D/KnoxShortcutUtil( 3949): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 3949):  KnoxContainerVersion 2.4.0
,D/ShortcutReceiver( 3949):  shortcut migration not required 
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/CheckinService( 1923): Disabling old GoogleServicesFramework version
,E/Zygote  ( 3983): MountEmulatedStorage(),
E/Zygote  ( 3983): v2
I/libpersona( 3983): KNOX_SDCARD checking this for 1000,
I/libpersona( 3983): KNOX_SDCARD not a persona
,I/SELinux ( 3983): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/SELinux ( 3983): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3983 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,E/SELinux ( 3983): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 3064:com.policydm/1000 (adj 15): empty #31
,D/ChimeraCfgMgr( 1923): Reading stored module config
,D/TimaKeyStoreProvider( 3983): TimaSignature is unavailable
,D/ActivityThread( 3983): Added TimaKeyStore provider
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.773334ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064d50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9064cd0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,D/ChimeraCfgMgr( 1923): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/BootCompletedReceiver( 1923): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 1923): Got an BootCompleted event.
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4001): MountEmulatedStorage()
,I/libpersona( 4001): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4001): v2
,I/libpersona( 4001): KNOX_SDCARD not a persona
I/SELinux ( 4001): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4001): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4001): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4001 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 3086:com.dropbox.android/u0a92 (adj 15): empty #31
,D/BootCompletedReceiver( 1923): Will NOT schedule AdAttestation signal task because it's disabled.
,D/SystemUpdateService( 1923): onCreate
,D/TimaKeyStoreProvider( 4001): TimaSignature is unavailable
,D/ActivityThread( 4001): Added TimaKeyStore provider
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.628959ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064c50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9064b50 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3064/cgroup.procs: No such file or directory
,E/KnoxSetupWizardClient( 3983): isShipMode : 1
I/KnoxSetupWizardClient( 3983): onReceive : android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,I/SurfaceFlinger(  257): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  257): id=10 Removed iello (-2/8)
,W/BindingManager( 3874): Cannot call determinedVisibility() - never saw a connection for the pid: 3874
,I/System.out( 3701): INFO:Resource not found:/Common.properties Using default values
,D/CustomFrequencyManagerService( 1015): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  tag : ACTIVITY_RESUME_BOOSTER@11
,I/chromium( 3874): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/libprocessgroup( 1015): failed to open /acct/uid_10092/pid_3086/cgroup.procs: No such file or directory
,E/SMD     (  287): DCD OFF
,I/CheckinService( 1923): Checking schedule, now: 1450189306682 next: 1450549542000
,I/CheckinService( 1923): active receiver: disabled
,D/SystemUpdateService( 1923): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4028): MountEmulatedStorage()
I/libpersona( 4028): KNOX_SDCARD checking this for 10107
E/Zygote  ( 4028): v2
I/libpersona( 4028): KNOX_SDCARD not a persona
,I/SELinux ( 4028): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4028 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 3026:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activit,ycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:assistant
I/AMMetaDataParserService( 3679): Resource data:2131034113
I/AMMetaDataParserService( 3679): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 3679): getResourceTypeNamexml
E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.825677ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9044590 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb90246c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 4028): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4028): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/System.err( 3983): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 3983): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 3983): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3983): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
W/System.err( 3983): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
W/System.err( 3983): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3983): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/art     (  304): Explicit concurrent mark sweep GC freed 8753(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 30.283ms,
,I/AMMetaDataParserService( 3679): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.844531ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9044590 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9064b50 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 26.916ms
V/AuthZen ( 1923): Handling intent: android.intent.action.BOOT_COMPLETED
,D/TimaKeyStoreProvider( 4028): TimaSignature is unavailable
D/ActivityThread( 4028): Added TimaKeyStore provider
,W/dex2oat ( 3842): Verification of boolean com.google.android.gms.common.mx.b(android.content.pm.PackageInfo, boolean) took 175.430ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 609us total 17.620ms
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.610260ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064a18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb90246c0 counterpartCT=4 counterpartW=96 counterparth=96
,W/dex2oat ( 3842): Verification of boolean com.google.android.gms.maps.b.e.onTransact(int, android.os.Parcel, android.os.Parcel, int) took 113.711ms
,I/AMMetaDataParserService( 3679): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.600989ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9027c78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb90436a8 counterpartCT=4 counterpartW=96 counterparth=96
,D/JsMessageQueue( 3874): Set native->JS mode to OnlineEventsBridgeMode
,I/AMMetaDataParserService( 3679): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/dex2oat ( 3842): Verification of void com.google.android.gms.maps.internal.bq.a(com.google.android.gms.a.a) took 120.559ms
,D/AuthZenEventHandler( 1923): Handling event: android.intent.action.BOOT_COMPLETED
,E/AndroidProtocolHandler( 3874): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.849219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9061950 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9064cd0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/SystemUpdateService( 1923): cancelUpdate (empty URL)
I/SystemUpdateService( 1923): active receiver: disabled
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 35870(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/39MB, paused 2.446ms total 162.448ms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 3518): getAccountsCursor
,D/SecurityLogAgent:SEDenialService( 1015): Got CLOSE_WRITE Event sk.log
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1015): failed to open /acct/uid_10057/pid_3026/cgroup.procs: No such file or directory
,D/SecurityLogAgent:SEDenialService( 1015): Got CLOSE_WRITE Event sk.log
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,W/dex2oat ( 3842): Verification of boolean com.google.android.gms.maps.internal.db.onTransact(int, android.os.Parcel, android.os.Parcel, int) took 221.558ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/dex2oat ( 3842): Verification of boolean com.google.android.gms.maps.internal.j.onTransact(int, android.os.Parcel, android.os.Parcel, int) took 201.961ms
,E/SQLiteLog( 3754): (284) automatic index on conversation_participants_view(conversation_id)
,I/DBG_POLICYDM( 4001): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 4001): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_DM  ( 2948): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,W/dex2oat ( 3842): Verification of boolean com.google.android.gms.maps.model.a.m.onTransact(int, android.os.Parcel, android.os.Parcel, int) took 111.133ms
,D/jxcore_app_log( 3874): JniHelper::setJavaVM(0xb8c87450), pthread_self() = -1189276528,
D/JX-Cordova( 3874): jxcore cordova android initializing,
,E/SQLiteLog( 3754): (284) automatic index on conversation_participants_view(conversation_id)
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,E/SQLiteLog( 3754): (284) automatic index on conversation_participants_view(conversation_id)
,W/BaseAppContext( 1923): Using Auth Proxy for data requests.
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.646406ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064c50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9064b00 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,W/jxcore-log( 3874): Initializing JXcore engine
,W/jxcore-log( 3874): JXcore engine is ready
E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,I/GFX raster( 3679): took 0.763072ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9061080 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9064b50 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1015): SIOP:: AP = 360
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/dex2oat ( 3842): Verification of void com.google.android.gms.signin.internal.l.a(com.google.android.gms.signin.internal.d) took 107.716ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/jxcore-log( 3874): Starting JXcore engine
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/dex2oat ( 3842): Verification of long com.google.d.a.a.b.a.a(java.io.InputStream, boolean, com.google.d.a.a.b.b) took 104.095ms
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3679): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/SQLiteLog( 3754): (284) automatic index on conversation_participants_view(conversation_id)
,I/DBG_POLICYDM( 4001): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 4001): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,E/SQLiteLog( 3754): (284) automatic index on conversation_participants_view(conversation_id)
,D/PackageManager( 1015): [MSG] MCS_UNBIND
,E/audit   ( 1922): type=1400 msg=audit(1450189307.293:203): avc:  denied  { ioctl } for  pid=3874 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1922):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1922): type=1300 msg=audit(1450189307.293:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=bea64d58 items=0 ppid=304 ppcomm=main pid=3874 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1922): type=1320 msg=audit(1450189307.293:203): 
,I/ActivityManager( 1015): Killing 3171:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 3186:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.542656ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064ab0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb90246c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3679): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
W/ContextImpl( 3679): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,I/DBG_POLICYDM( 4001): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,W/art     ( 3701): Suspending all threads took: 446.046ms
,W/dex2oat ( 3842): Verification of void com.google.h.a.i.a(byte[], java.lang.StringBuffer) took 147.649ms
,W/dex2oat ( 3842): Verification of int com.google.h.a.a.a(java.lang.CharSequence) took 181.347ms
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/jxcore-log( 3874): Platform android
W/jxcore-log( 3874): 
,W/jxcore-log( 3874): Process ARCH arm
W/jxcore-log( 3874): 
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:assistant
I/AMMetaDataParserService( 3679,): Resource data:2131165203
,E/BaseAppContext( 1923): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/DBG_POLICYDM( 4001): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/jxcore-log( 3874): JXcore Cordova bridge is ready!
I/jxcore-log( 3874): 
,W/jxcore-log( 3874): JXcore engine is started
,W/ResourcesManager( 3679): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3679): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3679): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3679): getResourceName:com.android.email:xml/email_assistant_menu
,I/AMMetaDataParserService( 3679): getResourceTypeNamexml
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3679): took 2.545052ms for 0*0 texture 0
,W/dex2oat ( 3842): Verification of int com.google.k.a.a.a.a.d.hashCode() took 115.546ms
,E/jxcore-log( 3874): >> samsung-SM-A500FU
E/jxcore-log( 3874): 
,I/jxcore-log( 3874): Total memory 1983791104
I/jxcore-log( 3874): 
,I/jxcore-log( 3874): Free memory 150491136
I/jxcore-log( 3874): 
,I/jxcore-log( 3874): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3874): 
I/jxcore-log( 3874): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3874): 
,I/GFX generate_partition_tables( 3679): took 10.343230ms for 0*0 texture 0
,I/GFX raster( 3679): took 13.720051ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9214960 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9214a98 counterpartCT=4 counterpartW=96 counterparth=96
,I/jxcore-log( 3874): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 3874): 
,I/AMMetaDataParserService( 3679): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
I/jxcore-log( 3874): Size 720 1280
I/jxcore-log( 3874): 
,I/jxcore-log( 3874): Screen Brightness 5
I/jxcore-log( 3874): 
,E/jxcore-log( 3874): Dummy Error Log.
E/jxcore-log( 3874): 
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.778385ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb90327c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9032870 counterpartCT=4 counterpartW=96 counterparth=96
,D/SamsungIME( 1764): Dismiss ExpandCandiate
,I/AMMetaDataParserService( 3679): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 1.536302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb90327c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8c8ee90 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,I/DBG_POLICYDM( 4001): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
W/libprocessgroup( 1015): failed to open /acct/uid_10092/pid_3186/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10003/pid_3171/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 4001): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 4001): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 4001): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,D/SystemUpdateService( 1923): onDestroy
,I/DBG_POLICYDM( 4001): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.847187ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb90327c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8c8ee90 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,I/DBG_POLICYDM( 4001): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.700729ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064d50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9064c50 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,I/art     ( 1626): Explicit concurrent mark sweep GC freed 3691(142KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 890us total 33.649ms
,I/GCoreUlr( 1746): DispatchingService.onCreate()
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.596875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064d50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c8ee90 counterpartCT=4 counterpartW=96 counterparth=96
,D/GCM     ( 1746): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/EnterpriseController(  275): uids 10012
D/EnterpriseController(  275): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  275): getNetworkForDns: using netid 0 for uid 10012
,I/AMMetaDataParserService( 3679): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:android.app.searchable
W/ContextImpl( 3679): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3679): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,E/Zygote  ( 4080): MountEmulatedStorage()
,E/Zygote  ( 4080): v2
I/libpersona( 4080): KNOX_SDCARD checking this for 10035
I/libpersona( 4080): KNOX_SDCARD not a persona
,I/SELinux ( 4080): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4080 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1015): Killing 3218:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,I/SELinux ( 4080): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SELinux ( 4080): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 3236:com.fmm.dm/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3679): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3679): getResourcePackageName:assistant
I/AMMetaDataParserService( 3679): Resource data:2131099648
,I/GCoreUlr( 1746): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/AuthZen ( 1923): Fetching signing key...
,D/TimaKeyStoreProvider( 4080): TimaSignature is unavailable
,D/ActivityThread( 4080): Added TimaKeyStore provider
,W/ResourcesManager( 3679): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3679): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3679): getResourceTypeNamexml
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3236/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10060/pid_3218/cgroup.procs: No such file or directory
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.971354ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb905c348 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb904a230 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/AuthZen ( 1923): Signing key fetched successfully!
,I/art     ( 1746): Explicit concurrent mark sweep GC freed 25282(1732KB) AllocSpace objects, 21(336KB) LOS objects, 40% free, 12MB/20MB, paused 1.611ms total 91.581ms
,I/DBG_POLICYDM( 4001): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,W/BaseAppContext( 1923): Using Auth Proxy for data requests.
,I/DBG_POLICYDM( 4001): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 4001): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,I/DBG_DM  ( 2948): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/DBG_POLICYDM( 4001): [com.policydm.agent.XDMTask(173/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,I/GFX construct_block_size_descriptor_2d second part( 3679): took 2.716979ms for 0*0 texture 0
,W/Auth    ( 1746): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/GFX generate_partition_tables( 3679): took 9.104635ms for 0*0 texture 0
,I/GFX raster( 3679): took 12.989010ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb904c470 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb904c518 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/GCoreFlp( 1746): No location to return for getLastLocation()
,W/FusedLocationProvider( 1746): location=null
,I/jxcore-log( 3874): getBuffer is called!!!!
I/jxcore-log( 3874): 
,E/SPPClientService( 4080): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4080): [PushClientApplication] Push log off : This is Ship build version
,D/a       ( 1923): Opening database auth.proximity.permit_store...
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 3679): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/AuthZenTransactionCache( 1923): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1923): Clearing transaction cache
,E/SPPClientService( 4080): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,W/GCoreFlp( 1746): No location to return for getLastLocation()
,W/FusedLocationProvider( 1746): location=null
,D/StrictMode( 4028): StrictMode policy violation; ~duration=1093 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4028): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4028): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4028): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4028): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4028): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4028): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4028): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4028): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 4028): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4028): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4028): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4028): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4028): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4028): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4028): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4028): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4028): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4028): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4028): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4028): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4028): StrictMode policy violation; ~duration=1071 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4028): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4028): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4028): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4028): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4028): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4028): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4028): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4028): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4028): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4028): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4028): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4028): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4028): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4028): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4028),: 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4028): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4028): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4028): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4028): StrictMode policy violation; ~duration=963 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4028): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4028): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4028): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4028): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4028): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4028): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4028): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 4028): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4028): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4028): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4028): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4028): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4028): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4028): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4028): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4028): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4028): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4028): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4028): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4028): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4028): StrictMode policy violation; ~duration=962 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4028): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4028): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4028): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4028): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4028): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4028): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4028): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4028): 	at android.app.Instrumentation.callApplicationOnCreate(Instru,mentation.java:1020)
D/StrictMode( 4028): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4028): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4028): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4028): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4028): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4028): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4028): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4028): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4028): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4028): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4028): StrictMode policy violation; ~duration=961 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4028): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4028): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4028): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4028): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4028): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4028): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4028): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4028): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4028): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4028): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4028): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4028): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4028): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4028): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4028): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4028): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4028): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4028): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4028): StrictMode policy violation; ~duration=958 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4028): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4028): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4028): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4028): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4028): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4028): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4028): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4028): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 4028): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 4028): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4028): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4028): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4028): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4028): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4028): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4028): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4028): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4028): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4028): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4028): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4028): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4028): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4028): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4028): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4028): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4028): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4028): StrictMode policy violation; ~duration=956 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4028): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4028): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4028): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4028): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4028): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4028): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4028): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4028): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 4028): 	at com.google.r.k.c(PG:583)
D/StrictMode( 4028): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 4028): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4028): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4028): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4028): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4028): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4028): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4028): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4028): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4028): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4028): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4028): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4028): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4028): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4028): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4028): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4028): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4028): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4028): StrictMode policy violation; ~duration=914 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4028): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4028): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4028): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4028): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4028): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4028): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4028): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 4028): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 4028): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4028): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4028): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4028): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4028): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4028): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4028): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4028): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4028): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4028): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4028): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4028): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4028): StrictMode policy violation; ~duration=913 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4028): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4028): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4028): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4028): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 4028): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4028): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4028): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4028): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4028): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4028): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4028): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4028): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4028): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4028): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4028): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4028): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4028): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/SPPClientService( 4080): PushLog.txt file is not deleted.
D/SPPClientService( 4080): PushLog.txt file is not deleted.
D/SPPClientService( 4080): ============PushLog. stop!
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/SamsungIME( 1764): getDebugLevel  : 0x4f4c
E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3679): took 0.789948ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb955c2b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb955c358 counterpartCT=4 counterpartW=96 counterparth=96
E/Zygote  ( 4106): MountEmulatedStorage()
E/Zygote  ( 4106): v2
I/libpersona( 4106): KNOX_SDCARD checking this for 1000
I/libpersona( 4106): KNOX_SDCARD not a persona
I/SELinux ( 4106): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4106): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4106 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 4106): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 3279:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,I/AMMetaDataParserService( 3679): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.808802ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb955d820 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb955d958 counterpartCT=4 counterpartW=96 counterparth=96
,D/PersistentNotificationBroadcastReceiver( 1746): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3679): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4106): TimaSignature is unavailable
,D/ActivityThread( 4106): Added TimaKeyStore provider
,I/SamsungIME( 1764): getDebugLevel  : 0x4f4c
,W/libprocessgroup( 1015): failed to open /acct/uid_10062/pid_3279/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1746): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/SamsungIME( 1764): KeybaordView init() : load resources
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.636615ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb95605d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9560708 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4124): MountEmulatedStorage()
E/Zygote  ( 4124): v2
I/libpersona( 4124): KNOX_SDCARD checking this for 10041
I/libpersona( 4124): KNOX_SDCARD not a persona
,I/SELinux ( 4124): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4124 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 4124): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4124): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 3299:com.fmm.ds/1000 (adj 15): empty #31
,I/SamsungIME( 1764): getCurrentKeyboard
I/SamsungIME( 1764): getTextKeyboard
,I/GCoreUlr( 1746): Unbound from all location providers
,I/GCoreUlr( 1746): Place inference reporting - stopped
,D/StatusChecker( 4106): onReceive : android.intent.action.BOOT_COMPLETED
,D/TimaKeyStoreProvider( 4124): TimaSignature is unavailable
D/ActivityThread( 4124): Added TimaKeyStore provider
,W/dex2oat ( 3842): Verification of void com.google.maps.api.android.lib6.gmm6.m.cv.f() took 119.822ms
,V/AlarmManager( 1015): waitForAlarm result :4
,I/StatusChecker( 4106): onReceive : net.mt.init : DONE
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/GFX raster( 3679): took 0.795521ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb904b1b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb904b2f0 counterpartCT=4 counterpartW=96 counterparth=96
,D/SamsungIME( 1764): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/AMMetaDataParserService( 3679): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,E/Zygote  ( 4142): MountEmulatedStorage(),
,E/Zygote  ( 4142): v2,
I/libpersona( 4142): KNOX_SDCARD checking this for 10116,
I/SELinux ( 4142): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4142): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4142 uid=10116 gids={50116, 9997} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 3330:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31,
I/SELinux ( 4142): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 4142): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:assistant
I/AMMetaDataParserService( 3679): Resource data:2131099648
,I/GCoreUlr( 1746): DispatchingService.onDestroy()
I/GCoreUlr( 1746): Stopping handler for UlrDispSvcFast
,I/AMMetaDataParserService( 3679): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3679): getResourceTypeNamexml
E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.682135ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb905c348 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9065b68 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,I/GCoreUlr( 1746): Unbound from all location providers
,I/GCoreUlr( 1746): Place inference reporting - stopped
,I/AMMetaDataParserService( 3679): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/dex2oat ( 3842): Verification of com.google.maps.api.android.lib6.gmm6.streetview.ac com.google.maps.api.android.lib6.gmm6.streetview.a.a(int, int, float, float, int, float, float, float, float, boolean) took 113.203ms
,D/TimaKeyStoreProvider( 4142): TimaSignature is unavailable
,D/ActivityThread( 4142): Added TimaKeyStore provider
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.633750ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9032790 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb9056fe8 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3299/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3330/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3679): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/iu.UploadsManager( 1923): End new media; added: 0, uploading: 0, time: 93 ms
,W/dex2oat ( 3842): Verification of void com.google.maps.api.android.lib6.gmm6.streetview.bg.a(long) took 110.732ms
,I/PageBuddyNotiSvc( 4142): Intent received : action=android.intent.action.BOOT_COMPLETED
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.750885ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9061950 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9061900 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/art     ( 3701): Suspending all threads took: 18.517ms
,I/GAV2    ( 3518): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl( 4142): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,I/PageBuddyNotiSvc( 4142): onCreate mCpBitFlag=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4164 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/Zygote  ( 4164): MountEmulatedStorage()
E/Zygote  ( 4164): v2
I/libpersona( 4164): KNOX_SDCARD checking this for 10125
I/libpersona( 4164): KNOX_SDCARD not a persona
,I/SELinux ( 4164): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4164): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4164): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SecDataIO(  256): Write to block,
,D/TimaKeyStoreProvider( 4164): TimaSignature is unavailable
,D/ActivityThread( 4164): Added TimaKeyStore provider
,W/ContextImpl( 2518): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,I/DBG_DM  ( 2948): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 2948): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,E/DBG_DM  ( 2948): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.764687ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064b50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9064cd0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4164): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4164): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4164): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/Process ( 2518): Sending signal. PID: 2518 SIG: 9
,I/SA      ( 4124): [SSP] onCreated
,I/DBG_DM  ( 2948): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,I/AMMetaDataParserService( 3679): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.632031ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9214240 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9043b48 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.834426ms for 96*96 texture 0
I/ActivityManager( 1015): Process com.sec.android.app.sysscope (pid 2518)(adj 0) has died(119,1102)
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064d50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9016430 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/QuickConnect( 4164): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,I/SA      ( 4124): [TPM] There is no property file
,D/QuickConnect( 4164): Util.setSCRunningSetting - [value]0
,I/SA      ( 4124): [SCU] isHaveSA() - false
,D/SettingsProvider( 1015): name = scon_is_running
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10125
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/com.google.a.a.b.d.a( 4028): Application name is not set. Call Builder#setApplicationName.
,I/SA      ( 4124): [TPM] getModelProperty : null
,I/SA      ( 4124): [TPM] getCSCProperty : null
,I/SA      ( 4124): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4124): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4124): [DM] TFT FEATURE: false
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:assistant
I/AMMetaDataParserService( 3679): Resource data:2131099648
,I/SA      ( 4124): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/AMMetaDataParserService( 3679): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3679): getResourceTypeNamexml
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/SA      ( 4124): [DM] init START
,I/GFX raster( 3679): took 0.901771ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb905c348 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9044480 counterpartCT=4 counterpartW=96 counterparth=96
,I/QuickConnect( 4164): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/QuickConnect( 4164): PeriphStartReceiver.onReceive - no need to start
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/dex2oat ( 3842): dex2oat took 4.041s (threads: 4)
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3679): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523,
,D/DexOptUtils( 1923): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.dex
D/DexOptUtils( 1923): Set odex to world readable.
D/DexOptUtils( 1923): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.odex
I/SA      ( 4124): [DM] This device is not a Vodafone
D/FileApkUtils( 1923): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12,
,E/Zygote  ( 4181): MountEmulatedStorage(),
I/libpersona( 4181): KNOX_SDCARD checking this for 10131
E/Zygote  ( 4181): v2
I/libpersona( 4181): KNOX_SDCARD not a persona
,I/SELinux ( 4181): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4181 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 3371:com.wssnps/1000 (adj 15): empty #31
I/SELinux ( 4181): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4181): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/ResourceType( 4124): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4124): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4124): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4124): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4124): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4124): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4124): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4124): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4124): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75),
W/ResourceType( 4124): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4124): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 4124): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 4124): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 4124): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 4124): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4124): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75),
D/GmsModuleFndr( 1923): Beginning GMS chimera module scan
W/ResourceType( 4124): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 4124): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4124): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75),
W/ResourceType( 4124): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 4124): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 4124): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4124): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 4124): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75),
W/ResourceType( 4124): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,D/TimaKeyStoreProvider( 4181): TimaSignature is unavailable
,D/ActivityThread( 4181): Added TimaKeyStore provider
,I/SA      ( 4124): [SCU] isHaveSA() - false
I/SA      ( 4124): support phone number id : false
,I/SA      ( 4124): [DM] Supports Ref Jpn : true
,I/SA      ( 4124): [DM] init END
,D/GmsModuleFndr( 1923): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping,
,D/ChimeraCfgMgr( 1923): Beginning module configuration check
D/ChimeraCfgMgr( 1923): Module APKs unchanged, check complete
E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3679): took 0.639063ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9032790 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb90246c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4124): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 4124): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,I/ActivityManager( 1015): Killing 3357:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,D/ActivityManager( 1015): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/AMMetaDataParserService( 3679): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/DBG_DM  ( 2948): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,I/SA      ( 4124): [OR] onReceive END
,I/DBG_DM  ( 2948): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4181): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4181): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4181): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/DBG_DM  ( 2948): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
W/ResourcesManager( 4181): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.790469ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9061950 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9064ab0 counterpartCT=4 counterpartW=96 counterparth=96,
,E/DBG_DM  ( 2948): [IlIIlIIlIllllIlllIII(226/llIIIIlllllIIllIIllI)] Network Status is not ready. DM Not Initialized
,I/SA      ( 4124): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/ActivityManager( 1015): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4197 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SA      ( 4124): [ODM] queryOpenData(key= GEO_IP )
I/AMMetaDataParserService( 3679): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
I/DBG_DM  ( 2948): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,E/Zygote  ( 4197): MountEmulatedStorage(),
E/Zygote  ( 4197): v2
I/SA      ( 4124): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4124): [LBE] REF_JPN : true,
I/SA      ( 4124): [BDC] create
I/libpersona( 4197): KNOX_SDCARD checking this for 10042
,I/libpersona( 4197): KNOX_SDCARD not a persona
,I/SELinux ( 4197): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4197): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/SELinux ( 4197): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/GFX raster( 3679): took 0.666510ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064b50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9043b48 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3679): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/libprocessgroup( 1015): failed to kill pid 3357: No such process
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3371/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10094/pid_3357/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4197): TimaSignature is unavailable
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ActivityThread( 4197): Added TimaKeyStore provider
I/GFX raster( 3679): took 0.660104ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9214240 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9064bd0 counterpartCT=4 counterpartW=96 counterparth=96
,D/SBrowserFeatureFlag( 4181): initialized in static block : loadCscFeatureValue() succeed! 
,I/AMMetaDataParserService( 3679): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/SA      ( 4124): [DBMV2] getEmailID
,I/SA      ( 4124): [DBMV2] getDataV02ForItems
I/SA      ( 4124): [SSP] query invoked
,W/ResourcesManager( 4197): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/SA      ( 4124): [SCU] get signed id from samsung account2.0 DB.
,D/ManifestProvider( 4181): onCreate()
,I/SA      ( 4124): [SCU] get signed id from samsung account1.0 DB.
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.722083ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064d50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb90246c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4124): [BDC] destroy
,I/ActivityManager( 1015): Killing 3126:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,I/AMMetaDataParserService( 3679): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,E/NetworkSettingsReceiver( 4181): onReceive: android.intent.action.BOOT_COMPLETED
,E/SBrowserFeatureFlag( 4181): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@38587792
,D/SBrowserFeatureFlag( 4181): initialize : initSupportedPkg() succeed! 
I/CalendarProvider2( 4197): CalendarProvider2.onCreate() called
,I/VerificationLog( 4181): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
,I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3679): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3679): Resource data:2131099648
I/AMMetaDataParserService( 3679): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3679): getResourceTypeNamexml
E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.685208ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb905c348 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9064b00 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/Zygote  ( 4217): MountEmulatedStorage()
,E/Zygote  ( 4217): v2
I/libpersona( 4217): KNOX_SDCARD checking this for 10135
I/libpersona( 4217): KNOX_SDCARD not a persona
I/SELinux ( 4217): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4217): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4217): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GFX raster( 3679): took 0.744220ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9032790 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb9064ab0 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3679): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.656770ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9061950 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8c7c0b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1015): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4217 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 3419:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,I/AMMetaDataParserService( 3679): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/TimaKeyStoreProvider( 4217): TimaSignature is unavailable
,D/ActivityThread( 4217): Added TimaKeyStore provider
,W/ResourcesManager( 4217): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4217): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ResourcesManager( 4217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/GFX raster( 3679): took 0.661771ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064b50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9044480 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.699843ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9214240 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9016430 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1015): failed to open /acct/uid_10009/pid_3126/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3679): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/daemonapp( 1347): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.716041ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064d50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9062598 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/libprocessgroup( 1015): failed to open /acct/uid_10014/pid_3419/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:assistant
I/AMMetaDataParserService( 3679): Resource data:2131099648
,I/AMMetaDataParserService( 3679): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3679): getResourceTypeNamexml
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.721250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb905c348 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9043b48 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,I/AMMetaDataParserService( 3679): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3679): took 0.786250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9032790 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb9064b00 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.621562ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9061950 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9062598 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/ActivityManager( 1015): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.641666ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064b50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9064bd0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3679): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/SamsungIME( 1764): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/CalendarProvider2( 4197): CalendarProvider2.onCreate() called
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/Zygote  ( 4243): MountEmulatedStorage()
E/Zygote  ( 4243): v2
I/libpersona( 4243): KNOX_SDCARD checking this for 10139
I/libpersona( 4243): KNOX_SDCARD not a persona
I/GFX raster( 3679): took 0.659375ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9214240 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9056ee8 counterpartCT=4 counterpartW=96 counterparth=96
I/SELinux ( 4243): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4243 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/SELinux ( 4243): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4243): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3679): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/TimaKeyStoreProvider( 4243): TimaSignature is unavailable
,D/ActivityThread( 4243): Added TimaKeyStore provider
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.781250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064d50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c7c0b8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4243): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4243): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4243): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4243): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,W/ResourcesManager( 4243): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3679): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:assistant
I/AMMetaDataParserService( 3679): Resource data:2131099648
,I/AMMetaDataParserService( 3679): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3679): getResourceTypeNamexml
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.708542ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb905c348 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb90436a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/ActivityManager( 1015): Killing 3437:com.sec.factory.camera/1000 (adj 15): empty #31
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.656198ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9032790 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb9065830 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4263): MountEmulatedStorage()
E/Zygote  ( 4263): v2
I/libpersona( 4263): KNOX_SDCARD checking this for 10145
I/libpersona( 4263): KNOX_SDCARD not a persona
,I/SELinux ( 4263): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4263): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4263 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/SELinux ( 4263): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3679): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.638698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9061950 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9064cd0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/TimaKeyStoreProvider( 4263): TimaSignature is unavailable
,D/ActivityThread( 4263): Added TimaKeyStore provider
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.635730ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064b50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9064ab0 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3437/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3679): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.859323ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9214240 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9016430 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/SMD     (  287): DCD OFF
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.763854ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9064d50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9044480 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
W/ContextImpl( 3679): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3679): Resource data:Loop ,for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3679): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:android.app.default_searchable
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity,
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 26182(1515KB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 26MB/39MB, paused 2.119ms total 136.462ms
,W/ResourcesManager( 4263): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4263): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4263): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4263): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4263): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 1015): Killing 3464:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:assistant
I/AMMetaDataParserService( 3679): Resource data:2131165197
,W/ResourcesManager( 3679): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3679): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3679): getResourceTypeNamexml
I/AMMetaDataParserService( 3679): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3679): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3679): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/libprocessgroup( 1015): failed to open /acct/uid_10100/pid_3464/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3679): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
,I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 3679): getResourcePackageName:assistant
I/AMMetaDataParserService( 3679): Resource data:2131165197
,I/AMMetaDataParserService( 3679): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3679): getResourceTypeNamexml
,I/AMMetaDataParserService( 3679): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3679): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3679): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3679): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:assistant
I/AMMetaDataParserService( 3679): Resource data:2131165197
,I/AMMetaDataParserService( 3679): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3679): getResourceTypeNamexml
,I/AMMetaDataParserService( 3679): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3679): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3679): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3679): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
,I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
W/ContextImpl( 3679): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartM,msSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
,I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3679): getResourcePackageName:assistant
I/AMMetaDataParserService( 3679): Resource data:2131099648
,W/ResourcesManager( 3679): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3679): getResourceName:com.sec.android.app.camera:xml/assistant
,I/AMMetaDataParserService( 3679): getResourceTypeNamexml
,I/AMMetaDataParserService( 3679): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId,
I/AMMetaDataParserService( 3679): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,E/Zygote  ( 4286): MountEmulatedStorage()
,E/Zygote  ( 4286): v2
I/libpersona( 4286): KNOX_SDCARD checking this for 10072
I/libpersona( 4286): KNOX_SDCARD not a persona
,I/SELinux ( 4286): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4286): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4286): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4286 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
W/ContextImpl( 3679): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,I/art     (  304): Explicit concurrent mark sweep GC freed 8690(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 19.800ms,
,D/ActivityManager( 1015): startService callerProcessName:com.android.email, calleePkgName: com.android.email
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,D/TimaKeyStoreProvider( 4286): TimaSignature is unavailable
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 16.898ms
,D/ActivityThread( 4286): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 627us total 16.688ms
,D/BadgeProvider( 4286): onCreate
,D/BadgeProvider( 4286): DatabaseHelper
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.exchange, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 4286): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/Zygote  ( 4307): MountEmulatedStorage()
E/Zygote  ( 4307): v2
I/libpersona( 4307): KNOX_SDCARD checking this for 10146
I/libpersona( 4307): KNOX_SDCARD not a persona
,I/SELinux ( 4307): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4307): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4307 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.GridSettings,
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:assistant
I/AMMetaDataParserService( 3679): Resource data:2131165220
E/SELinux ( 4307): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 3105:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 3396:com.samsung.android.sm/1000 (adj 15): empty #32
W/ResourcesManager( 3679): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3679): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3679): getResourceTypeNamexml
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.705833ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb975f830 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb975f560 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,D/Launcher.Model( 1466): reloadBadges entered.
D/BadgeProvider( 4286): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4286): sendNotify, [notify] : null
D/BadgeProvider( 4286): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4286): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4286): update, [UpdateCount] : 1
,D/TimaKeyStoreProvider( 4307): TimaSignature is unavailable
,D/ActivityThread( 4307): Added TimaKeyStore provider
,E/        ( 3679): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3679): took 0.612813ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3679): Bitmap=0xb9761778 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb97618b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3679): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,W/ResourcesManager( 4307): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings,.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE,
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings,
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS,
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
,I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$NearbySetti,ngsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check,
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
W/ContextImpl( 3679): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
W/ActivityManager( 1015): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED,
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
I/ActivityManager( 1015): Killing 3501:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
,I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.DisplaySettings
,I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.RunningServices
,I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
,I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
,I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SecuritySettings
,I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
W/ActivityManager( 1015): getTasks: caller 10145 does not hold GET_TASKS; limiting output
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
,I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.AppPicker
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.UsbSettings
,I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
,I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.BandMode
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
,I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
,I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3396/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,W/libprocessgroup( 1015): failed to open /acct/uid_10015/pid_3105/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
,I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
,I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ModePreview
,I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
,I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
D/ActivityManager( 1015): startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3679): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3679): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3679): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
I/Process ( 4263): Sending signal. PID: 4263 SIG: 9
D/RCPManagerService( 1015): exchangeData() failure , invalid userId
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,E/Zygote  ( 4325): MountEmulatedStorage()
I/libpersona( 4325): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4325): v2
I/libpersona( 4325): KNOX_SDCARD not a persona
I/SELinux ( 4325): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4325): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4325 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 4325): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3501/cgroup.procs: No such file or directory
E/lowmemorykiller(  254): Error opening /proc/4263/oom_score_adj; errno=2
I/ActivityManager( 1015): Process com.android.email (pid 4263)(adj 0) has died(110,1126)
I/ActivityThread( 4307): Removing dead content provider:android.content.ContentProviderProxy@7c61fe1
I/ActivityThread( 4307): Removing dead content provider:android.content.ContentProviderProxy@7c61fe1
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.exchange, calleePkgName: com.android.email
D/TimaKeyStoreProvider( 4325): TimaSignature is unavailable
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 4325): Added TimaKeyStore provider
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4340): MountEmulatedStorage()
I/libpersona( 4340): KNOX_SDCARD checking this for 10145
E/Zygote  ( 4340): v2
I/libpersona( 4340): KNOX_SDCARD not a persona
I/SELinux ( 4340): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4340 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 4340): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4340): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4340): TimaSignature is unavailable
,D/ActivityThread( 4340): Added TimaKeyStore provider
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4356 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
E/Zygote  ( 4356): MountEmulatedStorage()
I/libpersona( 4356): KNOX_SDCARD checking this for 1000,
E/Zygote  ( 4356): v2
I/libpersona( 4356): KNOX_SDCARD not a persona,
,I/SELinux ( 4356): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Killing 3555:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
I/SELinux ( 4356): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4356): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 3582:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4356): TimaSignature is unavailable
,D/ActivityThread( 4356): Added TimaKeyStore provider
,W/ResourcesManager( 4340): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4340): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4340): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4340): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4340): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/CalendarProvider2( 4197): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/ActivityManager( 1015): Killing 3622:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,D/SecurityLogAgent( 4356): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4356): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 4356): StateMachine : Current State = 1
,D/SecurityLogAgent( 4356): BootReceiver : completed task. Failed to return wakelock . 
I/splitIntent( 1015): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1015): Killing 3046:com.google.android.youtube/u0a166 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1015): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1015): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1015): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
,I/CalendarProvider2( 4197): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1746): callingUid 10012, callindPid: 1746
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1746): [227] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1923): Restart initialization of location
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1746): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1746): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1746): No location to return for getLastLocation()
,W/FusedLocationProvider( 1746): location=null
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/BadgeProvider( 4286): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/ActivityManager( 1015): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/Launcher.Model( 1466): reloadBadges entered.
D/BadgeProvider( 4286): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4286): sendNotify, [notify] : null
D/BadgeProvider( 4286): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4286): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4286): update, [UpdateCount] : 1
,W/ActivityManager( 1015): getTasks: caller 10146 does not hold GET_TASKS; limiting output
,I/Process ( 4307): Sending signal. PID: 4307 SIG: 9
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1746): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4387): MountEmulatedStorage(),
E/Zygote  ( 4387): v2
I/libpersona( 4387): KNOX_SDCARD checking this for 1000
I/libpersona( 4387): KNOX_SDCARD not a persona
,I/SELinux ( 4387): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4387): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4387): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4387 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1015): Process com.android.exchange (pid 4307)(adj 13) has died(119,1126)
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4387): TimaSignature is unavailable
,D/ActivityThread( 4387): Added TimaKeyStore provider
,E/MTPRx   ( 4387): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1015): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1015): mCursor = null
,V/MTPRx   ( 4387): sealedState: false
V/MTPRx   ( 4387): sealedUsbMassStorageState: false
,E/MTPRx   ( 4387): check value of boot_completed is1
E/MTPRx   ( 4387): check booting is completed_sys.boot_completed
,E/MTPRx   ( 4387): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4387): Status for mount/Unmount :removed
E/MTPRx   ( 4387): SDcard is not available
,W/MTPRx   ( 4387): value of connected istrue
W/MTPRx   ( 4387): value of configured istrue
W/MTPRx   ( 4387): value of mtpEnabled istrue
W/MTPRx   ( 4387): value of ptpEnabled isfalse
,E/MTPRx   ( 4387): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 4387): mFirstTime: false
,W/libprocessgroup( 1015): failed to open /acct/uid_10069/pid_3555/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10022/pid_3582/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3622/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10166/pid_3046/cgroup.procs: No such file or directory
,D/        ( 4387): MTP: reading debug level property
,E/MTPJNIInterface( 4387): Getting CryptionKey from JAVA
,E/MTPRx   ( 4387): currentUserId is 0
,E/MTPRx   ( 4387): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 4387): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 4387): is_Privatemode is NOT 1
,I/ValidateNoPeople( 1015): mEvictionCount: 0
,D/SettingsProvider( 1015): name = boot_time_connected
,E/MTPRx   ( 4387): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 4387): noti = 17
,D/SettingsProvider( 1015): name = mtp_usb_conditions_met
,D/SecContentProvider( 1015): uri = 18 selection = isUsbMediaPlayerAvailable,
E/MTPRx   ( 4387): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1015): name = mtp_running_status
,D/SettingsProvider( 1015): name = mtp_usb_conditions_met
,E/MTPRx   ( 4387): else part ... so first time!!!
,E/MTPPlaObsrvr( 4387): inside setContext()
E/MTPPlaObsrvr( 4387):  inside createplafiles
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 4387): playlist count is0
,E/MTPPlaObsrvr( 4387):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4387):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4387): Inside registerContentObserver
,E/MtpAdbObserver( 4387): inside setContext()
,E/MtpAdbObserver( 4387): Inside registerContentObserver
W/Settings( 4387): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,V/MtpMediaDBManager( 4387): inside deleteAllDB
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1015): name = mtp_running_status
D/SettingsProvider( 1015): name = mtp_usb_conditions_met
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
E/MtpService( 4387): onCreate.
,D/MtpService( 1228): updating state; isCurrentUser=true, mMtpLocked=false
,E/MtpService( 4387): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 4387): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 4387): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 4387): onStartCommand.
,W/MTPRx   ( 4387): calling native method
,E/MTPJNIInterface( 4387): < MTP > Registering BroadCast receiver :::::
,E/MTPJNIInterface( 4387): < MTP > Registering BroadCast receiver :::::::
,E/MtpService( 4387): handleMessage. msg= { when=-3ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,D/daemonapp( 1347): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
E/MTPJNIInterface( 4387): noti = 10
D/daemonapp( 1347): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,V/MtpMediaDBManager( 4387): inside Thread updateDB
D/daemonapp( 1347): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/MtpService( 4387): onStartCommand.
,W/MTPRx   ( 4387): calling native method
E/MTPRx   ( 4387): Checking the driver time out
E/MTPJNIInterface( 4387): noti = 2
D/        ( 4387): deleting sockets before message queue initialization
,D/        ( 4387): event handler thread is created, so set the flag
,D/daemonapp( 1347): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/MtpService( 4387): handleMessage. msg= { when=-3ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPRx   ( 4387): called native method
,E/        ( 4387): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 4387): Getting media scanner status0
E/MTPJNIInterface( 4387): setting Media scanner status0
E/MTPJNIInterface( 4387): After setting Media scanner status0
W/MTPRx   ( 4387): notification from stack 1
,E/MTPJNIInterface( 4387): DeviceName is A5-1
,D/daemonapp( 1347): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/MtpMediaDBManager( 4387): count : 27
,D/daemonapp( 1347): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1347): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1347): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1347): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1347): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1347): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1347): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1347): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1347): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1347): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1450210860000
D/daemonapp( 1347): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1450189311082
,D/daemonapp( 1347): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1347): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1347): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1347): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1347): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1347): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/daemonapp( 1347): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4409): MountEmulatedStorage()
I/libpersona( 4409): KNOX_SDCARD checking this for 10111
E/Zygote  ( 4409): v2
I/libpersona( 4409): KNOX_SDCARD not a persona
I/SELinux ( 4409): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=4409 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4409): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4409): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,W/MtpMediaDBManager( 4387): sending db update complete noti to stack,
E/MTPJNIInterface( 4387): noti = 29
,E/MTPJNIInterface( 4387): Status for mount/Unmount :removed
E/MTPJNIInterface( 4387): SDcard is not available
,E/        ( 4387): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452],
,E/        ( 4387): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,D/TimaKeyStoreProvider( 4409): TimaSignature is unavailable
,D/ActivityThread( 4409): Added TimaKeyStore provider,
E/MTPJNIInterface( 4387): Status for mount/Unmount :removed
E/MTPJNIInterface( 4387): SDcard is not available,
E/SQLiteLog( 4387): (21) API call with NULL database connection pointer,
E/SQLiteLog( 4387): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4387): (21) API call with NULL database connection pointer
E/SQLiteLog( 4387): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4387): (21) API call with NULL database connection pointer
E/SQLiteLog( 4387): (21) misuse at line 100726 of [9491ba7d73],
E/SQLiteLog( 4387): (21) API call with NULL database connection pointer
E/SQLiteLog( 4387): (21) misuse at line 106108 of [9491ba7d73]
D/        ( 4387): [mtp_init_device] Library open with 32 bits.
D/        ( 4387): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 4387): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 4387): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 4387):  [sua_support_present:1287] returning false 
D/        ( 4387): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
W/MTPRx   ( 4387): notification from stack 2

```
