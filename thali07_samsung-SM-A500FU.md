#### Test 50388019aa1a16d_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
E/USB_UICC(  296): Timeout! No signal received. Retry num = 28
--------- beginning of system
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
E/SMD     (  288): DCD OFF
W/InstanceID/Rpc( 1937): Found 10012
D/TimaKeyStoreProvider( 3470): TimaSignature is unavailable
D/ActivityThread( 3470): Added TimaKeyStore provider
V/VibratorService( 1016): hasVibrator - useVibetonz: true
I/KLMS-2.5.183: ( 3414): KLMSIntentService(): onDestroy()
I/ServiceManager(  314): Waiting for service AtCmdFwd...
I/dex2oat ( 3477): ----------------------------------------------------
I/dex2oat ( 3477): <SS>: S T A R T I N G . . .
I/dex2oat ( 3477): <SS>: Zip is absent. Canceled.
I/dex2oat ( 3477): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk --oat-fd=39 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 3451): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
E/Zygote  ( 3496): MountEmulatedStorage()
E/Zygote  ( 3496): v2
I/SELinux ( 3496): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
I/SELinux ( 3496): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1016): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3496 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 3496): KNOX_SDCARD checking this for 10042
I/libpersona( 3496): KNOX_SDCARD not a persona
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
E/SELinux ( 3496): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3510): MountEmulatedStorage()
I/libpersona( 3510): KNOX_SDCARD checking this for 10139
E/Zygote  ( 3510): v2
I/libpersona( 3510): KNOX_SDCARD not a persona
I/SELinux ( 3510): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3510): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/TimaKeyStoreProvider( 3496): TimaSignature is unavailable
E/SELinux ( 3510): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityThread( 3496): Added TimaKeyStore provider
I/ActivityManager( 1016): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=3510 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3527): MountEmulatedStorage()
I/libpersona( 3527): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3527): v2
I/libpersona( 3527): KNOX_SDCARD not a persona
I/SELinux ( 3527): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3527 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3527): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3527): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3527): TimaSignature is unavailable
D/ActivityThread( 3527): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 3510): TimaSignature is unavailable
D/ActivityThread( 3510): Added TimaKeyStore provider
W/ResourcesManager( 3496): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ResourcesManager( 3527): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 3510): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3510): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3510): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3510): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3510): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3552): MountEmulatedStorage()
E/Zygote  ( 3552): v2
I/libpersona( 3552): KNOX_SDCARD checking this for 1000
I/libpersona( 3552): KNOX_SDCARD not a persona
I/SELinux ( 3552): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3552 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 1568:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
I/SELinux ( 3552): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3552): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 2867:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/CalendarProvider2( 3496): CalendarProvider2.onCreate() called
E/Zygote  ( 3569): MountEmulatedStorage()
E/Zygote  ( 3569): v2
I/libpersona( 3569): KNOX_SDCARD checking this for 10145
I/libpersona( 3569): KNOX_SDCARD not a persona
I/SELinux ( 3569): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3569): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1016): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=3569 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
D/TimaKeyStoreProvider( 3552): TimaSignature is unavailable
D/ActivityThread( 3552): Added TimaKeyStore provider
E/SELinux ( 3569): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/GCM     ( 1937): COMPAT: Multi user not supported
D/TimaKeyStoreProvider( 3569): TimaSignature is unavailable
D/ActivityThread( 3569): Added TimaKeyStore provider
I/CheckinService( 1937): Disabling old GoogleServicesFramework version
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/GCM     ( 1662): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/MTPRx   ( 3552): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
D/SecContentProvider2( 1016): uri = 14 selection = getSealedState
D/SecContentProvider2( 1016): mCursor = null
W/ResourcesManager( 3569): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3569): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3569): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3569): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3569): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/SecContentProvider2( 1016): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1016): mCursor = null
V/MTPRx   ( 3552): sealedState: false
V/MTPRx   ( 3552): sealedUsbMassStorageState: false
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SettingsProvider( 1016): name = mtp_usb_connection_status
D/SystemUpdateService( 1937): onCreate
W/libprocessgroup( 1016): failed to open /acct/uid_10072/pid_1568/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10150/pid_2867/cgroup.procs: No such file or directory
D/SettingsProvider( 1016): name = media_player_mode
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/GCoreUlr( 1937): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
D/SystemUpdateService( 1937): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SettingsProvider( 1016): name = mtp_usb_conditions_met
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ConfigService( 1662): onCreate
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
I/CheckinService( 1937): Checking schedule, now: 1448020181811 next: 1448192721114
I/CheckinService( 1937): active receiver: disabled
I/ConfigFetchService( 1937): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SettingsProvider( 1016): name = mtp_running_status
V/AuthZen ( 1937): Handling intent: android.intent.action.BOOT_COMPLETED
D/AuthZenEventHandler( 1937): Handling event: android.intent.action.BOOT_COMPLETED
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/LockPatternUtils( 1282): isSmartCardAuthenticationAvailable: false
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 1937): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/SettingsProvider( 1016): name = media_mount_count
D/SettingsProvider( 1016): name = mtp_sync_alive
I/DBG_DM  ( 2837): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
D/SettingsProvider( 1016): name = sdcard_launch
D/SettingsProvider( 1016): name = boot_time_connected
D/SensorService( 1016): [SO] 0.172 0.077 10.228
D/SettingsProvider( 1016): name = mtp_open_session
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
W/BaseAppContext( 1937): Using Auth Proxy for data requests.
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
D/TimaService( 1016): TIMA: in getTimaVersion
I/PCWCLIENTTRACE_PushUtil( 3104): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3104): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3104): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3104): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3104): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3104): ACTION_BOOTUP - Push type: [SPP, GCM]
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
D/TimaService( 1016): TIMA3: KeyStore3_init
D/TimaService( 1016): TIMA: in getTimaVersion
E/TLC_TZ_KEYSTORE: ( 1016): Inside TZ_KEYSTORE_initialize()
I/TLC_TZ_KEYSTORE: ( 1016): creating new keystore context...
I/TLC_TZ_KEYSTORE: ( 1016): initializing ccm context...
I/TLC_TZ_KEYSTORE: ( 1016): root = /firmware/image, root_strlen = 15
I/TLC_TZ_KEYSTORE: ( 1016): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1016): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): aligned max_sendmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1016): aligned max_recvmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1016): max_message_size = 2176 = 0x880
D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x880
D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/USB_UICC(  296): Timeout! No signal received. Retry num = 29
D/QSEECOMAPI: ( 1016): Loaded image: APP id = 8
I/ServiceManager(  314): Waiting for service AtCmdFwd...
I/TZ: qc_tlc_communication( 1016): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
I/TLC_TZ_KEYSTORE: ( 1016): ctx = 0xb86689e8, comm = 0xb83f84c0, sendmsg = 0xa09a0000, recvmsg = 0xa09a0440
I/TZ_init: ( 1016): TZ_init: sending initialization request...
E/TZ_init: ( 1016): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 1016): trustlet initialization failed
I/TZ_init: ( 1016): TZ_init_START...
I/TZ_init: ( 1016): TZ_init_with_data: sending initialization request...
I/TZ_init: ( 1016): TZ_init: successful initialization
D/QSEECOMAPI: ( 1016): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1016): QSEECom_shutdown_app, app_id = 8
E/TLC_TZ_KEYSTORE: ( 1016): Count : 1, Ret : 0
I/GCoreUlr( 1720): DispatchingService.onCreate()
D/RCPManagerService( 1016): exchangeData() failure , invalid userId
I/GLSUser ( 1937): [ChannelManager] Attempting to channel bind connection HttpClient.
I/art     ( 1016): Explicit concurrent mark sweep GC freed 43718(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 26MB/40MB, paused 2.305ms total 232.417ms
D/AndroidRuntime( 3606): 
D/AndroidRuntime( 3606): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3606): CheckJNI is OFF
D/AndroidRuntime( 3606): readGMSProperty: start
D/AndroidRuntime( 3606): readGMSProperty: already setted!!
D/AndroidRuntime( 3606): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3606): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3606): readGMSProperty: end
D/AndroidRuntime( 3606): addProductProperty: start
W/PCWCLIENTTRACE_PCWHandler( 3104): [ensureRegistration] - netwrok is not available. action ignored
I/ConfigFetchService( 1937): service connected
I/SystemUpdateService( 1937): cancelUpdate (empty URL)
D/ChimeraCfgMgr( 1937): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/RCPManagerService( 1016): exchangeData() failure , invalid userId
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/SystemUpdateService( 1937): active receiver: disabled
I/ActivityManager( 1016): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3626 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2911:com.policydm/1000 (adj 15): empty #31
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/Zygote  ( 3626): MountEmulatedStorage()
E/Zygote  ( 3626): v2
I/libpersona( 3626): KNOX_SDCARD checking this for 10031
I/libpersona( 3626): KNOX_SDCARD not a persona
I/SELinux ( 3626): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3626): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
E/SELinux ( 3626): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/AffinityControl( 3606): AffinityControl: registerfunction enter
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1016): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3634 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/Zygote  ( 3634): MountEmulatedStorage()
I/libpersona( 3634): KNOX_SDCARD checking this for 10104
E/Zygote  ( 3634): v2
I/libpersona( 3634): KNOX_SDCARD not a persona
I/SELinux ( 3634): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3634): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3634): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/art     ( 3569): Verification of void com.android.email.activity.MessageListItemOuterContainer.checkInnerContainer() took 200.704ms
V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/RCPManagerService( 1016): exchangeData() failure , invalid userId
D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/Kids    ( 1937): [KidAccountFixer] No network connection
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4207, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
D/AndroidRuntime( 3606): Calling main entry com.android.commands.am.Am
W/art     ( 1720): Suspending all threads took: 19.805ms
I/GLSUser ( 1937): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
I/art     ( 1720): Explicit concurrent mark sweep GC freed 12071(734KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 10MB/17MB, paused 27.455ms total 139.506ms
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/TimaKeyStoreProvider( 3634): TimaSignature is unavailable
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/ActivityThread( 3634): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 3626): TimaSignature is unavailable
D/ActivityThread( 3626): Added TimaKeyStore provider
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
D/PowerUI ( 1174): Cable  true --> true mBootCompleted : true
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
D/PowerUI ( 1174): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2911/cgroup.procs: No such file or directory
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ResourcesManager( 3634): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1016): mDVFSHelper.acquire()
D/FocusedStackFrame( 1016): Set to : 0
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1016): *FMB* installDecor flags : 25362712
D/Launcher.HomeView( 1494): onPause
D/Launcher( 1494): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
W/ResourcesManager( 3626): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/dex2oat ( 3477): dex2oat took 1.540s (threads: 4)
W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 1494
D/AndroidRuntime( 3606): Shutting down VM
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/SurfaceFlinger(  257): id=10 createSurf (1x1),1 flag=404, iello
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
D/DexOptUtils( 1937): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex
D/DexOptUtils( 1937): Set odex to world readable.
D/DexOptUtils( 1937): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.odex
D/FileApkUtils( 1937): Keeping up-to-date module: module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3670): MountEmulatedStorage()
E/Zygote  ( 3670): v2
I/libpersona( 3670): KNOX_SDCARD checking this for 10174
I/libpersona( 3670): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3670 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 3670): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3670): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3670): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
I/DBG_DM  ( 2837): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
I/art     ( 1662): Explicit concurrent mark sweep GC freed 27322(1626KB) AllocSpace objects, 9(204KB) LOS objects, 39% free, 10MB/17MB, paused 1.257ms total 118.305ms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/SQLiteConnectionPool( 1662): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/TimaKeyStoreProvider( 3670): TimaSignature is unavailable
V/ActivityThread( 1494): updateVisibility : ActivityRecord{2aa449ff token=android.os.BinderProxy@2bdd0f26 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/ActivityThread( 3670): Added TimaKeyStore provider
E/Zygote  ( 3690): MountEmulatedStorage()
E/Zygote  ( 3690): v2
I/libpersona( 3690): KNOX_SDCARD checking this for 1000
I/libpersona( 3690): KNOX_SDCARD not a persona
I/VlingoApplication( 3626): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
I/SELinux ( 3690): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3690 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3690): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3690): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/BluetoothAdapter( 3626): 316490049: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3626): 316490049: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3626): 316490049: getState() :  mService = null. Returning STATE_OFF
I/VlingoAndroidCore( 3626): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
E/Zygote  ( 3703): MountEmulatedStorage()
E/Zygote  ( 3703): v2
I/libpersona( 3703): KNOX_SDCARD checking this for 10150
I/libpersona( 3703): KNOX_SDCARD not a persona
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3451): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3451): Resource data:2131165186
I/SELinux ( 3703): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3703): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1016): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3703 uid=10150 gids={50150, 9997} abi=armeabi-v7a
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
W/ResourcesManager( 3451): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
W/ResourcesManager( 3451): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3451): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
W/ResourcesManager( 3451): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3451): getResourceTypeNamexml
W/ResourcesManager( 3451): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
V/WindowManager( 1016): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
E/SELinux ( 3703): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/FactoryTestApp( 2539): [DummyFtClient$onDestroy](2539) Destroy DummyFtClient service
D/TimaKeyStoreProvider( 3690): TimaSignature is unavailable
D/ActivityThread( 3690): Added TimaKeyStore provider
D/Launcher.HomeView( 1494): onStop
V/ActivityThread( 1494): updateVisibility : ActivityRecord{2aa449ff token=android.os.BinderProxy@2bdd0f26 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1494): onTrimMemory. Level: 20
W/art     ( 3606): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/art     (  303): Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 25.746ms
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1016): isKioskContainerExistOnDevice
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 19.310ms
,I/AMMetaDataParserService( 3451): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 710us total 17.725ms
,D/TimaKeyStoreProvider( 3703): TimaSignature is unavailable
,D/ActivityThread( 3703): Added TimaKeyStore provider
,D/FactoryTestApp( 2539): [Support$Values.getString](2539) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2539): [ModuleCommon$isConnectionModeNone](2539) mConnectionMode = gsm
I/FactoryTestApp( 2539): [ModuleCommon$isRunningFtClient](2539) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2539): [DummyFtClient$onDestroy](2539) kill process
I/Process ( 2539): Sending signal. PID: 2539 SIG: 9
,D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1016): [SO] activate (ident=0xb84a83e8, enabled=0)
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1016): unregisterListener ::   
I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1016): [SO] changed settle time [1]
D/SensorService( 1016): [SO] setDelay [66000000]
D/SensorService( 1016): [SO] activate (ident=0xb84a83e8, enabled=1)
D/SensorService( 1016): [SO] AR_init
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,E/Zygote  ( 3724): MountEmulatedStorage()
E/Zygote  ( 3724): v2
,I/libpersona( 3724): KNOX_SDCARD checking this for 10072
I/libpersona( 3724): KNOX_SDCARD not a persona
I/SELinux ( 3724): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3724): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/ResourcesManager( 3690): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,E/SELinux ( 3724): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
V/AlarmManager( 1016): waitForAlarm result :4
,I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=3724 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,I/ActivityManager( 1016): Process com.sec.factory (pid 2539)(adj 0) has died(108,1091)
,W/SEAMService( 1016):  hashset_to_int_array returning null
,I/AMMetaDataParserService( 3451): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,D/TimaKeyStoreProvider( 3724): TimaSignature is unavailable
,D/ActivityThread( 3724): Added TimaKeyStore provider
,W/SEAMService( 1016):  hashset_to_int_array returning null
,E/SQLiteLog( 3527): (284) automatic index on seams_container_info(seams_container_id)
,E/SQLiteLog( 3527): (284) automatic index on seams_container_info(sp_id)
W/ContextImpl( 3690): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/SEAMService( 1016):  hashset_to_int_array returning null
,I/AMMetaDataParserService( 3451): Icon data: ResourceNew Tab2131755458android.intent.action.doNewWindow2130837510
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
W/ContextImpl( 3451): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
I/ActivityManager( 1016): Killing 2846:com.google.android.configupdater/u0a86 (adj 15): empty #31
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 30
,D/SensorService( 1016): [SO] currT = 36191131000, prevT = 35841089000, diff = 350042000, [0.172 0.096 10.247]
D/SensorService( 1016): [SO] 0.172 0.096 10.247
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/SensorService( 1016): [SO] [100 -> 255]
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,D/GmsModuleFndr( 1937): Beginning GMS chimera module scan
,I/F_PHONE ( 3690): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 3690): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,I/WebViewFactory( 3670): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/GmsModuleFndr( 1937): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
,I/libpersona( 3743): KNOX_SDCARD checking this for 1000
D/ChimeraCfgMgr( 1937): Beginning module configuration check
I/libpersona( 3743): KNOX_SDCARD not a persona
E/Zygote  ( 3743): MountEmulatedStorage()
E/Zygote  ( 3743): v2
I/SELinux ( 3743): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3743 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3743): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1016): Killing 2934:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,D/ChimeraCfgMgr( 1937): Module APKs unchanged, check complete
,E/SELinux ( 3743): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:assistant
I/AMMetaDataParserService( 3451): Resource data:2131034113
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 3451): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3451): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3451): getResourceTypeNamexml
,E/USB_UICC(  296): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  296): usb_uicc_init_qmi failed ! 
I/USB_UICC(  296): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  296): usb_uicc_cleanup, Issuing QMI deinit ... 
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3451): took 2.932500ms for 0*0 texture 0
,D/BadgeProvider( 3724): onCreate
,D/BadgeProvider( 3724): DatabaseHelper
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX generate_partition_tables( 3451): took 8.561560ms for 0*0 texture 0
,I/GFX raster( 3451): took 13.036299ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fe1748 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7fe8220 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3743): TimaSignature is unavailable
D/ConfigFetchService( 1937): ConfigApi connection successful.
D/SystemUpdateService( 1937): onDestroy
,D/ActivityThread( 3743): Added TimaKeyStore provider
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,I/AMMetaDataParserService( 3451): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,I/LibraryLoader( 3670): Time to load native libraries: 2 ms (timestamps 6351-6353)
I/LibraryLoader( 3670): Expected native library version number "",actual native library version number ""
,W/ResourcesManager( 3743): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3776): MountEmulatedStorage()
E/Zygote  ( 3776): v2
I/libpersona( 3776): KNOX_SDCARD checking this for 10146
I/libpersona( 3776): KNOX_SDCARD not a persona
,I/SELinux ( 3776): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1016): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=3776 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 3776): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3776): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3451): took 0.849843ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fe1748 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7ff0388 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1016): Killing 2990:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,D/F_PHONE ( 3690): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 3690): default registerAction()
I/F_PHONE ( 3690): [[com.sec.bcservice]] sendPendingMessage()
,W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
D/BadgeProvider( 3724): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,V/WebViewChromiumFactoryProvider( 3670): Binding Chromium to main looper Looper (main, tid 1) {ab4e436}
,I/LibraryLoader( 3670): Expected native library version number "",actual native library version number ""
,I/chromium( 3670): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/BluetoothBDAdrressReceiver( 3743): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3743): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,I/AMMetaDataParserService( 3451): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,I/ActivityManager( 1016): Killing 3016:com.sec.factory.camera/1000 (adj 15): empty #31
,I/SettingSearch/SearchIntentReceiver( 1282): InitSerachDBThread thread end!
,I/GLSActivity( 1662): [ac] getting account id
,D/TimaKeyStoreProvider( 3776): TimaSignature is unavailable
,D/ActivityThread( 3776): Added TimaKeyStore provider
,I/SurfaceFlinger(  257): id=8 Removed Mauncher (5/8)
,D/BadgeProvider( 3724): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 3724): sendNotify, [notify] : null
D/BadgeProvider( 3724): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 3724): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 3724): update, [UpdateCount] : 1
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3451): took 2.533177ms for 0*0 texture 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,I/BrowserStartupController( 3670): Initializing chromium process, singleProcess=true
,W/art     ( 3670): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3670): ApplicationContext is null in ApplicationStatus
,I/GFX generate_partition_tables( 3451): took 7.533333ms for 0*0 texture 0
,I/GFX raster( 3451): took 11.141823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fecc88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fecd50 counterpartCT=4 counterpartW=96 counterparth=96
,W/chromium( 3670): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/libprocessgroup( 1016): failed to open /acct/uid_10086/pid_2846/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10094/pid_2934/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10003/pid_2990/cgroup.procs: No such file or directory
,W/chromium( 3670): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/AuthZen ( 1937): Fetching signing key...
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/libEGL  ( 3670): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/AMMetaDataParserService( 3451): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
E/libEGL  ( 3670): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3670): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3670): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3670): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3670): Local Branch: 
I/Adreno-EGL( 3670): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3670): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3670):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/Launcher.Model( 1494): reloadBadges entered.
,I/AuthZen ( 1937): Signing key fetched successfully!
,W/ResourcesManager( 1468): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothBDTestService( 1468): onCreate()
,E/BluetoothBDTestService( 1468): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1468): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1468): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3016/cgroup.procs: No such file or directory
W/BaseAppContext( 1937): Using Auth Proxy for data requests.
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AuthZen ( 1937): Starting Enrollment...
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.919479ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7ff1748 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ff1810 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1016): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3798 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/ActivityManager( 1016): Killing 3032:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,W/ResourcesManager( 3776): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
,D/VlingoApplication( 3626): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,E/Zygote  ( 3798): MountEmulatedStorage(),
E/Zygote  ( 3798): v2
,D/VlingoApplication( 3626): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
I/libpersona( 3798): KNOX_SDCARD checking this for 1000,
I/libpersona( 3798): KNOX_SDCARD not a persona
,I/SELinux ( 3798): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/AMMetaDataParserService( 3451): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530,
,I/SELinux ( 3798): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3798): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/AuthZen ( 1937): getting auth token. Attempt 0
,D/DialogFlow( 3626): initQueue()
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.997657ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7feceb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fed1e0 counterpartCT=4 counterpartW=96 counterparth=96
,I/GLSUser ( 1662): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,I/AMMetaDataParserService( 3451): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.751042ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fec3d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fec498 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3451): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/TimaKeyStoreProvider( 3798): TimaSignature is unavailable
,D/ActivityThread( 3798): Added TimaKeyStore provider
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.968698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fed1e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fed498 counterpartCT=4 counterpartW=96 counterparth=96
,D/BluetoothAdapter( 3670): 317335507: getState() :  mService = null. Returning STATE_OFF
,I/GCoreUlr( 1720): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3451): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/libprocessgroup( 1016): failed to open /acct/uid_10060/pid_3032/cgroup.procs: No such file or directory
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ResourcesManager( 3798): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.566667ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb819a160 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb819a1b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3830): MountEmulatedStorage()
E/Zygote  ( 3830): v2
I/libpersona( 3830): KNOX_SDCARD checking this for 10032
I/libpersona( 3830): KNOX_SDCARD not a persona
,I/SELinux ( 3830): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3830): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3830): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1016): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3830 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
I/ActivityManager( 1016): Killing 3051:com.fmm.dm/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:assistant
I/AMMetaDataParserService( 3451): Resource data:2131034113
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 3451): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3451): getResourceTypeNamexml
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3830): TimaSignature is unavailable
,D/ActivityThread( 3830): Added TimaKeyStore provider
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2837): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/GFX raster( 3451): took 0.825677ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7d22838 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7fb3638 counterpartCT=4 counterpartW=96 counterparth=96
,I/CalendarProvider2( 3496): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/AMMetaDataParserService( 3451): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/ActivityManager( 1016): Killing 3068:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,E/AuthZen ( 1937): Error getting auth token
E/AuthZen ( 1937): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 1937): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 1937): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 1937): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 1937): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 1937): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 1937): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 1937): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 1937): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 1937): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 1937): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 1937): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 1937): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 1937): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 1937): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 1937): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 1937): 	at android.os.Looper.loop(Looper.java:145)
E/AuthZen ( 1937): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AuthZen ( 1937): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 1937): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 1937): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 1937): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 1937): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 1937): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 1937): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 1937): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 1937): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 1937): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 1937): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 1937): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 1937): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 1937): 	at android.os.Looper.loop(Looper.java:145)
E/AuthZen ( 1937): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager( 1016): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,I/Process ( 3569): Sending signal. PID: 3569 SIG: 9
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,D/a       ( 1937): Opening database auth.proximity.permit_store...
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/KnoxUsageLogPro( 3798): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,E/Zygote  ( 3851): MountEmulatedStorage(),
I/libpersona( 3851): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3851): v2
I/libpersona( 3851): KNOX_SDCARD not a persona
I/SELinux ( 3851): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=3851 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/KnoxUsageLogPro( 3798): savePreference: key = previous_sys_time value = 1448020184037
,I/KnoxUsageLogPro( 3798): premStatus:2
,I/KnoxUsageLogPro( 3798): isEulaShown : false
I/KnoxUsageLogPro( 3798): KnoxUsageReceiver onReceive : not Processible, just return
,I/SELinux ( 3851): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1016): Killing 3087:com.samsung.helphub/1000 (adj 15): empty #31
,E/SELinux ( 3851): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3851): TimaSignature is unavailable
,D/ActivityThread( 3851): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3051/cgroup.procs: No such file or directory
,I/ActivityManager( 1016): Process com.android.email (pid 3569)(adj 11) has died(103,1104)
,W/art     ( 3634): Suspending all threads took: 11.322ms
,W/libprocessgroup( 1016): failed to open /acct/uid_10100/pid_3068/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3087/cgroup.procs: No such file or directory
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3872): MountEmulatedStorage(),
E/Zygote  ( 3872): v2
I/libpersona( 3872): KNOX_SDCARD checking this for 1000
I/libpersona( 3872): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=3872 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3132:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,W/art     ( 3670): Attempt to remove local handle scope entry from IRT, ignoring
,I/Babel_SMS( 3634): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 3634): MmsConfig.loadMmsSettings
,I/Babel_SMS( 3634): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel_SMS( 3634): MmsConfig.loadFromDatabase
,I/SELinux ( 3872): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3872): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/AuthZenTransactionCache( 1937): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1937): Clearing transaction cache
,E/SELinux ( 3872): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KnoxUsageLogPro( 3798): savePreference: key = previous_elapsed_time value = 36905
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/AwContents( 3670): onDetachedFromWindow called when already detached. Ignoring
,E/Zygote  ( 3887): MountEmulatedStorage(),
E/Zygote  ( 3887): v2,
I/libpersona( 3887): KNOX_SDCARD checking this for 10145
,I/libpersona( 3887): KNOX_SDCARD not a persona
,I/SELinux ( 3887): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1016): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=3887 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/SELinux ( 3887): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3887): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PhoneWindow( 3670): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 3670): *FMB* installDecor flags : 8456448
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3872): TimaSignature is unavailable
,D/ActivityThread( 3872): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3887): TimaSignature is unavailable
,D/ActivityThread( 3887): Added TimaKeyStore provider
,E/Zygote  ( 3902): MountEmulatedStorage(),
E/Zygote  ( 3902): v2
I/libpersona( 3902): KNOX_SDCARD checking this for 10033
I/libpersona( 3902): KNOX_SDCARD not a persona,
D/SystemWebViewEngine( 3670): CordovaWebView is running on device made by: samsung
,I/ActivityManager( 1016): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3902 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
I/ActivityManager( 1016): Killing 3150:com.fmm.ds/1000 (adj 15): empty #31
,I/SELinux ( 3902): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3902): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3902): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/TimaKeyStoreProvider( 3902): TimaSignature is unavailable
,D/ActivityThread( 3902): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 3166:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,I/GFX raster( 3451): took 0.866980ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7d22838 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7fcff00 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.599375ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fb3638 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fcff00 counterpartCT=4 counterpartW=96 counterparth=96
,E/SMD     (  288): DCD OFF,
I/AMMetaDataParserService( 3451): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,E/Babel_SMS( 3634): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 3634): MmsConfig.loadFromResources
,E/Babel_SMS( 3634): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 3634): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.595729ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fcff00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb819df38 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.828698ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb819a030 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb819a068 counterpartCT=4 counterpartW=96 counterparth=96
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/AMMetaDataParserService( 3451): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.623750ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb819e000 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb819e328 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 25215(1535KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/40MB, paused 2.394ms total 153.059ms
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/GFX raster( 3451): took 0.678385ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fed1e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb819a068 counterpartCT=4 counterpartW=96 counterparth=96
,D/SecurityLogAgent:SEDenialService( 1016): Got CLOSE_WRITE Event sk.log
,D/SecurityLogAgent:SEDenialService( 1016): Got CLOSE_WRITE Event sk.log
,I/AMMetaDataParserService( 3451): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/art     ( 3670): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3670): Attempt to remove local handle scope entry from IRT, ignoring
,W/ResourcesManager( 3887): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3887): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3887): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3887): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3887): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/art     ( 3626): Suspending all threads took: 9.060ms
W/libprocessgroup( 1016): failed to open /acct/uid_10062/pid_3132/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3150/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3166/cgroup.procs: No such file or directory
,D/SecurityLogAgent( 3872): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 3872): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 3872): StateMachine : Current State = 1
D/SecurityLogAgent( 3872): BootReceiver : completed task. Failed to return wakelock . 
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3925): MountEmulatedStorage(),
,E/Zygote  ( 3925): v2
I/ActivityManager( 1016): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=3925 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
I/libpersona( 3925): KNOX_SDCARD checking this for 10152
I/libpersona( 3925): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Killing 2053:com.google.android.gms.wearable/u0a12 (adj 15): empty #31
I/SELinux ( 3925): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3925): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3925): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3925): TimaSignature is unavailable
,D/ActivityThread( 3925): Added TimaKeyStore provider
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/OpenGLRenderer( 3670): Render dirty regions requested: true
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
,D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,W/chromium( 3670): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/PhoneWindow( 3670): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3670): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  283): getCameraInfo: X
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  283): getCameraInfo: X
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/InputDispatcher( 1016): Focus entered window: 3670
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 3670): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 3670): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3670): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3670): Enabling debug mode 0
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/ActivityManager( 1016): getTasks: caller 10146 does not hold GET_TASKS; limiting output
,D/BadgeProvider( 3724): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/Process ( 3776): Sending signal. PID: 3776 SIG: 9
,W/libprocessgroup( 1016): failed to open /acct/uid_10012/pid_2053/cgroup.procs: No such file or directory
,W/art     ( 3634): Suspending all threads took: 11.301ms
,W/Settings( 3634): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/SQLiteLog( 3925): (284) automatic index on shooting_modes(title_id)
,D/BadgeProvider( 3724): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 3724): sendNotify, [notify] : null
D/Launcher.Model( 1494): reloadBadges entered.
,D/BadgeProvider( 3724): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 3724): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 3724): update, [UpdateCount] : 1
,I/Babel_Crash( 3634): startup - clean
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/ActivityManager( 1016): Process com.android.exchange (pid 3776)(adj 11) has died(74,1118)
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1174): There is/are notification(s) 
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/GFX raster( 3451): took 0.699427ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb819a160 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fcf208 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,I/Timeline( 3670): Timeline: Activity_idle id: android.os.BinderProxy@3b9e6b72 time:37619
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ResourcesManager( 3902): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3902): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3902): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3451): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/SamsungIME( 1774): getCurrentCandidateView
,I/Babel   ( 3634): deleted: false for 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
W/ResourcesManager( 3902): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
W/ResourcesManager( 3902): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
W/ResourcesManager( 3902): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3451): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3451): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3451): getResourcePackageName:assistant
I/AMMetaDataParserService( 3451): Resource data:2131034112
I/AMMetaDataParserService( 3451): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3451): getResourceTypeNamexml
E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.773490ms for 96*96 texture 0
I/ActivityManager( 1016): Displayed Component not be shown by security: +1s862ms
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fcff00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7f87a28 counterpartCT=4 counterpartW=96 counterparth=96
D/SamsungIME( 1774): Dismiss ExpandCandiate
D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1016): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@11
W/ResourcesManager( 3902): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3902): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 3902): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{2787566f u0 com.example.hello/.MainActivity t228} time:37666
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3451): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,E/Zygote  ( 3957): MountEmulatedStorage()
,E/Zygote  ( 3957): v2
,I/libpersona( 3957): KNOX_SDCARD checking this for 1000
I/libpersona( 3957): KNOX_SDCARD not a persona
,I/SELinux ( 3957): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1016): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=3957 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/SELinux ( 3957): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3957): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
I/SamsungIME( 1774): getDebugLevel  : 0x4f4c
,I/art     (  303): Explicit concurrent mark sweep GC freed 8757(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 657us total 41.133ms,
,I/GCoreUlr( 1720): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]},
,D/TimaKeyStoreProvider( 3957): TimaSignature is unavailable
,D/ActivityThread( 3957): Added TimaKeyStore provider
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 19.857ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 19.932ms
,I/GCoreUlr( 1720): Unbound from all location providers
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.613438ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fcff00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fd0980 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2837): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,E/Zygote  ( 3976): MountEmulatedStorage(),
E/Zygote  ( 3976): v2
I/libpersona( 3976): KNOX_SDCARD checking this for 1101
I/libpersona( 3976): KNOX_SDCARD not a persona
,I/SamsungIME( 1774): getDebugLevel  : 0x4f4c,
,I/SELinux ( 3976): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1016): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=3976 uid=1101 gids={41101, 9997} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3186:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,I/SELinux ( 3976): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
E/SELinux ( 3976): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/SamsungIME( 1774): KeybaordView init() : load resources
,D/TimaKeyStoreProvider( 3976): TimaSignature is unavailable
,D/ActivityThread( 3976): Added TimaKeyStore provider
,W/BindingManager( 3670): Cannot call determinedVisibility() - never saw a connection for the pid: 3670
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.683022ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7f87a28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7f87a60 counterpartCT=4 counterpartW=96 counterparth=96
,I/SurfaceFlinger(  257): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  257): id=10 Removed iello (-2/8)
,I/AMMetaDataParserService( 3451): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,W/ResourcesManager( 3976): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,I/SamsungIME( 1774): getCurrentKeyboard
I/SamsungIME( 1774): getTextKeyboard
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.719426ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb819e000 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7f87a60 counterpartCT=4 counterpartW=96 counterparth=96
,I/chromium( 3670): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/AMMetaDataParserService( 3451): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@11
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3186/cgroup.procs: No such file or directory
,D/SamsungIME( 1774): [SwiftkeyWrapper] currentLangauge : 1701729619
,V/SmartcardService( 3976): main Received broadcast
,V/SmartcardService( 3976): Starting smartcard service after boot completed
,D/ActivityManager( 1016): retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
,I/ActivityManager( 1016): Killing 3205:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParser,Service( 3451): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:assistant
I/AMMetaDataParserService( 3451): Resource data:2131034113
I/GCoreUlr( 1720): DispatchingService.onDestroy()
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3451): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3451): getResourceTypeNamexml
E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3451): took 0.841198ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7d22838 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7f87a60 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 3995): MountEmulatedStorage()
,E/Zygote  ( 3995): v2
I/libpersona( 3995): KNOX_SDCARD checking this for 1000,
,I/libpersona( 3995): KNOX_SDCARD not a persona
,I/SELinux ( 3995): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3995): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3995): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=3995 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/AMMetaDataParserService( 3451): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3205/cgroup.procs: No such file or directory
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GCoreUlr( 1720): Unbound from all location providers
,I/GFX raster( 3451): took 0.856562ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7d22838 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7f87a60 counterpartCT=4 counterpartW=96 counterparth=96
,D/JsMessageQueue( 3670): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 3670): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/AMMetaDataParserService( 3451): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.620521ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fb3638 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7f87a60 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 3634): Unrecognized profile 2130706433 for video/avc
,I/AMMetaDataParserService( 3451): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
I/System.out( 3626): INFO:Resource not found:/Common.properties Using default values
,W/AudioCapabilities( 3634): Unsupported mime audio/evrc
,D/TimaKeyStoreProvider( 3995): TimaSignature is unavailable
,D/ActivityThread( 3995): Added TimaKeyStore provider
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.618646ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fcff00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7f87a60 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.890468ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb819a030 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7f87a60 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/AudioCapabilities( 3634): Unsupported mime audio/qcelp
,W/ResourcesManager( 3830): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3830): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/AudioCapabilities( 3634): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3634): Unsupported mime audio/mpeg-L2
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ContextImpl( 3995): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
,I/GFX raster( 3451): took 0.878697ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb819e000 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7f87a60 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.716250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fed1e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7f87a60 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/Zygote  ( 4020): MountEmulatedStorage()
E/Zygote  ( 4020): v2
I/libpersona( 4020): KNOX_SDCARD checking this for 10157
I/libpersona( 4020): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4020 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,I/SELinux ( 4020): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4020): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4020): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/AudioCapabilities( 3634): Unsupported mime audio/x-ms-wma
,E/SQLiteLog( 1662): (10) POSIX Error : 11 SQLite Error : 3850
W/ResourcesManager( 3830): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/AudioCapabilities( 3634): Unsupported mime audio/x-ima
,W/AudioCapabilities( 3634): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3634): Unsupported mime audio/evrc
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.560416ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb819a160 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7f87a60 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,D/TimaKeyStoreProvider( 4020): TimaSignature is unavailable
,D/ActivityThread( 4020): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
W/ContextImpl( 3451): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,W/VideoCapabilities( 3634): Unsupported mime video/wvc1
,W/ResourcesManager( 4020): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/VideoCapabilities( 3634): Unsupported mime video/x-ms-wmv
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:assistant
I/AMMetaDataParserService( 3451,): Resource data:2131165203
I/Process ( 3902): Sending signal. PID: 3902 SIG: 9
W/ResourcesManager( 3451): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/VideoCapabilities( 3634): Unrecognized profile/level 32768/2 for video/mp4v-es
W/ResourcesManager( 3451): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/VideoCapabilities( 3634): Unsupported mime video/wvc1
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3451): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3451): getResourceTypeNamexml
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/VideoCapabilities( 3634): Unsupported mime video/x-ms-wmv
E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX construct_block_size_descriptor_2d second part( 3451): took 2.643958ms for 0*0 texture 0
W/VideoCapabilities( 3634): Unsupported mime video/x-ms-wmv7
E/Zygote  ( 4036): MountEmulatedStorage()
E/Zygote  ( 4036): v2
I/libpersona( 4036): KNOX_SDCARD checking this for 10159
I/libpersona( 4036): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4036 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/jxcore_app_log( 3670): JniHelper::setJavaVM(0xb7c14450), pthread_self() = -1206452272
D/JX-Cordova( 3670): jxcore cordova android initializing
,I/ActivityManager( 1016): Killing 2254:com.sec.android.app.mt/1000 (adj 15): empty #31
,I/SELinux ( 4036): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Process com.sec.android.app.sns3 (pid 3902)(adj 0) has died(41,1127)
,I/SELinux ( 4036): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/SELinux ( 4036): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 4043): MountEmulatedStorage()
E/Zygote  ( 4043): v2
I/libpersona( 4043): KNOX_SDCARD checking this for 10034
I/libpersona( 4043): KNOX_SDCARD not a persona
,I/GFX generate_partition_tables( 3451): took 10.481039ms for 0*0 texture 0
,I/SELinux ( 4043): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/GFX raster( 3451): took 13.976768ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb819aaa0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7fe9030 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1016): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4043 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a,
,I/SELinux ( 4043): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4043): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/AMMetaDataParserService( 3451): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.829583ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb8346038 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8346250 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,W/art     ( 3626): Suspending all threads took: 13.520ms
,D/TimaKeyStoreProvider( 4043): TimaSignature is unavailable
,W/VideoCapabilities( 3634): Unsupported mime video/x-ms-wmv8
,D/ActivityThread( 4043): Added TimaKeyStore provider
,W/jxcore-log( 3670): Initializing JXcore engine
W/jxcore-log( 3670): JXcore engine is ready
,W/jxcore-log( 3670): Starting JXcore engine
,W/VideoCapabilities( 3634): Unsupported mime video/mp43
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.796875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb8346038 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83485c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2254/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4036): TimaSignature is unavailable
,D/ActivityThread( 4036): Added TimaKeyStore provider
,W/VideoCapabilities( 3634): Unsupported mime video/sorenson
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3451): took 0.772656ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb8346038 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8349830 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,W/VideoCapabilities( 3634): Unsupported mime video/mp4v-esdp
,E/audit   ( 1846): type=1400 msg=audit(1448020185.691:203): avc:  denied  { ioctl } for  pid=3670 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1846):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1846): type=1300 msg=audit(1448020185.691:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=beb94d58 items=0 ppid=303 ppcomm=main pid=3670 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1846): type=1320 msg=audit(1448020185.691:203): 
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.613907ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb83499b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8349a60 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,I/Intent to TravelDirActivity( 4036): inside TravelBroadcastReceiver
,I/VideoCapabilities( 3634): Unsupported profile 4 for video/mp4v-es
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.712083ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb83499b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ff2158 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1016): Killing 2955:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,I/AMMetaDataParserService( 3451): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
W/ContextImpl( 3451): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3451): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3451): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3451): getResourcePackageName:assistant
I/AMMetaDataParserService( 3451): Resource data:2131099648
,I/ActivityManager( 1016): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4067 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/ActivityManager( 1016): Killing 3240:com.wssnps/1000 (adj 15): empty #31
,E/Zygote  ( 4067): MountEmulatedStorage()
E/Zygote  ( 4067): v2
I/libpersona( 4067): KNOX_SDCARD checking this for 1000
I/libpersona( 4067): KNOX_SDCARD not a persona
,W/ResourcesManager( 3451): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.,
W/ResourcesManager( 3451): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3451): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3451): getResourceName:com.android.mms:xml/assistant_messaging
W/ResourcesManager( 3451): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3451): getResourceTypeNamexml
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3451): took 0.789063ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fe0300 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fe7ea8 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 4067): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4067): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 4067): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3451): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/jxcore-log( 3670): Platform android
W/jxcore-log( 3670): 
W/jxcore-log( 3670): Process ARCH arm
W/jxcore-log( 3670): 
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3451): took 2.717188ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3451): took 8.970990ms for 0*0 texture 0
,I/GFX raster( 3451): took 12.794948ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fe2938 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7fd34d0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/TimaKeyStoreProvider( 4067): TimaSignature is unavailable
,I/GFX raster( 3451): took 0.805938ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb84f6a78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb84f6bb0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityThread( 4067): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3451): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/VideoCapabilities( 3634): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3634): Unrecognized profile 2130706433 for video/avc
,I/jxcore-log( 3670): JXcore Cordova bridge is ready!
I/jxcore-log( 3670): 
,W/jxcore-log( 3670): JXcore engine is started
,W/VideoCapabilities( 3634): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3634): Unrecognized profile 2130706433 for video/avc
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.659479ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb84fa2d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb834ece8 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1016): failed to open /acct/uid_10009/pid_2955/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3451): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3240/cgroup.procs: No such file or directory
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.677448ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb834ece8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fd9e48 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/DBG_DM  ( 2837): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.907604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb84f9bb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84f9cf0 counterpartCT=4 counterpartW=96 counterparth=96
,E/jxcore-log( 3670): >> samsung-SM-A500FU
E/jxcore-log( 3670): 
,I/jxcore-log( 3670): Total memory 1983787008
I/jxcore-log( 3670): 
,I/jxcore-log( 3670): Free memory 31469568
I/jxcore-log( 3670): 
I/jxcore-log( 3670): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3670): 
I/jxcore-log( 3670): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3670): 
,I/AMMetaDataParserService( 3451): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/jxcore-log( 3670): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 3670): 
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:assistant
I/AMMetaDataParserService( 3451): Resource data:2131099648
I/jxcore-log( 3670): Size 720 1280
I/jxcore-log( 3670): 
,I/AMMetaDataParserService( 3451): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3451): getResourceTypeNamexml
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/jxcore-log( 3670): Screen Brightness 5
I/jxcore-log( 3670): 
,I/GFX raster( 3451): took 0.905782ms for 96*96 texture 0
E/jxcore-log( 3670): Dummy Error Log.
E/jxcore-log( 3670): 
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fe0300 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7c08ef0 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4067): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/AMMetaDataParserService( 3451): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/DBG_POLICYDM( 4067): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/vclib   ( 3634): onServiceConnected
,W/Babel   ( 3634): Attempted to change video mute state without an active call.
,I/DBG_POLICYDM( 4067): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.652552ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fe2938 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7c08ef0 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_POLICYDM( 4067): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 4067): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,E/Zygote  ( 4086): MountEmulatedStorage(),
I/libpersona( 4086): KNOX_SDCARD checking this for 10035,
E/Zygote  ( 4086): v2
I/libpersona( 4086): KNOX_SDCARD not a persona
I/SELinux ( 4086): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 4086): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4086): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3451): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/DBG_POLICYDM( 4067): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/ActivityManager( 1016): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4086 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_POLICYDM( 4067): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/ActivityManager( 1016): Killing 2974:com.google.android.gms:car/u0a12 (adj 15): empty #31,
E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/GFX raster( 3451): took 0.692604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb84f6a78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7c08ef0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 4067): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 4067): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 4067): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,I/DBG_POLICYDM( 4067): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,I/AMMetaDataParserService( 3451): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/DBG_POLICYDM( 4067): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true],
I/DBG_POLICYDM( 4067): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 4067): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 4067): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,D/TimaKeyStoreProvider( 4086): TimaSignature is unavailable
,I/DBG_POLICYDM( 4067): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,D/ActivityThread( 4086): Added TimaKeyStore provider
,I/DBG_POLICYDM( 4067): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_POLICYDM( 4067): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.679532ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb84fa2d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7c08ef0 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3451): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.679896ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb834ece8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7c08ef0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520,
,I/ActivityManager( 1016): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4102 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/Zygote  ( 4102): MountEmulatedStorage()
I/libpersona( 4102): KNOX_SDCARD checking this for 10041
,E/Zygote  ( 4102): v2
I/libpersona( 4102): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Killing 3269:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
I/SELinux ( 4102): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
W/ActivityManager( 1016): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
,I/SELinux ( 4102): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4102): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4102): TimaSignature is unavailable
,D/ActivityThread( 4102): Added TimaKeyStore provider
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,I/DBG_POLICYDM( 4067): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 4067): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 4067): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,W/libprocessgroup( 1016): failed to open /acct/uid_10012/pid_2974/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10125/pid_3269/cgroup.procs: No such file or directory
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.735677ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fc9b38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83497f8 counterpartCT=4 counterpartW=96 counterparth=96
,E/DBG_POLICYDM( 4067): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,I/AMMetaDataParserService( 3451): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,E/SPPClientService( 4086): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4086): [PushClientApplication] Push log off : This is Ship build version
,I/SA      ( 4102): [SSP] onCreated
,E/SPPClientService( 4086): [SystemStateMoniter] Action Name : android.intent.action.BOOT_COMPLETED
E/SPPClientService( 4086): [SystemStateMoniter] Current Time : 39203
,D/SPPClientService( 4086): PushLog.txt file is not deleted.
,D/SPPClientService( 4086): PushLog.txt file is not deleted.
,D/SPPClientService( 4086): ============PushLog. stop!
,D/SSRM:n  ( 1016): SIOP:: AP = 400
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:assistant
I/AMMetaDataParserService( 3451): Resource data:2131099648
,I/AMMetaDataParserService( 3451): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3451): getResourceTypeNamexml
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3451): took 0.687552ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7ff0278 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7f76c00 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.622708ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7feb4c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7fb1f20 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4102): [TPM] There is no property file
,I/SA      ( 4102): [SCU] isHaveSA() - false
,E/Zygote  ( 4121): MountEmulatedStorage()
,E/Zygote  ( 4121): v2
I/libpersona( 4121): KNOX_SDCARD checking this for 10166
I/libpersona( 4121): KNOX_SDCARD not a persona
,I/AMMetaDataParserService( 3451): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
I/SELinux ( 4121): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4121 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/SA      ( 4102): [TPM] getModelProperty : null
I/ActivityManager( 1016): Killing 2892:com.android.vending/u0a28 (adj 15): empty #31
I/SA      ( 4102): [TPM] getCSCProperty : null
,I/SELinux ( 4121): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4121): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/SA      ( 4102): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4102): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4102): [DM] TFT FEATURE: false
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.706042ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7f79d70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7fb1fd8 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4102): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4102): [DM] init START
,I/AMMetaDataParserService( 3451): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/SA      ( 4102): [DM] This device is not a Vodafone
,D/TimaKeyStoreProvider( 4121): TimaSignature is unavailable
,D/ActivityThread( 4121): Added TimaKeyStore provider
,W/ResourceType( 4102): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4102): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4102): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4102): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4102): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 4102): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 4102): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4102): No package identifier when getting value for resource number 0x00000000
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ResourceType( 4102): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 4102): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4102): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 4102): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ResourceType( 4102): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 4102): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
I/GFX raster( 3451): took 0.659063ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fb1f20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7fd3150 counterpartCT=4 counterpartW=96 counterparth=96
W/ResourceType( 4102): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 4102): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 4102): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 4102): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 4102): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4102): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4102): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 4102): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4102): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4102): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 4102): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 4102): [SCU] isHaveSA() - false
I/SA      ( 4102): support phone number id : false
I/SA      ( 4102): [DM] Supports Ref Jpn : true
,I/SA      ( 4102): [DM] init END
,I/AMMetaDataParserService( 3451): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/SA      ( 4102): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
I/SA      ( 4102): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4102): [OR] onReceive END
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3451): took 0.633125ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb834ece8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7f7a4b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.735000ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fc9b38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fe0300 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4102): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4102): [ODM] queryOpenData(key= GEO_IP )
,I/AMMetaDataParserService( 3451): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:assistant
I/AMMetaDataParserService( 3451): Resource data:2131099648
,I/AMMetaDataParserService( 3451): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3451): getResourceTypeNamexml
,I/SA      ( 4102): getMccForGalaxyJpn step2 GEO_IP MCC : 260
E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/SA      ( 4102): [LBE] REF_JPN : true
I/SA      ( 4102): [BDC] create
,I/GFX raster( 3451): took 0.852969ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7ff0278 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7f7a4b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/jxcore-log( 3670): getBuffer is called!!!!
I/jxcore-log( 3670): 
,W/libprocessgroup( 1016): failed to open /acct/uid_10028/pid_2892/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3451): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.789271ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7feb4c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7fb1fd8 counterpartCT=4 counterpartW=96 counterparth=96
I/SA      ( 4102): [DBMV2] getEmailID
,I/SA      ( 4102): [DBMV2] getDataV02ForItems
,I/SA      ( 4102): [SSP] query invoked
,I/SA      ( 4102): [SCU] get signed id from samsung account2.0 DB.
,I/AMMetaDataParserService( 3451): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/SA      ( 4102): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4102): [BDC] destroy
,I/ActivityManager( 1016): Killing 3303:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,D/PackageManager( 1016): [MSG] MCS_UNBIND
,I/ActivityManager( 1016): Killing 3284:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.735208ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7f79d70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7fd3150 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/SQLiteLog( 1662): (10) POSIX Error : 11 SQLite Error : 3850
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.799583ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fb1f20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7fe0300 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.756928ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb834ece8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7c661c8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.893021ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fc9b38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fe2938 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:assistant
I/AMMetaDataParserService( 3451): Resource data:2131099648
,I/AMMetaDataParserService( 3451): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3451): getResourceTypeNamexml
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ResourcesManager( 4121): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4121): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/GFX raster( 3451): took 0.695156ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7ff0278 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fee690 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3303/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10014/pid_3284/cgroup.procs: No such file or directory
,V/JNIHelp ( 4121): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.709948ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7feb4c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7feafd8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityThread( 4121): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4121): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@38755f93: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4121): Installed default security provider GmsCore_OpenSSL
,I/AMMetaDataParserService( 3451): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.654167ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7f79d70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7f76c00 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.755261ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fb1f20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7feafd8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.744584ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb834ece8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7c661c8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.710104ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fc9b38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7f7a4b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 2837): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,I/AMMetaDataParserService( 3451): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:assistant
I/AMMetaDataParserService( 3451): Resource data:2131099648
,I/AMMetaDataParserService( 3451): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3451): getResourceTypeNamexml
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.700365ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7ff0278 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7f76c00 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.669688ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7feb4c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7fe1648 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.752187ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7f79d70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7fb1fd8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.759271ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fb1f20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7fceff8 counterpartCT=4 counterpartW=96 counterparth=96
,I/dex2oat ( 4150): ----------------------------------------------------
I/dex2oat ( 4150): <SS>: S T A R T I N G . . .
I/dex2oat ( 4150): <SS>: Zip is absent. Canceled.
I/dex2oat ( 4150): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1701885725.jar --oat-fd=25 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads1701885725.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/AMMetaDataParserService( 3451): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.629792ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb834ece8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fd3150 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3451): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/YouTube MDX( 4121): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 4150): dex2oat took 46.438ms (threads: 4)
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.717500ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb7fc9b38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7fe0300 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
W/ContextImpl( 3451): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3451): Resource data:Loop for ,running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3451): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:assistant
I/AMMetaDataParserService( 3451): Resource data:2131165197
W/ResourcesManager( 3451): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3451): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3451): getResourceTypeNamexml
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4121): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3451): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4167): MountEmulatedStorage()
E/Zygote  ( 4167): v2
I/libpersona( 4167): KNOX_SDCARD checking this for 10012
I/libpersona( 4167): KNOX_SDCARD not a persona
I/SELinux ( 4167): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=4167 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
I/SELinux ( 4167): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4167): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4167): TimaSignature is unavailable,
D/ActivityThread( 4167): Added TimaKeyStore provider
,W/ResourcesManager( 4167): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4167): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3451): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3451): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/MultiDex( 4167): VM with version 2.1.0 has multidex support
I/MultiDex( 4167): install
I/MultiDex( 4167): VM has multidex support, MultiDex support library is disabled.
,E/SMD     (  288): DCD OFF
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,V/JNIHelp ( 4167): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 4167): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4167): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2d8da791: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4167): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager( 1016): Killing 3347:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,I/AMMetaDataParserService( 3451): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3451): getResourcePackageName:assistant
I/AMMetaDataParserService( 3451): Resource data:2131165197
,I/AMMetaDataParserService( 3451): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3451): getResourceTypeNamexml
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4121): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/AMMetaDataParserService( 3451): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4121): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4121): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/InstanceID/Rpc( 4121): Found 10012
,W/libprocessgroup( 1016): failed to open /acct/uid_10069/pid_3347/cgroup.procs: No such file or directory
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,I/AMMetaDataParserService( 3451): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
W/ContextImpl( 4121): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/AMMetaDataParserService( 3451): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/AMMetaDataParserService( 3451): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:assistant
I/AMMetaDataParserService( 3451): Resource data:2131165197
,I/AMMetaDataParserService( 3451): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3451): getResourceTypeNamexml
,I/AMMetaDataParserService( 3451): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3451): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3451): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3451): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
W/ContextImpl( 3451): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.Pho,toNote
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3451): getResourcePackageName:assistant
I/AMMetaDataParserService( 3451): Resource data:2131099648
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 3451): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3451): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3451): getResourceTypeNamexml
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/AMMetaDataParserService( 3451): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3451): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4223): MountEmulatedStorage()
E/Zygote  ( 4223): v2
I/libpersona( 4223): KNOX_SDCARD checking this for 10101
I/libpersona( 4223): KNOX_SDCARD not a persona
,I/SELinux ( 4223): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4223): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4223): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 4223): TimaSignature is unavailable
I/ActivityManager( 1016): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4223 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityThread( 4223): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,W/ContextImpl( 3451): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,I/art     (  303): Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 975us total 22.647ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 603us total 16.876ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 609us total 17.080ms
,I/ActivityManager( 1016): Killing 3358:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 32434(1964KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 26MB/40MB, paused 2.316ms total 160.076ms
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:assistant
I/AMMetaDataParserService( 3451): Resource data:2131165220
,W/libprocessgroup( 1016): failed to open /acct/uid_10131/pid_3358/cgroup.procs: No such file or directory
,W/ResourcesManager( 3451): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3451): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3451): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3451): getResourceTypeNamexml
,I/iu.UploadsManager( 1937): End new media; added: 0, uploading: 0, time: 207 ms
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3451): took 0.703959ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb86eb848 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86eb578 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,E/        ( 3451): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3451): took 0.599635ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3451): Bitmap=0xb86eb698 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86fe1d8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3451): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SubSettings
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity,
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE,
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
,I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo,
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
,I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3451): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS,
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
,I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
W/ContextImpl( 3451): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/ActivityManager( 1016): Killing 3329:com.google.android.partnersetup/u0a15 (adj 15): empty #31
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
,I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
,I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
,I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
,I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
,I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMM,etaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:c,om.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
W/libprocessgroup( 1016): failed to open /acct/uid_10015/pid_3329/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
,I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3451): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3451): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3451): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
I/DBG_DM  ( 2837): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4223): getAccountsCursor
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 4223): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4223): Observing account changes for notifications
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 4223): Error finding the version of the Email provider.....
E/Gmail   ( 4223): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4223): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 4223): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4223): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4223): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4223): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4223): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 4223): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4223): We do not support migrating this version of the Email provider.
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/Gmail   ( 4223): getAccountsCursor
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4258): MountEmulatedStorage(),
E/Zygote  ( 4258): v2
I/libpersona( 4258): KNOX_SDCARD checking this for 10092
I/libpersona( 4258): KNOX_SDCARD not a persona
I/SELinux ( 4258): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 4258): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4258): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=4258 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 4258): TimaSignature is unavailable
,D/ActivityThread( 4258): Added TimaKeyStore provider
,E/ActivityThread( 4223): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2777b570 that was originally bound here
E/ActivityThread( 4223): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2777b570 that was originally bound here
E/ActivityThread( 4223): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 4223): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 4223): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 4223): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 4223): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 4223): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4223): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4223): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4223): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4223): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4223): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4223): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4223): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4223): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4223): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 4223): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): Unbind failed: could not find connection for android.os.BinderProxy@37af9a84
,E/SQLiteLog( 4223): (283) recovered 121 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,E/File    ( 4223): fail readDirectory() errno=2
,I/Gmail   ( 4223): notifyAccountChanged
,I/Gmail   ( 4223): getAccountsCursor
,I/Gmail   ( 4223): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/Gmail   ( 4223): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,E/Zygote  ( 4280): MountEmulatedStorage(),
E/Zygote  ( 4280): v2
I/libpersona( 4280): KNOX_SDCARD checking this for 10092
,I/libpersona( 4280): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=4280 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4280): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,I/SELinux ( 4280): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4280): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 4223): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
I/Gmail   ( 4223): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4223): calculateUnknownSyncRationalesAndPurgeInBackground: running,
,I/Gmail   ( 4223): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 4223): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
,D/TimaKeyStoreProvider( 4280): TimaSignature is unavailable
,D/ActivityThread( 4280): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 3470:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/com.dropbox.android.service.DropboxNetworkReceiver( 4258): Setting receiver enabled: false
,W/libprocessgroup( 1016): failed to open /acct/uid_10022/pid_3470/cgroup.procs: No such file or directory
,E/ActivityThread( 4258): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,I/Gmail   ( 4223): getAccountsCursor
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1016): Killing 3436:com.android.calendar/u0a135 (adj 15): empty #31
,I/dbxyzptlk.db300200.aw.h( 4258): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_9807ade0d39f04306c7e28de04204d1f53ae2228_armv7a
,D/breakpad( 4258): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,I/dbxyzptlk.db300200.aw.h( 4258): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_b492ffd532b8b6365d97439f842c164c3c90fd4e_armv7a
,I/dbxyzptlk.db300200.aw.h( 4258): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_e16babc055b114839529ea959e1ce06f2a593b63_armv7a
,W/libprocessgroup( 1016): failed to open /acct/uid_10135/pid_3436/cgroup.procs: No such file or directory
,I/libDropboxSync.so( 4258): Setting global terminate handler.
,I/dbxyzptlk.db300200.aw.h( 4258): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_aa417f8c60b792b71fc3cef90fc4bb8ddba4ea56_armv7a
,I/com.dropbox.sync.android.L( 4258): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,I/com.dropbox.sync.android.L( 4258): Removing unclaimed file/directory in cache: "local-dbapp_noauth"
,I/com.dropbox.sync.android.bf( 4258): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/3.0.2 DropboxSync/3.1+dev (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US)),
,W/art     ( 4258): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 4258): Attempt to remove local handle scope entry from IRT, ignoring
,I/DBG_DM  ( 2837): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,I/com.dropbox.sync.android.aS( 4258): Created NativeDbappNoAuthClientProvider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.sync.android.DbxSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,I/System.out( 4258): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 4258): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 4258): (HTTPLog)-Static: isShipBuild true
I/System.out( 4258): (HTTPLog)-Thread-677-197831632: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4258): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10092
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10092
,W/com.dropbox.sync.android.NativeHttp( 4258): GET failed: java.net.UnknownHostException: Unable to resolve host "api.dropbox.com": No address associated with hostname
,W/libDropboxSync.so(status)( 4258): NETWORK: CoreLogger.cpp:82: java.net.UnknownHostException: Unable to resolve host "api.dropbox.com": No address associated with hostname
,I/com.dropbox.sync.android.DbxSyncService( 4258): DbxSyncService starting.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4315): MountEmulatedStorage()
E/Zygote  ( 4315): v2
I/libpersona( 4315): KNOX_SDCARD checking this for 10057
I/ActivityManager( 1016): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4315 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
I/libpersona( 4315): KNOX_SDCARD not a persona
,I/SELinux ( 4315): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Killing 3451:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,I/SELinux ( 4315): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4315): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4315): TimaSignature is unavailable
,D/ActivityThread( 4315): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3451/cgroup.procs: No such file or directory
,D/LocationManagerService( 1016): getProviders()=[passive]
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4335 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,E/Zygote  ( 4335): MountEmulatedStorage()
E/Zygote  ( 4335): v2
I/libpersona( 4335): KNOX_SDCARD checking this for 10015
I/libpersona( 4335): KNOX_SDCARD not a persona
,I/SELinux ( 4335): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4335): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 4335): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/TimaKeyStoreProvider( 4335): TimaSignature is unavailable
,D/ActivityThread( 4335): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/splitIntent( 1016): Queue : backgroundsplit_2 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1016): Killing 3510:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/VelvetNetworkClient( 4315): Network connection not availble
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/GCM     ( 1662): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1662): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1937): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4370): MountEmulatedStorage()
,E/Zygote  ( 4370): v2
I/libpersona( 4370): KNOX_SDCARD checking this for 10012
I/libpersona( 4370): KNOX_SDCARD not a persona
I/SELinux ( 4370): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4370 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,I/SELinux ( 4370): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 4370): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 4315): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,D/TimaKeyStoreProvider( 4370): TimaSignature is unavailable
,D/ActivityThread( 4370): Added TimaKeyStore provider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1937): Restart initialization of location
,I/LibraryLoader( 4315): Time to load native libraries: 2 ms (timestamps 2606-2608)
I/LibraryLoader( 4315): Expected native library version number "",actual native library version number ""
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1662): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ResourcesManager( 4370): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4370): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/AuthorizationBluetoothService( 1662): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/art     ( 4315): Attempt to remove local handle scope entry from IRT, ignoring
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/MultiDex( 4370): VM with version 2.1.0 has multidex support
I/MultiDex( 4370): install
I/MultiDex( 4370): VM has multidex support, MultiDex support library is disabled.
,V/GmsCoreStatsServiceLauncher( 1937): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/JNIHelp ( 4370): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/libprocessgroup( 1016): failed to open /acct/uid_10139/pid_3510/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1937): Restart initialization of location
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityThread( 4370): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4370): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2d8da791: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4370): Installed default security provider GmsCore_OpenSSL
,W/art     ( 4315): Attempt to remove local handle scope entry from IRT, ignoring
,D/WearableService( 4370): callingUid 10012, callindPid: 4370
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,E/MDM     ( 1720): [190] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager( 1016): Killing 3552:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
E/MDM     ( 1720): [191] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2837): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,D/AuthorizationBluetoothService( 1662): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/GCM     ( 1662): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1937): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/art     ( 1937): Explicit concurrent mark sweep GC freed 27145(2044KB) AllocSpace objects, 24(384KB) LOS objects, 40% free, 10MB/17MB, paused 1.061ms total 59.114ms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1720): [192] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1937): Restart initialization of location
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3552/cgroup.procs: No such file or directory
,I/ValidateNoPeople( 1016): mEvictionCount: 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4411): MountEmulatedStorage()
I/libpersona( 4411): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4411): v2
I/libpersona( 4411): KNOX_SDCARD not a persona
I/SELinux ( 4411): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4411 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 4411): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4411): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4411): TimaSignature is unavailable
,D/ActivityThread( 4411): Added TimaKeyStore provider
,E/MTPRx   ( 4411): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1016): mCursor = null
,V/MTPRx   ( 4411): sealedState: false
V/MTPRx   ( 4411): sealedUsbMassStorageState: false
E/MTPRx   ( 4411): check value of boot_completed is1
E/MTPRx   ( 4411): check booting is completed_sys.boot_completed
,E/MTPRx   ( 4411): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4411): Status for mount/Unmount :removed
E/MTPRx   ( 4411): SDcard is not available
,W/MTPRx   ( 4411): value of connected istrue
W/MTPRx   ( 4411): value of configured istrue
W/MTPRx   ( 4411): value of mtpEnabled istrue
W/MTPRx   ( 4411): value of ptpEnabled isfalse
,E/MTPRx   ( 4411): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 4411): mFirstTime: false
,D/        ( 4411): MTP: reading debug level property
,E/MTPJNIInterface( 4411): Getting CryptionKey from JAVA
,E/MTPRx   ( 4411): currentUserId is 0
,E/MTPRx   ( 4411): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 4411): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 4411): is_Privatemode is NOT 1
,D/SettingsProvider( 1016): name = boot_time_connected
,E/MTPRx   ( 4411): Sending NORMAL_BOOT to stack
,E/MTPJNIInterface( 4411): noti = 17
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,E/SMD     (  288): DCD OFF
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 23033(1394KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/39MB, paused 1.987ms total 132.688ms
,D/SecContentProvider( 1016): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 4411): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1016): name = mtp_running_status
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,E/MTPRx   ( 4411): else part ... so first time!!!
,E/MTPPlaObsrvr( 4411): inside setContext()
E/MTPPlaObsrvr( 4411):  inside createplafiles
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text,
,E/MTPPlaObsrvr( 4411): playlist count is0
,E/MTPPlaObsrvr( 4411):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4411):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4411): Inside registerContentObserver
,E/MtpAdbObserver( 4411): inside setContext(),
E/MtpAdbObserver( 4411): Inside registerContentObserver
,W/Settings( 4411): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1016): name = mtp_running_status
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,E/MtpService( 4411): onCreate.
V/MtpMediaDBManager( 4411): inside deleteAllDB
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
E/MtpService( 4411): < MTP > Registering BroadCast receiver :::::
E/MtpService( 4411): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
E/MtpService( 4411): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
D/MtpService( 1224): updating state; isCurrentUser=true, mMtpLocked=false
E/MtpService( 4411): onStartCommand.
W/MTPRx   ( 4411): calling native method
E/MTPJNIInterface( 4411): < MTP > Registering BroadCast receiver :::::
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/MtpService( 4411): handleMessage. msg= { when=-2ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
V/MtpMediaDBManager( 4411): inside Thread updateDB
,E/Zygote  ( 4430): MountEmulatedStorage()
E/Zygote  ( 4430): v2
I/libpersona( 4430): KNOX_SDCARD checking this for 1000
I/libpersona( 4430): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4430 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 4430): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,E/MTPJNIInterface( 4411): < MTP > Registering BroadCast receiver :::::::,
I/SELinux ( 4430): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/MTPJNIInterface( 4411): noti = 10
E/MtpService( 4411): onStartCommand.
,W/MTPRx   ( 4411): calling native method
E/MTPRx   ( 4411): Checking the driver time out
E/MTPJNIInterface( 4411): noti = 2
D/        ( 4411): deleting sockets before message queue initialization
D/        ( 4411): event handler thread is created, so set the flag
,E/SELinux ( 4430): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/MtpService( 4411): handleMessage. msg= { when=-3ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPRx   ( 4411): called native method
E/MTPJNIInterface( 4411): setting Media scanner status0
E/MTPJNIInterface( 4411): After setting Media scanner status0
W/MTPRx   ( 4411): notification from stack 1,
E/        ( 4411): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 4411): Getting media scanner status0
,E/MtpMediaDBManager( 4411): count : 27
,E/MTPJNIInterface( 4411): DeviceName is Thali Test (Galaxy A5)
,W/MtpMediaDBManager( 4411): sending db update complete noti to stack
E/MTPJNIInterface( 4411): noti = 29
,D/TimaKeyStoreProvider( 4430): TimaSignature is unavailable
,D/ActivityThread( 4430): Added TimaKeyStore provider
,E/MTPJNIInterface( 4411): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4411): SDcard is not available
,E/        ( 4411): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface( 4411): Status for mount/Unmount :removed
E/MTPJNIInterface( 4411): SDcard is not available
E/SQLiteLog( 4411): (21) API call with NULL database connection pointer
E/SQLiteLog( 4411): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4411): (21) API call with NULL database connection pointer
E/SQLiteLog( 4411): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4411): (21) API call with NULL database connection pointer
E/SQLiteLog( 4411): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4411): (21) API call with NULL database connection pointer
E/SQLiteLog( 4411): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 4411): notification from stack 2
,D/        ( 4411): [mtp_init_device] Library open with 32 bits.
,D/        ( 4411): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 4411): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 4411): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,E/        ( 4411):  [sua_support_present:1287] returning false 
D/        ( 4411): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
