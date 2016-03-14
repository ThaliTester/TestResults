#### Test 6275440319c4f54_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
D/TimaKeyStoreProvider( 4055): TimaSignature is unavailable
D/ActivityThread( 4055): Added TimaKeyStore provider
E/SMD     (  288): DCD OFF
--------- beginning of system
W/ActivityManager( 1019): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 3839): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@3c54880e that was originally bound here
E/ActivityThread( 3839): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@3c54880e that was originally bound here
E/ActivityThread( 3839): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3839): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3839): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3839): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3839): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3839): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 3839): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 3839): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 3839): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 3839): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 3839): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 3839): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 3839): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3839): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3839): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3839): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/libprocessgroup( 1019): failed to open /acct/uid_10081/pid_2978/cgroup.procs: No such file or directory
W/ActivityManager( 1019): Unbind failed: could not find connection for android.os.BinderProxy@1af4ee92
E/SQLiteLog( 3839): (283) recovered 96 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/sCloudBackupApp( 3969): sCloudBackupApp Version Info : 4.04.7.KK_APP
I/KLMS-2.5.123: ( 2624): KLMSIntentService(): onDestroy()
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
V/GLSActivity( 1835): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 4055): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/GLSActivity( 1835): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/LockPatternUtils( 1319): isSmartCardAuthenticationAvailable: false
E/Zygote  ( 4075): MountEmulatedStorage()
I/ActivityManager( 1019): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4075 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 4075): v2
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SELinux ( 4075): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4075): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4075): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/libpersona( 4075): KNOX_SDCARD checking this for 10058
I/libpersona( 4075): KNOX_SDCARD not a persona
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4085): MountEmulatedStorage()
E/Zygote  ( 4085): v2
I/SELinux ( 4085): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/TimaKeyStoreProvider( 4075): TimaSignature is unavailable
D/ActivityThread( 4075): Added TimaKeyStore provider
I/SELinux ( 4085): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/libpersona( 4085): KNOX_SDCARD checking this for 1000
I/libpersona( 4085): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4085 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 3285:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
E/SELinux ( 4085): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/qtaguid ( 3663): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3663, getuid(): 10052
I/qtaguid ( 3663): Untagging socket 43
I/qtaguid ( 3663): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3663, getuid(): 10052
I/qtaguid ( 3663): Untagging socket 43
I/qtaguid ( 3663): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3663, getuid(): 10052
I/qtaguid ( 3663): Untagging socket 43
I/qtaguid ( 3663): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3663, getuid(): 10052
I/qtaguid ( 3663): Untagging socket 43
I/qtaguid ( 3663): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3663, getuid(): 10052
I/qtaguid ( 3663): Untagging socket 43
I/qtaguid ( 3663): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3663, getuid(): 10052
I/qtaguid ( 3663): Untagging socket 43
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 4085): TimaSignature is unavailable
D/ActivityThread( 4085): Added TimaKeyStore provider
I/qtaguid ( 3663): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3663, getuid(): 10052
I/qtaguid ( 3663): Untagging socket 43
I/qtaguid ( 3663): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3663, getuid(): 10052
I/qtaguid ( 3663): Untagging socket 43
I/qtaguid ( 3663): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3663, getuid(): 10052
W/libprocessgroup( 1019): failed to open /acct/uid_1101/pid_3285/cgroup.procs: No such file or directory
I/qtaguid ( 3663): Untagging socket 43
I/qtaguid ( 3663): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3663, getuid(): 10052
I/qtaguid ( 3663): Untagging socket 43
I/qtaguid ( 3663): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3663, getuid(): 10052
I/qtaguid ( 3663): Untagging socket 43
I/qtaguid ( 3663): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3663, getuid(): 10052
I/qtaguid ( 3663): Untagging socket 43
I/qtaguid ( 3663): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3663, getuid(): 10052
I/qtaguid ( 3663): Untagging socket 43
I/RlzPingService( 3778): Setting next ping for 1458573124125
I/ExternalOEMControlProvider( 4075): onCreate
E/MTPRx   ( 4085): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
D/SecContentProvider2( 1019): uri = 14 selection = getSealedState
D/SecContentProvider2( 1019): mCursor = null
D/SecContentProvider2( 1019): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1019): mCursor = null
V/MTPRx   ( 4085): sealedState: false
V/MTPRx   ( 4085): sealedUsbMassStorageState: false
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4109): MountEmulatedStorage()
E/Zygote  ( 4109): v2
I/libpersona( 4109): KNOX_SDCARD checking this for 1000
I/libpersona( 4109): KNOX_SDCARD not a persona
I/SELinux ( 4109): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4109): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=4109 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 3328:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
E/SELinux ( 4109): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SettingsProvider( 1019): name = mtp_usb_connection_status
D/SettingsProvider( 1019): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10058
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
D/GCM     ( 2105): COMPAT: Multi user not supported
I/art     (  304): Explicit concurrent mark sweep GC freed 8706(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 617us total 24.937ms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 4109): TimaSignature is unavailable
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 4109): Added TimaKeyStore provider
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 20.019ms
I/qtaguid ( 3663): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3663, getuid(): 10052
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 23.185ms
D/SettingsProvider( 1019): name = media_player_mode
W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
D/SettingsProvider( 1019): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10058
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
D/SettingsProvider( 1019): name = mtp_usb_conditions_met
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
I/ContactAccountLoggerTas( 3663): canRun() : Opted Out
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/GCM     ( 1835): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1019): name = mtp_running_status
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3328/cgroup.procs: No such file or directory
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
D/SettingsProvider( 1019): name = media_mount_count
I/DBG_DM  ( 3570): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
W/ResourcesManager( 4109): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
I/ServiceMode( 4109): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 4109): setReferenceIsDumpState : 0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4128): MountEmulatedStorage()
I/libpersona( 4128): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4128): v2
I/libpersona( 4128): KNOX_SDCARD not a persona
I/SELinux ( 4128): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=4128 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 4128): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4128): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 4128): TimaSignature is unavailable
D/ActivityThread( 4128): Added TimaKeyStore provider
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SettingsProvider( 1019): name = mtp_sync_alive
D/SettingsProvider( 1019): name = sdcard_launch
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
D/SettingsProvider( 1019): name = boot_time_connected
I/GCoreUlr( 2105): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
D/SystemUpdateService( 2105): onCreate
D/SettingsProvider( 1019): name = mtp_open_session
D/btif_config_util( 3080): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
I/GCoreUlr( 1835): DispatchingService.onCreate()
D/NPS_WSSNPS( 4128): [] android.intent.action.BOOT_COMPLETED
W/ContextImpl( 4128): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
I/CheckinService( 2105): Disabling old GoogleServicesFramework version
D/NPS_WSSNPS( 4128): [] Service onCreate!!
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4151): MountEmulatedStorage()
E/Zygote  ( 4151): v2
I/libpersona( 4151): KNOX_SDCARD checking this for 1000
I/libpersona( 4151): KNOX_SDCARD not a persona
I/SELinux ( 4151): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4151): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4151): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=4151 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/NPS_WSSNPS( 4128): [50.150321] NpsServiceTask Start
I/CheckinService( 2105): Checking schedule, now: 1457968324595 next: 1458299986961
I/CheckinService( 2105): active receiver: disabled
D/TimaKeyStoreProvider( 4151): TimaSignature is unavailable
D/ActivityThread( 4151): Added TimaKeyStore provider
I/PCWCLIENTTRACE_PushUtil( 3887): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3887): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3887): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3887): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3887): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3887): ACTION_BOOTUP - Push type: [SPP, GCM]
D/SystemUpdateService( 2105): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/SystemUpdateService( 2105): cancelUpdate (empty URL)
I/SystemUpdateService( 2105): active receiver: disabled
D/SettingsProvider( 1019): name = access_control_enabled
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/NPS_WSSNPS( 4128): [50.150321] smlDBHelper
E/Zygote  ( 4177): MountEmulatedStorage()
E/Zygote  ( 4177): v2
I/libpersona( 4177): KNOX_SDCARD checking this for 10065
I/SELinux ( 4177): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4177): KNOX_SDCARD not a persona
I/SELinux ( 4177): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4177): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=4177 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 2962:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
W/PCWCLIENTTRACE_AccountUtil( 3887): [hasSamungAccount] - No Samsung Account
D/TimaKeyStoreProvider( 4177): TimaSignature is unavailable
D/ActivityThread( 4177): Added TimaKeyStore provider
I/NPS_WSSNPS( 4128): [50.150321] AsyncBulkFlagCheck
I/NPS_WSSNPS( 4128): [50.150321] IsRemain_AsyncBulkCheck
I/NPS_WSSNPS( 4128): [50.150321] IsRemain_Asyncing nothing
W/ContextImpl( 4128): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
I/Babel   ( 4055): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 4055): MmsConfig.loadMmsSettings
I/Babel   ( 4055): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel   ( 4055): MmsConfig.loadFromDatabase
E/Babel   ( 4055): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4055): MmsConfig.loadFromResources
E/Babel   ( 4055): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4055): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
W/art     ( 4055): Suspending all threads took: 15.949ms
W/VideoCapabilities( 4055): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4055): Unsupported mime audio/evrc
W/AudioCapabilities( 4055): Unsupported mime audio/qcelp
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
W/libprocessgroup( 1019): failed to open /acct/uid_10153/pid_2962/cgroup.procs: No such file or directory
D/AndroidRuntime( 4101): 
D/AndroidRuntime( 4101): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/NPS_WSSNPS( 4128): [50.150321] Service onDestroy
D/AndroidRuntime( 4101): CheckJNI is OFF
D/AndroidRuntime( 4101): readGMSProperty: start
D/AndroidRuntime( 4101): readGMSProperty: already setted!!
D/AndroidRuntime( 4101): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4101): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4101): readGMSProperty: end
D/AndroidRuntime( 4101): addProductProperty: start
I/NPS_WSSNPS( 4128): [50.150321] smlBRConfigurationDelete
I/NPS_WSSNPS( 4128): [50.150321] smlBRMessageDelete
E/File    ( 3839): fail readDirectory() errno=2
I/NPS_WSSNPS( 4128): [50.150321] smlBREmailDelete
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ContextImpl( 1319): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/NPS_WSSNPS( 4128): [50.150321] smlBRNetworkDelete
I/NPS_WSSNPS( 4128): [50.150321] smlBRCallLogDelete
I/NPS_WSSNPS( 4128): [50.150321] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 4128): [50.150321] smlBRPenMemoMDelete
I/NPS_WSSNPS( 4128): [50.150321] smlBRSMemoDelete
I/NPS_WSSNPS( 4128): [50.150321] cpuBooster release : false
W/ContextImpl( 1319): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
I/ActivityManager( 1019): Killing 3344:flipboard.app/u0a96 (adj 15): empty #31
I/SettingSearch/SearchIntentReceiver( 1319): InitSerachDBThread thread end!
D/NPS_WSSNPS( 4128): [50.150321] dsServerSocket close
I/Gmail   ( 3839): notifyAccountChanged
I/ActivityManager( 1019): Killing 3362:com.sec.usbsettings/1000 (adj 15): empty #31
I/ActivityManager( 1019): Killing 2386:com.android.mms/u0a41 (adj 15): empty #31
I/Gmail   ( 3839): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/AudioCapabilities( 4055): Unsupported mime audio/mpeg-L1
W/AudioCapabilities( 4055): Unsupported mime audio/mpeg-L2
W/AudioCapabilities( 4055): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4055): Unsupported mime audio/x-ima
I/PCWCLIENTTRACE_SecurePreferencesJNI( 3887): [GetString-S]
W/AudioCapabilities( 4055): Unsupported mime audio/qcelp
W/AudioCapabilities( 4055): Unsupported mime audio/evrc
I/Gmail   ( 3839): getAccountsCursor
I/ReactiveServiceManager( 3887): Supported : 1
D/QSEECOMAPI: ( 1019): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 1019): App is not loaded in QSEE
V/GLSActivity( 1835): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/FactoryTestApp( 3059): [DummyFtClient$onDestroy](3059) Destroy DummyFtClient service
D/FactoryTestApp( 3059): [Support$Values.getString](3059) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 3059): [ModuleCommon$isConnectionModeNone](3059) mConnectionMode = gsm
I/FactoryTestApp( 3059): [ModuleCommon$isRunningFtClient](3059) RUNNING_FTCLIENT : false
D/FactoryTestApp( 3059): [DummyFtClient$onDestroy](3059) kill process
I/Process ( 3059): Sending signal. PID: 3059 SIG: 9
D/QSEECOMAPI: ( 1019): Loaded image: APP id = 10
W/Settings( 4055): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/QSEECOMAPI: ( 1019): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1019): QSEECom_shutdown_app, app_id = 10
E/terrier ( 1019): handleString: Failed to handle string(-4)
E/terrier ( 1019): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 3887): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 3887): [GetString-E]
I/Gmail   ( 3839): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/PCWCLIENTTRACE_PushUtil( 3887): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3887): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3887): getPushTypeList : [SPP, GCM]
D/CountryDetector( 1019): No listener is left
I/art     ( 1019): Explicit concurrent mark sweep GC freed 23684(1289KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/33MB, paused 3.978ms total 180.290ms
E/PCWCLIENTTRACE_PCWHandler( 3887): [ensureRegistration] - No Samsung account
W/VideoCapabilities( 4055): Unsupported mime video/wvc1
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/GCoreUlr( 1835): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
E/Zygote  ( 4209): MountEmulatedStorage()
E/Zygote  ( 4209): v2
I/libpersona( 4209): KNOX_SDCARD checking this for 10028
I/libpersona( 4209): KNOX_SDCARD not a persona
I/SELinux ( 4209): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4209): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=4209 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
E/SELinux ( 4209): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Killing 3407:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
D/FileShare-Server( 4177): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
I/Gmail   ( 3839): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 3839): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/AuthZen ( 2105): Handling intent: android.intent.action.BOOT_COMPLETED
W/VideoCapabilities( 4055): Unsupported mime video/x-ms-wmv
W/libprocessgroup( 1019): failed to open /acct/uid_10096/pid_3344/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3362/cgroup.procs: No such file or directory
I/ActivityManager( 1019): Process com.sec.factory (pid 3059)(adj 0) has died(47,621)
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 4209): TimaSignature is unavailable
D/ActivityThread( 4209): Added TimaKeyStore provider
W/VideoCapabilities( 4055): Unrecognized profile/level 32768/2 for video/mp4v-es
I/art     ( 1670): Explicit concurrent mark sweep GC freed 3563(152KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 4MB/6MB, paused 824us total 77.182ms
W/SQLiteConnectionPool( 1670): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/libprocessgroup( 1019): failed to open /acct/uid_10041/pid_2386/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10043/pid_3407/cgroup.procs: No such file or directory
W/VideoCapabilities( 4055): Unsupported mime video/wvc1
W/VideoCapabilities( 4055): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 4055): Unsupported mime video/x-ms-wmv7
W/VideoCapabilities( 4055): Unsupported mime video/x-ms-wmv8
W/VideoCapabilities( 4055): Unsupported mime video/mp43
W/VideoCapabilities( 4055): Unsupported mime video/sorenson
W/VideoCapabilities( 4055): Unsupported mime video/mp4v-esdp
D/AuthZenEventHandler( 2105): Handling event: android.intent.action.BOOT_COMPLETED
I/VideoCapabilities( 4055): Unsupported profile 4 for video/mp4v-es
I/Icing   ( 2105): Storage manager: low false usage 2.09MB avail 9.95GB capacity 11.63GB
E/AffinityControl( 4101): AffinityControl: registerfunction enter
I/DBG_DM  ( 3570): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
I/ActivityManager( 1019): Killing 3378:com.google.android.configupdater/u0a82 (adj 15): empty #31
I/DBG_POLICYDM( 3685): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
D/AndroidRuntime( 4101): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): Waited long enough for: ServiceRecord{2a165ab7 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
D/ChimeraCfgMgr( 2105): Reading stored module config
V/Babel   ( 4055): babel boot account: SMS
V/Babel   ( 4055): babel boot account: thalitester@gmail.com
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 3685): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
I/DBG_POLICYDM( 3685): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
I/DBG_POLICYDM( 3685): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
I/DBG_POLICYDM( 3685): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
I/DBG_POLICYDM( 3685): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
I/DBG_POLICYDM( 3685): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
E/Zygote  ( 4236): MountEmulatedStorage()
I/DBG_POLICYDM( 3685): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
I/libpersona( 4236): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4236): v2
I/libpersona( 4236): KNOX_SDCARD not a persona
I/SELinux ( 4236): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4236 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 3463:com.dropbox.android/u0a88 (adj 15): empty #31
I/SELinux ( 4236): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4236): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 4236): TimaSignature is unavailable
D/ActivityThread( 4236): Added TimaKeyStore provider
V/AlarmManager( 1019): waitForAlarm result :4
V/AlarmManager( 1019): waitForAlarm result :4
I/Gmail   ( 3839): getAccountsCursor
V/GLSActivity( 1835): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/libprocessgroup( 1019): failed to open /acct/uid_10082/pid_3378/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10088/pid_3463/cgroup.procs: No such file or directory
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/System.out( 4209): Inside onCreate() of WakeupTriggerProvide
I/System.out( 4209): Inside WakeupProvider
I/GCoreUlr( 1835): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1019): mDVFSHelper.acquire()
D/FocusedStackFrame( 1019): Set to : 0
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1019): *FMB* installDecor flags : -2122120936
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1019): Focused application set to: xxxx
D/Launcher.HomeView( 1494): onPause
D/InputDispatcher( 1019): Focus left window: 1494
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, uhalitest
D/AndroidRuntime( 4101): Shutting down VM
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/Launcher( 1494): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
E/Zygote  ( 4256): MountEmulatedStorage()
E/Zygote  ( 4256): v2
I/libpersona( 4256): KNOX_SDCARD checking this for 1000
I/libpersona( 4256): KNOX_SDCARD not a persona
I/SELinux ( 4256): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
I/SELinux ( 4256): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4256): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4256 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 2783:com.google.android.apps.plus/u0a117 (adj 15): empty #31
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1019): Killing 1611:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
V/GLSActivity( 1835): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1835): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TimaKeyStoreProvider( 4256): TimaSignature is unavailable
D/ActivityThread( 4256): Added TimaKeyStore provider
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
W/ContextImpl( 1019): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
D/BootCompletedReceiver( 2105): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
D/BootCompletedReceiver( 2105): Got an BootCompleted event.
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4273): MountEmulatedStorage()
E/Zygote  ( 4273): v2
I/libpersona( 4273): KNOX_SDCARD checking this for 10167
I/libpersona( 4273): KNOX_SDCARD not a persona
I/SELinux ( 4273): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4273 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4273): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4273): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 4273): TimaSignature is unavailable
D/ActivityThread( 4273): Added TimaKeyStore provider
I/VlingoApplication( 4209): VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
E/Zygote  ( 4288): MountEmulatedStorage()
I/libpersona( 4288): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4288): v2
I/libpersona( 4288): KNOX_SDCARD not a persona
I/SELinux ( 4288): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=4288 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 4288): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
V/ActivityThread( 1494): updateVisibility : ActivityRecord{3dd88b7d token=android.os.BinderProxy@7317aee {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
E/SELinux ( 4288): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/TimaKeyStoreProvider( 4288): TimaSignature is unavailable
D/ActivityThread( 4288): Added TimaKeyStore provider
E/KnoxSetupWizardClient( 4256): isShipMode : 1
I/KnoxSetupWizardClient( 4256): onReceive : android.intent.action.BOOT_COMPLETED
D/Launcher.HomeView( 1494): onStop
V/ActivityThread( 1494): updateVisibility : ActivityRecord{3dd88b7d token=android.os.BinderProxy@7317aee {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1019): isKioskContainerExistOnDevice
I/GCoreUlr( 1835): Unbound from all location providers
I/GCoreUlr( 1835): Place inference reporting - stopped
W/art     ( 4101): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/libprocessgroup( 1019): failed to open /acct/uid_10117/pid_2783/cgroup.procs: No such file or directory
D/Launcher( 1494): onTrimMemory. Level: 20
W/libprocessgroup( 1019): failed to open /acct/uid_10068/pid_1611/cgroup.procs: No such file or directory
W/System.err( 4256): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub,
,W/System.err( 4256): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4256): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4256): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 4256): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 4256): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4256): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/GCoreUlr( 1835): DispatchingService.onDestroy()
I/GCoreUlr( 1835): Stopping handler for UlrDispSvcFast
,D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1019): [SO] activate (ident=0xb84ab9d8, enabled=0)
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/ShortcutReceiver( 4256):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,D/BootCompletedReceiver( 2105): Will NOT schedule AdAttestation signal task because it's disabled.
,D/SensorManager( 1019): unregisterListener ::   
,I/Sensors ( 1019): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1019): [SO] changed settle time [1]
D/SensorService( 1019): [SO] setDelay [66000000]
D/SensorService( 1019): [SO] activate (ident=0xb84ab9d8, enabled=1)
D/SensorService( 1019): [SO] AR_init
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/GCoreUlr( 1835): Unbound from all location providers
I/GCoreUlr( 1835): Place inference reporting - stopped
,I/VlingoAndroidCore( 4209): AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,W/BaseAppContext( 2105): Using Auth Proxy for data requests.
,D/SensorManager( 1019): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/KnoxShortcutUtil( 4256): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4256):  KnoxContainerVersion 2.3.0
D/ShortcutReceiver( 4256):  shortcut migration not required 
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4308): MountEmulatedStorage(),
E/Zygote  ( 4308): v2
I/libpersona( 4308): KNOX_SDCARD checking this for 1000
I/libpersona( 4308): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4308 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 4308): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Killing 3503:com.sec.dsm.system/1000 (adj 15): empty #31
,I/SELinux ( 4308): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4308): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SystemUpdateService( 2105): onDestroy
,D/TimaKeyStoreProvider( 4308): TimaSignature is unavailable
,D/ActivityThread( 4308): Added TimaKeyStore provider
,D/SensorService( 1019): [SO] Reset Rotation Old [100], Init [1]
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 4288): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/StatusChecker( 4308): onReceive : android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3503/cgroup.procs: No such file or directory
,E/BaseAppContext( 2105): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,E/Zygote  ( 4332): MountEmulatedStorage()
,E/Zygote  ( 4332): v2
I/libpersona( 4332): KNOX_SDCARD checking this for 1000
I/libpersona( 4332): KNOX_SDCARD not a persona
,I/SELinux ( 4332): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4332 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4332): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/SensorService( 1019): [SO] currT = 45341062000, prevT = 45011085000, diff = 329977000, [-0.421 0.172 9.902]
D/SensorService( 1019): [SO] -0.421 0.172 9.902
D/SensorService( 1019): [SO] [100 -> 255]
,I/StatusChecker( 4308): onReceive : net.mt.init : DONE
,E/SELinux ( 4332): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/WebViewFactory( 4273): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/LibraryLoader( 4273): Loading: webviewchromium
,I/LibraryLoader( 4273): Time to load native libraries: 5 ms (timestamps 5359-5364),
I/LibraryLoader( 4273): Expected native library version number "",actual native library version number ""
,E/Zygote  ( 4348): MountEmulatedStorage()
I/libpersona( 4348): KNOX_SDCARD checking this for 10113
E/Zygote  ( 4348): v2
I/libpersona( 4348): KNOX_SDCARD not a persona
,I/SELinux ( 4348): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4348): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4348): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4332): TimaSignature is unavailable
D/ActivityThread( 4332): Added TimaKeyStore provider
,I/ActivityManager( 1019): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4348 uid=10113 gids={50113, 9997} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 3538:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
I/art     (  304): Explicit concurrent mark sweep GC freed 8748(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 621us total 21.774ms
D/TimaKeyStoreProvider( 4348): TimaSignature is unavailable
D/ActivityThread( 4348): Added TimaKeyStore provider
,V/WebViewChromiumFactoryProvider( 4273): Binding Chromium to main looper Looper (main, tid 1) {158cdc75}
,I/LibraryLoader( 4273): Expected native library version number "",actual native library version number ""
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 988us total 17.437ms
,I/chromium( 4273): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
W/ResourcesManager( 4332): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 16.763ms
,W/ContextImpl( 4332): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,I/BrowserStartupController( 4273): Initializing chromium process, renderers=0
,D/VlingoApplication( 4209): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/VlingoApplication( 4209): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,E/Zygote  ( 4370): MountEmulatedStorage(),
,E/Zygote  ( 4370): v2
I/PageBuddyNotiSvc( 4348): Intent received : action=android.intent.action.BOOT_COMPLETED
,I/libpersona( 4370): KNOX_SDCARD checking this for 1000
I/libpersona( 4370): KNOX_SDCARD not a persona
I/SELinux ( 4370): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1019): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=4370 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/F_PHONE ( 4332): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
W/ContextImpl( 4332): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,I/SELinux ( 4370): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,E/SELinux ( 4370): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,W/ContextImpl( 4348): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,I/PageBuddyNotiSvc( 4348): onCreate mCpBitFlag=0
,D/F_PHONE ( 4332): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 4332): default registerAction()
I/F_PHONE ( 4332): [[com.sec.bcservice]] sendPendingMessage()
W/art     ( 4273): Attempt to remove local handle scope entry from IRT, ignoring
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4370): TimaSignature is unavailable
,D/ActivityThread( 4370): Added TimaKeyStore provider
,D/DialogFlow( 4209): initQueue()
,E/Zygote  ( 4390): MountEmulatedStorage()
I/libpersona( 4390): KNOX_SDCARD checking this for 10121
E/Zygote  ( 4390): v2
I/libpersona( 4390): KNOX_SDCARD not a persona
I/SELinux ( 4390): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4390): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1019): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4390 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 4390): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SurfaceFlinger(  257): id=9 Removed Mauncher (5/8)
,I/SurfaceFlinger(  257): id=9 Removed Mauncher (-2/8)
,W/chromium( 4273): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 4273): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 4273): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,I/DBG_DM  ( 3570): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,D/TimaKeyStoreProvider( 4390): TimaSignature is unavailable
,D/ActivityThread( 4390): Added TimaKeyStore provider
,W/ResourcesManager( 4370): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/art     ( 2105): Suspending all threads took: 8.688ms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/BluetoothBDAdrressReceiver( 4370): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 4370): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 ,
,E/Zygote  ( 4417): MountEmulatedStorage()
,E/Zygote  ( 4417): v2,
I/libpersona( 4417): KNOX_SDCARD checking this for 10030
I/libpersona( 4417): KNOX_SDCARD not a persona
I/SELinux ( 4417): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4417): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4417): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4417 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,I/Adreno-EGL( 4273): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4273): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4273): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4273): Local Branch: 
I/Adreno-EGL( 4273): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4273): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4273):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/ResourcesManager( 4390): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4390): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4390): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3538/cgroup.procs: No such file or directory
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4429): MountEmulatedStorage(),
E/Zygote  ( 4429): v2
I/libpersona( 4429): KNOX_SDCARD checking this for 1000
I/libpersona( 4429): KNOX_SDCARD not a persona
,I/SELinux ( 4429): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4429): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=4429 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 4429): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 1461): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/ActivityManager( 1019): Killing 3547:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
,D/BluetoothBDTestService( 1461): onCreate()
E/BluetoothBDTestService( 1461): onStart(), extra_type: BOOT_COMPLETED,
,E/BluetoothBDTestService( 1461): bd_address_path: /efs/bluetooth/bt_addr
E/BluetoothBDTestService( 1461): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:2, health:2, present:true, voltage: 4297, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/TimaKeyStoreProvider( 4417): TimaSignature is unavailable
D/ActivityThread( 4417): Added TimaKeyStore provider
,I/ActivityManager( 1019): Killing 3604:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 4429): TimaSignature is unavailable
D/ActivityThread( 4429): Added TimaKeyStore provider
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
D/PowerUI ( 1172): Cable  true --> true mBootCompleted : true
V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/PowerUI ( 1172): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 3080): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3080): Disconnected process message: 10
,D/QuickConnect( 4390): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,W/ResourcesManager( 4429): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SettingsProvider( 1019): name = scon_is_running
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10121
,D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1019): ret = -1
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4288): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 4288): Resource data:2131165186
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,W/SQLiteConnectionPool( 2105): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/ResourcesManager( 4288): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4288): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 4288): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 4288): getResourceTypeNamexml
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/QuickConnect( 4390): Utils.setQCRunningSetting - set : 0
,I/QuickConnect( 4390): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service,
,I/QuickConnect( 4390): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,W/Auth    ( 1835): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/AuthZen ( 2105): Fetching signing key...
,I/AMMetaDataParserService( 4288): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509,
,E/Zygote  ( 4456): MountEmulatedStorage()
E/Zygote  ( 4456): v2
,I/libpersona( 4456): KNOX_SDCARD checking this for 10127
I/libpersona( 4456): KNOX_SDCARD not a persona
,I/ActivityManager( 1019): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4456 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,W/libprocessgroup( 1019): failed to open /acct/uid_10088/pid_3547/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10146/pid_3604/cgroup.procs: No such file or directory
,I/SELinux ( 4456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4456): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4456): TimaSignature is unavailable
,D/ActivityThread( 4456): Added TimaKeyStore provider
,V/GLSActivity( 1835): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 4456): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4456): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4456): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4456): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/GCoreFlp( 1835): No location to return for getLastLocation()
,W/FusedLocationProvider( 1835): location=null
,I/ActivityManager( 1019): Killing 3631:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,I/KnoxUsageLogPro( 4429): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,W/GCoreFlp( 1835): No location to return for getLastLocation()
,W/FusedLocationProvider( 1835): location=null
,I/KnoxUsageLogPro( 4429): savePreference: key = previous_sys_time value = 1457968326692
,I/KnoxUsageLogPro( 4429): premStatus:2
,I/KnoxUsageLogPro( 4429): isEulaShown : false
,I/KnoxUsageLogPro( 4429): KnoxUsageReceiver onReceive : not Processible, just return
,D/PersistentNotificationBroadcastReceiver( 1835): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager( 1019): Killing 3018:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,I/AuthZen ( 2105): Signing key fetched successfully!
,I/AMMetaDataParserService( 4288): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/chromium( 4273): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/BaseAppContext( 2105): Using Auth Proxy for data requests.
,W/chromium( 4273): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3631/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10090/pid_3018/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 4288): Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
D/a       ( 2105): Opening database auth.proximity.permit_store...
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom,.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,W/ContextImpl( 4288): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 4417): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 4417): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4417): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/art     ( 4273): Attempt to remove local handle scope entry from IRT, ignoring
E/Zygote  ( 4481): MountEmulatedStorage()
W/AwContents( 4273): onDetachedFromWindow called when already detached. Ignoring
,E/Zygote  ( 4481): v2
I/libpersona( 4481): KNOX_SDCARD checking this for 10026
I/libpersona( 4481): KNOX_SDCARD not a persona
I/SELinux ( 4481): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4481): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/AuthZenTransactionCache( 2105): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2105): Clearing transaction cache
,E/SELinux ( 4481): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4481 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PhoneWindow( 4273): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 4273): *FMB* installDecor flags : -2139027200
,D/SystemWebViewEngine( 4273): CordovaWebView is running on device made by: samsung
,D/TimaKeyStoreProvider( 4481): TimaSignature is unavailable
,D/ActivityThread( 4481): Added TimaKeyStore provider
W/ResourcesManager( 4417): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4417): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4417): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/art     ( 4273): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4273): Attempt to remove local handle scope entry from IRT, ignoring
E/SMD     (  288): DCD OFF
I/KnoxUsageLogPro( 4429): savePreference: key = previous_elapsed_time value = 45938
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:assistant
I/AMMetaDataParserService( 4288): Resource data:2131034113
,W/ResourcesManager( 4288): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4288): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 4288): getResourceTypeNamexml
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 4288): took 2.254948ms for 0*0 texture 0
,I/GFX generate_partition_tables( 4288): took 6.010729ms for 0*0 texture 0
,I/GFX raster( 4288): took 9.515885ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80be918 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb80db1e8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4417): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 4417): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4288): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 4288): took 0.842552ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80be918 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb80db1e8 counterpartCT=4 counterpartW=96 counterparth=96
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/SBrowserFeatureFlag( 4456): initialized in static block : loadCscFeatureValue() succeed! 
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{2a049c9f u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService},
,I/DBG_DM  ( 3570): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,I/AMMetaDataParserService( 4288): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/OpenGLRenderer( 4273): Render dirty regions requested: true
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,D/PhoneWindow( 4273): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 4273): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1019): Focus entered window: 4273
,D/ManifestProvider( 4456): onCreate()
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 4273): log_dcs ThreadedRenderer::initialize entered! 
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,I/OpenGLRenderer( 4273): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4273): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 4273): Enabling debug mode 0
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1019): Displayed Component not be shown by security: +1s756ms
,D/PanelView( 1172): There is/are notification(s) 
,E/NetworkSettingsReceiver( 4456): onReceive: android.intent.action.BOOT_COMPLETED
D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11,
,I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{3dacbf6d u0 com.test.thalitest/.MainActivity t11} time:46731
W/ActivityManager( 1019): mDVFSHelper.release()
,I/Timeline( 4273): Timeline: Activity_idle id: android.os.BinderProxy@1c8431c8 time:46758
,D/Finsky  ( 4481): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/System.err( 4456): java.lang.NoSuchMethodException: isEnabled []
,W/System.err( 4456): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 4456): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
W/System.err( 4456): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
W/System.err( 4456): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
W/System.err( 4456): 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
W/System.err( 4456): 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
W/System.err( 4456): 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
W/System.err( 4456): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 4456): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 4456): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 4456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4456): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 4456): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 4456): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4456): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4456): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 4456): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SBrowserFeatureFlag( 4456): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@16dbcaf1
,D/SBrowserFeatureFlag( 4456): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 4456): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,I/SamsungIME( 1868): getCurrentCandidateView
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4528): MountEmulatedStorage(),
E/Zygote  ( 4528): v2
I/libpersona( 4528): KNOX_SDCARD checking this for 10131
I/libpersona( 4528): KNOX_SDCARD not a persona
,I/SELinux ( 4528): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SurfaceFlinger(  257): id=11 Removed uhalitest (7/8)
,I/SurfaceFlinger(  257): id=11 Removed uhalitest (-2/8)
I/SELinux ( 4528): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4528): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4528 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/PCWCLIENTTRACE_AccountAppFacade2_0( 3887): unregister AuthInfo UpdateReceiver v2.0
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 4288): took 3.077292ms for 0*0 texture 0
,D/TimaKeyStoreProvider( 4528): TimaSignature is unavailable
,D/ActivityThread( 4528): Added TimaKeyStore provider
,I/GFX generate_partition_tables( 4288): took 8.581927ms for 0*0 texture 0
,I/GFX raster( 4288): took 12.746407ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80dbd68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80db1e8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4288): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/ResourcesManager( 4528): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4528): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4528): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/JsMessageQueue( 4273): Set native->JS mode to OnlineEventsBridgeMode
,D/SamsungIME( 1868): Dismiss ExpandCandiate
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,I/SamsungIME( 1868): getDebugLevel  : 0x4f4c
,D/daemonapp( 1808): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/Icing   ( 2105): updateResources: need to parse f{com.google.android.gms}
,I/SamsungIME( 1868): getDebugLevel  : 0x4f4c
,D/Finsky  ( 4481): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/SamsungIME( 1868): KeybaordView init() : load resources
,W/Settings( 4481): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4481): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SamsungIME( 1868): getCurrentKeyboard
I/SamsungIME( 1868): getTextKeyboard
,I/chromium( 4273): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 4273): 
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/SamsungIME( 1868): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/GFX raster( 4288): took 0.744062ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80db1e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7d27360 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4288): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4288): took 1.022082ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb7d27360 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80ca660 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4288): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 38353(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 22MB/33MB, paused 2.879ms total 199.587ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
I/GFX raster( 4288): took 0.658022ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80c9780 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80c98b8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 3839): Thread[GAThread,5,main]: No campaign data found.
,I/Process ( 4417): Sending signal. PID: 4417 SIG: 9
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,I/GAV2    ( 3663): Thread[GAThread,5,main]: No campaign data found.
,I/AMMetaDataParserService( 4288): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4288): took 0.717813ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80d4060 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80d42d8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
I/AMMetaDataParserService( 4288): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
D/jxcore_app_log( 4273): JniHelper::setJavaVM(0xb7d1f448), pthread_self() = -1204175280
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4273): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4273):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4273):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4273):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4273):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4273): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8184337 added. We now have 1 listener(s)
,I/System.out( 4209): INFO:Resource not found:/Common.properties Using default values
,E/Zygote  ( 4584): MountEmulatedStorage()
,E/Zygote  ( 4584): v2
I/libpersona( 4584): KNOX_SDCARD checking this for 10135
I/libpersona( 4584): KNOX_SDCARD not a persona
,I/SELinux ( 4584): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4584 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/SELinux ( 4584): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4584): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4595): MountEmulatedStorage()
,E/Zygote  ( 4595): v2
I/libpersona( 4595): KNOX_SDCARD checking this for 10037
I/libpersona( 4595): KNOX_SDCARD not a persona
,I/DBG_DM  ( 3570): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
I/ActivityManager( 1019): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4595 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4595): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4595): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4595): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Process com.sec.android.app.sns3 (pid 4417)(adj 0) has died(25,625)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4273): setBluetoothMacAddress: 08:EC:A9:50:76:27
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4273): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4273): setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4273): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4273): setHandshakeRequired: true -> false
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 4288): took 0.525000ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80ca520 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80da7b8 counterpartCT=4 counterpartW=96 counterparth=96
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4273): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4273):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4273):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4273):     - Bluetooth MAC address: 08:EC:A9:50:76:27
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4273):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4273):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4273):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4273):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4273):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4273):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4273): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36311c2 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4273): addListener: New listener added - the number of listeners is now 1
,D/TimaKeyStoreProvider( 4584): TimaSignature is unavailable
,D/ActivityThread( 4584): Added TimaKeyStore provider
,I/AMMetaDataParserService( 4288): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,E/Zygote  ( 4611): MountEmulatedStorage(),
E/Zygote  ( 4611): v2
I/libpersona( 4611): KNOX_SDCARD checking this for 10031
I/libpersona( 4611): KNOX_SDCARD not a persona
,I/SELinux ( 4611): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4611): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4611): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:assistant
I/AMMetaDataParserService( 4288): Resource data:2131034113
,I/ActivityManager( 1019): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4611 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4273): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,D/TimaKeyStoreProvider( 4595): TimaSignature is unavailable
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4273): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4273): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4273): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4273): setScanMode: 1 -> 2
,D/ActivityThread( 4595): Added TimaKeyStore provider
,I/AMMetaDataParserService( 4288): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 4288): getResourceTypeNamexml
E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/SSRM:n  ( 1019): SIOP:: AP = 410
,I/GFX raster( 4288): took 1.030364ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80be918 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb80da7b8 counterpartCT=4 counterpartW=96 counterparth=96
,D/Volley  ( 4481): [701] DiskBasedCache.clear: Cache cleared.
I/AMMetaDataParserService( 4288): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,I/ActivityManager( 1019): Killing 3707:com.sec.factory.camera/1000 (adj 15): empty #31
,I/ActivityManager( 1019): Killing 3685:com.policydm/1000 (adj 15): empty #32
,D/TimaKeyStoreProvider( 4611): TimaSignature is unavailable
,D/ActivityThread( 4611): Added TimaKeyStore provider
,D/Finsky  ( 4481): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4481): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 4481): Skipping gmscore version check
,W/ResourcesManager( 4595): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/chromium( 4273): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ResourcesManager( 4584): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4584): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4584): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4584): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4584): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/Finsky  ( 4481): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Volley  ( 4481): [708] DiskBasedCache.clear: Cache cleared.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4634 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,E/Zygote  ( 4634): MountEmulatedStorage()
E/Zygote  ( 4634): v2
I/libpersona( 4634): KNOX_SDCARD checking this for 10141
I/libpersona( 4634): KNOX_SDCARD not a persona
,I/SELinux ( 4634): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/CalendarProvider2( 4595): CalendarProvider2.onCreate() called,
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0,
,I/SELinux ( 4634): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4634): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  304): Explicit concurrent mark sweep GC freed 8714(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 682us total 38.935ms
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 4288): took 0.801615ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80be918 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb80da7b8 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4634): TimaSignature is unavailable
D/ActivityThread( 4634): Added TimaKeyStore provider
,I/AMMetaDataParserService( 4288): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 27.734ms
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3707/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3685/cgroup.procs: No such file or directory
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 691us total 22.451ms
,E/Zygote  ( 4649): MountEmulatedStorage()
,I/libpersona( 4649): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4649): v2
I/libpersona( 4649): KNOX_SDCARD not a persona
,I/SELinux ( 4649): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1019): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4649 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4649): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4649): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Killing 3755:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 4288): took 0.610156ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80dbd68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80da7b8 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4649): TimaSignature is unavailable
D/ActivityThread( 4649): Added TimaKeyStore provider
,I/AMMetaDataParserService( 4288): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/ResourcesManager( 4634): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4288): took 0.648021ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80db1e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80da7b8 counterpartCT=4 counterpartW=96 counterparth=96
,D/Finsky  ( 4481): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ResourcesManager( 4634): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4634): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4634): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 1019): Killing 3803:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,I/AMMetaDataParserService( 4288): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/art     ( 4209): Suspending all threads took: 18.855ms
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4288): took 0.817187ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb7d27360 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80da7b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4288): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/libprocessgroup( 1019): failed to open /acct/uid_10095/pid_3755/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10098/pid_3803/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 4649): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 4649): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_POLICYDM( 4649): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 4649): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 4649): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 4649): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 4649): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 4649): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,I/DBG_POLICYDM( 4649): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 4649): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 4649): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,I/DBG_POLICYDM( 4649): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 4649): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,V/AlarmManager( 1019): waitForAlarm result :8
,I/DBG_POLICYDM( 4649): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 4649): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 4649): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 4649): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_POLICYDM( 4649): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4671 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 4671): MountEmulatedStorage()
E/Zygote  ( 4671): v2
I/libpersona( 4671): KNOX_SDCARD checking this for 10032
I/libpersona( 4671): KNOX_SDCARD not a persona
,I/SELinux ( 4671): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Killing 3824:com.fmm.dm/1000 (adj 15): empty #31
,I/SELinux ( 4671): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4671): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4671): TimaSignature is unavailable,
,D/ActivityThread( 4671): Added TimaKeyStore provider
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4288): took 0.798177ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80c9780 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80da7b8 counterpartCT=4 counterpartW=96 counterparth=96
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/AMMetaDataParserService( 4288): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/DBG_POLICYDM( 4649): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 4649): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4649): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 4288): took 0.675990ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80d4060 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80da7b8 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_POLICYDM( 4649): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 4649): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,I/DBG_POLICYDM( 4649): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,I/AMMetaDataParserService( 4288): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/DBG_POLICYDM( 4649): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,I/DBG_POLICYDM( 4649): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 4649): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 4649): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 4649): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 4649): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4649): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 4649): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/20/16:34:31,
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3824/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 4649): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 4649): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 4649): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 4649): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/14/16:12:09
,I/DBG_POLICYDM( 4649): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 4649): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 4649): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 4649): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 4649): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 4649): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4288): took 0.649739ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80ca520 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80da7b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4649): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,I/DBG_DM  ( 3570): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,I/AMMetaDataParserService( 4288): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527,
,I/DBG_POLICYDM( 4649): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 4288): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 4288): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4288): getResourcePackageName:assistant
I/AMMetaDataParserService( 4288): Resource data:2131034112
I/AMMetaDataParserService( 4288): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 4288): getResourceTypeNamexml
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/SPPClientService( 4671): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 4671): [PushClientApplication] Push log off : This is Ship build version
,I/GFX raster( 4288): took 0.769533ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80db1e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80da7b8 counterpartCT=4 counterpartW=96 counterparth=96
,E/SPPClientService( 4671): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,I/AMMetaDataParserService( 4288): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,D/SPPClientService( 4671): PushLog.txt file is not deleted.
,D/SPPClientService( 4671): PushLog.txt file is not deleted.
D/SPPClientService( 4671): ============PushLog. stop!
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,I/DBG_POLICYDM( 4649): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/Zygote  ( 4695): MountEmulatedStorage(),
I/libpersona( 4695): KNOX_SDCARD checking this for 10036
E/Zygote  ( 4695): v2
I/libpersona( 4695): KNOX_SDCARD not a persona
I/SELinux ( 4695): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4695): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4695): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4695 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_POLICYDM( 4649): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1,
,I/GFX raster( 4288): took 0.645105ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80db1e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80da7b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4649): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,I/AMMetaDataParserService( 4288): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,D/TimaKeyStoreProvider( 4695): TimaSignature is unavailable
,D/ActivityThread( 4695): Added TimaKeyStore provider
,I/ActivityManager( 1019): Killing 1519:com.android.defcontainer/u0a3 (adj 15): empty #31
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,W/art     ( 4209): Suspending all threads took: 59.297ms
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4288): took 0.635677ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80da7b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7d25a30 counterpartCT=4 counterpartW=96 counterparth=96
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 4288): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,W/libprocessgroup( 1019): failed to open /acct/uid_10003/pid_1519/cgroup.procs: No such file or directory
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4288): took 0.775938ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80db1e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80be918 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4288): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activit,ycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:assistant
I/AMMetaDataParserService( 4288): Resource data:2131034113
I/AMMetaDataParserService( 4288): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 4288): getResourceTypeNamexml
E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 4288): took 0.811302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80d3eb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb80be918 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4649): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,I/AMMetaDataParserService( 4288): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 4649): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,E/Zygote  ( 4715): MountEmulatedStorage()
E/Zygote  ( 4715): v2
I/libpersona( 4715): KNOX_SDCARD checking this for 10068
I/libpersona( 4715): KNOX_SDCARD not a persona
,I/SELinux ( 4715): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4288): took 0.834687ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80d3eb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7d7ede0 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 4715): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4715 uid=10068 gids={50068, 9997} abi=armeabi-v7a
E/SELinux ( 4715): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/SensorService( 1019): [SO] -0.421 0.172 9.864
,I/DBG_POLICYDM( 4649): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false,
,I/AMMetaDataParserService( 4288): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/TimaKeyStoreProvider( 4715): TimaSignature is unavailable
,D/ActivityThread( 4715): Added TimaKeyStore provider
,I/Icing   ( 2105): Internal init done: storage state 0
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4288): took 0.596146ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80be918 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7d7ede0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4288): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/Icing   ( 2105): Post-init done
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
,V/AlarmManager( 1019): waitForAlarm result :4
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email,
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/GFX raster( 4288): took 0.596614ms for 96*96 texture 0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb7d7ede0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80e6ed0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4288): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/Zygote  ( 4732): MountEmulatedStorage()
E/Zygote  ( 4732): v2
I/libpersona( 4732): KNOX_SDCARD checking this for 10117
I/libpersona( 4732): KNOX_SDCARD not a persona
,I/SELinux ( 4732): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService: pid=4732 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4732): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SELinux ( 4732): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 4715): onCreate
D/BadgeProvider( 4715): DatabaseHelper
,D/TimaKeyStoreProvider( 4732): TimaSignature is unavailable
,D/ActivityThread( 4732): Added TimaKeyStore provider
,D/BadgeProvider( 4715): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4288): took 0.820000ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80c9018 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80c8f48 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4732): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 4695): [SSP] onCreated
I/AMMetaDataParserService( 4288): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Watchdog( 1019): !@Sync 1,
,E/Zygote  ( 4754): MountEmulatedStorage()
,E/Zygote  ( 4754): v2
I/libpersona( 4754): KNOX_SDCARD checking this for 10142,
,I/ActivityManager( 1019): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4754 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/libpersona( 4754): KNOX_SDCARD not a persona
,D/SettingsProvider( 1019): name = audio_safe_volume_state
,I/SELinux ( 4754): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4754): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1019): Killing 3940:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
I/ActivityManager( 1019): Killing 3913:com.fmm.ds/1000 (adj 15): empty #32
,E/SELinux ( 4754): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SMD     (  288): DCD OFF
,D/BadgeProvider( 4715): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4715): sendNotify, [notify] : null
D/BadgeProvider( 4715): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4715): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4715): update, [UpdateCount] : 1
,D/Launcher.Model( 1494): reloadBadges entered.
D/TimaKeyStoreProvider( 4754): TimaSignature is unavailable
,D/ActivityThread( 4754): Added TimaKeyStore provider
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4288): took 0.789896ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80db1e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7d27360 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4754): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
,I/AMMetaDataParserService( 4288): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4288): took 0.682500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb7d7f870 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7d25a30 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4288): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/libprocessgroup( 1019): failed to open /acct/uid_10055/pid_3940/cgroup.procs: No such file or directory
,W/ActivityManager( 1019): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3913/cgroup.procs: No such file or directory
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): getTasks: caller 10141 does not hold GET_TASKS; limiting output
,W/art     ( 4273): Suspending all threads took: 8.605ms
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId,
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/art     ( 4273): Background sticky concurrent mark sweep GC freed 30078(2MB) AllocSpace objects, 0(0B) LOS objects, 7% free, 17MB/19MB, paused 9.654ms total 35.960ms
,I/Process ( 4634): Sending signal. PID: 4634 SIG: 9
,I/SA      ( 4695): [TPM] There is no property file
,I/SA      ( 4695): [SCU] isHaveSA() - false
,I/SA      ( 4695): [TPM] getModelProperty : null
I/SA      ( 4695): [TPM] getCSCProperty : null
,I/SA      ( 4695): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4695): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4695): [DM] TFT FEATURE: false
,I/SA      ( 4695): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4695): [DM] init START
,I/SA      ( 4695): [DM] This device is not a Vodafone
,I/ActivityManager( 1019): Process com.android.email (pid 4634)(adj 9) has died(56,576)
,W/jxcore-log( 4273): Initializing JXcore engine
,W/jxcore-log( 4273): JXcore engine is ready
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4776): MountEmulatedStorage()
E/Zygote  ( 4776): v2
I/libpersona( 4776): KNOX_SDCARD checking this for 1000
I/libpersona( 4776): KNOX_SDCARD not a persona
,I/SELinux ( 4776): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4776): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4776 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 4776): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4776): TimaSignature is unavailable
,D/ActivityThread( 4776): Added TimaKeyStore provider
,E/Zygote  ( 4789): MountEmulatedStorage()
,I/libpersona( 4789): KNOX_SDCARD checking this for 10141
E/Zygote  ( 4789): v2
I/libpersona( 4789): KNOX_SDCARD not a persona
I/SELinux ( 4789): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4789): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1019): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4789 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,W/ResourceType( 4695): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75),
W/ResourceType( 4695): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4695): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 4695): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4695): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75),
W/ResourceType( 4695): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4695): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,E/SELinux ( 4789): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourceType( 4695): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4695): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 4695): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 4695): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4695): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4695): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 4695): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 4695): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 4695): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4695): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 4695): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
,W/ResourceType( 4695): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4695): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 4695): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4695): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 4695): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4695): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 4695): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 4695): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,D/TimaKeyStoreProvider( 4789): TimaSignature is unavailable
,D/ActivityThread( 4789): Added TimaKeyStore provider
I/SA      ( 4695): [SCU] isHaveSA() - false
I/SA      ( 4695): support phone number id : false
I/SA      ( 4695): [DM] Supports Ref Jpn : true
,I/SA      ( 4695): [DM] init END
,I/ActivityManager( 1019): Killing 3731:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,I/SA      ( 4695): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 4695): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4695): [OR] onReceive END
,W/ResourcesManager( 4789): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4789): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4789): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4789): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SA      ( 4695): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 4695): [ODM] queryOpenData(key= GEO_IP )
,I/SA      ( 4695): getMccForGalaxyJpn step2 GEO_IP MCC : 260
,W/libprocessgroup( 1019): failed to open /acct/uid_10008/pid_3731/cgroup.procs: No such file or directory
,I/SA      ( 4695): [LBE] REF_JPN : true
I/SA      ( 4695): [BDC] create
,I/DBG_DM  ( 3570): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,E/audit   ( 1920): type=1400 msg=audit(1457968330.381:205): avc:  denied  { ioctl } for  pid=4624 comm="Thread-667" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1920):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1920): type=1300 msg=audit(1457968330.381:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=920db8f8 items=0 ppid=304 ppcomm=main pid=4624 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-667" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1920): type=1320 msg=audit(1457968330.381:205): 
,I/SA      ( 4695): [DBMV2] getEmailID
,I/SA      ( 4695): [DBMV2] getDataV02ForItems
I/SA      ( 4695): [SSP] query invoked
,W/jxcore-log( 4273): Starting JXcore engine
,I/SA      ( 4695): [SCU] get signed id from samsung account2.0 DB.
,I/SA      ( 4695): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4695): [BDC] destroy
,I/ActivityManager( 1019): Killing 3969:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4820): MountEmulatedStorage()
E/Zygote  ( 4820): v2
I/libpersona( 4820): KNOX_SDCARD checking this for 1000
I/libpersona( 4820): KNOX_SDCARD not a persona
,I/SELinux ( 4820): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4820 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 3993:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,I/SELinux ( 4820): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4820): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Killing 3839:com.google.android.gm/u0a99 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4820): TimaSignature is unavailable
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4288): took 0.541458ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80e6ed0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80c8f48 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityThread( 4820): Added TimaKeyStore provider
,I/AMMetaDataParserService( 4288): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
W/ContextImpl( 4288): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,D/BadgeProvider( 4715): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:assistant
I/AMMetaDataParserService( 4288): Resource data:2131165203
,W/ResourcesManager( 4288): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/BadgeProvider( 4715): sendNotify entered. [uri] : content://com.sec.badge/apps/1
W/ResourcesManager( 4288): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/BadgeProvider( 4715): sendNotify, [notify] : null
,D/BadgeProvider( 4715): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4715): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4715): update, [UpdateCount] : 1
,D/Launcher.Model( 1494): reloadBadges entered.
,W/ActivityManager( 1019): getTasks: caller 10142 does not hold GET_TASKS; limiting output
,I/Process ( 4754): Sending signal. PID: 4754 SIG: 9
,I/AMMetaDataParserService( 4288): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 4288): getResourceTypeNamexml
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX construct_block_size_descriptor_2d second part( 4288): took 3.598646ms for 0*0 texture 0
,D/SecurityLogAgent( 4820): KnoxConfiguration : Current State = 1
I/GFX generate_partition_tables( 4288): took 17.239062ms for 0*0 texture 0
,I/GFX raster( 4288): took 21.382135ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80d90e8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb80d9df0 counterpartCT=4 counterpartW=80 counterparth=80
,D/SecurityLogAgent( 4820): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 4820): StateMachine : Current State = 1
I/AMMetaDataParserService( 4288): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,D/SecurityLogAgent( 4820): BootReceiver : completed task. Failed to return wakelock . 
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4844 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 4029:com.android.managedprovisioning/u0a20 (adj 15): empty #31
,E/Zygote  ( 4844): MountEmulatedStorage()
E/Zygote  ( 4844): v2
I/libpersona( 4844): KNOX_SDCARD checking this for 10148
I/libpersona( 4844): KNOX_SDCARD not a persona
,W/libprocessgroup( 1019): failed to open /acct/uid_10056/pid_3969/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10099/pid_3839/cgroup.procs: No such file or directory
,I/SELinux ( 4844): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/libprocessgroup( 1019): failed to open /acct/uid_10013/pid_3993/cgroup.procs: No such file or directory
I/SELinux ( 4844): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4844): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Process com.android.exchange (pid 4754)(adj 13) has died(38,596),
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX construct_block_size_descriptor_2d second part( 4288): took 2.814844ms for 0*0 texture 0
,D/TimaKeyStoreProvider( 4844): TimaSignature is unavailable
,D/ActivityThread( 4844): Added TimaKeyStore provider
,I/GFX generate_partition_tables( 4288): took 5.352082ms for 0*0 texture 0
,I/GFX raster( 4288): took 9.398436ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb844c320 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb844c3c8 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 4288): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,W/libprocessgroup( 1019): failed to open /acct/uid_10020/pid_4029/cgroup.procs: No such file or directory
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 4288): took 0.741510ms for 80*80 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb844c320 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb80d81e0 counterpartCT=4 counterpartW=80 counterparth=80
,E/SQLiteLog( 4844): (284) automatic index on shooting_modes(title_id)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 4288): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,E/Zygote  ( 4866): MountEmulatedStorage(),
I/libpersona( 4866): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4866): v2,
I/libpersona( 4866): KNOX_SDCARD not a persona
I/SELinux ( 4866): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4866 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 4866): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 4866): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80,
I/GFX raster( 4288): took 0.696458ms for 80*80 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb844c320 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8448720 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 4288): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575,
D/TimaKeyStoreProvider( 4866): TimaSignature is unavailable,
D/ActivityThread( 4866): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 854us total 40.446ms,
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 19.492ms,
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 23074(1262KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 22MB/33MB, paused 2.686ms total 153.947ms,
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 17.564ms
,I/splitIntent( 1019): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1019): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1019): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,I/splitIntent( 1019): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
,I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX raster( 4288): took 0.765781ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80d90e8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7d7ede0 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 4288): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,D/SIP     ( 1461): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,E/File    ( 1461): fail readDirectory() errno=2
,I/CalendarProvider2( 4595): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 4288): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 4288): took 0.796563ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4288): Bitmap=0xb80d90e8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb80be918 counterpartCT=4 counterpartW=80 counterparth=80
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/ActivityManager( 1019): Killing 4055:com.google.android.talk/u0a102 (adj 15): empty #31
,I/AMMetaDataParserService( 4288): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
W/ContextImpl( 4288): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4288): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/ActivityManager( 1019): Killing 3778:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,D/WearableService( 1835): callingUid 10011, callindPid: 1835
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1835): [227] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2105): Restart initialization of location
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 4288): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4288): getResourcePackageName:assistant
I/AMMetaDataParserService( 4288): Resource data:2131099648
,W/ResourcesManager( 4288): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4288): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4288): getResourceTypeNamexml
,I/AMMetaDataParserService( 4288): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityManager( 1019): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/AMMetaDataParserService( 4288): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 4288): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1461): query,matched:0, calling pid = 2105
,D/TP/SmsProvider( 1461): match 0:Elapsed time : 1.524 ms
,D/TP/MmsProvider( 1461): Query uri=content://mms, match=0, calling pid = 2105
,D/TP/SmsProvider( 1461): query,matched:0, calling pid = 2105
,D/TP/SmsProvider( 1461): match 0:Elapsed time : 1.306 ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3570): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,I/AMMetaDataParserService( 4288): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/TP/MmsProvider( 1461): Query uri=content://mms, match=0, calling pid = 2105
,I/AMMetaDataParserService( 4288): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/AMMetaDataParserService( 4288): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/IcingInternalCorpora( 2105): getNumBytesRead when not calculated.
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:assistant
I/AMMetaDataParserService( 4288): Resource data:2131099648
,I/AMMetaDataParserService( 4288): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4288): getResourceTypeNamexml
,I/AMMetaDataParserService( 4288): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/AMMetaDataParserService( 4288): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 4288): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/AMMetaDataParserService( 4288): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/AMMetaDataParserService( 4288): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/AMMetaDataParserService( 4288): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
,I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:assistant
I/AMMetaDataParserService( 4288): Resource data:2131099648
,I/AMMetaDataParserService( 4288): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4288): getResourceTypeNamexml
,I/AMMetaDataParserService( 4288): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/AMMetaDataParserService( 4288): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 4288): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/AMMetaDataParserService( 4288): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1835): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/a       ( 1835): Opening database auth.proximity.permit_store...
,I/AMMetaDataParserService( 4288): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4288): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,V/GLSActivity( 1835): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:assistant
I/AMMetaDataParserService( 4288): Resource data:2131099648
,I/AMMetaDataParserService( 4288): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4288): getResourceTypeNamexml
,V/GLSActivity( 1835): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 4288): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4288): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 4288): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/AMMetaDataParserService( 4288): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/AMMetaDataParserService( 4288): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/libprocessgroup( 1019): failed to open /acct/uid_10102/pid_4055/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10014/pid_3778/cgroup.procs: No such file or directory
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4288): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,V/GLSActivity( 1835): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:assistant
I/AMMetaDataParserService( 4288): Resource data:2131099648
,I/AMMetaDataParserService( 4288): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4288): getResourceTypeNamexml
,I/AMMetaDataParserService( 4288): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4288): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 4288): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/GCoreFlp( 1835): No location to return for getLastLocation()
,W/FusedLocationProvider( 1835): location=null
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 4288): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 4288): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 4288): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:assistant
I/AMMetaDataParserService( 4288): Resource data:2131099648
,I/AMMetaDataParserService( 4288): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4288): getResourceTypeNamexml
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 4288): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1019): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1019): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1019): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4288): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4288): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1835): [242] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4288): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2105): Restart initialization of location
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4288): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1835): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/AMMetaDataParserService( 4288): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
W/ContextImpl( 4288): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 4288): Resource data:Loop for ,running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4288): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService,( 4288): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:assistant
I/AMMetaDataParserService( 4288): Resource data:2131165197
W/ResourcesManager( 4288): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 4288): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 4288): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 4288): getResourceTypeNamexml
,I/art     ( 1835): Explicit concurrent mark sweep GC freed 29189(1900KB) AllocSpace objects, 21(335KB) LOS objects, 40% free, 9MB/16MB, paused 1.178ms total 83.167ms
,I/AMMetaDataParserService( 4288): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,V/GLSActivity( 1835): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4288): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/GCoreFlp( 1835): No location to return for getLastLocation()
,W/FusedLocationProvider( 1835): location=null
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4916): MountEmulatedStorage()
,I/libpersona( 4916): KNOX_SDCARD checking this for 10041
E/Zygote  ( 4916): v2
I/libpersona( 4916): KNOX_SDCARD not a persona
I/SELinux ( 4916): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4916): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.widget.MmsWidgetProvider: pid=4916 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/SELinux ( 4916): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/AMMetaDataParserService( 4288): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/TimaKeyStoreProvider( 4916): TimaSignature is unavailable
,D/ActivityThread( 4916): Added TimaKeyStore provider
,I/AMMetaDataParserService( 4288): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4288): getResourcePackageName:assistant
I/AMMetaDataParserService( 4288): Resource data:2131165197
,I/AMMetaDataParserService( 4288): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 4288): getResourceTypeNamexml
,W/ResourcesManager( 4916): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4916): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4916): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4916): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4916): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4288): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 4288): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/Mms/MmsApp( 4916): [start]    onCreate() consume time = 0.0
,I/AMMetaDataParserService( 4288): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/DBG_DM  ( 3570): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,I/AMMetaDataParserService( 4288): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.cooliris.media.Gallery
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:assistant
I/AMMetaDataParserService( 4288): Resource data:2131165197
,I/AMMetaDataParserService( 4288): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 4288): getResourceTypeNamexml
,I/AMMetaDataParserService( 4288): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 4288): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623,
,I/AMMetaDataParserService( 4288): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/art     ( 4916): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 120.440ms
,I/AMMetaDataParserService( 4288): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/DBG_POLICYDM( 4649): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
W/ContextImpl( 4288): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.Pho,toNote
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 4288): getResourcePackageName:assistant
I/AMMetaDataParserService( 4288): Resource data:2131099648
,W/ResourcesManager( 4288): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4288): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 4288): getResourceTypeNamexml
,I/DBG_POLICYDM( 4649): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 4649): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 4649): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4649): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4649): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 4649): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4649): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/AMMetaDataParserService( 4288): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,W/art     ( 4916): Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 114.037ms
,D/Mms/ArtClassLoader( 4916): init before art
,D/Mms/TelephonyPermission( 4916): start operation mode monitor
,I/AMMetaDataParserService( 4288): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,W/ResourcesManager( 4916): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
W/ContextImpl( 4288): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/Mms/TelephonyPermission( 4916): DefaultSmsApp is com.android.mms
,D/Mms/TelephonyPermission( 4916): isDefault true
,D/Mms/MmsApp( 4916): onCreate() com.android.mms
,D/Mms/MmsApp( 4916): [start]    initCountryIso consume time = 360.281354
,D/CountryDetector( 1019): The first listener is added
,D/Mms/MmsApp( 4916): [end]    initCountryIso consume time = 7.882552
D/Mms/MmsConfig( 4916): [start]    MmsConfig.init() consume time = 0.141563
,D/Mms/MmsConfig( 4916): before partial update
,D/Mms/MmsConfig( 4916): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 4916): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 4916): isAuth is false
,D/Mms/MmsConfig( 4916): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:assistant
I/AMMetaDataParserService( 4288): Resource data:2131165220
,D/TP/MmsSmsProvider( 1461): query,matched:2117, calling pid = 4916
,D/TP/MmsSmsProvider( 1461): match 2117:Elapsed time : 1.876 ms
,W/ResourcesManager( 4288): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4288): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4288): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 4288): getResourceTypeNamexml
,D/EasySignUpManager_1.0.1( 4916): isAuth is false
D/EasySignUpManager_1.0.1( 4916): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 4916): mps_code.dat does not exist
E/CscParser( 4916): customer_path =/system/csc/customer.xml
E/CscParser( 4916): fileName + /system/csc/customer.xml
,I/AMMetaDataParserService( 4288): Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
,I/AMMetaDataParserService( 4288): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,E/CscParser( 4916): mps_code.dat does not exist
E/CscParser( 4916): customer_path =/system/csc/customer.xml
E/CscParser( 4916): fileName + /system/csc/customer.xml
,D/CscParser( 4916): getInstance fileName =/system/csc/customer.xml,
,D/Mms/MmsConfig( 4916):  enable multiwindow = false
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SubSettings
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL,
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
,I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
,I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity,
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings,
,I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check,
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity,
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE,
I/AMMetaDataParserService( 4288): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
W/ContextImpl( 4288): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.TetherSettings,
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/ActivityManager( 1019): Killing 4075:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
,I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
,I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
,I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.DockSettings
,I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
,I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
,I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
,I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.MediaFormat
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
,I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
,I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ActivityPicker
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
,I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
,I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
,I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
,I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ModePreview,
E/Mms/MessageUtils( 4916): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 4916): updateCountryIso : update country iso info 
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.sec.android.sdk.cover.MODE
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
,I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/Mms/MmsConfig( 4916): [end]    init() consume time = 137.489843
,D/Mms/Contact( 4916): [start]    init() consume time = 0.552448
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 4288): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4288): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 4288): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
D/TP/MmsSmsProvider( 1461): query,matched:13, calling pid = 4916
D/TP/MmsSmsProvider( 1461): match 13:Elapsed time : 1.800 ms
D/Mms/Contact( 4916): [end]    init consume time = 35.561927
D/Mms/DraftCache( 4916): [start]    rebuildCache consume time = 10.338959
D/TP/MmsSmsProvider( 1461): query,matched:12, calling pid = 4916
D/TP/MmsSmsProvider( 1461): match 12:Elapsed time : 1.239 ms
D/Mms/MethodReflector( 4916): getSubId is called
D/Mms/TelephonyUtils( 4916): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 4916): getTelephonyProperty is called
D/Mms/DownloadManager( 4916): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4916): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4916): auto download without roaming -> true
D/Mms/DownloadManager( 4916): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/MethodReflector( 4916): getSubId is called
D/Mms/MethodReflector( 4916): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 4916): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 4916): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 4916): getTelephonyProperty is called
D/Mms/DownloadManager( 4916): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 4916): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 4916): auto download without roaming -> true
D/Mms/DraftCache( 4916): [end]    rebuildCache consume time = 21.238385
D/Mms/DownloadManager( 4916): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 4916): auto download during roaming secondary -> false
D/Mms/DownloadManager( 4916): mAutoDownload ------> true
E/SMD     (  288): DCD OFF
D/ComposerPerformance( 4916): 1457968332942 ms / [DONE] Composer constructor
E/CII     ( 4916): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 4916): ReservationManager()
I/Mms/ReservationManager( 4916): resetAfterConnected()
D/TP/MmsSmsProvider( 1461): query,matched:7, calling pid = 4916
D/TP/MmsSmsProvider( 1461): match 7:Elapsed time : 2.877 ms
I/Mms/ReservationManager( 4916): getReservedSendMessageCount(): retMessageCount=0
D/Mms/Conversation( 4916): [start]    init() consume time = 50.571042
D/TP/MmsSmsProvider( 1461): deleteConversation threadId: 9223372036854775807
D/Mms/MmsApp( 4916): [end]    onCreate() consume time = 2.934687
D/TP/MmsSmsProvider( 1461): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1461): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1461): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1461): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1461): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1461): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1461): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1461): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1461): (284) automatic index on im_threads(normal_thread_id)
,D/Mms/DownloadManager( 4916): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 4916): roaming ------> false, mSimSlot = 0
D/TP/MmsSmsProvider( 1461): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1461): need read changed broadcast:false
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
I/ActivityManager( 1019): Killing 4085:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
D/Mms/MethodReflector( 4916): getSubId is called
D/Mms/TelephonyUtils( 4916): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 4916): getTelephonyProperty is called
D/Mms/DownloadManager( 4916): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4916): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4916): auto download without roaming -> true
D/Mms/DownloadManager( 4916): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/DownloadManager( 4916): mAutoDownload ------> true
D/Mms/Conversation( 4916): [end]    init consume time = 28.044323
D/Mms/MessagingNotification( 4916): [start]    init() consume time = 1.50349
D/Mms/MessagingNotification( 4916): [end]    init consume time = 3.559687
W/libprocessgroup( 1019): failed to open /acct/uid_10058/pid_4075/cgroup.procs: No such file or directory
D/TP/MmsSmsProvider( 1461): query,matched:0, calling pid = 4916
V/TP/MmsSmsProvider( 1461): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1461): match 0:Elapsed time : 3.960 ms
D/Mms/Synchronizer( 4916): [start]    doSync consume time = 9.549167
D/TP/MmsSmsProvider( 1461): update, matched:300, calling pid = 4916
V/TP/MmsSmsProvider( 1461): syncDBData start
V/TP/MmsSmsProvider( 1461): syncDBData sms end
V/TP/MmsSmsProvider( 1461): syncDBData mms end
V/TP/MmsSmsProvider( 1461): syncDBData end
D/Mms/Synchronizer( 4916): [end]    doSync consume time = 6.622604
,D/Mms/SpamFilter( 4916): [start]    SpamFilter fill() begin consume time = 1.752604
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/TP/MmsSmsProvider( 1461): query,matched:400, calling pid = 4916
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/Mms/ArtClassLoader( 4916): init [DONE] art
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/SpamFilter( 4916): [end]    SpamFilter fill() finished consume time = 24.12974
,D/Mms/MessagingNotification( 4916): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1461): query,matched:26, calling pid = 4916
,D/TP/SmsProvider( 1461): match 26:Elapsed time : 1.402 ms
,D/TP/MmsSmsProvider( 1461): query,matched:6, calling pid = 4916
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4085/cgroup.procs: No such file or directory
,D/TP/MmsSmsProvider( 1461): match 6:Elapsed time : 2.652 ms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4945): MountEmulatedStorage()
,I/ActivityManager( 1019): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4945 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 4945): v2
I/libpersona( 4945): KNOX_SDCARD checking this for 1000
I/libpersona( 4945): KNOX_SDCARD not a persona
,I/SELinux ( 4945): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4945): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4945): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4955): MountEmulatedStorage()
,E/Zygote  ( 4955): v2
I/libpersona( 4955): KNOX_SDCARD checking this for 10023
I/libpersona( 4955): KNOX_SDCARD not a persona
,I/SELinux ( 4955): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4955): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4955 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,E/SELinux ( 4955): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4945): TimaSignature is unavailable
,D/ActivityThread( 4945): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 4955): TimaSignature is unavailable
,D/ActivityThread( 4955): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ActivityManager( 1019): Killing 4109:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/MTPRx   ( 4945): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1019): uri = 14 selection = getSealedState
D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1019): mCursor = null
,V/MTPRx   ( 4945): sealedState: false
V/MTPRx   ( 4945): sealedUsbMassStorageState: false
E/MTPRx   ( 4945): check value of boot_completed is1
E/MTPRx   ( 4945): check booting is completed_sys.boot_completed
,E/MTPRx   ( 4945): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4945): Status for mount/Unmount :removed
,E/MTPRx   ( 4945): SDcard is not available
,W/MTPRx   ( 4945): value of connected istrue
W/MTPRx   ( 4945): value of configured istrue
W/MTPRx   ( 4945): value of mtpEnabled istrue
W/MTPRx   ( 4945): value of ptpEnabled isfalse
,E/MTPRx   ( 4945): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 4945): mFirstTime: false
,D/        ( 4945): MTP: reading debug level property
,E/MTPJNIInterface( 4945): Getting CryptionKey from JAVA
,E/MTPRx   ( 4945): currentUserId is 0
,I/ValidateNoPeople( 1019): mEvictionCount: 0
,D/Mms/Contact( 4916): sContactsObserver.onChange(),selfUpdate=false
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4109/cgroup.procs: No such file or directory
,D/Mms/Contact( 4916): performUpdate:widgetCount=0
,E/MTPRx   ( 4945): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 4945): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 4945): is_Privatemode is NOT 1
,D/Mms/ContactsCache( 4916): [start]    invalidate() consume time = 245.977395
,D/Mms/ContactsCache( 4916): [end]    invalidate() consume time = 0.871511
,D/SettingsProvider( 1019): name = boot_time_connected
,E/MTPRx   ( 4945): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 4945): noti = 17
,D/SettingsProvider( 1019): name = mtp_usb_conditions_met
,D/SecContentProvider( 1019): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 4945): sending MTP_ICON_ENABLED to stack
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1019): name = mtp_running_status
,D/SettingsProvider( 1019): name = mtp_usb_conditions_met
,E/MTPRx   ( 4945): else part ... so first time!!!
,E/MTPPlaObsrvr( 4945): inside setContext()
E/MTPPlaObsrvr( 4945):  inside createplafiles
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,I/OMACP   ( 4955): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,E/MTPPlaObsrvr( 4945): playlist count is0
E/MTPPlaObsrvr( 4945):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4945):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4945): Inside registerContentObserver
,E/MtpAdbObserver( 4945): inside setContext()
E/MtpAdbObserver( 4945): Inside registerContentObserver
W/Settings( 4945): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/Mms/Omacp( 4916): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1019): name = mtp_running_status
,D/SettingsProvider( 1019): name = mtp_usb_conditions_met
,E/MtpService( 4945): onCreate.
,I/DBG_DM  ( 3570): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
,E/MtpService( 4945): < MTP > Registering BroadCast receiver :::::
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/OMACP   ( 4955): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,V/MtpMediaDBManager( 4945): inside deleteAllDB
,I/OMACP   ( 4955): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 4955): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 4955): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 4955): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false,
,I/OMACP   ( 4955): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false,
,I/OMACP   ( 4955): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false,
,I/OMACP   ( 4955): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false,
E/MtpService( 4945): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,D/MtpService( 1226): updating state; isCurrentUser=true, mMtpLocked=false,
I/OMACP   ( 4955): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 4955): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 4955): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false,
,I/OMACP   ( 4955): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 4955): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false,
,E/MtpService( 4945): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 4945): onStartCommand.
,W/MTPRx   ( 4945): calling native method
E/MTPJNIInterface( 4945): < MTP > Registering BroadCast receiver :::::
E/MtpService( 4945): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 4945): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 4945): noti = 10
,E/MtpService( 4945): onStartCommand.,
W/MTPRx   ( 4945): calling native method
E/MTPRx   ( 4945): Checking the driver time out
E/MTPJNIInterface( 4945): noti = 2,
D/        ( 4945): deleting sockets before message queue initialization,
D/        ( 4945): event handler thread is created, so set the flag
E/MtpService( 4945): handleMessage. msg= { when=-4ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
E/MTPRx   ( 4945): called native method
E/MTPJNIInterface( 4945): setting Media scanner status0
E/MTPJNIInterface( 4945): After setting Media scanner status0
,W/MTPRx   ( 4945): notification from stack 1
,E/        ( 4945): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 4945): Getting media scanner status0
,E/MTPJNIInterface( 4945): DeviceName is Thali Test (Galaxy A3)
,V/MtpMediaDBManager( 4945): inside Thread updateDB
,W/ContextImpl( 3307): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 23462(1424KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/33MB, paused 2.524ms total 144.444ms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4982): MountEmulatedStorage(),
I/libpersona( 4982): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4982): v2
I/libpersona( 4982): KNOX_SDCARD not a persona
,I/SELinux ( 4982): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4982 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
I/SELinux ( 4982): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 4982): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3570): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 3570): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,E/DBG_DM  ( 3570): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,E/MtpMediaDBManager( 4945): count : 26
,I/DBG_DM  ( 3570): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/Process ( 3307): Sending signal. PID: 3307 SIG: 9
,D/TimaKeyStoreProvider( 4982): TimaSignature is unavailable
,W/MtpMediaDBManager( 4945): sending db update complete noti to stack
E/MTPJNIInterface( 4945): noti = 29
D/ActivityThread( 4982): Added TimaKeyStore provider
,E/MTPJNIInterface( 4945): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4945): SDcard is not available
,E/        ( 4945): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface( 4945): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4945): SDcard is not available
E/SQLiteLog( 4945): (21) API call with NULL database connection pointer
E/SQLiteLog( 4945): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4945): (21) API call with NULL database connection pointer
E/SQLiteLog( 4945): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4945): (21) API call with NULL database connection pointer
E/SQLiteLog( 4945): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4945): (21) API call with NULL database connection pointer
E/SQLiteLog( 4945): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 4945): notification from stack 2
,D/        ( 4945): [mtp_init_device] Library open with 32 bits.
D/        ( 4945): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 4945): [mtp_init_device 702]  After open the MTP fd = 33 and line = 702...
,D/        ( 4945): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 4945):  [sua_support_present:1287] returning false 
D/        ( 4945): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
