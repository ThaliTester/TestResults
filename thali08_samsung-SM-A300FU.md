#### Test 613623665d5a4d6_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
I/System.out( 4141): Inside onCreate() of WakeupTriggerProvide
I/System.out( 4141): Inside WakeupProvider
D/SettingsProvider( 1017): name = access_control_enabled
I/NPS_WSSNPS( 4194): [50.150321] AsyncBulkFlagCheck
I/NPS_WSSNPS( 4194): [50.150321] IsRemain_AsyncBulkCheck
--------- beginning of system
W/ContextImpl( 4194): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
I/NPS_WSSNPS( 4194): [50.150321] IsRemain_Asyncing nothing
,I/qtaguid ( 3756): Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3756, getuid(): 10052
I/ContactAccountLoggerTas( 3756): canRun() : Opted Out
E/File    ( 3756): fail readDirectory() errno=2
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.googlequicksearchbox/files/download_cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3756): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.googlequicksearchbox/files/download_cache
I/GCoreUlr( 1807): DispatchingService.onCreate()
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/VlingoApplication( 4141): VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
I/DBG_POLICYDM( 3737): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
E/File    ( 3968): fail readDirectory() errno=2
E/Zygote  ( 4256): MountEmulatedStorage()
E/Zygote  ( 4256): v2
I/libpersona( 4256): KNOX_SDCARD checking this for 10065
I/libpersona( 4256): KNOX_SDCARD not a persona
I/SELinux ( 4256): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4256): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4256): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=4256 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/FactoryTestApp( 3099): [DummyFtClient$onDestroy](3099) Destroy DummyFtClient service
I/Gmail   ( 3968): notifyAccountChanged
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
D/FactoryTestApp( 3099): [Support$Values.getString](3099) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 3099): [ModuleCommon$isConnectionModeNone](3099) mConnectionMode = gsm
I/FactoryTestApp( 3099): [ModuleCommon$isRunningFtClient](3099) RUNNING_FTCLIENT : false
D/FactoryTestApp( 3099): [DummyFtClient$onDestroy](3099) kill process
I/Process ( 3099): Sending signal. PID: 3099 SIG: 9
D/TimaKeyStoreProvider( 4256): TimaSignature is unavailable
D/ActivityThread( 4256): Added TimaKeyStore provider
I/Gmail   ( 3968): getAccountsCursor
D/NPS_WSSNPS( 4194): [50.150321] Service onDestroy
I/NPS_WSSNPS( 4194): [50.150321] smlBRConfigurationDelete
I/NPS_WSSNPS( 4194): [50.150321] smlBRMessageDelete
I/NPS_WSSNPS( 4194): [50.150321] smlBREmailDelete
I/NPS_WSSNPS( 4194): [50.150321] smlBRNetworkDelete
I/DBG_POLICYDM( 3737): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
I/NPS_WSSNPS( 4194): [50.150321] smlBRCallLogDelete
I/NPS_WSSNPS( 4194): [50.150321] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 4194): [50.150321] smlBRPenMemoMDelete
I/NPS_WSSNPS( 4194): [50.150321] smlBRSMemoDelete
I/NPS_WSSNPS( 4194): [50.150321] cpuBooster release : false
D/NPS_WSSNPS( 4194): [50.150321] dsServerSocket close
I/ActivityManager( 1017): Killing 3420:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
I/Gmail   ( 3968): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ActivityManager( 1017): Process com.sec.factory (pid 3099)(adj 0) has died(48,612)
D/FileShare-Server( 4256): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
D/SystemUpdateService( 2113): onCreate
I/Gmail   ( 3968): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/libprocessgroup( 1017): failed to open /acct/uid_10043/pid_3420/cgroup.procs: No such file or directory
I/CheckinService( 2113): Checking schedule, now: 1457344226698 next: 1457732977569
I/CheckinService( 2113): active receiver: disabled
I/DBG_POLICYDM( 3737): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
I/DBG_POLICYDM( 3737): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
I/DBG_POLICYDM( 3737): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
I/DBG_POLICYDM( 3737): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
I/DBG_POLICYDM( 3737): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
I/DBG_POLICYDM( 3737): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
D/SystemUpdateService( 2113): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/VlingoAndroidCore( 4141): AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
V/AuthZen ( 2113): Handling intent: android.intent.action.BOOT_COMPLETED
V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 3968): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 3968): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SystemUpdateService( 2113): cancelUpdate (empty URL)
I/DBG_DM  ( 3674): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
I/Gmail   ( 3968): getAccountsCursor
I/SystemUpdateService( 2113): active receiver: disabled
V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/System.out( 1807): (HTTPLog)-Static: isSBSettingEnabled false
I/GCoreUlr( 1807): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
I/qtaguid ( 1807): Tagging socket 75 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1807, getuid(): 10011
W/ContextImpl( 1305): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
W/ContextImpl( 1305): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
I/ActivityManager( 1017): Killing 3447:com.google.android.configupdater/u0a82 (adj 15): empty #31
I/SettingSearch/SearchIntentReceiver( 1305): InitSerachDBThread thread end!
I/Babel   ( 4187): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 4187): MmsConfig.loadMmsSettings
I/Babel   ( 4187): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel   ( 4187): MmsConfig.loadFromDatabase
I/ActivityManager( 1017): Waited long enough for: ServiceRecord{2c2d918 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
D/VlingoApplication( 4141): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 4141): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SQLiteLog( 2113): (10) POSIX Error : 11 SQLite Error : 3850
D/ChimeraCfgMgr( 2113): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/DialogFlow( 4141): initQueue()
W/libprocessgroup( 1017): failed to open /acct/uid_10082/pid_3447/cgroup.procs: No such file or directory
D/AuthZenEventHandler( 2113): Handling event: android.intent.action.BOOT_COMPLETED
W/Settings( 4187): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BootCompletedReceiver( 2113): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
I/ActivityManager( 1017): Killing 3508:com.dropbox.android/u0a88 (adj 15): empty #31
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Babel   ( 4187): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4187): MmsConfig.loadFromResources
E/Babel   ( 4187): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4187): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
E/Zygote  ( 4297): MountEmulatedStorage()
E/Zygote  ( 4297): v2
I/libpersona( 4297): KNOX_SDCARD checking this for 10030
I/libpersona( 4297): KNOX_SDCARD not a persona
I/SELinux ( 4297): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4297): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4297): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/BootCompletedReceiver( 2113): Got an BootCompleted event.
I/ActivityManager( 1017): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4297 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/TimaKeyStoreProvider( 4297): TimaSignature is unavailable
D/ActivityThread( 4297): Added TimaKeyStore provider
D/AndroidRuntime( 4253): 
D/AndroidRuntime( 4253): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/VideoCapabilities( 4187): Unrecognized profile 2130706433 for video/avc
D/AndroidRuntime( 4253): CheckJNI is OFF
D/AndroidRuntime( 4253): readGMSProperty: start
D/AndroidRuntime( 4253): readGMSProperty: already setted!!
D/AndroidRuntime( 4253): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4253): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4253): readGMSProperty: end
D/AndroidRuntime( 4253): addProductProperty: start
W/AudioCapabilities( 4187): Unsupported mime audio/evrc
D/BootCompletedReceiver( 2113): Will NOT schedule AdAttestation signal task because it's disabled.
W/AudioCapabilities( 4187): Unsupported mime audio/qcelp
W/AudioCapabilities( 4187): Unsupported mime audio/mpeg-L1
W/AudioCapabilities( 4187): Unsupported mime audio/mpeg-L2
W/BaseAppContext( 2113): Using Auth Proxy for data requests.
W/AudioCapabilities( 4187): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4187): Unsupported mime audio/x-ima
W/AudioCapabilities( 4187): Unsupported mime audio/qcelp
W/AudioCapabilities( 4187): Unsupported mime audio/evrc
W/VideoCapabilities( 4187): Unsupported mime video/wvc1
E/BaseAppContext( 2113): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/VideoCapabilities( 4187): Unsupported mime video/x-ms-wmv
V/Babel   ( 4187): babel boot account: SMS
V/Babel   ( 4187): babel boot account: thalitester@gmail.com
W/libprocessgroup( 1017): failed to open /acct/uid_10088/pid_3508/cgroup.procs: No such file or directory
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4328): MountEmulatedStorage()
E/Zygote  ( 4328): v2
I/libpersona( 4328): KNOX_SDCARD checking this for 1000
I/libpersona( 4328): KNOX_SDCARD not a persona
I/SELinux ( 4328): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4328): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4328): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4328 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/VideoCapabilities( 4187): Unrecognized profile/level 32768/2 for video/mp4v-es
I/ActivityManager( 1017): Killing 3475:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
W/VideoCapabilities( 4187): Unsupported mime video/wvc1
W/VideoCapabilities( 4187): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 4187): Unsupported mime video/x-ms-wmv7
W/VideoCapabilities( 4187): Unsupported mime video/x-ms-wmv8
D/TimaKeyStoreProvider( 4328): TimaSignature is unavailable
D/ActivityThread( 4328): Added TimaKeyStore provider
W/VideoCapabilities( 4187): Unsupported mime video/mp43
W/VideoCapabilities( 4187): Unsupported mime video/sorenson
W/VideoCapabilities( 4187): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 4187): Unsupported profile 4 for video/mp4v-es
V/AlarmManager( 1017): waitForAlarm result :4
V/AlarmManager( 1017): waitForAlarm result :4
W/libprocessgroup( 1017): failed to open /acct/uid_10068/pid_3475/cgroup.procs: No such file or directory
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4345 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 4345): MountEmulatedStorage()
I/ActivityManager( 1017): Killing 3567:com.sec.dsm.system/1000 (adj 15): empty #31
E/Zygote  ( 4345): v2
I/libpersona( 4345): KNOX_SDCARD checking this for 1000
I/libpersona( 4345): KNOX_SDCARD not a persona
I/SELinux ( 4345): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4345): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4345): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/art     ( 4141): Suspending all threads took: 6.346ms
I/AuthZen ( 2113): Fetching signing key...
D/TimaKeyStoreProvider( 4345): TimaSignature is unavailable
D/ActivityThread( 4345): Added TimaKeyStore provider
I/art     ( 1651): Explicit concurrent mark sweep GC freed 4615(203KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 4MB/6MB, paused 747us total 25.872ms
W/SQLiteConnectionPool( 1651): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3567/cgroup.procs: No such file or directory
I/AuthZen ( 2113): Signing key fetched successfully!
I/ContactAccountLoggerTas( 3756): canRun() : Opted Out
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 2113): Using Auth Proxy for data requests.
I/GCoreUlr( 1807): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1807): Unbound from all location providers
I/GCoreUlr( 1807): Place inference reporting - stopped
E/KnoxSetupWizardClient( 4345): isShipMode : 1
I/KnoxSetupWizardClient( 4345): onReceive : android.intent.action.BOOT_COMPLETED
I/GCoreUlr( 1807): DispatchingService.onDestroy()
I/GCoreUlr( 1807): Stopping handler for UlrDispSvcFast
E/AffinityControl( 4253): AffinityControl: registerfunction enter
D/a       ( 2113): Opening database auth.proximity.permit_store...
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
I/GCoreUlr( 1807): Unbound from all location providers
I/GCoreUlr( 1807): Place inference reporting - stopped
D/AuthZenTransactionCache( 2113): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2113): Clearing transaction cache
D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4312, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
D/AndroidRuntime( 4253): Calling main entry com.android.commands.am.Am
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
W/ResourcesManager( 4297): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4297): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4297): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
D/PowerUI ( 1171): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1171): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
V/EmergencyMode( 1444): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1444): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
V/HeadsetService( 3122): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3122): Disconnected process message: 10
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/System.err( 4345): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 4345): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4345): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4345): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 4345): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 4345): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4345): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
D/ShortcutReceiver( 4345):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
W/ResourcesManager( 4297): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4297): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4297): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1017): mDVFSHelper.acquire()
D/FocusedStackFrame( 1017): Set to : 0
D/Launcher.HomeView( 1507): onPause
D/Launcher( 1507): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
W/ResourcesManager( 4297): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 4297): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 1507
D/KnoxShortcutUtil( 4345): getIsShortcutMigrationFor_2_3_0_Done true
D/AndroidRuntime( 4253): Shutting down VM
D/ShortcutReceiver( 4345):  KnoxContainerVersion 2.3.0
D/ShortcutReceiver( 4345):  shortcut migration not required 
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : -2122120936
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
I/ActivityManager( 1017): Killing 3606:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
E/Zygote  ( 4372): MountEmulatedStorage()
E/Zygote  ( 4372): v2
I/libpersona( 4372): KNOX_SDCARD checking this for 1000
I/libpersona( 4372): KNOX_SDCARD not a persona
I/SELinux ( 4372): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4372): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4372 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 4372): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, uhalitest
I/ActivityManager( 1017): Killing 3621:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
W/ContextImpl( 1017): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
I/ActivityManager( 1017): Killing 3657:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
D/TimaKeyStoreProvider( 4372): TimaSignature is unavailable
D/ActivityThread( 4372): Added TimaKeyStore provider
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 3674): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
E/Zygote  ( 4387): MountEmulatedStorage()
E/Zygote  ( 4387): v2
I/libpersona( 4387): KNOX_SDCARD checking this for 10167
I/libpersona( 4387): KNOX_SDCARD not a persona
I/SELinux ( 4387): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4387): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4387): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4387 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 4387): TimaSignature is unavailable
E/Zygote  ( 4403): MountEmulatedStorage()
I/libpersona( 4403): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4403): v2
I/libpersona( 4403): KNOX_SDCARD not a persona
D/ActivityThread( 4387): Added TimaKeyStore provider
I/SELinux ( 4403): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4403): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3606/cgroup.procs: No such file or directory
V/ActivityThread( 1507): updateVisibility : ActivityRecord{1414a186 token=android.os.BinderProxy@164c4ebc {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
E/SELinux ( 4403): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=4403 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1507): onStop
V/ActivityThread( 1507): updateVisibility : ActivityRecord{1414a186 token=android.os.BinderProxy@164c4ebc {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/TimaKeyStoreProvider( 4403): TimaSignature is unavailable
D/ActivityThread( 4403): Added TimaKeyStore provider
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1017): isKioskContainerExistOnDevice
W/libprocessgroup( 1017): failed to open /acct/uid_10146/pid_3657/cgroup.procs: No such file or directory
W/art     ( 4253): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/libprocessgroup( 1017): failed to open /acct/uid_10088/pid_3621/cgroup.procs: No such file or directory
,D/StatusChecker( 4372): onReceive : android.intent.action.BOOT_COMPLETED
,I/Icing   ( 2113): updateResources: need to parse f{com.google.android.gms}
,D/Launcher( 1507): onTrimMemory. Level: 20
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1017): [SO] activate (ident=0xb8da9758, enabled=0)
,I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,E/SMD     (  289): DCD OFF
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1017): [SO] changed settle time [1]
D/SensorService( 1017): [SO] setDelay [66000000]
D/SensorService( 1017): [SO] activate (ident=0xb8da9758, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/SystemUpdateService( 2113): onDestroy
,I/StatusChecker( 4372): onReceive : net.mt.init : DONE
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4423): MountEmulatedStorage()
E/Zygote  ( 4423): v2
I/libpersona( 4423): KNOX_SDCARD checking this for 10113
I/libpersona( 4423): KNOX_SDCARD not a persona
,I/SELinux ( 4423): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4423): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1017): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4423 uid=10113 gids={50113, 9997} abi=armeabi-v7a
,E/SELinux ( 4423): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     (  304): Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 33.961ms
,D/TimaKeyStoreProvider( 4423): TimaSignature is unavailable
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 16.899ms
,D/ActivityThread( 4423): Added TimaKeyStore provider
,W/ContextImpl( 4403): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 16.639ms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SensorService( 1017): [SO] currT = 46381184000, prevT = 46041076000, diff = 340108000, [-0.421 0.153 9.883]
D/SensorService( 1017): [SO] -0.421 0.153 9.883
D/SensorService( 1017): [SO] [100 -> 255]
,E/Zygote  ( 4441): MountEmulatedStorage(),
E/Zygote  ( 4441): v2
I/libpersona( 4441): KNOX_SDCARD checking this for 1000
I/libpersona( 4441): KNOX_SDCARD not a persona
,I/SELinux ( 4441): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4441): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/WebViewFactory( 4387): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,E/SELinux ( 4441): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4441 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/System.out( 4141): INFO:Resource not found:/Common.properties Using default values
,D/PCWCLIENTTRACE_AccountAppFacade2_0( 3830): unregister AuthInfo UpdateReceiver v2.0
,D/TimaKeyStoreProvider( 4441): TimaSignature is unavailable
D/ActivityThread( 4441): Added TimaKeyStore provider
,I/LibraryLoader( 4387): Loading: webviewchromium
,I/LibraryLoader( 4387): Time to load native libraries: 5 ms (timestamps 6434-6439)
I/LibraryLoader( 4387): Expected native library version number "",actual native library version number ""
,I/PageBuddyNotiSvc( 4423): Intent received : action=android.intent.action.BOOT_COMPLETED
,W/ResourcesManager( 4441): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,V/WebViewChromiumFactoryProvider( 4387): Binding Chromium to main looper Looper (main, tid 1) {121717d9}
,W/ContextImpl( 4423): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,I/LibraryLoader( 4387): Expected native library version number "",actual native library version number ""
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
I/chromium( 4387): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
W/ContextImpl( 4441): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
I/PageBuddyNotiSvc( 4423): onCreate mCpBitFlag=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/BrowserStartupController( 4387): Initializing chromium process, renderers=0
I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4469 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/Zygote  ( 4469): MountEmulatedStorage()
E/Zygote  ( 4469): v2
I/libpersona( 4469): KNOX_SDCARD checking this for 10121
I/libpersona( 4469): KNOX_SDCARD not a persona
,W/art     ( 4387): Attempt to remove local handle scope entry from IRT, ignoring
I/SELinux ( 4469): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4469): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4469): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,W/GCoreFlp( 1807): No location to return for getLastLocation()
,D/TimaKeyStoreProvider( 4469): TimaSignature is unavailable
,W/FusedLocationProvider( 1807): location=null
D/ActivityThread( 4469): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/F_PHONE ( 4441): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,I/ActivityManager( 1017): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=4490 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 4490): MountEmulatedStorage(),
W/chromium( 4387): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,E/Zygote  ( 4490): v2,
I/chromium( 4387): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/libpersona( 4490): KNOX_SDCARD checking this for 1000,
I/ActivityManager( 1017): Killing 3693:com.sec.android.diagmonagent/1000 (adj 15): empty #31,
I/SELinux ( 4490): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4490): KNOX_SDCARD not a persona
,I/SELinux ( 4490): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4490): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/8)
,I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/8)
I/chromium( 4387): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/ContextImpl( 4441): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,D/TimaKeyStoreProvider( 4490): TimaSignature is unavailable
D/ActivityThread( 4490): Added TimaKeyStore provider
,I/Adreno-EGL( 4387): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4387): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4387): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4387): Local Branch: 
I/Adreno-EGL( 4387): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4387): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4387):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/ResourcesManager( 4469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3693/cgroup.procs: No such file or directory
,W/GCoreFlp( 1807): No location to return for getLastLocation()
,W/FusedLocationProvider( 1807): location=null
,W/ResourcesManager( 4490): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/Process ( 4297): Sending signal. PID: 4297 SIG: 9
,D/BluetoothBDAdrressReceiver( 4490): onReceive(), action: android.intent.action.BOOT_COMPLETED,
W/ContextImpl( 4490): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,W/Auth    ( 1807): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 1483): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothBDTestService( 1483): onCreate()
E/BluetoothBDTestService( 1483): onStart(), extra_type: BOOT_COMPLETED
E/Zygote  ( 4521): MountEmulatedStorage()
E/Zygote  ( 4521): v2
I/libpersona( 4521): KNOX_SDCARD checking this for 1000
E/BluetoothBDTestService( 1483): bd_address_path: /efs/bluetooth/bt_addr
I/libpersona( 4521): KNOX_SDCARD not a persona
,E/BluetoothBDTestService( 1483): already exist!( /efs/bluetooth/bt_addr ), file length: 17
I/SELinux ( 4521): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4521): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=4521 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 4521): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/F_PHONE ( 4441): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 4441): default registerAction()
I/F_PHONE ( 4441): [[com.sec.bcservice]] sendPendingMessage()
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4521): TimaSignature is unavailable
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityThread( 4521): Added TimaKeyStore provider
,D/QuickConnect( 4469): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1017): name = scon_is_running
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10121
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/QuickConnect( 4469): Utils.setQCRunningSetting - set : 0
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{33406152 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,W/ResourcesManager( 4521): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 53181(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 22MB/34MB, paused 2.647ms total 235.526ms
,I/QuickConnect( 4469): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/SecKeyguardClockSingleView( 1171): Ignore. Because it is same clock text
I/QuickConnect( 4469): PeriphStartReceiver.onReceive - no need to start
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4537): MountEmulatedStorage()
,E/Zygote  ( 4537): v2
I/libpersona( 4537): KNOX_SDCARD checking this for 10127
I/libpersona( 4537): KNOX_SDCARD not a persona
,I/SELinux ( 4537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4537 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
E/SELinux ( 4537): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Process com.sec.android.app.sns3 (pid 4297)(adj 0) has died(32,638)
,D/TimaKeyStoreProvider( 4537): TimaSignature is unavailable
,D/ActivityThread( 4537): Added TimaKeyStore provider,
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/chromium( 4387): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,E/Zygote  ( 4553): MountEmulatedStorage(),
E/Zygote  ( 4553): v2
I/libpersona( 4553): KNOX_SDCARD checking this for 10031,
I/libpersona( 4553): KNOX_SDCARD not a persona
,I/SELinux ( 4553): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1017): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4553 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4403): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4403): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 4403): Resource data:2131165186
,I/SELinux ( 4553): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ResourcesManager( 4403): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/SELinux ( 4553): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 4403): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 4403): getResourceTypeNamexml
,W/chromium( 4387): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1171): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/AMMetaDataParserService( 4403): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,D/TimaKeyStoreProvider( 4553): TimaSignature is unavailable
,D/ActivityThread( 4553): Added TimaKeyStore provider
,W/ResourcesManager( 4537): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4537): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4537): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4537): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/art     ( 4387): Attempt to remove local handle scope entry from IRT, ignoring
,I/AMMetaDataParserService( 4403): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,D/PersistentNotificationBroadcastReceiver( 1807): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/KnoxUsageLogPro( 4521): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,I/KnoxUsageLogPro( 4521): savePreference: key = previous_sys_time value = 1457344228813
,W/AwContents( 4387): onDetachedFromWindow called when already detached. Ignoring
,I/KnoxUsageLogPro( 4521): premStatus:2
,I/KnoxUsageLogPro( 4521): isEulaShown : false
,I/KnoxUsageLogPro( 4521): KnoxUsageReceiver onReceive : not Processible, just return
,I/ActivityManager( 1017): Killing 3057:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,D/PhoneWindow( 4387): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 4387): *FMB* installDecor flags : -2139027200
,D/SystemWebViewEngine( 4387): CordovaWebView is running on device made by: samsung
,I/DBG_DM  ( 3674): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,W/art     ( 4387): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4387): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4403): Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,I/ActivityManager( 1017): Killing 3737:com.policydm/1000 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_10090/pid_3057/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCr,eateAccountActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4579): MountEmulatedStorage()
,E/Zygote  ( 4579): v2
,I/libpersona( 4579): KNOX_SDCARD checking this for 10026
I/libpersona( 4579): KNOX_SDCARD not a persona
,I/SELinux ( 4579): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4579 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4579): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4579): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4579): TimaSignature is unavailable
D/ActivityThread( 4579): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3737/cgroup.procs: No such file or directory
,W/ContextImpl( 4403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/OpenGLRenderer( 4387): Render dirty regions requested: true
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4595): MountEmulatedStorage(),
E/Zygote  ( 4595): v2
I/libpersona( 4595): KNOX_SDCARD checking this for 1000,
I/libpersona( 4595): KNOX_SDCARD not a persona
,I/SELinux ( 4595): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4595): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4595 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3792:com.fmm.dm/1000 (adj 15): empty #31
D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
E/SELinux ( 4595): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,D/PhoneWindow( 4387): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 4387): *FMB* isFloatingMenuEnabled return false
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:assistant
I/AMMetaDataParserService( 4403): Resource data:2131034113
,W/ResourcesManager( 4403): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 4403): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, NainActivit
W/ResourcesManager( 4403): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/SBrowserFeatureFlag( 4537): initialized in static block : loadCscFeatureValue() succeed! 
,D/TimaKeyStoreProvider( 4595): TimaSignature is unavailable
,D/ActivityThread( 4595): Added TimaKeyStore provider
,D/InputDispatcher( 1017): Focus entered window: 4387
,D/SRIB_DCS( 4387): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 4387): Initialized EGL, version 1.4
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/OpenGLRenderer( 4387): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 4387): Enabling debug mode 0
,I/DBG_POLICYDM( 4595): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 4595): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/AMMetaDataParserService( 4403): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 4403): getResourceTypeNamexml
,I/DBG_POLICYDM( 4595): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1171): Icon Only
E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/PanelView( 1171): There is/are notification(s) 
,I/GFX construct_block_size_descriptor_2d second part( 4403): took 3.433906ms for 0*0 texture 0
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3792/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 4595): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/Timeline( 4387): Timeline: Activity_idle id: android.os.BinderProxy@c52747c time:47498
,I/DBG_POLICYDM( 4595): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 4595): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 4595): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 4595): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/ActivityManager( 1017): Displayed Component not be shown by security: +1s462ms
I/DBG_POLICYDM( 4595): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,I/DBG_POLICYDM( 4595): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,I/GFX generate_partition_tables( 4403): took 7.363178ms for 0*0 texture 0
,I/DBG_POLICYDM( 4595): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,W/ActivityManager( 1017): mDVFSHelper.release()
I/GFX raster( 4403): took 12.452448ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb859b838 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb892fea8 counterpartCT=4 counterpartW=96 counterparth=96
D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/DBG_POLICYDM( 4595): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{216b2286 u0 com.test.thalitest/.MainActivity t11} time:47509
,I/DBG_POLICYDM( 4595): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 4595): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 4595): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 4595): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 4403): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,I/DBG_POLICYDM( 4595): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,I/DBG_POLICYDM( 4595): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4403): took 0.840469ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb859b838 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb89507e8 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4621): MountEmulatedStorage()
E/Zygote  ( 4621): v2
I/libpersona( 4621): KNOX_SDCARD checking this for 10032
I/libpersona( 4621): KNOX_SDCARD not a persona
,I/SELinux ( 4621): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4621): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4621): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
I/AMMetaDataParserService( 4403): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533,
,I/SamsungIME( 1838): getCurrentCandidateView
,I/ActivityManager( 1017): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4621 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ManifestProvider( 4537): onCreate()
D/TimaKeyStoreProvider( 4621): TimaSignature is unavailable
D/ActivityThread( 4621): Added TimaKeyStore provider
,E/NetworkSettingsReceiver( 4537): onReceive: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SurfaceFlinger(  258): id=11 Removed uhalitest (7/8)
,I/SurfaceFlinger(  258): id=11 Removed uhalitest (-2/8)
,I/KnoxUsageLogPro( 4521): savePreference: key = previous_elapsed_time value = 47004
,I/DBG_POLICYDM( 4595): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 4595): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4595): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 4595): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 4595): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,I/DBG_POLICYDM( 4595): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,I/DBG_POLICYDM( 4595): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,D/SSRM:n  ( 1017): SIOP:: AP = 410
,I/DBG_POLICYDM( 4595): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,D/Finsky  ( 4579): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/DBG_POLICYDM( 4595): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 4595): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 4595): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 4595): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4595): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/13/12:50:23
,I/DBG_POLICYDM( 4595): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/07/10:50:29
,I/DBG_POLICYDM( 4595): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 4595): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 4595): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,W/System.err( 4537): java.lang.NoSuchMethodException: isEnabled []
,I/DBG_POLICYDM( 4595): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,W/System.err( 4537): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 4537): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
W/System.err( 4537): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
W/System.err( 4537): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
W/System.err( 4537): 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
W/System.err( 4537): 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
W/System.err( 4537): 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
W/System.err( 4537): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 4537): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 4537): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 4537): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4537): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 4537): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 4537): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4537): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4537): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 4537): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SBrowserFeatureFlag( 4537): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@e594daa
,D/SBrowserFeatureFlag( 4537): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 4537): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,I/DBG_POLICYDM( 4595): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 4595): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 4595): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 4595): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 4595): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 4595): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,D/SamsungIME( 1838): Dismiss ExpandCandiate
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4655): MountEmulatedStorage()
E/Zygote  ( 4655): v2
I/libpersona( 4655): KNOX_SDCARD checking this for 10131
I/libpersona( 4655): KNOX_SDCARD not a persona
I/SELinux ( 4655): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4655 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
,E/SPPClientService( 4621): ============PushLog. commonIsShipBuild. stop!
I/ActivityManager( 1017): Killing 3861:com.sec.factory.camera/1000 (adj 15): empty #31
E/SPPClientService( 4621): [PushClientApplication] Push log off : This is Ship build version
E/SPPClientService( 4621): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,I/SELinux ( 4655): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4655): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 4595): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,D/TimaKeyStoreProvider( 4655): TimaSignature is unavailable
,D/ActivityThread( 4655): Added TimaKeyStore provider
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ResourcesManager( 4655): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4655): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/SamsungIME( 1838): getDebugLevel  : 0x4f4c
,D/JsMessageQueue( 4387): Set native->JS mode to OnlineEventsBridgeMode
,D/SPPClientService( 4621): PushLog.txt file is not deleted.
,D/SPPClientService( 4621): PushLog.txt file is not deleted.
D/SPPClientService( 4621): ============PushLog. stop!
,I/DBG_POLICYDM( 4595): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3861/cgroup.procs: No such file or directory
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 4675): MountEmulatedStorage(),
I/libpersona( 4675): KNOX_SDCARD checking this for 10036
E/Zygote  ( 4675): v2
I/libpersona( 4675): KNOX_SDCARD not a persona
,I/SELinux ( 4675): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4675 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3893:com.fmm.ds/1000 (adj 15): empty #31
,I/SELinux ( 4675): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4675): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3674): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/art     (  304): Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 680us total 25.240ms
,D/TimaKeyStoreProvider( 4675): TimaSignature is unavailable
D/ActivityThread( 4675): Added TimaKeyStore provider
D/jxcore_app_log( 4387): JniHelper::setJavaVM(0xb8594448), pthread_self() = -1195342824,
,I/SamsungIME( 1838): getDebugLevel  : 0x4f4c
I/DBG_POLICYDM( 4595): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 21.950ms
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4387): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4387):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4387):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4387):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4387):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4387): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1348757b added. We now have 1 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4387): setBluetoothMacAddress: 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4387): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4387): setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 806us total 18.533ms
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4387): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4387):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4387):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4387):     - Bluetooth MAC address: 08:EC:A9:50:76:27
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4387):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4387):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4387):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4387):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4387):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4387):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4387): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b5eee57 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4387): addListener: New listener added - the number of listeners is now 1
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3893/cgroup.procs: No such file or directory
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4387): setDiscoveryMode: Discovery mode BLE is supported
,I/GFX construct_block_size_descriptor_2d second part( 4403): took 3.053439ms for 0*0 texture 0
,I/SamsungIME( 1838): KeybaordView init() : load resources
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/GFX generate_partition_tables( 4403): took 7.894843ms for 0*0 texture 0
,I/GFX raster( 4403): took 12.171406ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb892fea8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8933f70 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/Finsky  ( 4579): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/SamsungIME( 1838): getCurrentKeyboard
I/SamsungIME( 1838): getTextKeyboard
,E/Zygote  ( 4709): MountEmulatedStorage()
,E/Zygote  ( 4709): v2
I/libpersona( 4709): KNOX_SDCARD checking this for 10037
I/libpersona( 4709): KNOX_SDCARD not a persona
I/AMMetaDataParserService( 4403): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/SELinux ( 4709): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4709): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1017): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4709 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/SELinux ( 4709): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4724): MountEmulatedStorage(),
E/Zygote  ( 4724): v2
I/libpersona( 4724): KNOX_SDCARD checking this for 10135
I/libpersona( 4724): KNOX_SDCARD not a persona
,I/SELinux ( 4724): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4724 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/SELinux ( 4724): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4724): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4709): TimaSignature is unavailable
,D/ActivityThread( 4709): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 4724): TimaSignature is unavailable
,D/ActivityThread( 4724): Added TimaKeyStore provider
,I/DBG_POLICYDM( 4595): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,I/DBG_POLICYDM( 4595): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,W/ResourcesManager( 4709): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 4724): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 4724): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4724): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 4724): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4724): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 4595): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,D/SamsungIME( 1838): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/CalendarProvider2( 4709): CalendarProvider2.onCreate() called
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 3968): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1017): Killing 3912:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4403): took 0.606823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb89512c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8951628 counterpartCT=4 counterpartW=96 counterparth=96
,W/Settings( 4579): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SA      ( 4675): [SSP] onCreated
,I/DBG_POLICYDM( 4595): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/AMMetaDataParserService( 4403): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/Settings( 4579): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4403): took 0.813802ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb8969da8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89507e8 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 4403): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
E/Zygote  ( 4746): MountEmulatedStorage()
E/Zygote  ( 4746): v2
I/libpersona( 4746): KNOX_SDCARD checking this for 10141
I/libpersona( 4746): KNOX_SDCARD not a persona
I/SELinux ( 4746): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4746): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4746): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4746 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1017): failed to open /acct/uid_10095/pid_3912/cgroup.procs: No such file or directory
,I/GAV2    ( 3756): Thread[GAThread,5,main]: No campaign data found.
,D/TimaKeyStoreProvider( 4746): TimaSignature is unavailable
,D/ActivityThread( 4746): Added TimaKeyStore provider
,I/DBG_POLICYDM( 4595): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,V/AlarmManager( 1017): waitForAlarm result :8
,W/ResourcesManager( 4746): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4746): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4746): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4746): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/Volley  ( 4579): [706] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 4579): [713] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager( 1017): Killing 2940:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 3946:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #32
,D/Ads     ( 4579): Skipping gmscore version check
,I/SA      ( 4675): [TPM] There is no property file
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
I/SA      ( 4675): [SCU] isHaveSA() - false
,I/SA      ( 4675): [TPM] getModelProperty : null
,I/SA      ( 4675): [TPM] getCSCProperty : null
,I/SA      ( 4675): [DM] FLOATING AMOLED FEATURE: true
,I/SA      ( 4675): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4675): [DM] TFT FEATURE: false
,I/SA      ( 4675): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4675): [DM] init START
,D/Finsky  ( 4579): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
D/Finsky  ( 4579): [1] Libraries$2.run: Finished loading 1 libraries.
,W/libprocessgroup( 1017): failed to open /acct/uid_10008/pid_2940/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10098/pid_3946/cgroup.procs: No such file or directory
,I/SA      ( 4675): [DM] This device is not a Vodafone
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/chromium( 4387): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 4387): 
,D/SensorService( 1017): [SO] -0.402 0.172 9.883
,D/Finsky  ( 4579): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/chromium( 4387): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/ResourceType( 4675): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4675): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 4675): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4675): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 4675): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 4675): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 4675): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4675): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4675): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 4675): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4675): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4675): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4675): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4675): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 4675): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4675): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 4675): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 4675): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
,W/ResourceType( 4675): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4675): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4675): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 4675): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 4675): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 4675): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4675): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 4675): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4403): took 0.916615ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb8933f70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8951628 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4403): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/SA      ( 4675): [SCU] isHaveSA() - false
I/SA      ( 4675): support phone number id : false
I/SA      ( 4675): [DM] Supports Ref Jpn : true
,I/SA      ( 4675): [DM] init END
,I/SA      ( 4675): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 4675): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,D/Finsky  ( 4579): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4403): took 0.826667ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb89507e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8951628 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4403): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4675): [OR] onReceive END
,E/Watchdog( 1017): !@Sync 1
,D/SettingsProvider( 1017): name = audio_safe_volume_state
,I/SA      ( 4675): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4675): [ODM] queryOpenData(key= GEO_IP )
,I/SA      ( 4675): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4675): [LBE] REF_JPN : true
I/SA      ( 4675): [BDC] create
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4403): took 0.757656ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb8951628 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8948570 counterpartCT=4 counterpartW=96 counterparth=96
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 4403): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/SA      ( 4675): [DBMV2] getEmailID
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:assistant
I/AMMetaDataParserService( 4403): Resource data:2131034113
,I/AMMetaDataParserService( 4403): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 4403): getResourceTypeNamexml
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4403): took 0.808281ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb859b838 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8948570 counterpartCT=4 counterpartW=96 counterparth=96
I/SA      ( 4675): [DBMV2] getDataV02ForItems
I/SA      ( 4675): [SSP] query invoked
,I/SA      ( 4675): [SCU] get signed id from samsung account2.0 DB.
,I/AMMetaDataParserService( 4403): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,I/SA      ( 4675): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4675): [BDC] destroy
,I/ActivityManager( 1017): Killing 3985:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,I/DBG_DM  ( 3674): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4403): took 0.801771ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb859b838 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8948570 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4403): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4403): took 0.620157ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb892fea8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8948570 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4403): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4783): MountEmulatedStorage()
,E/Zygote  ( 4783): v2
I/libpersona( 4783): KNOX_SDCARD checking this for 10068
I/libpersona( 4783): KNOX_SDCARD not a persona
I/SELinux ( 4783): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4783 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
I/SELinux ( 4783): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4783): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4783): TimaSignature is unavailable
,D/ActivityThread( 4783): Added TimaKeyStore provider
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4403): took 0.608958ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb89512c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8948570 counterpartCT=4 counterpartW=96 counterparth=96
,I/Icing   ( 2113): Internal init done: storage state 0
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 4403): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/SMD     (  289): DCD OFF
W/libprocessgroup( 1017): failed to open /acct/uid_10055/pid_3985/cgroup.procs: No such file or directory
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4403): took 0.820937ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb8969da8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8948570 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,D/BadgeProvider( 4783): onCreate
,D/BadgeProvider( 4783): DatabaseHelper
,I/AMMetaDataParserService( 4403): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4403): took 0.642084ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb8933f70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8948570 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4403): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/BadgeProvider( 4783): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4403): took 0.689323ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb89507e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8948570 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4403): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,V/AlarmManager( 1017): waitForAlarm result :4
,V/AlarmManager( 1017): waitForAlarm result :4
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4403): took 0.523854ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb8951628 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8948570 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4403): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 4403): getResourcePackageName:com.samsung.android.multiuser.install_only_owner,
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity,
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity,
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 4403): Resource data:Loop for running activityalias.DialShortcut,
I/AMMetaDataParserService( 4403): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/libpersona( 4810): KNOX_SDCARD checking this for 10142
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/libpersona( 4810): KNOX_SDCARD not a persona
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4403): getResourcePackageName:assistant
I/AMMetaDataParserService( 4403): Resource data:2131034112
I/AMMetaDataParserService( 4403): getResourceName:com.android.contacts:xml/assistant_detail
,I/AMMetaDataParserService( 4403): getResourceTypeNamexml
E/Zygote  ( 4810): MountEmulatedStorage()
E/Zygote  ( 4810): v2
I/SELinux ( 4810): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4810): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4810): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4810 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Icing   ( 2113): Post-init done,
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4403): took 0.592604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb89512c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8948570 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1017): Killing 4000:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,I/AMMetaDataParserService( 4403): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BadgeProvider( 4783): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 4783): sendNotify, [notify] : null
D/BadgeProvider( 4783): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 4783): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4783): update, [UpdateCount] : 1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4810): TimaSignature is unavailable
,D/ActivityThread( 4810): Added TimaKeyStore provider
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4403): took 0.627605ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb89512c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8948570 counterpartCT=4 counterpartW=96 counterparth=96
,D/Launcher.Model( 1507): reloadBadges entered.
,I/AMMetaDataParserService( 4403): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4403): took 0.641615ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb8969e10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8948570 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4403): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4403): took 0.758385ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb8933f70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89506e0 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1017): failed to open /acct/uid_10013/pid_4000/cgroup.procs: No such file or directory
,W/jxcore-log( 4387): Initializing JXcore engine
W/jxcore-log( 4387): JXcore engine is ready
,W/ResourcesManager( 4810): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4403): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 29474(1636KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 22MB/33MB, paused 3.541ms total 249.838ms
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activit,ycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:assistant
I/AMMetaDataParserService( 4403): Resource data:2131034113
I/AMMetaDataParserService( 4403): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 4403): getResourceTypeNamexml
E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 4403): took 0.884948ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb89506e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8969da8 counterpartCT=4 counterpartW=96 counterparth=96
E/audit   ( 1950): type=1400 msg=audit(1457344231.573:205): avc:  denied  { ioctl } for  pid=4703 comm="Thread-677" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1950):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1950): type=1300 msg=audit(1457344231.573:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9dbfb8f8 items=0 ppid=304 ppcomm=main pid=4703 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-677" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1950): type=1320 msg=audit(1457344231.573:205): 
W/ActivityManager( 1017): getTasks: caller 10141 does not hold GET_TASKS; limiting output
I/AMMetaDataParserService( 4403): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/ActivityManager( 1017): Killing 4022:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/iu.UploadsManager( 2113): End new media; added: 0, uploading: 0, time: 455 ms
,I/GFX raster( 4403): took 0.827031ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb89506e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8911238 counterpartCT=4 counterpartW=96 counterparth=96
,W/jxcore-log( 4387): Starting JXcore engine
,E/Zygote  ( 4831): MountEmulatedStorage(),
E/Zygote  ( 4831): v2
I/libpersona( 4831): KNOX_SDCARD checking this for 1000
I/SELinux ( 4831): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4831): KNOX_SDCARD not a persona
,I/SELinux ( 4831): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 4831): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4831 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/AMMetaDataParserService( 4403): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/ActivityManager( 1017): Killing 4055:com.android.managedprovisioning/u0a20 (adj 15): empty #31
,I/Process ( 4746): Sending signal. PID: 4746 SIG: 9
,E/lowmemorykiller(  255): Error writing /proc/4746/oom_score_adj; errno=22
,I/ActivityManager( 1017): Killing 3820:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4831): TimaSignature is unavailable
,D/ActivityThread( 4831): Added TimaKeyStore provider
,I/ActivityThread( 4810): Removing dead content provider:android.content.ContentProviderProxy@c494220
I/ActivityThread( 4810): Removing dead content provider:android.content.ContentProviderProxy@c494220
,I/ActivityManager( 1017): Process com.android.email (pid 4746)(adj 9) has died(44,588)
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1017): failed to open /acct/uid_10056/pid_4022/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10020/pid_4055/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10014/pid_3820/cgroup.procs: No such file or directory
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 4403): took 0.603021ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb894f928 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89507e8 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4847): MountEmulatedStorage()
E/Zygote  ( 4847): v2
I/libpersona( 4847): KNOX_SDCARD checking this for 10141
I/libpersona( 4847): KNOX_SDCARD not a persona
,I/SELinux ( 4847): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4847): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4847): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4847 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/AMMetaDataParserService( 4403): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4403): took 0.594062ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb892fea8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb859b838 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4847): TimaSignature is unavailable
,D/ActivityThread( 4847): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 4403): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/jxcore-log( 4387): Platform android
W/jxcore-log( 4387): 
,W/jxcore-log( 4387): Process ARCH arm
W/jxcore-log( 4387): 
,W/ResourcesManager( 4847): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4847): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4847): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4847): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 4403): took 0.885937ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb8911238 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89512c0 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4863): MountEmulatedStorage()
,E/Zygote  ( 4863): v2
I/libpersona( 4863): KNOX_SDCARD checking this for 1000
I/libpersona( 4863): KNOX_SDCARD not a persona,
,I/SELinux ( 4863): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4863 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 4081:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 4403): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532,
I/SELinux ( 4863): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4863): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/DBG_DM  ( 3674): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,D/TimaKeyStoreProvider( 4863): TimaSignature is unavailable
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityThread( 4863): Added TimaKeyStore provider
,I/GFX raster( 4403): took 0.648125ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb8933f70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb86ad760 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4403): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/GFX raster( 4403): took 0.679636ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb89507e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8951628 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4403): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4081/cgroup.procs: No such file or directory
,D/SecurityLogAgent( 4863): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4863): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 4863): StateMachine : Current State = 1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecurityLogAgent( 4863): BootReceiver : completed task. Failed to return wakelock . 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4884): MountEmulatedStorage()
E/Zygote  ( 4884): v2
I/libpersona( 4884): KNOX_SDCARD checking this for 10148
I/libpersona( 4884): KNOX_SDCARD not a persona
I/SELinux ( 4884): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4403): took 0.570521ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb859b838 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89512c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 4884): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4884 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
I/AMMetaDataParserService( 4403): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
I/ActivityManager( 1017): Killing 1406:com.android.defcontainer/u0a3 (adj 15): empty #31
E/SELinux ( 4884): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,W/ContextImpl( 4403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 4884): TimaSignature is unavailable
,D/ActivityThread( 4884): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:assistant
I/AMMetaDataParserService( 4403,): Resource data:2131165203
W/ResourcesManager( 4403): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 4403): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 4403): getResourceTypeNamexml
E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
I/GFX construct_block_size_descriptor_2d second part( 4403): took 3.468750ms for 0*0 texture 0
I/GFX generate_partition_tables( 4403): took 17.140209ms for 0*0 texture 0
I/GFX raster( 4403): took 21.206823ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb8b114a0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb8b11b08 counterpartCT=4 counterpartW=80 counterparth=80
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 4884): (284) automatic index on shooting_modes(title_id)
,I/AMMetaDataParserService( 4403): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,I/CalendarProvider2( 4709): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,E/Zygote  ( 4905): MountEmulatedStorage()
,E/Zygote  ( 4905): v2
I/libpersona( 4905): KNOX_SDCARD checking this for 1000
I/libpersona( 4905): KNOX_SDCARD not a persona,
,I/SELinux ( 4905): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/GFX construct_block_size_descriptor_2d second part( 4403): took 2.349427ms for 0*0 texture 0
,I/SELinux ( 4905): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4905 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/GFX generate_partition_tables( 4403): took 5.119375ms for 0*0 texture 0
,I/GFX raster( 4403): took 8.523593ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb8cbdf50 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8cbdff8 counterpartCT=4 counterpartW=80 counterparth=80
,W/libprocessgroup( 1017): failed to open /acct/uid_10003/pid_1406/cgroup.procs: No such file or directory
,E/SELinux ( 4905): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1017): Killing 3830:com.sec.pcw.device/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4905): TimaSignature is unavailable
,W/ActivityManager( 1017): getTasks: caller 10142 does not hold GET_TASKS; limiting output
,D/ActivityThread( 4905): Added TimaKeyStore provider
,I/AMMetaDataParserService( 4403): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,I/Process ( 4810): Sending signal. PID: 4810 SIG: 9
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/BadgeProvider( 4783): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,E/lowmemorykiller(  255): Error writing /proc/4810/oom_score_adj; errno=22
,I/GFX raster( 4403): took 0.753698ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb8cbdf50 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8e6bae8 counterpartCT=4 counterpartW=80 counterparth=80
,I/ActivityManager( 1017): Killing 4119:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,D/Launcher.Model( 1507): reloadBadges entered.
,D/BadgeProvider( 4783): sendNotify entered. [uri] : content://com.sec.badge/apps/1
I/AMMetaDataParserService( 4403): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,D/BadgeProvider( 4783): sendNotify, [notify] : null
D/BadgeProvider( 4783): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4783): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 4783): update, [UpdateCount] : 1
,I/splitIntent( 1017): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.sec.android.daemonapp
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 4403): took 0.705053ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb8cbdf50 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb894e808 counterpartCT=4 counterpartW=80 counterparth=80
,I/ActivityManager( 1017): Killing 3968:com.google.android.gm/u0a99 (adj 15): empty #31
,I/AMMetaDataParserService( 4403): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,W/SQLiteConnectionPool( 2113): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ActivityManager( 1017): Process com.android.exchange (pid 4810)(adj 13) has died(27,588)
,D/daemonapp( 1961): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1961): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 4403): took 0.681042ms for 80*80 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb8950f20 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8e6b978 counterpartCT=4 counterpartW=80 counterparth=80
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 4403): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 1961): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1961): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1961): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1961): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:456 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 1961): [MSC_Daemon]>>> WU:1381 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 1961): [MSC_Daemon]>>> WU:1401 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:460 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:464 [0:0] selLocation : null
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
E/        ( 4403): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 4403): took 0.652813ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4403): Bitmap=0xb8950f20 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8e69ea8 counterpartCT=4 counterpartW=80 counterparth=80
,W/ResourcesManager( 3756): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4403): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:490 [0:0] today==null
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 1961): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1961): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ResourcesManager( 3756): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3756): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
W/ResourcesManager( 3756): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 1961): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1961): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1961): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1961): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:456 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 1961): [MSC_Daemon]>>> WU:1381 [0:0] cDayONight() ::: sunrise is null ,
,D/daemonapp( 1961): [MSC_Daemon]>>> WU:1401 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:460 [0:0] checkDay:true, UtilgetIsDay():false
D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/jxcore-log( 4387): JXcore Cordova bridge is ready!
I/jxcore-log( 4387): 
D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:464 [0:0] selLocation : null
D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/jxcore-log( 4387): JXcore engine is started
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:android.app.spellscroll
W/ContextImpl( 4403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4403): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/org.thaliproject.p2p.ThaliPermissions( 4387): execute: REQUEST_ACCESS_COARSE_LOCATION
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:490 [0:0] today==null
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
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 4403): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4403): getResourcePackageName:assistant
I/AMMetaDataParserService( 4403): Resource data:2131099648
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ResourcesManager( 4403): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4403): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4403): getResourceTypeNamexml
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 1961): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1961): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 4403): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/AMMetaDataParserService( 4403): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 1961): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1961): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1961): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1961): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:456 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 1961): [MSC_Daemon]>>> WU:1381 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 1961): [MSC_Daemon]>>> WU:1401 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:460 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:464 [0:0] selLocation : null
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:490 [0:0] today==null
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.sec.android.daemonapp
,I/AMMetaDataParserService( 4403): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/daemonapp( 1961): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1961): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 1961): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1961): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1961): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1961): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:456 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 1961): [MSC_Daemon]>>> WU:1381 [0:0] cDayONight() ::: sunrise is null ,
D/daemonapp( 1961): [MSC_Daemon]>>> WU:1401 [0:0] cDayONight() ::: sunset is null ,
D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:460 [0:0] checkDay:true, UtilgetIsDay():false
D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings,
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:464 [0:0] selLocation : null
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/AMMetaDataParserService( 4403): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:490 [0:0] today==null
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1884): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionAPPWIDGET_UPDATE
,I/AMMetaDataParserService( 4403): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,I/AMMetaDataParserService( 4403): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/accuweather( 1884): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1884): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1884): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1884): [KK AccuPhone]>>> WCW:42 [0:0] weather widget id size = 1
,D/accuweather( 1884): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionAPPWIDGET_UPDATE
,D/accuweather( 1884): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1884): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:assistant
I/AMMetaDataParserService( 4403): Resource data:2131099648
,I/AMMetaDataParserService( 4403): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4403): getResourceTypeNamexml
D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/AMMetaDataParserService( 4403): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 4403): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/accuweather( 1884): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,D/accuweather( 1884): [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,D/accuweather( 1884): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,D/accuweather( 1884): [KK AccuPhone]>>> UIM:964 [0:0]  cUI : cnt = 0
D/accuweather( 1884): [KK AccuPhone]>>> UIM:983 [0:0]  composeEmptyCityUI : true
,E/accuweather( 1884): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 10 50
,E/accuweather( 1884): [KK AccuPhone]>>> UIM:967 [0:0] ========>>> mRefreshManagerisRefreshCompleted() = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/AMMetaDataParserService( 4403): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/accuweather( 1884): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionAPPWIDGET_UPDATE
,D/accuweather( 1884): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 1961): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1961): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 4403): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/comsamsunglog( 1961): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1961): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,I/AMMetaDataParserService( 4403): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/comsamsunglog( 1961): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1961): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:widgetappapheroaccuweather, cp:Accuweather, aRS:false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1961): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1961): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,I/AMMetaDataParserService( 4403): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/UpdateIcingCorporaServi( 3756): UpdateCorporaTask done [took 7528 ms] updated apps [took 7528 ms] 
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:assistant
I/AMMetaDataParserService( 4403): Resource data:2131099648
,I/AMMetaDataParserService( 4403): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4403): getResourceTypeNamexml
,I/AMMetaDataParserService( 4403): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/daemonapp( 1961): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1961): [MSC_Daemon]>>> WDSM:140 [0:0] Widget flag autoRefreshSet :  false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1017): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1017): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1017): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4403): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/DBG_DM  ( 3674): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,I/AMMetaDataParserService( 4403): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/WearableService( 1807): callingUid 10011, callindPid: 1807
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1807): [249] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4403): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2113): Restart initialization of location
,I/AMMetaDataParserService( 4403): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1807): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 4403): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3830/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10058/pid_4119/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10099/pid_3968/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:assistant
I/AMMetaDataParserService( 4403): Resource data:2131099648
,I/AMMetaDataParserService( 4403): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4403): getResourceTypeNamexml
,I/art     ( 1807): Explicit concurrent mark sweep GC freed 38236(2MB) AllocSpace objects, 48(1440KB) LOS objects, 40% free, 9MB/16MB, paused 1.310ms total 92.929ms
,I/AMMetaDataParserService( 4403): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/GCoreFlp( 1807): No location to return for getLastLocation()
,W/FusedLocationProvider( 1807): location=null
,I/AMMetaDataParserService( 4403): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 4403): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/AMMetaDataParserService( 4403): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 4403): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 4595): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,E/Zygote  ( 4931): MountEmulatedStorage()
E/Zygote  ( 4931): v2
I/libpersona( 4931): KNOX_SDCARD checking this for 10041
I/libpersona( 4931): KNOX_SDCARD not a persona
,I/SELinux ( 4931): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4931): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4931): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.android.mms for broadcast com.android.mms/.widget.MmsWidgetProvider: pid=4931 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 4931): TimaSignature is unavailable,
D/ActivityThread( 4931): Added TimaKeyStore provider,
,I/art     (  304): Explicit concurrent mark sweep GC freed 8733(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.240ms total 26.634ms,
,I/AMMetaDataParserService( 4403): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 17.283ms,
,W/ResourcesManager( 4931): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4931): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4931): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4931): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4931): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity,
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4403): getResourcePackageName:assistant
I/AMMetaDataParserService( 4403): Resource data:2131099648
,I/AMMetaDataParserService( 4403): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4403): getResourceTypeNamexml
,I/AMMetaDataParserService( 4403): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 695us total 20.882ms
,I/DBG_POLICYDM( 4595): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 4595): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/AMMetaDataParserService( 4403): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/DBG_POLICYDM( 4595): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4595): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4595): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 4595): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4595): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/Mms/MmsApp( 4931): [start]    onCreate() consume time = 0.0
,I/AMMetaDataParserService( 4403): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/AMMetaDataParserService( 4403): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/AMMetaDataParserService( 4403): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/ValidateNoPeople( 1017): mEvictionCount: 0
,I/AMMetaDataParserService( 4403): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:assistant
I/AMMetaDataParserService( 4403): Resource data:2131099648
,I/AMMetaDataParserService( 4403): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4403): getResourceTypeNamexml
,I/AMMetaDataParserService( 4403): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/AMMetaDataParserService( 4403): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 4403): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/AMMetaDataParserService( 4403): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/AMMetaDataParserService( 4403): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/AMMetaDataParserService( 4403): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4403): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
,I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4403): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4403): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
,W/ContextImpl( 4403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:assistant
I/AMMetaDataParserService( 4403): Resource data:2131165197
,W/ResourcesManager( 4403): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 4403): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4403): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 4403): getResourceTypeNamexml
,I/AMMetaDataParserService( 4403): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 4403): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 4403): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/art     ( 4931): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 164.736ms
,I/AMMetaDataParserService( 4403): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
,I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4403): getResourcePackageName:assistant
I/AMMetaDataParserService( 4403): Resource data:2131165197
,I/AMMetaDataParserService( 4403): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 4403): getResourceTypeNamexml
,I/AMMetaDataParserService( 4403): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 4403): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 4403): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 4403): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.cooliris.media.Gallery,
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:assistant
I/AMMetaDataParserService( 4403): Resource data:2131165197
,I/AMMetaDataParserService( 4403): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 4403): getResourceTypeNamexml
,D/Mms/TelephonyPermission( 4931): start operation mode monitor
,D/Mms/ArtClassLoader( 4931): init before art
,W/ResourcesManager( 4931): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission( 4931): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 4931): isDefault true
,D/Mms/MmsApp( 4931): onCreate() com.android.mms
,I/AMMetaDataParserService( 4403): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 4403): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/Mms/MmsApp( 4931): [start]    initCountryIso consume time = 396.992188
,D/CountryDetector( 1017): The first listener is added
,I/AMMetaDataParserService( 4403): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/Mms/MmsApp( 4931): [end]    initCountryIso consume time = 22.319427
,D/Mms/MmsConfig( 4931): [start]    MmsConfig.init() consume time = 1.157083
,I/AMMetaDataParserService( 4403): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
W/ContextImpl( 4403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.Pho,toNote
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 4403): getResourcePackageName:assistant
I/AMMetaDataParserService( 4403): Resource data:2131099648
W/ResourcesManager( 4403): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 4403): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 4403): getResourceTypeNamexml
D/Mms/MmsConfig( 4931): before partial update
,I/Icing   ( 2113): Indexing D2B2F813CD55909B17D100D9886DFA4C4B449F6E from com.google.android.googlequicksearchbox
,I/AMMetaDataParserService( 4403): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,D/Mms/MmsConfig( 4931): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 4931): serviceId : 1, features : -1,
,D/EasySignUpManager_1.0.1( 4931): isAuth is false
,D/Mms/MmsConfig( 4931): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,I/AMMetaDataParserService( 4403): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,D/TP/MmsSmsProvider( 1483): query,matched:2117, calling pid = 4931
,D/TP/MmsSmsProvider( 1483): match 2117:Elapsed time : 1.865 ms
,D/EasySignUpManager_1.0.1( 4931): isAuth is false
,D/EasySignUpManager_1.0.1( 4931): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 4931): mps_code.dat does not exist
E/CscParser( 4931): customer_path =/system/csc/customer.xml
E/CscParser( 4931): fileName + /system/csc/customer.xml
,E/CscParser( 4931): mps_code.dat does not exist
E/CscParser( 4931): customer_path =/system/csc/customer.xml
E/CscParser( 4931): fileName + /system/csc/customer.xml
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
W/ContextImpl( 4403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/CscParser( 4931): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 4931):  enable multiwindow = false
,E/Mms/MessageUtils( 4931): setCountryDetector : update country detector info 
,E/Mms/MessageUtils( 4931): updateCountryIso : update country iso info 
,I/DBG_DM  ( 3674): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,D/Mms/MmsConfig( 4931): [end]    init() consume time = 151.910052
,D/Mms/Contact( 4931): [start]    init() consume time = 1.804896
,D/TP/MmsSmsProvider( 1483): query,matched:13, calling pid = 4931
,D/TP/MmsSmsProvider( 1483): match 13:Elapsed time : 3.146 ms
,D/Mms/Contact( 4931): [end]    init consume time = 46.159948
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:assistant
I/AMMetaDataParserService( 4403): Resource data:2131165220
,D/Mms/DraftCache( 4931): [start]    rebuildCache consume time = 24.015833
,D/TP/MmsSmsProvider( 1483): query,matched:12, calling pid = 4931
,D/TP/MmsSmsProvider( 1483): match 12:Elapsed time : 2.234 ms
,W/ResourcesManager( 4403): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
D/Mms/MethodReflector( 4931): getSubId is called
W/ResourcesManager( 4403): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/Mms/TelephonyUtils( 4931): getLongSubId from simSlot 0, return Value = -1
W/ResourcesManager( 4403): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4403): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/Mms/MethodReflector( 4931): getTelephonyProperty is called
D/Mms/DownloadManager( 4931): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4931): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4931): auto download without roaming -> true
,D/Mms/DownloadManager( 4931): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/MethodReflector( 4931): getSubId is called
,D/Mms/DraftCache( 4931): [end]    rebuildCache consume time = 18.92026
,I/AMMetaDataParserService( 4403): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 4403): getResourceTypeNamexml
,D/Mms/MethodReflector( 4931): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 4931): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 4931): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 4931): getTelephonyProperty is called
D/Mms/DownloadManager( 4931): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 4931): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 4931): auto download without roaming -> true
D/Mms/DownloadManager( 4931): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 4931): auto download during roaming secondary -> false
D/Mms/DownloadManager( 4931): mAutoDownload ------> true
,D/ComposerPerformance( 4931): 1457344233997 ms / [DONE] Composer constructor
,I/AMMetaDataParserService( 4403): Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
,I/AMMetaDataParserService( 4403): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,E/CII     ( 4931): CommonIMSInterface: VoLTE CSC feature disabled.
,D/Mms/Conversation( 4931): [start]    init() consume time = 34.168438
,I/Mms/ReservationManager( 4931): ReservationManager()
,I/Mms/ReservationManager( 4931): resetAfterConnected()
,D/TP/MmsSmsProvider( 1483): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1483): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1483): updateThread(), thread_id = 9223372036854775807
,D/TP/MmsSmsProvider( 1483): query,matched:7, calling pid = 4931
,D/TP/MmsSmsProvider( 1483): match 7:Elapsed time : 6.056 ms
,E/SMD     (  289): DCD OFF
,V/TP/MmsSmsDatabaseHelper( 1483): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1483): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1483): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1483): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1483): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1483): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1483): (284) automatic index on im_threads(normal_thread_id)
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SubSettings
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  chec,k
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
D/TP/MmsSmsProvider( 1483): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1483): need read changed broadcast:false
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
D/Mms/Conversation( 4931): [end]    init consume time = 36.984687
D/Mms/MessagingNotification( 4931): [start]    init() consume time = 1.235573
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
W/ContextImpl( 4403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ManageApplications
,I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
D/Mms/MessagingNotification( 4931): [end]    init consume time = 8.664636
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:,Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/ActivityManager( 1017): Killing 4159:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 4403): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4403): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 4403): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
I/Mms/ReservationManager( 4931): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1483): query,matched:0, calling pid = 4931
V/TP/MmsSmsProvider( 1483): getSimpleConversations entered.
D/Mms/MmsApp( 4931): [end]    onCreate() consume time = 33.565625
D/TP/MmsSmsProvider( 1483): match 0:Elapsed time : 7.733 ms
D/Mms/DownloadManager( 4931): Service state changed: Bundle[mParcelledData.dataSize=744]
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/DownloadManager( 4931): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 4931): getSubId is called
D/Mms/TelephonyUtils( 4931): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 4931): getTelephonyProperty is called
D/Mms/Downl,oadManager( 4931): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4931): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4931): auto download without roaming -> true
D/Mms/DownloadManager( 4931): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/DownloadManager( 4931): mAutoDownload ------> true
D/Mms/MessagingNotification( 4931): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1483): query,matched:26, calling pid = 4931
D/TP/SmsProvider( 1483): match 26:Elapsed time : 1.968 ms
D/Mms/ArtClassLoader( 4931): init [DONE] art
D/Mms/SpamFilter( 4931): [start]    SpamFilter fill() begin consume time = 70.470677
D/TP/MmsSmsProvider( 1483): query,matched:6, calling pid = 4931
,D/Mms/Synchronizer( 4931): [start]    doSync consume time = 4.356458
,D/TP/MmsSmsProvider( 1483): match 6:Elapsed time : 4.478 ms
,I/Icing   ( 2113): Indexing done D2B2F813CD55909B17D100D9886DFA4C4B449F6E
,D/TP/MmsSmsProvider( 1483): query,matched:400, calling pid = 4931
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/Mms/SpamFilter( 4931): [end]    SpamFilter fill() finished consume time = 12.20651
,D/TP/MmsSmsProvider( 1483): update, matched:300, calling pid = 4931
V/TP/MmsSmsProvider( 1483): syncDBData start
,V/TP/MmsSmsProvider( 1483): syncDBData sms end
,V/TP/MmsSmsProvider( 1483): syncDBData mms end
,V/TP/MmsSmsProvider( 1483): syncDBData end
,D/Mms/Synchronizer( 4931): [end]    doSync consume time = 11.335
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4960): MountEmulatedStorage()
I/libpersona( 4960): KNOX_SDCARD checking this for 10023
E/Zygote  ( 4960): v2
I/libpersona( 4960): KNOX_SDCARD not a persona
,I/SELinux ( 4960): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4960): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4960): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4960 uid=10023 gids={50023, 9997} abi=armeabi-v7a,
,V/UserPresentBroadcastReceiver( 1807): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4960): TimaSignature is unavailable
D/ActivityThread( 4960): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4976): MountEmulatedStorage()
,E/Zygote  ( 4976): v2
,I/libpersona( 4976): KNOX_SDCARD checking this for 1000,
I/libpersona( 4976): KNOX_SDCARD not a persona
,I/SELinux ( 4976): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4976 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4976): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1017): Killing 4187:com.google.android.talk/u0a102 (adj 15): empty #31
,E/SELinux ( 4976): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_4159/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4976): TimaSignature is unavailable
,D/ActivityThread( 4976): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_10102/pid_4187/cgroup.procs: No such file or directory
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 25715(1561KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/33MB, paused 2.611ms total 162.262ms
,E/MTPRx   ( 4976): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1017): mCursor = null
,V/MTPRx   ( 4976): sealedState: false
V/MTPRx   ( 4976): sealedUsbMassStorageState: false
E/MTPRx   ( 4976): check value of boot_completed is1
E/MTPRx   ( 4976): check booting is completed_sys.boot_completed
,E/MTPRx   ( 4976): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4976): Status for mount/Unmount :removed
E/MTPRx   ( 4976): SDcard is not available
,W/MTPRx   ( 4976): value of connected istrue
,W/MTPRx   ( 4976): value of configured istrue
W/MTPRx   ( 4976): value of mtpEnabled istrue
W/MTPRx   ( 4976): value of ptpEnabled isfalse
,E/MTPRx   ( 4976): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 4976): mFirstTime: false
,D/        ( 4976): MTP: reading debug level property
,E/MTPJNIInterface( 4976): Getting CryptionKey from JAVA
,E/MTPRx   ( 4976): currentUserId is 0
,E/MTPRx   ( 4976): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 4976): cannot open file : /sys/class/android_usb/android0/bcdUSB
,E/MTPRx   ( 4976): is_Privatemode is NOT 1
,D/SettingsProvider( 1017): name = boot_time_connected
,E/MTPRx   ( 4976): Sending NORMAL_BOOT to stack
,I/OMACP   ( 4960): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
E/MTPJNIInterface( 4976): noti = 17
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,D/SecContentProvider( 1017): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 4976): sending MTP_ICON_ENABLED to stack
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1017): name = mtp_running_status
,D/Mms/Omacp( 4931): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,I/SecKeyguardClockSingleView( 1171): Ignore. Because it is same clock text
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,E/MTPRx   ( 4976): else part ... so first time!!!
E/MTPPlaObsrvr( 4976): inside setContext()
E/MTPPlaObsrvr( 4976):  inside createplafiles
,E/MTPPlaObsrvr( 4976): playlist count is0
,E/MTPPlaObsrvr( 4976):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4976):  inside deleteing plas createplafiles
,I/OMACP   ( 4960): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,E/MTPPlaObsrvr( 4976): Inside registerContentObserver
,I/OMACP   ( 4960): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 4960): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,E/MtpAdbObserver( 4976): inside setContext()
,E/MtpAdbObserver( 4976): Inside registerContentObserver
W/Settings( 4976): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
I/OMACP   ( 4960): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 4960): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 4960): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,I/OMACP   ( 4960): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,I/OMACP   ( 4960): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,D/SettingsProvider( 1017): name = mtp_running_status
,I/OMACP   ( 4960): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,I/OMACP   ( 4960): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 4960): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 4960): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 4960): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,E/MtpService( 4976): onCreate.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,V/MtpMediaDBManager( 4976): inside deleteAllDB
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/MtpService( 4976): < MTP > Registering BroadCast receiver :::::
,D/MtpService( 1224): updating state; isCurrentUser=true, mMtpLocked=false
,E/Zygote  ( 4995): MountEmulatedStorage()
E/Zygote  ( 4995): v2
I/libpersona( 4995): KNOX_SDCARD checking this for 1000
I/libpersona( 4995): KNOX_SDCARD not a persona
,I/SELinux ( 4995): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SELinux ( 4995): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4995 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
E/SELinux ( 4995): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/MtpService( 4976): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 4976): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 4976): onStartCommand.
,V/MtpMediaDBManager( 4976): inside Thread updateDB
,E/MtpService( 4976): handleMessage. msg= { when=-2ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MtpMediaDBManager( 4976): count : 26
,W/MTPRx   ( 4976): calling native method
E/MTPJNIInterface( 4976): < MTP > Registering BroadCast receiver :::::
,D/TimaKeyStoreProvider( 4995): TimaSignature is unavailable
,D/ActivityThread( 4995): Added TimaKeyStore provider
,E/MTPJNIInterface( 4976): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 4976): noti = 10
,E/MtpService( 4976): onStartCommand.
W/MTPRx   ( 4976): calling native method
E/MTPRx   ( 4976): Checking the driver time out
E/MTPJNIInterface( 4976): noti = 2
D/        ( 4976): deleting sockets before message queue initialization
,D/        ( 4976): event handler thread is created, so set the flag
,E/MTPRx   ( 4976): called native method
E/MTPJNIInterface( 4976): setting Media scanner status0
E/MTPJNIInterface( 4976): After setting Media scanner status0
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1171): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/MTPRx   ( 4976): notification from stack 1
,E/        ( 4976): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 4976): Getting media scanner status0
,E/MtpService( 4976): handleMessage. msg= { when=-3ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 4976): DeviceName is Thali Test (Galaxy A3)
,W/MtpMediaDBManager( 4976): sending db update complete noti to stack
E/MTPJNIInterface( 4976): noti = 29
,E/SQLiteLog( 4976): (5) database is locked
,E/SQLiteLog( 4976): (5) database is locked
,E/MTPJNIInterface( 4976): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4976): SDcard is not available
,E/        ( 4976): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface( 4976): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4976): SDcard is not available
,E/SQLiteLog( 4976): (21) API call with NULL database connection pointer
,E/SQLiteLog( 4976): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4976): (21) API call with NULL database connection pointer
E/SQLiteLog( 4976): (21) misuse at line 100726 of [9491ba7d73]
,E/SQLiteLog( 4976): (21) API call with NULL database connection pointer
E/SQLiteLog( 4976): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4976): (21) API call with NULL database connection pointer
E/SQLiteLog( 4976): (21) misuse at line 106108 of [9491ba7d73]
W/MTPRx   ( 4976): notification from stack 2
D/        ( 4976): [mtp_init_device] Library open with 32 bits.
D/        ( 4976): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 4976): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 4976): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 4976):  [sua_support_present:1287] returning false 
D/        ( 4976): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
