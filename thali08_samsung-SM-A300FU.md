#### Test 60124347d1a8dac_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
I/KLMS-2.5.123: ( 3705): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 10 15:21:14 GMT+01:00 2016
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/RlzPingService( 3417): Setting next ping for 1458224474478
I/KLMS-2.5.123: ( 3705): KLMSAbstractReciever(): onReceive().END.
D/SystemUpdateService( 2064): onDestroy
--------- beginning of system
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3728): TimaSignature is unavailable
I/KLMS-2.5.123: ( 3705): KLMSIntentService(): onCreate()
D/ActivityThread( 3728): Added TimaKeyStore provider
E/Zygote  ( 3745): MountEmulatedStorage()
E/Zygote  ( 3745): v2
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2933/cgroup.procs: No such file or directory
I/libpersona( 3745): KNOX_SDCARD checking this for 10020
I/libpersona( 3745): KNOX_SDCARD not a persona
I/KLMS-2.5.123: ( 3705): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/SELinux ( 3745): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/KLMS-2.5.123: ( 3705): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/SELinux ( 3745): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3745): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3705): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
W/art     ( 2064): Suspending all threads took: 5.034ms
I/KLMS-2.5.123: ( 3705): KLMSIntentService(): BOOT_COMPLETED
I/ActivityManager( 1017): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3745 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
D/TimaKeyStoreProvider( 3745): TimaSignature is unavailable
D/ActivityThread( 3745): Added TimaKeyStore provider
I/qtaguid ( 3303): Tagging socket 39 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3766): MountEmulatedStorage()
I/ActivityManager( 1017): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3766 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 3766): v2
I/ActivityManager( 1017): Killing 2256:flipboard.app/u0a96 (adj 15): empty #31
I/SELinux ( 3766): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 3766): KNOX_SDCARD checking this for 1000
I/libpersona( 3766): KNOX_SDCARD not a persona
I/SELinux ( 3766): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3766): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3766): TimaSignature is unavailable
D/ActivityThread( 3766): Added TimaKeyStore provider
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
D/NPS_WSSNPS( 3728): [] android.intent.action.BOOT_COMPLETED
I/Gmail   ( 3610): getAccountsCursor
W/ContextImpl( 3728): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/NPS_WSSNPS( 3728): [] Service onCreate!!
E/Zygote  ( 3787): MountEmulatedStorage()
E/Zygote  ( 3787): v2
I/libpersona( 3787): KNOX_SDCARD checking this for 1000
I/libpersona( 3787): KNOX_SDCARD not a persona
I/SELinux ( 3787): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3787): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3787): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3787 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/GAV2    ( 3610): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/NPS_WSSNPS( 3728): [50.150321] NpsServiceTask Start
I/KLMS-2.5.123: ( 3705): KLMSIntentService(): onDestroy()
D/TimaKeyStoreProvider( 3787): TimaSignature is unavailable
D/ActivityThread( 3787): Added TimaKeyStore provider
W/libprocessgroup( 1017): failed to open /acct/uid_10096/pid_2256/cgroup.procs: No such file or directory
D/NPS_WSSNPS( 3728): [50.150321] smlDBHelper
I/qtaguid ( 3303): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
I/qtaguid ( 3303): Untagging socket 43
I/qtaguid ( 3303): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
I/qtaguid ( 3303): Untagging socket 43
I/qtaguid ( 3303): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
I/qtaguid ( 3303): Untagging socket 43
I/qtaguid ( 3303): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
I/qtaguid ( 3303): Untagging socket 43
I/qtaguid ( 3303): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
E/MTPRx   ( 3766): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
I/qtaguid ( 3303): Untagging socket 43
I/qtaguid ( 3303): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
I/qtaguid ( 3303): Untagging socket 43
I/qtaguid ( 3303): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
I/qtaguid ( 3303): Untagging socket 43
I/qtaguid ( 3303): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
I/qtaguid ( 3303): Untagging socket 43
D/SecContentProvider2( 1017): uri = 14 selection = getSealedState
D/SecContentProvider2( 1017): mCursor = null
I/qtaguid ( 3303): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
I/qtaguid ( 3303): Untagging socket 43
I/qtaguid ( 3303): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
I/qtaguid ( 3303): Untagging socket 43
I/qtaguid ( 3303): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
I/qtaguid ( 3303): Untagging socket 43
I/qtaguid ( 3303): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
I/qtaguid ( 3303): Untagging socket 43
I/qtaguid ( 3303): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
D/SecContentProvider2( 1017): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1017): mCursor = null
V/MTPRx   ( 3766): sealedState: false
V/MTPRx   ( 3766): sealedUsbMassStorageState: false
I/qtaguid ( 3303): Untagging socket 43
D/SettingsProvider( 1017): name = mtp_usb_connection_status
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/SettingsProvider( 1017): name = access_control_enabled
I/NPS_WSSNPS( 3728): [50.150321] AsyncBulkFlagCheck
D/SettingsProvider( 1017): name = media_player_mode
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
I/NPS_WSSNPS( 3728): [50.150321] IsRemain_AsyncBulkCheck
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/NPS_WSSNPS( 3728): [50.150321] IsRemain_Asyncing nothing
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 3728): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
D/SettingsProvider( 1017): name = mtp_usb_conditions_met
E/Zygote  ( 3813): MountEmulatedStorage()
E/Zygote  ( 3813): v2
I/libpersona( 3813): KNOX_SDCARD checking this for 10065
I/libpersona( 3813): KNOX_SDCARD not a persona
I/SELinux ( 3813): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3813): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3813 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/SettingsProvider( 1017): name = mtp_running_status
E/SELinux ( 3813): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 2856:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
D/SettingsProvider( 1017): name = media_mount_count
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
D/NPS_WSSNPS( 3728): [50.150321] Service onDestroy
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/SettingsProvider( 1017): name = mtp_sync_alive
W/ActivityManager( 1017): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/NPS_WSSNPS( 3728): [50.150321] smlBRConfigurationDelete
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/NPS_WSSNPS( 3728): [50.150321] smlBRMessageDelete
I/NPS_WSSNPS( 3728): [50.150321] smlBREmailDelete
I/NPS_WSSNPS( 3728): [50.150321] smlBRNetworkDelete
I/NPS_WSSNPS( 3728): [50.150321] smlBRCallLogDelete
I/NPS_WSSNPS( 3728): [50.150321] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 3728): [50.150321] smlBRPenMemoMDelete
I/NPS_WSSNPS( 3728): [50.150321] smlBRSMemoDelete
I/NPS_WSSNPS( 3728): [50.150321] cpuBooster release : false
E/Gmail   ( 3610): Error finding the version of the Email provider.....
E/Gmail   ( 3610): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3610): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3610): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 3610): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3610): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3610): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3610): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3610): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 3610): We do not support migrating this version of the Email provider.
D/NPS_WSSNPS( 3728): [50.150321] dsServerSocket close
D/TimaKeyStoreProvider( 3813): TimaSignature is unavailable
I/ActivityManager( 1017): Killing 2387:com.android.mms/u0a41 (adj 15): empty #31
D/ActivityThread( 3813): Added TimaKeyStore provider
I/qtaguid ( 3303): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
E/BaseAppContext( 2064): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
D/SettingsProvider( 1017): name = sdcard_launch
D/SettingsProvider( 1017): name = boot_time_connected
D/CountryDetector( 1017): No listener is left
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/SettingsProvider( 1017): name = mtp_open_session
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 3610): Observing account changes for notifications
I/ActivityManager( 1017): Killing 3009:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
W/art     ( 3303): Suspending all threads took: 21.080ms
W/libprocessgroup( 1017): failed to open /acct/uid_10081/pid_2856/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10041/pid_2387/cgroup.procs: No such file or directory
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/art     ( 1628): Explicit concurrent mark sweep GC freed 3856(152KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 775us total 35.713ms
D/FileShare-Server( 3813): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
I/PCWCLIENTTRACE_PushUtil( 3474): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3474): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3474): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3474): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3474): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3474): ACTION_BOOTUP - Push type: [SPP, GCM]
W/GAV2    ( 3303): Thread[Background Non-Blocking-1,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/GAV2    ( 3303): Thread[Background Non-Blocking-1,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ContactAccountLoggerTas( 3303): canRun() : Opted Out
I/ContactAccountLoggerTas( 3303): canRun() : Opted Out
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
I/ContactAccountLoggerTas( 3303): canRun() : Opted Out
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/PCWCLIENTTRACE_AccountUtil( 3474): [hasSamungAccount] - No Samsung Account
W/libprocessgroup( 1017): failed to open /acct/uid_10043/pid_3009/cgroup.procs: No such file or directory
E/Zygote  ( 3844): MountEmulatedStorage()
I/libpersona( 3844): KNOX_SDCARD checking this for 10102
E/Zygote  ( 3844): v2
I/libpersona( 3844): KNOX_SDCARD not a persona
I/SELinux ( 3844): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/GoogleHttpClient( 1628): GMS http client unavailable, use old client
I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3844 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager( 1017): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/SELinux ( 3844): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3844): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/AuthZen ( 2064): Fetching signing key...
E/ActivityThread( 3610): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@e958f4f that was originally bound here
E/ActivityThread( 3610): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@e958f4f that was originally bound here
E/ActivityThread( 3610): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3610): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3610): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3610): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3610): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3610): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 3610): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 3610): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 3610): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 3610): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 3610): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 3610): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 3610): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3610): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3610): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3610): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1017): Unbind failed: could not find connection for android.os.BinderProxy@c2ccdeb
D/TimaKeyStoreProvider( 3844): TimaSignature is unavailable
D/ActivityThread( 3844): Added TimaKeyStore provider
I/PCWCLIENTTRACE_SecurePreferencesJNI( 3474): [GetString-S]
I/ReactiveServiceManager( 3474): Supported : 1
D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
E/SQLiteLog( 2064): (10) POSIX Error : 11 SQLite Error : 3850
D/FactoryTestApp( 2627): [DummyFtClient$onDestroy](2627) Destroy DummyFtClient service
D/FactoryTestApp( 2627): [Support$Values.getString](2627) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2627): [ModuleCommon$isConnectionModeNone](2627) mConnectionMode = gsm
I/FactoryTestApp( 2627): [ModuleCommon$isRunningFtClient](2627) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2627): [DummyFtClient$onDestroy](2627) kill process
I/Process ( 2627): Sending signal. PID: 2627 SIG: 9
W/ResourcesManager( 3844): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/AuthZen ( 2064): Signing key fetched successfully!
W/BaseAppContext( 2064): Using Auth Proxy for data requests.
D/QSEECOMAPI: ( 1017): Loaded image: APP id = 9
D/QSEECOMAPI: ( 1017): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1017): QSEECom_shutdown_app, app_id = 9
E/terrier ( 1017): handleString: Failed to handle string(-4)
E/terrier ( 1017): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 3474): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 3474): [GetString-E]
I/PCWCLIENTTRACE_PushUtil( 3474): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3474): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3474): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 3474): [ensureRegistration] - No Samsung account
D/AndroidRuntime( 3784): 
D/AndroidRuntime( 3784): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3784): CheckJNI is OFF
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 3784): readGMSProperty: start
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 3784): readGMSProperty: already setted!!
D/AndroidRuntime( 3784): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3784): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3784): readGMSProperty: end
D/AndroidRuntime( 3784): addProductProperty: start
E/Zygote  ( 3861): MountEmulatedStorage()
E/Zygote  ( 3861): v2
I/libpersona( 3861): KNOX_SDCARD checking this for 10028
I/libpersona( 3861): KNOX_SDCARD not a persona
I/SELinux ( 3861): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3861): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3861 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3057:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
E/SELinux ( 3861): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/a       ( 2064): Opening database auth.proximity.permit_store...
D/AuthZenTransactionCache( 2064): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2064): Clearing transaction cache
I/ActivityManager( 1017): Process com.sec.factory (pid 2627)(adj 0) has died(73,611)
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 1734): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TimaKeyStoreProvider( 3861): TimaSignature is unavailable
D/ActivityThread( 3861): Added TimaKeyStore provider
I/GCoreUlr( 1734): DispatchingService.onCreate()
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3057/cgroup.procs: No such file or directory
D/btif_config_util( 2649): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
I/DBG_DM  ( 3215): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
I/DBG_POLICYDM( 3282): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 3282): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
I/DBG_POLICYDM( 3282): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
I/DBG_POLICYDM( 3282): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
I/DBG_POLICYDM( 3282): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
I/DBG_POLICYDM( 3282): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
I/DBG_POLICYDM( 3282): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
I/DBG_POLICYDM( 3282): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
I/System.out( 3861): Inside onCreate() of WakeupTriggerProvide
I/System.out( 3861): Inside WakeupProvider
E/AffinityControl( 3784): AffinityControl: registerfunction enter
I/VlingoApplication( 3861): VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
I/Babel   ( 3844): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3844): MmsConfig.loadMmsSettings
I/Babel   ( 3844): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel   ( 3844): MmsConfig.loadFromDatabase
D/AndroidRuntime( 3784): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1017): mDVFSHelper.acquire()
D/FocusedStackFrame( 1017): Set to : 0
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 1499
D/AndroidRuntime( 3784): Shutting down VM
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : -2122120936
W/Settings( 3844): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/VlingoAndroidCore( 3861): AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/Launcher.HomeView( 1499): onPause
D/Launcher( 1499): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=11 createSurf (1x1),1 flag=404, uhalitest
E/Babel   ( 3844): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3844): MmsConfig.loadFromResources
E/Babel   ( 3844): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3844): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/GCM     ( 1734): GCM config loaded
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3908): MountEmulatedStorage()
E/Zygote  ( 3908): v2
I/libpersona( 3908): KNOX_SDCARD checking this for 10167
I/libpersona( 3908): KNOX_SDCARD not a persona
W/art     ( 3844): Suspending all threads took: 16.231ms
I/SELinux ( 3908): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3908 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3908): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3908): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/VideoCapabilities( 3844): Unrecognized profile 2130706433 for video/avc
V/ActivityThread( 1499): updateVisibility : ActivityRecord{33e3e612 token=android.os.BinderProxy@376b2f90 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
W/GoogleHttpServiceClient( 1734): Timeout on service connection
W/GoogleHttpServiceClient( 1734): java.lang.Throwable
W/GoogleHttpServiceClient( 1734): 	at com.google.android.gms.http.e.a(:com.google.android.gms:97)
W/GoogleHttpServiceClient( 1734): 	at com.google.android.gms.http.g.a(:com.google.android.gms:146)
W/GoogleHttpServiceClient( 1734): 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:757)
W/GoogleHttpServiceClient( 1734): 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:665)
W/GoogleHttpServiceClient( 1734): 	at com.google.android.gms.auth.j.a.a(:com.google.android.gms:77)
W/GoogleHttpServiceClient( 1734): 	at com.google.android.gms.auth.j.a.a(:com.google.android.gms:114)
W/GoogleHttpServiceClient( 1734): 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:115)
W/GoogleHttpServiceClient( 1734): 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
W/GoogleHttpServiceClient( 1734): 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
W/GoogleHttpServiceClient( 1734): 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
W/GoogleHttpServiceClient( 1734): 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
W/GoogleHttpServiceClient( 1734): 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
W/GoogleHttpServiceClient( 1734): 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
W/GoogleHttpServiceClient( 1734): 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
W/GoogleHttpServiceClient( 1734): 	at com.google.android.gms.auth.o.a(:com.google.android.gms:118)
W/GoogleHttpServiceClient( 1734): 	at com.google.android.b.b.onTransact(:com.google.android.gms:63)
W/GoogleHttpServiceClient( 1734): 	at android.os.Binder.execTransact(Binder.java:461)
D/TimaKeyStoreProvider( 3908): TimaSignature is unavailable
D/ActivityThread( 3908): Added TimaKeyStore provider
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
W/AudioCapabilities( 3844): Unsupported mime audio/evrc
I/System.out( 1734): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1734): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1734): (HTTPLog)-Static: isShipBuild true
I/System.out( 1734): (HTTPLog)-Thread-145-1005419078: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1734): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
D/Launcher.HomeView( 1499): onStop
V/ActivityThread( 1499): updateVisibility : ActivityRecord{33e3e612 token=android.os.BinderProxy@376b2f90 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1499): onTrimMemory. Level: 20
W/AudioCapabilities( 3844): Unsupported mime audio/qcelp
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1017): isKioskContainerExistOnDevice
W/AudioCapabilities( 3844): Unsupported mime audio/mpeg-L1
W/AudioCapabilities( 3844): Unsupported mime audio/mpeg-L2
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1017): [SO] activate (ident=0xb7fbc2d8, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/SensorManager( 1017): unregisterListener ::   
I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 66000000(ns)
W/AudioCapabilities( 3844): Unsupported mime audio/x-ms-wma
D/SensorService( 1017): [SO] changed settle time [1]
D/SensorService( 1017): [SO] setDelay [66000000]
D/SensorService( 1017): [SO] activate (ident=0xb7fbc2d8, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
W/AudioCapabilities( 3844): Unsupported mime audio/x-ima
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/AudioCapabilities( 3844): Unsupported mime audio/qcelp
W/AudioCapabilities( 3844): Unsupported mime audio/evrc
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/art     ( 3784): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/art     ( 3844): Suspending all threads took: 17.243ms
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,I/System.out( 1734): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1734): Tagging socket 54 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1734, getuid(): 10011
,W/VideoCapabilities( 3844): Unsupported mime video/wvc1
,W/VideoCapabilities( 3844): Unsupported mime video/x-ms-wmv
,I/Gmail   ( 3610): getAccountsCursor
,D/VlingoApplication( 3861): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 3861): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,W/VideoCapabilities( 3844): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 3844): Unsupported mime video/wvc1
,I/Icing   ( 2064): Storage manager: low false usage 2.09MB avail 9.95GB capacity 11.63GB
,E/SQLiteLog( 3610): (283) recovered 103 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
W/VideoCapabilities( 3844): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 3844): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 3844): Unsupported mime video/x-ms-wmv8
,D/SensorService( 1017): [SO] currT = 42721051000, prevT = 42391385000, diff = 329666000, [-0.402 0.172 9.902]
D/SensorService( 1017): [SO] -0.402 0.172 9.902
D/SensorService( 1017): [SO] [100 -> 255]
,W/VideoCapabilities( 3844): Unsupported mime video/mp43
,W/VideoCapabilities( 3844): Unsupported mime video/sorenson
,W/VideoCapabilities( 3844): Unsupported mime video/mp4v-esdp
,D/DialogFlow( 3861): initQueue()
,I/qtaguid ( 1734): Tagging socket 69 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1734, getuid(): 10011
,V/Babel   ( 3844): babel boot account: SMS
,V/Babel   ( 3844): babel boot account: thalitester@gmail.com
,I/GCoreUlr( 1734): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/VideoCapabilities( 3844): Unsupported profile 4 for video/mp4v-es
,I/WebViewFactory( 3908): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 43386(2MB) AllocSpace objects, 38(608KB) LOS objects, 39% free, 10MB/16MB, paused 1.548ms total 182.038ms
,I/LibraryLoader( 3908): Loading: webviewchromium
,I/LibraryLoader( 3908): Time to load native libraries: 10 ms (timestamps 2846-2856)
I/LibraryLoader( 3908): Expected native library version number "",actual native library version number ""
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 43355(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 22MB/34MB, paused 2.702ms total 216.552ms
,I/ActivityManager( 1017): Killing 3084:com.sec.dsm.system/1000 (adj 15): empty #31
,V/AlarmManager( 1017): waitForAlarm result :4
,V/WebViewChromiumFactoryProvider( 3908): Binding Chromium to main looper Looper (main, tid 1) {1ea94695}
,I/LibraryLoader( 3908): Expected native library version number "",actual native library version number ""
,I/chromium( 3908): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1017): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3945): MountEmulatedStorage(),
E/Zygote  ( 3945): v2
I/libpersona( 3945): KNOX_SDCARD checking this for 1000
,I/libpersona( 3945): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3945 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/BrowserStartupController( 3908): Initializing chromium process, renderers=0
,I/DBG_DM  ( 3215): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,I/ActivityManager( 1017): Killing 3137:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31,
W/art     ( 3908): Attempt to remove local handle scope entry from IRT, ignoring
,I/SELinux ( 3945): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 3945): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3945): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/8)
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/8)
,E/Zygote  ( 3966): MountEmulatedStorage()
E/Zygote  ( 3966): v2
I/libpersona( 3966): KNOX_SDCARD checking this for 1000
I/libpersona( 3966): KNOX_SDCARD not a persona
,W/chromium( 3908): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 3908): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/ActivityManager( 1017): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3966 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3966): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/TimaKeyStoreProvider( 3945): TimaSignature is unavailable
D/ActivityThread( 3945): Added TimaKeyStore provider
I/SELinux ( 3966): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3966): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/chromium( 3908): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
E/File    ( 3610): fail readDirectory() errno=2
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3084/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3137/cgroup.procs: No such file or directory
,I/art     (  308): Explicit concurrent mark sweep GC freed 8711(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 35.372ms
,V/AlarmManager( 1017): waitForAlarm result :4
,D/TimaKeyStoreProvider( 3966): TimaSignature is unavailable
,D/ActivityThread( 3966): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 605us total 17.556ms,
,I/Adreno-EGL( 3908): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3908): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3908): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3908): Local Branch: 
I/Adreno-EGL( 3908): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3908): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3908):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 18.757ms
,I/Gmail   ( 3610): notifyAccountChanged
,I/Gmail   ( 3610): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/GCoreFlp( 1734): No location to return for getLastLocation()
,W/FusedLocationProvider( 1734): location=null
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3990): MountEmulatedStorage(),
E/Zygote  ( 3990): v2
,I/libpersona( 3990): KNOX_SDCARD checking this for 10029
I/libpersona( 3990): KNOX_SDCARD not a persona,
,I/SELinux ( 3990): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3990 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 1598:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
I/SELinux ( 3990): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3990): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
,E/SMD     (  290): DCD OFF
,D/TimaKeyStoreProvider( 3990): TimaSignature is unavailable
,D/ActivityThread( 3990): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 3159:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 3197:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,I/Gmail   ( 3610): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3610): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3610): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ContextImpl( 3966): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4008 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/libprocessgroup( 1017): failed to open /acct/uid_10068/pid_1598/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10146/pid_3197/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3159/cgroup.procs: No such file or directory
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4008): MountEmulatedStorage()
E/Zygote  ( 4008): v2
,I/libpersona( 4008): KNOX_SDCARD checking this for 1000
I/libpersona( 4008): KNOX_SDCARD not a persona
,I/SELinux ( 4008): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4008): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4008): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 4019): MountEmulatedStorage()
E/Zygote  ( 4019): v2
I/libpersona( 4019): KNOX_SDCARD checking this for 1000
I/libpersona( 4019): KNOX_SDCARD not a persona
,I/SELinux ( 4019): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4019 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 4019): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4019): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4008): TimaSignature is unavailable
,D/ActivityThread( 4008): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4039): MountEmulatedStorage()
E/Zygote  ( 4039): v2
,I/libpersona( 4039): KNOX_SDCARD checking this for 10030
I/libpersona( 4039): KNOX_SDCARD not a persona
,I/SELinux ( 4039): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4039 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3115:com.google.android.configupdater/u0a82 (adj 15): empty #31
I/SELinux ( 4039): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4039): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4019): TimaSignature is unavailable
,D/ActivityThread( 4019): Added TimaKeyStore provider
,W/ResourcesManager( 4008): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 4039): TimaSignature is unavailable
,D/ActivityThread( 4039): Added TimaKeyStore provider
,E/KnoxSetupWizardClient( 4019): isShipMode : 1
I/KnoxSetupWizardClient( 4019): onReceive : android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 4008): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/F_PHONE ( 4008): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,E/Zygote  ( 4061): MountEmulatedStorage()
,E/Zygote  ( 4061): v2
I/libpersona( 4061): KNOX_SDCARD checking this for 1000
I/libpersona( 4061): KNOX_SDCARD not a persona
,I/SELinux ( 4061): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4061): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4061): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=4061 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ContextImpl( 4008): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,D/TimaKeyStoreProvider( 4061): TimaSignature is unavailable
,D/ActivityThread( 4061): Added TimaKeyStore provider
,D/F_PHONE ( 4008): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 4008): default registerAction()
I/F_PHONE ( 4008): [[com.sec.bcservice]] sendPendingMessage()
,W/ResourcesManager( 4061): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ShortcutReceiver( 4019):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,W/System.err( 4019): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,I/System.out( 3236): Thread-418(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3236): Thread-418(ApacheHTTPLog):isShipBuild true
I/System.out( 3236): Thread-418(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3236): Thread-418(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10088
W/System.err( 4019): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4019): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4019): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 4019): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 4019): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4019): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,D/BluetoothBDAdrressReceiver( 4061): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 4061): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,D/KnoxShortcutUtil( 4019): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4019):  KnoxContainerVersion 2.3.0
D/ShortcutReceiver( 4019):  shortcut migration not required 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4083): MountEmulatedStorage(),
,E/Zygote  ( 4083): v2
I/libpersona( 4083): KNOX_SDCARD checking this for 1000
I/libpersona( 4083): KNOX_SDCARD not a persona
W/ResourcesManager( 1468): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/SELinux ( 4083): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/BluetoothBDTestService( 1468): onCreate()
E/BluetoothBDTestService( 1468): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1468): bd_address_path: /efs/bluetooth/bt_addr
,I/SELinux ( 4083): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/BluetoothBDTestService( 1468): already exist!( /efs/bluetooth/bt_addr ), file length: 17
E/SELinux ( 4083): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1017): failed to open /acct/uid_10082/pid_3115/cgroup.procs: No such file or directory
,D/GCMRegistrar( 3236): resetting backoff for com.dropbox.android
,V/GCMRegistrar( 3236): Registering app com.dropbox.android of senders 735665981150
,I/ActivityManager( 1017): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4083 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4083): TimaSignature is unavailable,
D/ActivityThread( 4083): Added TimaKeyStore provider
,E/Zygote  ( 4098): MountEmulatedStorage(),
E/Zygote  ( 4098): v2
I/libpersona( 4098): KNOX_SDCARD checking this for 1000
I/libpersona( 4098): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=4098 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4098): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Killing 3236:com.dropbox.android/u0a88 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.google.process.gapps
I/SELinux ( 4098): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4098): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/chromium( 3908): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 3908): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4098): TimaSignature is unavailable
,D/ActivityThread( 4098): Added TimaKeyStore provider
,D/StatusChecker( 4083): onReceive : android.intent.action.BOOT_COMPLETED
,I/ActivityManager( 1017): Killing 3257:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
,W/art     ( 3908): Attempt to remove local handle scope entry from IRT, ignoring
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,W/AwContents( 3908): onDetachedFromWindow called when already detached. Ignoring
,W/ResourcesManager( 4098): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/FrameworkListener(  280): read() failed (Connection reset by peer)
,D/PhoneWindow( 3908): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3908): *FMB* installDecor flags : -2139027200
,I/StatusChecker( 4083): onReceive : net.mt.init : DONE
,W/Auth    ( 1734): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,D/SystemWebViewEngine( 3908): CordovaWebView is running on device made by: samsung
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4122): MountEmulatedStorage()
I/libpersona( 4122): KNOX_SDCARD checking this for 10113
E/Zygote  ( 4122): v2
I/libpersona( 4122): KNOX_SDCARD not a persona
,I/SELinux ( 4122): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4122): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 4122): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4122 uid=10113 gids={50113, 9997} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3282:com.policydm/1000 (adj 15): empty #31
,W/art     ( 3908): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3908): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ContactAccountLoggerTas( 3303): canRun() : Opted Out
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 4122): TimaSignature is unavailable
,D/ActivityThread( 4122): Added TimaKeyStore provider
,I/System.out( 1734): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1734): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/OpenGLRenderer( 3908): Render dirty regions requested: true
,W/libprocessgroup( 1017): failed to open /acct/uid_10088/pid_3236/cgroup.procs: No such file or directory
,D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,D/PhoneWindow( 3908): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3908): *FMB* isFloatingMenuEnabled return false
,I/PageBuddyNotiSvc( 4122): Intent received : action=android.intent.action.BOOT_COMPLETED,
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3282/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10088/pid_3257/cgroup.procs: No such file or directory
,D/PersistentNotificationBroadcastReceiver( 1734): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, NainActivit
,W/ContextImpl( 4122): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,D/InputDispatcher( 1017): Focus entered window: 3908
,I/PageBuddyNotiSvc( 4122): onCreate mCpBitFlag=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 3908): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 3908): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3908): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096,
D/OpenGLRenderer( 3908): Enabling debug mode 0
,I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4146 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/Zygote  ( 4146): MountEmulatedStorage()
E/Zygote  ( 4146): v2
I/libpersona( 4146): KNOX_SDCARD checking this for 10121,
I/libpersona( 4146): KNOX_SDCARD not a persona,
,I/SELinux ( 4146): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4146): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4146): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KnoxUsageLogPro( 4098): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/KnoxUsageLogPro( 4098): savePreference: key = previous_sys_time value = 1457619677350
,I/KnoxUsageLogPro( 4098): premStatus:2
,I/KnoxUsageLogPro( 4098): isEulaShown : false
,I/KnoxUsageLogPro( 4098): KnoxUsageReceiver onReceive : not Processible, just return
,I/ActivityManager( 1017): Killing 3402:com.fmm.dm/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4146): TimaSignature is unavailable
,D/ActivityThread( 4146): Added TimaKeyStore provider
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PCWCLIENTTRACE_AccountAppFacade2_0( 3474): unregister AuthInfo UpdateReceiver v2.0
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/GCoreUlr( 1734): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3402/cgroup.procs: No such file or directory
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1172): There is/are notification(s) 
,I/DBG_DM  ( 3215): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/Timeline( 3908): Timeline: Activity_idle id: android.os.BinderProxy@ae2268 time:43974
,E/Zygote  ( 4171): MountEmulatedStorage()
I/libpersona( 4171): KNOX_SDCARD checking this for 10026
E/Zygote  ( 4171): v2
I/libpersona( 4171): KNOX_SDCARD not a persona
,I/SELinux ( 4171): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ResourcesManager( 4039): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4039): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4039): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/ActivityManager( 1017): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4171 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4171): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4171): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Displayed Component not be shown by security: +1s555ms
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{20a69753 u0 com.test.thalitest/.MainActivity t11} time:44008
W/ActivityManager( 1017): mDVFSHelper.release()
,W/ResourcesManager( 4146): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4146): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4146): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/GCoreUlr( 1734): Unbound from all location providers
,I/GCoreUlr( 1734): Place inference reporting - stopped
D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/TimaKeyStoreProvider( 4171): TimaSignature is unavailable
,D/ActivityThread( 4171): Added TimaKeyStore provider
,W/ResourcesManager( 4039): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4039): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4039): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4039): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 4039): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/GCoreUlr( 1734): DispatchingService.onDestroy()
I/GCoreUlr( 1734): Stopping handler for UlrDispSvcFast
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,I/GCoreUlr( 1734): Unbound from all location providers
I/GCoreUlr( 1734): Place inference reporting - stopped
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Gmail   ( 3610): getAccountsCursor
,I/SurfaceFlinger(  259): id=11 Removed uhalitest (7/8)
,I/SurfaceFlinger(  259): id=11 Removed uhalitest (-2/8)
,W/art     ( 3861): Suspending all threads took: 57.716ms
,D/SSRM:n  ( 1017): SIOP:: AP = 420
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3966): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3966): Resource data:2131165186
,W/ResourcesManager( 3966): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3966): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SamsungIME( 1872): getCurrentCandidateView
,I/AMMetaDataParserService( 3966): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3966): getResourceTypeNamexml
,D/QuickConnect( 4146): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3966): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,D/SettingsProvider( 1017): name = scon_is_running
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10121
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/QuickConnect( 4146): Utils.setQCRunningSetting - set : 0
,I/QuickConnect( 4146): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,I/QuickConnect( 4146): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4193): MountEmulatedStorage(),
E/Zygote  ( 4193): v2
I/libpersona( 4193): KNOX_SDCARD checking this for 10127
I/libpersona( 4193): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4193 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 4193): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4193): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 4193): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/JsMessageQueue( 3908): Set native->JS mode to OnlineEventsBridgeMode
,I/art     (  308): Explicit concurrent mark sweep GC freed 8735(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 33.554ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 18.187ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 20.370ms
,D/TimaKeyStoreProvider( 4193): TimaSignature is unavailable
,D/ActivityThread( 4193): Added TimaKeyStore provider
,I/System.out( 3861): INFO:Resource not found:/Common.properties Using default values
,W/ResourcesManager( 3990): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 4193): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4193): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4193): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4193): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 3990): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3990): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3990): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/Finsky  ( 4171): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/SamsungIME( 1872): Dismiss ExpandCandiate
,I/SamsungIME( 1872): getDebugLevel  : 0x4f4c
,I/chromium( 3908): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 3908): 
,I/SamsungIME( 1872): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1872): KeybaordView init() : load resources
,D/SBrowserFeatureFlag( 4193): initialized in static block : loadCscFeatureValue() succeed! 
,D/jxcore_app_log( 3908): JniHelper::setJavaVM(0xb785a448), pthread_self() = -1208402936
,I/KnoxUsageLogPro( 4098): savePreference: key = previous_elapsed_time value = 43899
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/AMMetaDataParserService( 3966): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,D/Finsky  ( 4171): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/SamsungIME( 1872): getCurrentKeyboard
I/SamsungIME( 1872): getTextKeyboard
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{326882e2 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,D/ManifestProvider( 4193): onCreate()
,I/DBG_DM  ( 3215): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,D/SamsungIME( 1872): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/AMMetaDataParserService( 3966): Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3908): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3908):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3908):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3908):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3908):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3908): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@300f6c57 added. We now have 1 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3908): setBluetoothMacAddress: 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3908): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3908): setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3908): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3908):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3908):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3908):     - Bluetooth MAC address: 08:EC:A9:50:76:27
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3908):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3908):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3908):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3908):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3908):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3908):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3908): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a3476f3 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3908): addListener: New listener added - the number of listeners is now 1
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCr,eateAccountActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
W/ContextImpl( 3966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
E/NetworkSettingsReceiver( 4193): onReceive: android.intent.action.BOOT_COMPLETED
W/Settings( 4171): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4171): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3908): setDiscoveryMode: Discovery mode BLE is supported
,V/AlarmManager( 1017): waitForAlarm result :8
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity,
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:assistant
I/AMMetaDataParserService( 3966): Resource data:2131034113
,W/ResourcesManager( 3966): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.,
W/ResourcesManager( 3966): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3966): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3966): getResourceTypeNamexml
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3966): took 2.564844ms for 0*0 texture 0
,I/chromium( 3908): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/GFX generate_partition_tables( 3966): took 6.170208ms for 0*0 texture 0
,I/GFX raster( 3966): took 9.995313ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb78b3b68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7bd4b08 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3966): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,W/System.err( 4193): java.lang.NoSuchMethodException: isEnabled []
,W/System.err( 4193): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 4193): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
W/System.err( 4193): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
W/System.err( 4193): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
W/System.err( 4193): 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
W/System.err( 4193): 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
W/System.err( 4193): 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
W/System.err( 4193): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 4193): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 4193): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 4193): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4193): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 4193): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 4193): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4193): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4193): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 4193): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3966): took 1.042188ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb78b3b68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7c16370 counterpartCT=4 counterpartW=96 counterparth=96
,E/SBrowserFeatureFlag( 4193): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@228f5076
,D/SBrowserFeatureFlag( 4193): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 4193): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,I/AMMetaDataParserService( 3966): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3966): took 2.684583ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3966): took 7.484688ms for 0*0 texture 0
,I/GFX raster( 3966): took 11.143230ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7c163f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7bf32e0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3966): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/Gmail   ( 3610): getAccountsCursor
,E/Zygote  ( 4244): MountEmulatedStorage()
E/Zygote  ( 4244): v2
I/libpersona( 4244): KNOX_SDCARD checking this for 10131
I/libpersona( 4244): KNOX_SDCARD not a persona
,I/SELinux ( 4244): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4244): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4244): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4244 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3966): took 0.633073ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7c16370 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7c16e28 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1017): Killing 3443:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 3966): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,D/TimaKeyStoreProvider( 4244): TimaSignature is unavailable
,D/ActivityThread( 4244): Added TimaKeyStore provider
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3966): took 0.849531ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7bd4c70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7a708c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3966): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/art     ( 3861): Suspending all threads took: 7.411ms
,D/Volley  ( 4171): [618] DiskBasedCache.clear: Cache cleared.,
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3966): took 0.630104ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7c16e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7bf32e0 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1017): Killing 3512:com.fmm.ds/1000 (adj 15): empty #31
I/ActivityManager( 1017): Killing 3493:com.sec.factory.camera/1000 (adj 15): empty #32
D/Volley  ( 4171): [611] DiskBasedCache.clear: Cache cleared.
D/Ads     ( 4171): Skipping gmscore version check
I/AMMetaDataParserService( 3966): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
D/Finsky  ( 4171): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4171): [1] Libraries$2.run: Finished loading 1 libraries.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/ResourcesManager( 4244): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
W/ResourcesManager( 4244): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4244): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
I/GFX raster( 3966): took 0.675312ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7a708c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7bf32e0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3966): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/Finsky  ( 4171): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3966): took 0.538854ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7bf32e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78ae660 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3966): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3493/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10090/pid_3443/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3512/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:assistant
I/AMMetaDataParserService( 3966): Resource data:2131034113
,I/AMMetaDataParserService( 3966): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3966): getResourceTypeNamexml
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3966): took 0.919480ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb78b3b68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7bd52c0 counterpartCT=4 counterpartW=96 counterparth=96
,D/Finsky  ( 4171): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/AMMetaDataParserService( 3966): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 33204(1842KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 22MB/34MB, paused 2.645ms total 200.671ms
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3966): took 0.817032ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb78b3b68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7c34010 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3966): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,V/HeadsetService( 2649): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2649): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3966): took 0.676977ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7c163f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78ae660 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3966): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531,
,D/daemonapp( 1826): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/Process ( 4039): Sending signal. PID: 4039 SIG: 9
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3966): took 0.729271ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7c16370 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7bd52c0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/AMMetaDataParserService( 3966): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3966): took 0.828958ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7bd4c70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7c34010 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3966): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4283): MountEmulatedStorage()
E/Zygote  ( 4283): v2
I/libpersona( 4283): KNOX_SDCARD checking this for 10037
I/libpersona( 4283): KNOX_SDCARD not a persona
,I/SELinux ( 4283): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4283): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4283): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/Icing   ( 2064): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager( 1017): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4283 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/GFX raster( 3966): took 0.631458ms for 96*96 texture 0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7c16e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7c34010 counterpartCT=4 counterpartW=96 counterparth=96
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3966): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/DBG_DM  ( 3215): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,I/ActivityManager( 1017): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4292 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
,E/Zygote  ( 4292): MountEmulatedStorage()
,E/Zygote  ( 4292): v2
I/libpersona( 4292): KNOX_SDCARD checking this for 10135
I/libpersona( 4292): KNOX_SDCARD not a persona,
,I/SELinux ( 4292): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4292): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4292): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Process com.sec.android.app.sns3 (pid 4039)(adj 0) has died(25,609)
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4283): TimaSignature is unavailable
,D/ActivityThread( 4283): Added TimaKeyStore provider
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3966): took 0.804216ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7a708c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7bf4738 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1017): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4307 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
,E/Zygote  ( 4307): MountEmulatedStorage(),
E/Zygote  ( 4307): v2
I/libpersona( 4307): KNOX_SDCARD checking this for 10031
I/libpersona( 4307): KNOX_SDCARD not a persona
,I/SELinux ( 4307): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/AMMetaDataParserService( 3966): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/SELinux ( 4307): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4307): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4292): TimaSignature is unavailable
D/ActivityThread( 4292): Added TimaKeyStore provider
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3966): took 0.555573ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7bf32e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7bfb840 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4307): TimaSignature is unavailable
,D/ActivityThread( 4307): Added TimaKeyStore provider
,W/ResourcesManager( 4283): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 4292): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 4292): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4292): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3966): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
W/ResourcesManager( 4292): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4292): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3966): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3966): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3966): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3966): getResourcePackageName:assistant
I/AMMetaDataParserService( 3966): Resource data:2131034112
I/AMMetaDataParserService( 3966): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3966): getResourceTypeNamexml
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3966): took 0.675623ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7c16370 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7bf4738 counterpartCT=4 counterpartW=96 counterparth=96
,E/SMD     (  290): DCD OFF
,I/AMMetaDataParserService( 3966): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4331 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
I/ActivityManager( 1017): Killing 3520:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,E/Zygote  ( 4331): MountEmulatedStorage()
I/libpersona( 4331): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4331): v2
I/libpersona( 4331): KNOX_SDCARD not a persona
,I/SELinux ( 4331): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4331): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4331): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GAV2    ( 3610): Thread[GAThread,5,main]: No campaign data found.
V/AlarmManager( 1017): waitForAlarm result :4
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/ActivityManager( 1017): Killing 3544:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
,I/GFX raster( 3966): took 0.665312ms for 96*96 texture 0
,D/TimaKeyStoreProvider( 4331): TimaSignature is unavailable
,D/ActivityThread( 4331): Added TimaKeyStore provider
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7c16370 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78ae660 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,V/AlarmManager( 1017): waitForAlarm result :4
,I/AMMetaDataParserService( 3966): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,I/CalendarProvider2( 4283): CalendarProvider2.onCreate() called
,E/Zygote  ( 4349): MountEmulatedStorage(),
E/Zygote  ( 4349): v2
I/ActivityManager( 1017): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4349 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
I/libpersona( 4349): KNOX_SDCARD checking this for 10141,
I/libpersona( 4349): KNOX_SDCARD not a persona,
,I/SELinux ( 4349): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4349): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4349): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3966): took 0.689896ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7c34010 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7bfb840 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1017): failed to open /acct/uid_10095/pid_3544/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10055/pid_3520/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4349): TimaSignature is unavailable
,D/ActivityThread( 4349): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3966): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3966): took 0.687239ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7c16e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78ae660 counterpartCT=4 counterpartW=96 counterparth=96
,I/iu.UploadsManager( 2064): End new media; added: 0, uploading: 0, time: 155 ms
,W/ResourcesManager( 4349): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4349): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4349): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3966): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,I/DBG_POLICYDM( 4331): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 4331): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_POLICYDM( 4331): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 4331): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 4331): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 4331): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard,
,I/DBG_POLICYDM( 4331): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 4331): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 4331): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activit,ycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:assistant
I/AMMetaDataParserService( 3966): Resource data:2131034113
I/DBG_POLICYDM( 4331): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
I/AMMetaDataParserService( 3966): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3966): getResourceTypeNamexml
I/DBG_POLICYDM( 4331): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3966): took 1.154792ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7bd4c70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7a708c0 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_POLICYDM( 4331): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 4331): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 4331): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
I/DBG_POLICYDM( 4331): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_POLICYDM( 4331): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
I/DBG_POLICYDM( 4331): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3966): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4372): MountEmulatedStorage(),
E/Zygote  ( 4372): v2
I/libpersona( 4372): KNOX_SDCARD checking this for 10032,
I/SELinux ( 4372): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4372): KNOX_SDCARD not a persona
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/ActivityManager( 1017): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4372 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/GFX raster( 3966): took 0.817344ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7bd4c70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7c163f8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
I/SELinux ( 4372): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4372): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/jxcore-log( 3908): Initializing JXcore engine
,W/jxcore-log( 3908): JXcore engine is ready
,I/GAV2    ( 3303): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1017): Killing 3562:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/AMMetaDataParserService( 3966): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/TimaKeyStoreProvider( 4372): TimaSignature is unavailable
,D/ActivityThread( 4372): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_10056/pid_3562/cgroup.procs: No such file or directory
,E/audit   ( 1906): type=1400 msg=audit(1457619680.142:205): avc:  denied  { ioctl } for  pid=4237 comm="Thread-567" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1906):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1906): type=1300 msg=audit(1457619680.142:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=4 a3=92ee78f8 items=0 ppid=308 ppcomm=main pid=4237 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-567" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1906): type=1320 msg=audit(1457619680.142:205): 
,I/DBG_POLICYDM( 4331): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,W/jxcore-log( 3908): Starting JXcore engine
,I/DBG_POLICYDM( 4331): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4331): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7,
,I/DBG_POLICYDM( 4331): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3966): took 0.661927ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7bf32e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79627e8 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4331): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,I/AMMetaDataParserService( 3966): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString,
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3966): took 0.591459ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7968690 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7a708c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3966): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/jxcore-log( 3908): Platform android
W/jxcore-log( 3908): 
W/jxcore-log( 3908): Process ARCH arm
W/jxcore-log( 3908): 
,I/GFX raster( 3966): took 1.001460ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7c163f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79627e8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3966): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0,
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 4331): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] ,
,I/DBG_POLICYDM( 4331): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 4331): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 4331): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4331): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/13/12:50:23
,I/DBG_POLICYDM( 4331): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/10/15:21:20
,I/DBG_POLICYDM( 4331): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 4331): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 4331): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 4331): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 4331): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 4331): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 4331): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 4331): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/DBG_DM  ( 3215): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,E/SPPClientService( 4372): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 4372): [PushClientApplication] Push log off : This is Ship build version
,I/DBG_POLICYDM( 4331): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,E/SPPClientService( 4372): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,D/SPPClientService( 4372): PushLog.txt file is not deleted.
,D/SPPClientService( 4372): PushLog.txt file is not deleted.
,D/SPPClientService( 4372): ============PushLog. stop!
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3966): took 0.692762ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7c16e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7be3598 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3966): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3966): took 0.685417ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7a708c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79627e8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3966): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4396): MountEmulatedStorage()
E/Zygote  ( 4396): v2
I/libpersona( 4396): KNOX_SDCARD checking this for 10036
I/libpersona( 4396): KNOX_SDCARD not a persona
,I/SELinux ( 4396): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4396 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 1794:com.android.defcontainer/u0a3 (adj 15): empty #31
,I/SELinux ( 4396): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4396): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 4331): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3966): took 0.524479ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7be3598 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79627e8 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4396): TimaSignature is unavailable
,D/ActivityThread( 4396): Added TimaKeyStore provider
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3966): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/DBG_POLICYDM( 4331): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
W/ContextImpl( 3966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,W/libprocessgroup( 1017): failed to open /acct/uid_10003/pid_1794/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:assistant
I/AMMetaDataParserService( 3966): Resource data:2131165203
,W/ResourcesManager( 3966): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3966): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3966): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3966): getResourceTypeNamexml
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX construct_block_size_descriptor_2d second part( 3966): took 3.475364ms for 0*0 texture 0,
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0],
,I/SA      ( 4396): [SSP] onCreated
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,I/GFX generate_partition_tables( 3966): took 17.227657ms for 0*0 texture 0
,I/GFX raster( 3966): took 21.295520ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7c12cf0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb7c12d98 counterpartCT=4 counterpartW=80 counterparth=80
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3966): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,E/Zygote  ( 4418): MountEmulatedStorage(),
E/Zygote  ( 4418): v2
I/libpersona( 4418): KNOX_SDCARD checking this for 10068
,I/libpersona( 4418): KNOX_SDCARD not a persona
I/SELinux ( 4418): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4418): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4418): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4418 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80,
I/GFX construct_block_size_descriptor_2d second part( 3966): took 2.560729ms for 0*0 texture 0
,D/TimaKeyStoreProvider( 4418): TimaSignature is unavailable
,D/ActivityThread( 4418): Added TimaKeyStore provider
,I/GFX generate_partition_tables( 3966): took 5.168386ms for 0*0 texture 0
,I/GFX raster( 3966): took 8.773334ms for 80*80 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7f8ca50 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7f8caf8 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3966): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,I/jxcore-log( 3908): JXcore Cordova bridge is ready!
I/jxcore-log( 3908): 
,W/jxcore-log( 3908): JXcore engine is started
,I/ActivityManager( 1017): Killing 3593:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,I/org.thaliproject.p2p.ThaliPermissions( 3908): execute: REQUEST_ACCESS_COARSE_LOCATION
,D/BadgeProvider( 4418): onCreate
D/BadgeProvider( 4418): DatabaseHelper
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/SA      ( 4396): [TPM] There is no property file
,I/SA      ( 4396): [SCU] isHaveSA() - false
,E/jxcore  ( 3908): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3908): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/SA      ( 4396): [TPM] getModelProperty : null
I/SA      ( 4396): [TPM] getCSCProperty : null
,I/SA      ( 4396): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4396): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4396): [DM] TFT FEATURE: false
,I/chromium( 3908): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
D/BadgeProvider( 4418): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/SA      ( 4396): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
,I/SA      ( 4396): [DM] init START
,I/SA      ( 4396): [DM] This device is not a Vodafone
,D/FocusedStackFrame( 1017): Set to : 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1017): Focused application set to: xxxx
,D/InputDispatcher( 1017): Focus left window: 3908
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (189 us)
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3966): took 0.897552ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7f8ca50 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7c124f0 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3966): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,W/PluginManager( 3908): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 69ms. Plugin should use CordovaInterface.getThreadPool().
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ResourceType( 4396): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4396): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4396): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4396): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ActivityManager( 1017): mDVFSHelper.acquire()
W/ResourceType( 4396): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4396): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4396): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4396): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4396): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 4396): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4396): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4396): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4396): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4396): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 4396): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4396): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 4396): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,W/ResourceType( 4396): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
,W/ResourceType( 4396): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3966): took 0.868021ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7f8ca50 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7c223c0 counterpartCT=4 counterpartW=80 counterparth=80
,W/ResourceType( 4396): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,D/Launcher( 1499): onRestart, Launcher: 579817590
,I/AMMetaDataParserService( 3966): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,D/Launcher( 1499): onStart, Launcher: 579817590
W/libprocessgroup( 1017): failed to open /acct/uid_10098/pid_3593/cgroup.procs: No such file or directory
,D/Launcher.HomeView( 1499): onStart
W/ResourceType( 4396): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4396): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 4396): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4396): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4396): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,D/Launcher( 1499): onResume, Launcher: 579817590
W/ResourceType( 4396): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,D/SettingsProvider( 1017): name = kids_home_mode
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10006
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/Launcher.HomeView( 1499): onResume
,I/SA      ( 4396): [SCU] isHaveSA() - false
I/SA      ( 4396): support phone number id : false
I/SA      ( 4396): [DM] Supports Ref Jpn : true
I/SA      ( 4396): [DM] init END
,D/Launcher( 1499): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1017): [SO] activate (ident=0xb7fbc2d8, enabled=0)
,I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/SA      ( 4396): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 4396): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1017): [SO] changed settle time [0]
,D/SensorService( 1017): [SO] setDelay [200000000]
D/SensorService( 1017): [SO] activate (ident=0xb7fbc2d8, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,E/Zygote  ( 4444): MountEmulatedStorage()
,E/Zygote  ( 4444): v2
I/libpersona( 4444): KNOX_SDCARD checking this for 10142
I/libpersona( 4444): KNOX_SDCARD not a persona
,I/SELinux ( 4444): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/BadgeProvider( 4418): sendNotify entered. [uri] : content://com.sec.badge/apps/1,
D/BadgeProvider( 4418): sendNotify, [notify] : null
D/BadgeProvider( 4418): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4418): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4418): update, [UpdateCount] : 1
I/SELinux ( 4444): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4444): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4444 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,I/ActivityManager( 1017): Killing 3334:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4396): [OR] onReceive END
,D/MenuAppsGridFragment( 1499): onResume
,D/ActivityManager( 1017): handle home activity for 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
I/WallpaperManagerService( 1017): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1017): post home show event for user 0
D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/WallpaperManagerService( 1017):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1017): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,I/SurfaceFlinger(  259): id=13 createSurf (540x960),1 flag=4, Mauncher
,D/TimaKeyStoreProvider( 4444): TimaSignature is unavailable
,D/ActivityThread( 4444): Added TimaKeyStore provider
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/SA      ( 4396): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4396): [ODM] queryOpenData(key= GEO_IP )
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/InputDispatcher( 1017): Focus entered window: 1499
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
I/GFX raster( 3966): took 0.660104ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7f8b258 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7f8b290 counterpartCT=4 counterpartW=80 counterparth=80
,D/SRIB_DCS( 1499): log_dcs ThreadedRenderer::initialize entered! 
,I/SA      ( 4396): getMccForGalaxyJpn step2 GEO_IP MCC : 260,
I/SA      ( 4396): [LBE] REF_JPN : true
I/SA      ( 4396): [BDC] create
I/AMMetaDataParserService( 3966): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,D/Launcher.Model( 1499): reloadBadges entered.
,W/ResourcesManager( 4444): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101,
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/        ( 3966): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3966): took 0.678750ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3966): Bitmap=0xb7f8b258 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7c15038 counterpartCT=4 counterpartW=80 counterparth=80
,D/Launcher( 1499): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ActivityManager( 1017): getTasks: caller 10141 does not hold GET_TASKS; limiting output
,I/SA      ( 4396): [DBMV2] getEmailID
,D/PanelView( 1172): There is/are notification(s) 
,I/ActivityManager( 1017): Displayed Component not be shown by security: +216ms
,I/SA      ( 4396): [DBMV2] getDataV02ForItems
,I/SA      ( 4396): [SSP] query invoked
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Process ( 4349): Sending signal. PID: 4349 SIG: 9
,I/SA      ( 4396): [SCU] get signed id from samsung account2.0 DB.
,W/libprocessgroup( 1017): failed to open /acct/uid_10008/pid_3334/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3966): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,I/SA      ( 4396): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4396): [BDC] destroy
,E/lowmemorykiller(  256): Error writing /proc/4349/oom_score_adj; errno=22
I/ActivityManager( 1017): Killing 3651:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,D/SamsungIME( 1872): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/ActivityManager( 1017): Killing 3629:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,W/IInputConnectionWrapper( 3908): showStatusIcon on inactive InputConnection
,I/Timeline( 1499): Timeline: Activity_idle id: android.os.BinderProxy@376b2f90 time:47888
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
W/ContextImpl( 3966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3966): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3966): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3966): getResourcePackageName:assistant
I/AMMetaDataParserService( 3966): Resource data:2131099648
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
W/ResourcesManager( 3966): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 3966): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3966): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3966): getResourceTypeNamexml
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1017): failed to open /acct/uid_10058/pid_3651/cgroup.procs: No such file or directory
,E/Zygote  ( 4468): MountEmulatedStorage()
,E/Zygote  ( 4468): v2
,I/libpersona( 4468): KNOX_SDCARD checking this for 1000
I/libpersona( 4468): KNOX_SDCARD not a persona
I/SELinux ( 4468): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1017): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4468 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/Icing   ( 2064): Internal init done: storage state 0
W/libprocessgroup( 1017): failed to open /acct/uid_10013/pid_3629/cgroup.procs: No such file or directory
I/SELinux ( 4468): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/AMMetaDataParserService( 3966): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
E/lowmemorykiller(  256): Error opening /proc/4349/oom_score_adj; errno=2,
E/SELinux ( 4468): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Process com.android.email (pid 4349)(adj 0) has died(41,569)
,I/ActivityThread( 4444): Removing dead content provider:android.content.ContentProviderProxy@b8464c
I/ActivityThread( 4444): Removing dead content provider:android.content.ContentProviderProxy@b8464c
,I/DBG_DM  ( 3215): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,I/art     (  308): Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 605us total 29.109ms
,I/AMMetaDataParserService( 3966): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4468): TimaSignature is unavailable
D/ActivityThread( 4468): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3966): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 18.452ms
,I/AMMetaDataParserService( 3966): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 643us total 16.349ms,
,I/AMMetaDataParserService( 3966): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/Zygote  ( 4483): MountEmulatedStorage()
I/AMMetaDataParserService( 3966): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
E/Zygote  ( 4483): v2
,I/libpersona( 4483): KNOX_SDCARD checking this for 10141,
I/libpersona( 4483): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4483 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,I/SELinux ( 4483): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 4483): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4483): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:assistant
I/AMMetaDataParserService( 3966): Resource data:2131099648
,I/AMMetaDataParserService( 3966): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3966): getResourceTypeNamexml
,I/AMMetaDataParserService( 3966): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/TimaKeyStoreProvider( 4483): TimaSignature is unavailable
,D/ActivityThread( 4483): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3966): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ResourcesManager( 4483): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4483): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4483): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4483): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 1017): Killing 3685:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,I/Icing   ( 2064): Post-init done
,D/SensorService( 1017): [SO] currT = 48131066000, prevT = 47691096000, diff = 439970000, [-0.421 0.172 9.883]
D/SensorService( 1017): [SO] -0.421 0.172 9.883
D/SensorService( 1017): [SO] [100 -> 255]
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1017): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3966): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/Zygote  ( 4500): MountEmulatedStorage(),
E/Zygote  ( 4500): v2
I/libpersona( 4500): KNOX_SDCARD checking this for 1000,
I/libpersona( 4500): KNOX_SDCARD not a persona
,I/SELinux ( 4500): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4500 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3417:com.google.android.partnersetup/u0a14 (adj 15): empty #31
I/SELinux ( 4500): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4500): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/AMMetaDataParserService( 3966): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/TimaKeyStoreProvider( 4500): TimaSignature is unavailable
,D/ActivityThread( 4500): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3966): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3966): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:assistant
I/AMMetaDataParserService( 3966): Resource data:2131099648
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3685/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10014/pid_3417/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3966): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3966): getResourceTypeNamexml
,I/AMMetaDataParserService( 3966): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{2df8ba83 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t10} time:48279
,I/ActivityManager( 1017): Killing 3745:com.android.managedprovisioning/u0a20 (adj 15): empty #31
,I/SurfaceFlinger(  259): id=12 Removed NainActivit (7/8)
,I/SurfaceFlinger(  259): id=12 Removed NainActivit (-2/8)
,I/CalendarProvider2( 4283): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/ActivityManager( 1017): Killing 3766:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3966): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/SecurityLogAgent( 4500): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4500): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 4500): StateMachine : Current State = 1
,D/SecurityLogAgent( 4500): BootReceiver : completed task. Failed to return wakelock . 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3966): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/Zygote  ( 4523): MountEmulatedStorage()
E/Zygote  ( 4523): v2
I/libpersona( 4523): KNOX_SDCARD checking this for 10148
I/libpersona( 4523): KNOX_SDCARD not a persona
,I/SELinux ( 4523): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4523): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4523): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4523 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3728:com.wssnps/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3966): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/TimaKeyStoreProvider( 4523): TimaSignature is unavailable
,D/ActivityThread( 4523): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3966): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ScreenOrientationListener( 3908): Removing an inexistent observer!
,I/AMMetaDataParserService( 3966): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,E/SQLiteLog( 4523): (284) automatic index on shooting_modes(title_id)
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:assistant
I/AMMetaDataParserService( 3966): Resource data:2131099648
,I/AMMetaDataParserService( 3966): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3966): getResourceTypeNamexml
,I/AMMetaDataParserService( 3966): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,W/libprocessgroup( 1017): failed to open /acct/uid_10020/pid_3745/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3766/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3728/cgroup.procs: No such file or directory
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4539): MountEmulatedStorage()
E/Zygote  ( 4539): v2
I/libpersona( 4539): KNOX_SDCARD checking this for 1000
I/libpersona( 4539): KNOX_SDCARD not a persona
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 23723(1316KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 24MB/36MB, paused 4.426ms total 173.702ms
I/SELinux ( 4539): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4539): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/AMMetaDataParserService( 3966): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/SELinux ( 4539): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1017): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4539 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/AMMetaDataParserService( 3966): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
D/BadgeProvider( 4418): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3966): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/Launcher.Model( 1499): reloadBadges entered.
,W/ActivityManager( 1017): getTasks: caller 10142 does not hold GET_TASKS; limiting output
,D/TimaKeyStoreProvider( 4539): TimaSignature is unavailable
,D/ActivityThread( 4539): Added TimaKeyStore provider
,D/BadgeProvider( 4418): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4418): sendNotify, [notify] : null
D/BadgeProvider( 4418): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4418): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4418): update, [UpdateCount] : 1
,I/AMMetaDataParserService( 3966): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/Process ( 4444): Sending signal. PID: 4444 SIG: 9
,I/AMMetaDataParserService( 3966): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:assistant
I/AMMetaDataParserService( 3966): Resource data:2131099648
,I/AMMetaDataParserService( 3966): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3966): getResourceTypeNamexml
,I/AMMetaDataParserService( 3966): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/splitIntent( 1017): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,E/lowmemorykiller(  256): Error writing /proc/4444/oom_score_adj; errno=22
,I/ActivityManager( 1017): Killing 3787:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1017): Process com.android.exchange (pid 4444)(adj 15) has died(46,566)
,I/AMMetaDataParserService( 3966): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 3966): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/PCWCLIENTTRACE_PushUtil( 3474): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3474): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3474): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3474): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1017): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=15, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,I/splitIntent( 1017): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3966): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4560): MountEmulatedStorage()
,E/Zygote  ( 4560): v2
I/libpersona( 4560): KNOX_SDCARD checking this for 10108
I/libpersona( 4560): KNOX_SDCARD not a persona
,I/SELinux ( 4560): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4560): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4560): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1017): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4560 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/accuweather( 1745): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/AMMetaDataParserService( 3966): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/KLMS-2.5.123: ( 3705): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 10 15:21:22 GMT+01:00 2016
,D/daemonapp( 1826): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/TimaKeyStoreProvider( 4560): TimaSignature is unavailable,
,D/ActivityThread( 4560): Added TimaKeyStore provider
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/AMMetaDataParserService( 3966): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/KLMS-2.5.123: ( 3705): KLMSAbstractReciever(): onReceive().END.
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/accuweather( 1745): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1745): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:assistant
D/accuweather( 1745): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
I/AMMetaDataParserService( 3966): Resource data:2131099648
D/accuweather( 1745): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3705): KLMSIntentService(): onCreate()
,I/AMMetaDataParserService( 3966): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3966): getResourceTypeNamexml
,E/Watchdog( 1017): !@Sync 1
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3966): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/KLMS-2.5.123: ( 3705): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/AMMetaDataParserService( 3966): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/accuweather( 1745): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3705): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3705): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/accuweather( 1745): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KLMS-2.5.123: ( 3705): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
D/SecurityLogAgent( 4500): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4500): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4500): StateMachine : Current State = 1
,D/SecurityLogAgent( 4500): StateMachine : Changed Current State = 1
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3966): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/KLMS-2.5.123: ( 3705): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3705): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3705): NetworkChangeOperations(): uploadRequestLog().START 
,E/Zygote  ( 4576): MountEmulatedStorage()
I/ActivityManager( 1017): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4576 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 4576): v2
I/libpersona( 4576): KNOX_SDCARD checking this for 10077
I/libpersona( 4576): KNOX_SDCARD not a persona
I/SELinux ( 4576): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4576): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4576): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/SettingsProvider( 1017): name = audio_safe_volume_state
,I/DBG_POLICYDM( 4331): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3705): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3705): StateImplV2(): networkChangeListener().END
,D/TimaKeyStoreProvider( 4576): TimaSignature is unavailable
,D/ActivityThread( 4576): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3705): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 4331): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/DBG_POLICYDM( 4331): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 4331): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/DBG_POLICYDM( 4331): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,W/SQLiteConnectionPool( 1628): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,E/SPPClientService( 4372): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 4396): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 4396): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 4396): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 4396): [SLFUCHKMGR] constructor called
,I/SA      ( 4396): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4396): [OR] == isSIMCardReady false ==
,I/SA      ( 4396): [SCU] == networkStateCheck == true
,I/SA      ( 4396): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 4396): isChinaCountryCode : false
I/SA      ( 4396): [SCU] is ChinestModel Data Restricted   : false
,I/SA      ( 4396): [OR] == networkStateCheck true ==
,I/DBG_POLICYDM( 4331): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/iu.SyncManager( 2064): SYNC; picasa accounts
,W/art     ( 4331): Suspending all threads took: 37.345ms
,I/SA      ( 4396): [OR] GetMyCountryZoneTask
,I/SA      ( 4396): [OR] onReceive END
,V/DownloadManager( 1232): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
I/DBG_POLICYDM( 4331): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/NetworkLogImpl( 2064): Loaded NetworkSpeedPredictor
,I/DBG_POLICYDM( 4331): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/iu.Environment( 2064): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/SecContentProvider2( 1017): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1017): mCursor = null
,I/DBG_DM  ( 3215): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,I/SA      ( 4396): [SRS] prepareGetMyCountryZone
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/SA      ( 4396): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4396): [SSP] query invoked
,E/Zygote  ( 4600): MountEmulatedStorage()
E/Zygote  ( 4600): v2
I/libpersona( 4600): KNOX_SDCARD checking this for 10009
I/libpersona( 4600): KNOX_SDCARD not a persona
,I/SELinux ( 4600): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4600): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4600): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/SA      ( 4396): [TPMU] GetMccFromDB : null
I/SA      ( 4396): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4396): [TPM] isNoProxy(default) : true
,I/ActivityManager( 1017): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4600 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 4600): TimaSignature is unavailable
,D/ActivityThread( 4600): Added TimaKeyStore provider
,I/iu.UploadsManager( 2064): num queued entries: 0
,I/iu.UploadsManager( 2064): num updated entries: 0
,I/iu.SyncManager( 2064): NEXT; no task
,E/File    ( 4396): fail readDirectory() errno=2
,E/DBG_POLICYDM( 4331): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3787/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3966): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/DBG_POLICYDM( 4331): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,I/AMMetaDataParserService( 3966): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/AMMetaDataParserService( 3966): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Zygote  ( 4615): MountEmulatedStorage()
E/Zygote  ( 4615): v2
I/libpersona( 4615): KNOX_SDCARD checking this for 10110
,I/libpersona( 4615): KNOX_SDCARD not a persona
I/SELinux ( 4615): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4615 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1017): Killing 3813:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,I/SELinux ( 4615): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4615): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4615): TimaSignature is unavailable
,D/ActivityThread( 4615): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
W/ContextImpl( 3966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3966): Resource data:Loop for ,running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3966): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:assistant
I/AMMetaDataParserService( 3966): Resource data:2131165197
W/ResourcesManager( 3966): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3966): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3966): getResourceTypeNamexml
W/libprocessgroup( 1017): failed to open /acct/uid_10065/pid_3813/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3966): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3966): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623,
,D/WaitQueueForNetworkActivate( 4600): notifyNetworkActivated
,I/MusicStore( 4560): Database version: 104
,I/AMMetaDataParserService( 3966): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/AMMetaDataParserService( 3966): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3966): getResourcePackageName:assistant
I/AMMetaDataParserService( 3966): Resource data:2131165197
,I/AMMetaDataParserService( 3966): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3966): getResourceTypeNamexml
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/AMMetaDataParserService( 3966): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/ContextImpl( 4600): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1017): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/AMMetaDataParserService( 3966): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/ResourcesManager( 4560): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4560): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3966): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3966): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:assistant
I/AMMetaDataParserService( 3966): Resource data:2131165197
,I/AMMetaDataParserService( 3966): getResourceName:com.sec.android.gallery3d:xml/assistant,
I/AMMetaDataParserService( 3966): getResourceTypeNamexml
,V/JNIHelp ( 4560): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...,
,I/AMMetaDataParserService( 3966): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3966): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3966): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3966): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,W/ActivityThread( 4560): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4560): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31b8e65e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4560): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4560): GMSCore installation verified
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
,I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3966): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
,I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
,I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
W/ContextImpl( 3966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,W/ContextImpl( 4615): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3966): getResourcePackageName:assistant
I/AMMetaDataParserService( 3966): Resource data:2131099648
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4615): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/ResourcesManager( 3966): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3966): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3966): getResourceTypeNamexml
,I/ConfigStore( 4560): Config Database version: 1
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4615): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4615): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/AMMetaDataParserService( 3966): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,I/AMMetaDataParserService( 3966): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4560): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3215): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 4600): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 4600): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 4600): exit::IDLE
D/InitializeManagerStateMachine( 4600): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4600): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4600): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4600): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4600): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4600): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4600): entry::SUCCESS
D/hcjo    ( 4600): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4600): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4560): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4560): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/hcjo    ( 4600): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 4600): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4600): exit::SUCCESS
D/InitializeManagerStateMachine( 4600): entry::IDLE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1017): getStreamVolume 3 index 0
,I/MediaRouter( 4560): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/WebViewFactory( 4615): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
W/ContextImpl( 3966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,I/LibraryLoader( 4615): Loading: webviewchromium,
,I/LibraryLoader( 4615): Time to load native libraries: 4 ms (timestamps 122-126)
I/LibraryLoader( 4615): Expected native library version number "",actual native library version number ""
,I/NetworkMonitor( 4560): type=WIFI subType= reason=null isConnected=true
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,V/WebViewChromiumFactoryProvider( 4615): Binding Chromium to main looper Looper (main, tid 1) {28091ff8}
,I/LibraryLoader( 4615): Expected native library version number "",actual native library version number "",
I/chromium( 4615): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/ActivityManager( 1017): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4665 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 4665): MountEmulatedStorage()
I/libpersona( 4665): KNOX_SDCARD checking this for 10001
E/Zygote  ( 4665): v2
I/libpersona( 4665): KNOX_SDCARD not a persona
,I/SELinux ( 4665): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4665): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4665): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor( 4560): type=WIFI subType= reason=null isConnected=true
,D/TimaKeyStoreProvider( 4665): TimaSignature is unavailable
,D/ActivityThread( 4665): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 3610:com.google.android.gm/u0a99 (adj 15): empty #31
,I/DBG_POLICYDM( 4331): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/BrowserStartupController( 4615): Initializing chromium process, renderers=0
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:assistant
I/AMMetaDataParserService( 3966): Resource data:2131165220
,I/DBG_POLICYDM( 4331): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,W/art     ( 4615): Attempt to remove local handle scope entry from IRT, ignoring
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,W/ResourcesManager( 3966): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/DBG_POLICYDM( 4331): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
W/ResourcesManager( 3966): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3966): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3966): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3966): getResourceTypeNamexml
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/AMMetaDataParserService( 3966): Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
,W/chromium( 4615): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 4615): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 4615): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/AMMetaDataParserService( 3966): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,W/AudioManagerAndroid( 4615): Requires BLUETOOTH permission
,I/Adreno-EGL( 4615): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4615): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4615): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4615): Local Branch: 
I/Adreno-EGL( 4615): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4615): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4615):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/libprocessgroup( 1017): failed to open /acct/uid_10099/pid_3610/cgroup.procs: No such file or directory
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4696): MountEmulatedStorage()
E/Zygote  ( 4696): v2
,I/libpersona( 4696): KNOX_SDCARD checking this for 1000
I/libpersona( 4696): KNOX_SDCARD not a persona
,I/SELinux ( 4696): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4696): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4696 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3844:com.google.android.talk/u0a102 (adj 15): empty #31
E/SELinux ( 4696): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings,.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParse,rService( 3966): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/NSApplication( 4615): Starting up...
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/ActivityManager( 1017): Killing 3945:com.samsung.helphub/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,D/TimaKeyStoreProvider( 4696): TimaSignature is unavailable
D/ActivityThread( 4696): Added TimaKeyStore provider
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
W/ContextImpl( 2893): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
W/ContextImpl( 3966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/DBG_DM  ( 3215): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
I/DBG_DM  ( 3215): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
E/DBG_DM  ( 3215): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
I/Process ( 2893): Sending signal. PID: 2893 SIG: 9
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.andro,id.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/ActivityManager( 1017): Killing 3861:com.vlingo.midas/u0a28 (adj 15): empty #31
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for run,ning activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/ActivityManager( 1017): Killing 3966:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): g,etResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3966): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3966): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3966): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
D/QuickConnect( 4146): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect( 4146): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 4146): PeriphStartReceiver.onReceive - no need to start
I/DBG_DM  ( 3215): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,I/DIAGMON_AGENT( 4696): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
I/ActivityManager( 1017): Process com.sec.android.app.sysscope (pid 2893)(adj 0) has died(80,558)
,W/libprocessgroup( 1017): failed to open /acct/uid_10102/pid_3844/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3945/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10028/pid_3861/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3966/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 4696): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 4696): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 4696): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 4696): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 4696): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 4696): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SA      ( 4396): [RC New] Execute method=[GET] start
,D/PackageManager( 1017): [MSG] SEND_PENDING_BROADCAST
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.PACKAGE_CHANGED
,I/SA      ( 4396): [RC New] Security=[true]
,I/System.out( 4396): Thread-655(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PageBuddyNotiSvc( 4122): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,I/System.out( 4396): Thread-655(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 4396): Thread-655(ApacheHTTPLog):isShipBuild true
,I/DBG_POLICYDM( 4331): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/System.out( 4396): Thread-655(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4396): Thread-655(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/DBG_POLICYDM( 4331): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10036
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true,
,D/RegisteredServicesCache( 1457): empty dynamic service
,W/IntentResolver( 1017): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,I/DBG_POLICYDM( 4331): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 4331): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 4331): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4720): MountEmulatedStorage()
E/Zygote  ( 4720): v2
I/libpersona( 4720): KNOX_SDCARD checking this for 10008
I/libpersona( 4720): KNOX_SDCARD not a persona
I/SELinux ( 4720): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4720 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4720): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4720): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     (  308): Explicit concurrent mark sweep GC freed 8711(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 22.928ms
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 4720): TimaSignature is unavailable
D/ActivityThread( 4720): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 742us total 17.767ms
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 16.971ms
,D/WallpaperManager( 1499): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1499): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/ActivityManager( 1017): Killing 4019:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,I/FOTA_Client( 4720): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 4720): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 4720): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/FOTA_Client( 4720): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory,
,I/splitIntent( 1017): Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1017): Killing 4061:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,I/DBG_DM  ( 3215): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 12 sec
,I/DBG_DM  ( 3215): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3215): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,I/DBG_DM  ( 3215): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/BackupManagerService( 1017): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService( 1017): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/splitIntent( 1017): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
I/splitIntent( 1017): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/DBG_DM  ( 3215): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/FOTA_Client( 4720): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,V/BackupManagerService( 1017): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 1017): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2fe0feb0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3215): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 3
,E/Zygote  ( 4739): MountEmulatedStorage(),
I/libpersona( 4739): KNOX_SDCARD checking this for 10058
E/Zygote  ( 4739): v2
I/libpersona( 4739): KNOX_SDCARD not a persona,
I/SELinux ( 4739): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/DBG_DM  ( 3215): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2,
,I/DBG_DM  ( 3215): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/SELinux ( 4739): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4739): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1017): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4739 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/FOTA_Client( 4720): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
I/DBG_DM  ( 3215): [IlIlllIlllllIlIllllI(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [3]
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{a9450c u0 com.samsung.android.providers.context/.ContextService}
,I/DBG_DM  ( 3215): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 3215): [com.wssyncmldm.llIIllllIIlllIIIIlll(1140/handleMessage)] 
,D/daemonapp( 1826): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1826): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,I/DBG_DM  ( 3215): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,D/TimaKeyStoreProvider( 4739): TimaSignature is unavailable
,D/ActivityThread( 4739): Added TimaKeyStore provider
I/DBG_DM  ( 3215): [com.wssyncmldm.XDMService(685/llIIlIlIIIllIIIIIllI)] 
I/DBG_DM  ( 3215): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
D/daemonapp( 1826): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1826): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings,
,I/DBG_DM  ( 3215): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/daemonapp( 1826): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1826): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1826): [MSC_Daemon]>>> ====================================================================================================================,
I/ActivityManager( 1017): Waited long enough for: ServiceRecord{212ba5f8 u0 com.android.settings/.wifi.WifiCredService}
D/comsamsunglog( 1826): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1826): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1826): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1826): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1826): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1826): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,I/KLMS-2.5.123: ( 3705): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Mar 10 15:21:24 GMT+01:00 2016
I/DBG_DM  ( 3215): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3215): [com.wssyncmldm.ui.XUIFotaPostponeActivity(501/llIIIIlllllIIllIIllI)] 
,D/daemonapp( 1826): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1826): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1826): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/daemonapp( 1826): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/DBG_DM  ( 3215): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,E/daemonapp( 1826): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,I/KLMS-2.5.123: ( 3705): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3705): KLMSIntentService(): onCreate()
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
D/comdaemonstockapp( 1826): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1826): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
I/KLMS-2.5.123: ( 3705): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3705): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/DBG_DM  ( 3215): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
,I/SA      ( 4396): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/KLMS-2.5.123: ( 3705): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,D/SecurityLogAgent( 4500): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4500): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4500): StateMachine : Current State = 1
,I/KLMS-2.5.123: ( 3705): KLMSIntentService(): TIME_CHANGED
,I/KLMS-2.5.123: ( 3705): StateImplV2(): dateTimeChanged().START : Thu Mar 10 15:21:24 GMT+01:00 2016,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3705): StateImplV2(): dateTimeChanged().END
,E/Zygote  ( 4757): MountEmulatedStorage()
,I/libpersona( 4757): KNOX_SDCARD checking this for 10153
E/Zygote  ( 4757): v2
I/ActivityManager( 1017): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4757 uid=10153 gids={50153, 9997} abi=armeabi-v7a
I/libpersona( 4757): KNOX_SDCARD not a persona
I/SELinux ( 4757): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4757): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4757): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ExternalOEMControlProvider( 4739): onCreate
,I/KLMS-2.5.123: ( 3705): KLMSIntentService(): onDestroy()
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4757): TimaSignature is unavailable
,D/ActivityThread( 4757): Added TimaKeyStore provider
,I/GCoreNlp( 1734): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/accuweather( 1745): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1745): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4019/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4061/cgroup.procs: No such file or directory
,D/WindowManager( 1017): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ResourcesManager( 1172): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ Time Manager ( 4739): Time Difference not stored. TIME_DIFFERENCE
,D/KnoxNotification( 1172): ----- inflateViews : modified publicViewLocal -----
,D/KnoxNotification( 1172): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1172): PersonaID is invalid or persona doesn't exists. : 0
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
,D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/SensorService( 1017): [SO] -0.421 0.172 9.883
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 38316(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 24MB/37MB, paused 3.072ms total 162.036ms
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,W/ResourcesManager( 4757): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4774): MountEmulatedStorage()
,E/Zygote  ( 4774): v2
I/libpersona( 4774): KNOX_SDCARD checking this for 10041
I/libpersona( 4774): KNOX_SDCARD not a persona
,I/SELinux ( 4774): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4774): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4774): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4774 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a,
,D/TimaKeyStoreProvider( 4774): TimaSignature is unavailable
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 4774): Added TimaKeyStore provider
,E/Zygote  ( 4789): MountEmulatedStorage()
,I/ActivityManager( 1017): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4789 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 4789): v2
I/libpersona( 4789): KNOX_SDCARD checking this for 10081
I/libpersona( 4789): KNOX_SDCARD not a persona
,I/SELinux ( 4789): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/LocationProviderProxy( 1017): applying state to connected service
,I/SELinux ( 4789): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4789): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LocationProviderProxy( 1017): applying state to connected service
,W/ResourcesManager( 4774): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4774): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4774): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4774): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4774): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4789): TimaSignature is unavailable
,D/ActivityThread( 4789): Added TimaKeyStore provider
,E/Zygote  ( 4804): MountEmulatedStorage()
I/libpersona( 4804): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4804): v2
I/libpersona( 4804): KNOX_SDCARD not a persona
,I/SELinux ( 4804): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4804): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4804): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4804 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/ActivityManager( 1017): Killing 4083:com.sec.android.app.mt/1000 (adj 15): empty #31
,W/ResourcesManager( 4789): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4789): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4789): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4789): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4789): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 4804): TimaSignature is unavailable
,D/ActivityThread( 4804): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 4098:com.sec.knox.bridge/1000 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/MmsApp( 4774): [start]    onCreate() consume time = 0.0
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4083/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4098/cgroup.procs: No such file or directory
,D/TimeService( 4804): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1457619685160
D/        ( 4804): TimeServiceNative: User Time to be set is 1457619685161
D/QC-time-services( 4804): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4804): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4804): Lib:time_genoff_operation: pargs->ts_val = 1457619685161
,D/QC-time-services(  320): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 4804): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  320): Daemon:Received base = 2, unit = 1, operation = 0,value = 1457619685161
D/QC-time-services(  320): Daemon:genoff_opr: Base = 2, val = 1457619685161, operation = 0
,D/QC-time-services(  320): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/5/70 17:58:7
D/QC-time-services(  320): Daemon:Value read from RTC seconds = 21405487000
D/QC-time-services(  320): Daemon:new time 1457619685161 
D/QC-time-services(  320): Daemon: delta 1436214198161 genoff 1436214198161 
D/QC-time-services(  320): Daemon:genoff_persistent_update: Writing genoff = 1436214198161 to memory
D/QC-time-services(  320): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  320): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  320): Updating the TOD offset
D/QC-time-services(  320): Daemon:genoff_persistent_update: Writing genoff = 1436214198161 to memory
D/QC-time-services(  320): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  320): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/SettingsProvider( 1017): name = next_alarm_formatted
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 10081
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,E/QC-time-services(  320): Daemon:Update to modem bit set
D/QC-time-services(  320): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  320): Daemon: Base = 2, Value being sent to MODEM = 1120249398161
,E/QC-time-services( 4804): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  320): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  320): Daemon: Time-services: Waiting to acceptconnection
,I/ActivityManager( 1017): Killing 4193:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
,W/art     ( 4774): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 118.579ms
,D/Mms/ArtClassLoader( 4774): init before art
,D/Mms/TelephonyPermission( 4774): start operation mode monitor
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,W/libprocessgroup( 1017): failed to open /acct/uid_10127/pid_4193/cgroup.procs: No such file or directory
,W/ResourcesManager( 4774): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4823): MountEmulatedStorage()
E/Zygote  ( 4823): v2
I/libpersona( 4823): KNOX_SDCARD checking this for 10090
I/libpersona( 4823): KNOX_SDCARD not a persona
,I/SELinux ( 4823): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4823): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=4823 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,E/SELinux ( 4823): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 4171:com.android.vending/u0a26 (adj 15): empty #31
,D/Mms/TelephonyPermission( 4774): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 4774): isDefault true
,I/SA      ( 4396): [RC New] [v2liruge] api execute + 1172
I/SA      ( 4396): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4396): AsyncTask #1 calls detatch()
D/Mms/MmsApp( 4774): onCreate() com.android.mms
,I/SA      ( 4396): [ODM] saveOpenData( GEO_IP, PL )
,D/TimaKeyStoreProvider( 4823): TimaSignature is unavailable
,D/ActivityThread( 4823): Added TimaKeyStore provider
,I/SA      ( 4396): [OCP] update openData : PL
,I/SA      ( 4396): [TPMU] getNetworkMcc : 
,I/SA      ( 4396): [SCU] saveMccToPreferece Start
I/SA      ( 4396): [SCU] RegionMCC : 260
I/SA      ( 4396): [SSP] query invoked
,I/SA      ( 4396): [TPMU] GetMccFromDB : null
I/SA      ( 4396): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4396): [SCU] saveMccToPreferece End
,I/SA      ( 4396): [RC New] executeRequest [v2liruge] end. 1256
I/SA      ( 4396): [RC New] Execute end
,I/SA      ( 4396): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 4396): [OR] GetMyCountryZoneTask Success
,D/Mms/MmsApp( 4774): [start]    initCountryIso consume time = 334.908542
,D/elm:15121( 4823): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15121( 4823): ELMEngine.ELMEngine( context ).
,D/elm:15121( 4823): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 4823): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/elm:15121( 4823): ElmAgentService : onCreate()
,D/elm:15121( 4823): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService },
,D/CountryDetector( 1017): The first listener is added
,D/elm:15121( 4823): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/Mms/MmsApp( 4774): [end]    initCountryIso consume time = 28.499791
,D/Mms/MmsConfig( 4774): [start]    MmsConfig.init() consume time = 0.342032
,D/elm:15121( 4823): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:15121( 4823): ModuleBase.ModifySetAlarm()
D/elm:15121( 4823): MDMBridge.getInstance()
D/elm:15121( 4823): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 4843): MountEmulatedStorage()
I/libpersona( 4843): KNOX_SDCARD checking this for 10130
E/Zygote  ( 4843): v2
I/libpersona( 4843): KNOX_SDCARD not a persona
,I/SELinux ( 4843): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4843): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4843): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=4843 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,D/elm:15121( 4823): ElmAgentService : onDestroy().
,I/ActivityManager( 1017): Killing 4292:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,D/Mms/MmsConfig( 4774): before partial update
,D/TimaKeyStoreProvider( 4843): TimaSignature is unavailable,
,D/ActivityThread( 4843): Added TimaKeyStore provider
,D/Mms/MmsConfig( 4774): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 4774): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 4774): isAuth is false
D/Mms/MmsConfig( 4774): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,W/ResourcesManager( 4843): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4843): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/TP/MmsSmsProvider( 1468): query,matched:2117, calling pid = 4774
,D/TP/MmsSmsProvider( 1468): match 2117:Elapsed time : 1.648 ms
,D/EasySignUpManager_1.0.1( 4774): isAuth is false
,D/EasySignUpManager_1.0.1( 4774): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 4774): mps_code.dat does not exist
,E/CscParser( 4774): customer_path =/system/csc/customer.xml
,E/CscParser( 4774): fileName + /system/csc/customer.xml
,I/ActivityManager( 1017): Killing 4468:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,E/CscParser( 4774): mps_code.dat does not exist
E/CscParser( 4774): customer_path =/system/csc/customer.xml
E/CscParser( 4774): fileName + /system/csc/customer.xml
,D/CscParser( 4774): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 4774):  enable multiwindow = false
,E/Mms/MessageUtils( 4774): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 4774): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 4774): [end]    init() consume time = 116.699739
,D/Mms/Contact( 4774): [start]    init() consume time = 0.554792
,D/TP/MmsSmsProvider( 1468): query,matched:13, calling pid = 4774
,D/TP/MmsSmsProvider( 1468): match 13:Elapsed time : 1.311 ms
,D/Mms/Contact( 4774): [end]    init consume time = 9.605573
,D/Mms/DraftCache( 4774): [start]    rebuildCache consume time = 3.307864
,D/Mms/MethodReflector( 4774): getSubId is called
,D/Mms/TelephonyUtils( 4774): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4774): getTelephonyProperty is called
D/Mms/DownloadManager( 4774): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4774): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4774): auto download without roaming -> true
D/Mms/DownloadManager( 4774): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/MethodReflector( 4774): getSubId is called
,D/TP/MmsSmsProvider( 1468): query,matched:12, calling pid = 4774
,D/Mms/MethodReflector( 4774): getDefaultSmsSubId is called
,D/TP/MmsSmsProvider( 1468): match 12:Elapsed time : 2.536 ms
,E/Mms/TelephonyUtils( 4774): subID is null or 0 length, so get DefaultSubId!!
,D/Mms/TelephonyUtils( 4774): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 4774): getTelephonyProperty is called
D/Mms/DownloadManager( 4774): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 4774): [NotificationTransaction] getAutoDownloadState simSlot : 1
,D/Mms/DownloadManager( 4774): auto download without roaming -> true
D/Mms/DownloadManager( 4774): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 4774): auto download during roaming secondary -> false
D/Mms/DownloadManager( 4774): mAutoDownload ------> true
,D/Mms/DraftCache( 4774): [end]    rebuildCache consume time = 20.408021
,D/ComposerPerformance( 4774): 1457619685587 ms / [DONE] Composer constructor
,D/Mms/Conversation( 4774): [start]    init() consume time = 10.378125
,D/TP/MmsSmsProvider( 1468): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1468): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1468): updateThread(), thread_id = 9223372036854775807
,W/libprocessgroup( 1017): failed to open /acct/uid_10026/pid_4171/cgroup.procs: No such file or directory
,D/Mms/ArtClassLoader( 4774): init [DONE] art
,V/TP/MmsSmsDatabaseHelper( 1468): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
,E/CII     ( 4774): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 4774): ReservationManager()
I/Mms/ReservationManager( 4774): resetAfterConnected()
,D/TP/MmsSmsProvider( 1468): query,matched:7, calling pid = 4774
,D/TP/MmsSmsProvider( 1468): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1468): need read changed broadcast:false
,D/Mms/Conversation( 4774): [end]    init consume time = 18.662292
,D/TP/MmsSmsProvider( 1468): match 7:Elapsed time : 3.287 ms
,D/Mms/MessagingNotification( 4774): [start]    init() consume time = 1.131354
,W/libprocessgroup( 1017): failed to open /acct/uid_10135/pid_4292/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4468/cgroup.procs: No such file or directory
,D/Mms/MessagingNotification( 4774): [end]    init consume time = 2.426042
,D/Mms/Synchronizer( 4774): [start]    doSync consume time = 1.807552
,I/Mms/ReservationManager( 4774): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1468): query,matched:0, calling pid = 4774
V/TP/MmsSmsProvider( 1468): getSimpleConversations entered.
,D/Mms/SpamFilter( 4774): [start]    SpamFilter fill() begin consume time = 3.222031
,D/TP/MmsSmsProvider( 1468): update, matched:300, calling pid = 4774
D/TP/MmsSmsProvider( 1468): match 0:Elapsed time : 1.980 ms
,V/TP/MmsSmsProvider( 1468): syncDBData start
,D/TP/MmsSmsProvider( 1468): query,matched:400, calling pid = 4774
,V/TP/MmsSmsProvider( 1468): syncDBData sms end
,D/Mms/MmsApp( 4774): [end]    onCreate() consume time = 5.645156
,V/TP/MmsSmsProvider( 1468): syncDBData mms end
,V/TP/MmsSmsProvider( 1468): syncDBData end
,D/Mms/DownloadManager( 4774): Service state changed: Bundle[mParcelledData.dataSize=744]
,I/splitIntent( 1017): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
,D/Mms/Synchronizer( 4774): [end]    doSync consume time = 3.621094
,E/SMD     (  290): DCD OFF
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/ActivityManager( 1017): Killing 3908:com.test.thalitest/u0a167 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/DownloadManager( 4774): roaming ------> false, mSimSlot = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/MethodReflector( 4774): getSubId is called
D/Mms/TelephonyUtils( 4774): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4774): getTelephonyProperty is called
D/Mms/DownloadManager( 4774): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4774): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4774): auto download without roaming -> true
D/Mms/DownloadManager( 4774): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/DownloadManager( 4774): mAutoDownload ------> true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/SpamFilter( 4774): [end]    SpamFilter fill() finished consume time = 23.416562
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/MessagingNotification( 4774): checkBadgeCount unreadCount=0 badgeCount=0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TP/SmsProvider( 1468): query,matched:26, calling pid = 4774,
,D/TP/SmsProvider( 1468): match 26:Elapsed time : 2.782 ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TP/MmsSmsProvider( 1468): query,matched:6, calling pid = 4774
,D/TP/MmsSmsProvider( 1468): match 6:Elapsed time : 1.934 ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4867 uid=10023 gids={50023, 9997} abi=armeabi-v7a,
,E/Zygote  ( 4867): MountEmulatedStorage()
I/libpersona( 4867): KNOX_SDCARD checking this for 10023
E/Zygote  ( 4867): v2
I/libpersona( 4867): KNOX_SDCARD not a persona
,I/SELinux ( 4867): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/SELinux ( 4867): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 4867): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TimaKeyStoreProvider( 4867): TimaSignature is unavailable
,D/ActivityThread( 4867): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1017): Killing 4523:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/libprocessgroup( 1017): failed to open /acct/uid_10167/pid_3908/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SIP     ( 1468): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/File    ( 1468): fail readDirectory() errno=2,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1017): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1017): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1017): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/OMACP   ( 4867): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1734): callingUid 10011, callindPid: 1734
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/Omacp( 4774): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10148/pid_4523/cgroup.procs: No such file or directory
,E/MDM     ( 1734): [241] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/OMACP   ( 4867): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 4867): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 4867): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 4867): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 4867): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/OMACP   ( 4867): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false,
D/LocationInitializer( 2064): Restart initialization of location
I/OMACP   ( 4867): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false,
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/OMACP   ( 4867): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 4867): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 4867): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 4867): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 4867): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 4867): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1734): No location to return for getLastLocation()
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/FusedLocationProvider( 1734): location=null
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4890 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,E/Zygote  ( 4890): MountEmulatedStorage(),
E/Zygote  ( 4890): v2
I/libpersona( 4890): KNOX_SDCARD checking this for 1000
I/libpersona( 4890): KNOX_SDCARD not a persona
,I/SELinux ( 4890): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4890): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4890): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4890): TimaSignature is unavailable
,D/ActivityThread( 4890): Added TimaKeyStore provider
,E/MTPRx   ( 4890): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1017): mCursor = null
,V/MTPRx   ( 4890): sealedState: false
V/MTPRx   ( 4890): sealedUsbMassStorageState: false
E/MTPRx   ( 4890): check value of boot_completed is1
E/MTPRx   ( 4890): check booting is completed_sys.boot_completed
,E/MTPRx   ( 4890): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4890): Status for mount/Unmount :removed
E/MTPRx   ( 4890): SDcard is not available
,W/MTPRx   ( 4890): value of connected istrue
W/MTPRx   ( 4890): value of configured istrue
W/MTPRx   ( 4890): value of mtpEnabled istrue
W/MTPRx   ( 4890): value of ptpEnabled isfalse
,E/MTPRx   ( 4890): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 4890): mFirstTime: false
,D/        ( 4890): MTP: reading debug level property
,E/MTPJNIInterface( 4890): Getting CryptionKey from JAVA
E/MTPRx   ( 4890): currentUserId is 0
,E/MTPRx   ( 4890): Start observing USB_STATE_MATCH 
,D/Mms/Contact( 4774): sContactsObserver.onChange(),selfUpdate=false
E/MTPRx   ( 4890): cannot open file : /sys/class/android_usb/android0/bcdUSB
,E/MTPRx   ( 4890): is_Privatemode is NOT 1
,D/Mms/Contact( 4774): performUpdate:widgetCount=0
,D/SettingsProvider( 1017): name = boot_time_connected
,D/Mms/ContactsCache( 4774): [start]    invalidate() consume time = 569.637813
D/Mms/ContactsCache( 4774): [end]    invalidate() consume time = 0.121614
,I/ValidateNoPeople( 1017): mEvictionCount: 0
,E/MTPRx   ( 4890): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 4890): noti = 17
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,D/SecContentProvider( 1017): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 4890): sending MTP_ICON_ENABLED to stack
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1017): name = mtp_running_status
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,E/MTPRx   ( 4890): else part ... so first time!!!
E/MTPPlaObsrvr( 4890): inside setContext()
E/MTPPlaObsrvr( 4890):  inside createplafiles
,V/AlarmManager( 1017): waitForAlarm result :4
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 4890): playlist count is0
,E/MTPPlaObsrvr( 4890):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4890):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4890): Inside registerContentObserver
,E/MtpAdbObserver( 4890): inside setContext()
,E/MtpAdbObserver( 4890): Inside registerContentObserver
,W/Settings( 4890): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1017): name = mtp_running_status
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,V/MtpMediaDBManager( 4890): inside deleteAllDB
,E/MtpService( 4890): onCreate.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/MtpService( 4890): < MTP > Registering BroadCast receiver :::::
,D/MtpService( 1232): updating state; isCurrentUser=true, mMtpLocked=false
,E/MtpService( 4890): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4911): MountEmulatedStorage(),
I/ActivityManager( 1017): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4911 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 4911): v2
I/libpersona( 4911): KNOX_SDCARD checking this for 1000
I/SELinux ( 4911): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/libpersona( 4911): KNOX_SDCARD not a persona
,E/MtpService( 4890): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,I/SELinux ( 4911): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/MtpService( 4890): onStartCommand.
,W/MTPRx   ( 4890): calling native method
V/MtpMediaDBManager( 4890): inside Thread updateDB
E/MTPJNIInterface( 4890): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 4890): handleMessage. msg= { when=-2ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MtpMediaDBManager( 4890): count : 26
E/SELinux ( 4911): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/MTPJNIInterface( 4890): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 4890): noti = 10
E/MtpService( 4890): onStartCommand.
W/MTPRx   ( 4890): calling native method
E/MTPRx   ( 4890): Checking the driver time out
E/MTPJNIInterface( 4890): noti = 2
D/        ( 4890): deleting sockets before message queue initialization
,E/MtpService( 4890): handleMessage. msg= { when=-1ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
D/        ( 4890): event handler thread is created, so set the flag
E/MTPRx   ( 4890): called native method
E/MTPJNIInterface( 4890): setting Media scanner status0
E/MTPJNIInterface( 4890): After setting Media scanner status0
,W/MTPRx   ( 4890): notification from stack 1
E/        ( 4890): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 4890): Getting media scanner status0
,E/MTPJNIInterface( 4890): DeviceName is Thali Test (Galaxy A3)
,W/MtpMediaDBManager( 4890): sending db update complete noti to stack
E/MTPJNIInterface( 4890): noti = 29
,E/SQLiteLog( 4890): (5) database is locked
,D/TimaKeyStoreProvider( 4911): TimaSignature is unavailable
,D/ActivityThread( 4911): Added TimaKeyStore provider
,E/MTPJNIInterface( 4890): Status for mount/Unmount :removed
E/MTPJNIInterface( 4890): SDcard is not available
,E/        ( 4890): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface( 4890): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4890): SDcard is not available
,E/SQLiteLog( 4890): (21) API call with NULL database connection pointer
,E/SQLiteLog( 4890): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4890): (21) API call with NULL database connection pointer
E/SQLiteLog( 4890): (21) misuse at line 100726 of [9491ba7d73]
,E/SQLiteLog( 4890): (21) API call with NULL database connection pointer
,E/SQLiteLog( 4890): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4890): (21) API call with NULL database connection pointer
E/SQLiteLog( 4890): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 4890): notification from stack 2
,D/        ( 4890): [mtp_init_device] Library open with 32 bits.
,D/        ( 4890): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 4890): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 4890): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,E/        ( 4890):  [sua_support_present:1287] returning false 
D/        ( 4890): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
