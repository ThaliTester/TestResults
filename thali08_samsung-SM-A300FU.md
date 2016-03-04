#### Test 617161634bd7322_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
E/Zygote  ( 3788): MountEmulatedStorage()
E/Zygote  ( 3788): v2
I/SELinux ( 3788): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3788): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
--------- beginning of system
I/libpersona( 3788): KNOX_SDCARD checking this for 1000
I/libpersona( 3788): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3788 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 2925:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
E/SELinux ( 3788): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3788): TimaSignature is unavailable
D/ActivityThread( 3788): Added TimaKeyStore provider
D/NPS_WSSNPS( 3788): [] android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
D/NPS_WSSNPS( 3788): [] Service onCreate!!
W/ContextImpl( 3788): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3808): MountEmulatedStorage()
E/Zygote  ( 3808): v2
I/libpersona( 3808): KNOX_SDCARD checking this for 1000
I/libpersona( 3808): KNOX_SDCARD not a persona
I/SELinux ( 3808): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3808): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3808 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 3808): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SettingsProvider( 1019): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10058
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
E/MTPRx   ( 3748): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
D/SecContentProvider2( 1019): uri = 14 selection = getSealedState
D/SecContentProvider2( 1019): mCursor = null
D/NPS_WSSNPS( 3788): [50.150321] NpsServiceTask Start
D/TimaKeyStoreProvider( 3808): TimaSignature is unavailable
D/ActivityThread( 3808): Added TimaKeyStore provider
W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
D/GCM     ( 2012): COMPAT: Multi user not supported
D/SecContentProvider2( 1019): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1019): mCursor = null
D/NPS_WSSNPS( 3788): [50.150321] smlDBHelper
V/MTPRx   ( 3748): sealedState: false
V/MTPRx   ( 3748): sealedUsbMassStorageState: false
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
I/ActivityManager( 1019): Killing 2945:com.sec.usbsettings/1000 (adj 15): empty #31
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SettingsProvider( 1019): name = mtp_usb_connection_status
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/NPS_WSSNPS( 3788): [50.150321] AsyncBulkFlagCheck
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SettingsProvider( 1019): name = media_player_mode
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
D/SettingsProvider( 1019): name = mtp_usb_conditions_met
E/File    ( 3537): fail readDirectory() errno=2
E/Zygote  ( 3834): MountEmulatedStorage()
E/Zygote  ( 3834): v2
I/libpersona( 3834): KNOX_SDCARD checking this for 10100
I/libpersona( 3834): KNOX_SDCARD not a persona
I/SELinux ( 3834): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3834): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=3834 uid=10100 gids={50100, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 3834): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ContextImpl( 1367): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1019): Killing 2391:com.android.mms/u0a41 (adj 15): empty #31
W/ContextImpl( 1367): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
W/libprocessgroup( 1019): failed to open /acct/uid_1101/pid_2884/cgroup.procs: No such file or directory
I/SettingSearch/SearchIntentReceiver( 1367): InitSerachDBThread thread end!
I/Gmail   ( 3537): notifyAccountChanged
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/Gmail   ( 3537): getAccountsCursor
W/libprocessgroup( 1019): failed to open /acct/uid_10153/pid_2925/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_2945/cgroup.procs: No such file or directory
I/Gmail   ( 3537): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/SettingsProvider( 1019): name = mtp_running_status
I/NPS_WSSNPS( 3788): [50.150321] IsRemain_AsyncBulkCheck
I/NPS_WSSNPS( 3788): [50.150321] IsRemain_Asyncing nothing
W/ContextImpl( 3788): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
D/TimaKeyStoreProvider( 3834): TimaSignature is unavailable
D/ActivityThread( 3834): Added TimaKeyStore provider
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
D/NPS_WSSNPS( 3788): [50.150321] Service onDestroy
I/ActivityManager( 1019): Killing 2980:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
D/CountryDetector( 1019): No listener is left
I/Gmail   ( 3537): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/SettingsProvider( 1019): name = access_control_enabled
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/Gmail   ( 3537): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 3537): calculateUnknownSyncRationalesAndPurgeInBackground: running
E/Zygote  ( 3850): MountEmulatedStorage()
E/Zygote  ( 3850): v2
I/libpersona( 3850): KNOX_SDCARD checking this for 10065
I/libpersona( 3850): KNOX_SDCARD not a persona
I/SELinux ( 3850): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3850 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 2869:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
I/SELinux ( 3850): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/libprocessgroup( 1019): failed to open /acct/uid_10043/pid_2980/cgroup.procs: No such file or directory
E/SELinux ( 3850): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1019): failed to open /acct/uid_10041/pid_2391/cgroup.procs: No such file or directory
W/art     ( 2012): Verification of void com.google.android.gms.checkin.d.a(javax.microedition.khronos.egl.EGL10, javax.microedition.khronos.egl.EGLDisplay, javax.microedition.khronos.egl.EGLConfig, int[], int[], java.util.Set) took 112.179ms
D/TimaKeyStoreProvider( 3850): TimaSignature is unavailable
D/ActivityThread( 3850): Added TimaKeyStore provider
I/NPS_WSSNPS( 3788): [50.150321] smlBRConfigurationDelete
I/NPS_WSSNPS( 3788): [50.150321] smlBRMessageDelete
I/NPS_WSSNPS( 3788): [50.150321] smlBREmailDelete
I/NPS_WSSNPS( 3788): [50.150321] smlBRNetworkDelete
I/NPS_WSSNPS( 3788): [50.150321] smlBRCallLogDelete
I/NPS_WSSNPS( 3788): [50.150321] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 3788): [50.150321] smlBRPenMemoMDelete
I/NPS_WSSNPS( 3788): [50.150321] smlBRSMemoDelete
I/NPS_WSSNPS( 3788): [50.150321] cpuBooster release : false
W/art     ( 2012): Suspending all threads took: 142.795ms
D/SettingsProvider( 1019): name = media_mount_count
D/NPS_WSSNPS( 3788): [50.150321] dsServerSocket close
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
I/ActivityManager( 1019): Killing 2262:flipboard.app/u0a96 (adj 15): empty #31
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
D/SettingsProvider( 1019): name = mtp_sync_alive
D/FactoryTestApp( 2609): [DummyFtClient$onDestroy](2609) Destroy DummyFtClient service
D/FactoryTestApp( 2609): [Support$Values.getString](2609) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2609): [ModuleCommon$isConnectionModeNone](2609) mConnectionMode = gsm
I/FactoryTestApp( 2609): [ModuleCommon$isRunningFtClient](2609) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2609): [DummyFtClient$onDestroy](2609) kill process
I/Process ( 2609): Sending signal. PID: 2609 SIG: 9
D/PowerManagerService( 1019): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1175 (0x0)
I/Gmail   ( 3537): getAccountsCursor
D/FileShare-Server( 3850): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
D/SettingsProvider( 1019): name = sdcard_launch
D/SettingsProvider( 1019): name = boot_time_connected
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
I/DBG_POLICYDM( 3312): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
W/AbstractGoogleClient( 3834): Application name is not set. Call Builder#setApplicationName.
W/art     ( 3724): Suspending all threads took: 29.879ms
I/GCoreUlr( 2012): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
W/libprocessgroup( 1019): failed to open /acct/uid_10081/pid_2869/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10096/pid_2262/cgroup.procs: No such file or directory
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
D/SettingsProvider( 1019): name = mtp_open_session
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
E/Zygote  ( 3875): MountEmulatedStorage()
E/Zygote  ( 3875): v2
I/libpersona( 3875): KNOX_SDCARD checking this for 10037
I/libpersona( 3875): KNOX_SDCARD not a persona
I/SELinux ( 3875): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3875 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1019): Process com.sec.factory (pid 2609)(adj 0) has died(69,612)
I/DBG_POLICYDM( 3312): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
I/DBG_POLICYDM( 3312): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
I/DBG_POLICYDM( 3312): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
I/SELinux ( 3875): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/DBG_POLICYDM( 3312): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
E/SELinux ( 3875): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 3312): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
I/DBG_POLICYDM( 3312): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
I/DBG_POLICYDM( 3312): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
I/Babel   ( 3724): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3724): MmsConfig.loadMmsSettings
I/Babel   ( 3724): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel   ( 3724): MmsConfig.loadFromDatabase
I/PCWCLIENTTRACE_PushUtil( 3520): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3520): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3520): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3520): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3520): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3520): ACTION_BOOTUP - Push type: [SPP, GCM]
D/TimaKeyStoreProvider( 3875): TimaSignature is unavailable
D/ActivityThread( 3875): Added TimaKeyStore provider
W/PCWCLIENTTRACE_AccountUtil( 3520): [hasSamungAccount] - No Samsung Account
I/DBG_DM  ( 3189): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
I/CheckinService( 2012): Checkin interval check for package: unspecified last checkin: 1456599118758 min interval config: 0 actual interval: 503474869
I/Icing   ( 2012): Storage manager: low false usage 2.11MB avail 9.96GB capacity 11.63GB
W/ResourcesManager( 3875): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/CheckinService( 2012): Disabling old GoogleServicesFramework version
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/PCWCLIENTTRACE_SecurePreferencesJNI( 3520): [GetString-S]
D/SystemUpdateService( 2012): onCreate
W/VideoCapabilities( 3724): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 3724): Unsupported mime audio/evrc
W/AudioCapabilities( 3724): Unsupported mime audio/qcelp
E/Babel   ( 3724): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3724): MmsConfig.loadFromResources
E/Babel   ( 3724): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3724): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
W/AudioCapabilities( 3724): Unsupported mime audio/mpeg-L1
W/AudioCapabilities( 3724): Unsupported mime audio/mpeg-L2
I/ReactiveServiceManager( 3520): Supported : 1
D/QSEECOMAPI: ( 1019): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 1019): App is not loaded in QSEE
W/AudioCapabilities( 3724): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 3724): Unsupported mime audio/x-ima
W/AudioCapabilities( 3724): Unsupported mime audio/qcelp
W/AudioCapabilities( 3724): Unsupported mime audio/evrc
D/QSEECOMAPI: ( 1019): Loaded image: APP id = 9
D/QSEECOMAPI: ( 1019): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1019): QSEECom_shutdown_app, app_id = 9
E/terrier ( 1019): handleString: Failed to handle string(-4)
E/terrier ( 1019): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 3520): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 3520): [GetString-E]
I/PCWCLIENTTRACE_PushUtil( 3520): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3520): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3520): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 3520): [ensureRegistration] - No Samsung account
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
W/VideoCapabilities( 3724): Unsupported mime video/wvc1
W/VideoCapabilities( 3724): Unsupported mime video/x-ms-wmv
E/Zygote  ( 3899): MountEmulatedStorage()
E/Zygote  ( 3899): v2
I/libpersona( 3899): KNOX_SDCARD checking this for 10028
I/libpersona( 3899): KNOX_SDCARD not a persona
I/SELinux ( 3899): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3899 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 3899): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3899): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Killing 3017:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
I/CalendarProvider2( 3875): CalendarProvider2.onCreate() called
D/SystemUpdateService( 2012): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
V/AuthZen ( 2012): Handling intent: android.intent.action.BOOT_COMPLETED
W/VideoCapabilities( 3724): Unrecognized profile/level 32768/2 for video/mp4v-es
D/TimaKeyStoreProvider( 3899): TimaSignature is unavailable
D/ActivityThread( 3899): Added TimaKeyStore provider
W/VideoCapabilities( 3724): Unsupported mime video/wvc1
W/VideoCapabilities( 3724): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 3724): Unsupported mime video/x-ms-wmv7
W/VideoCapabilities( 3724): Unsupported mime video/x-ms-wmv8
W/Settings( 3724): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/VideoCapabilities( 3724): Unsupported mime video/mp43
D/ChimeraCfgMgr( 2012): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AndroidRuntime( 3828): 
D/AndroidRuntime( 3828): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/VideoCapabilities( 3724): Unsupported mime video/sorenson
D/AndroidRuntime( 3828): CheckJNI is OFF
D/AndroidRuntime( 3828): readGMSProperty: start
D/AndroidRuntime( 3828): readGMSProperty: already setted!!
D/AndroidRuntime( 3828): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3828): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3828): readGMSProperty: end
D/AndroidRuntime( 3828): addProductProperty: start
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3017/cgroup.procs: No such file or directory
I/CheckinService( 2012): Checking schedule, now: 1457102593922 next: 1457166045303
I/CheckinService( 2012): active receiver: disabled
W/VideoCapabilities( 3724): Unsupported mime video/mp4v-esdp
I/SystemUpdateService( 2012): cancelUpdate (empty URL)
I/SystemUpdateService( 2012): active receiver: disabled
I/VideoCapabilities( 3724): Unsupported profile 4 for video/mp4v-es
D/BootCompletedReceiver( 2012): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
D/BootCompletedReceiver( 2012): Got an BootCompleted event.
D/AuthZenEventHandler( 2012): Handling event: android.intent.action.BOOT_COMPLETED
D/BootCompletedReceiver( 2012): Will NOT schedule AdAttestation signal task because it's disabled.
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 2012): Using Auth Proxy for data requests.
V/Babel   ( 3724): babel boot account: SMS
V/Babel   ( 3724): babel boot account: thalitester@gmail.com
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/art     ( 1649): Explicit concurrent mark sweep GC freed 4592(193KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 772us total 28.854ms
E/Zygote  ( 3934): MountEmulatedStorage()
E/Zygote  ( 3934): v2
I/libpersona( 3934): KNOX_SDCARD checking this for 1000
I/libpersona( 3934): KNOX_SDCARD not a persona
I/SELinux ( 3934): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/SQLiteConnectionPool( 1649): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/ActivityManager( 1019): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3934 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3934): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Killing 1609:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
E/SELinux ( 3934): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Killing 3057:com.google.android.configupdater/u0a82 (adj 15): empty #31
I/art     (  315): Explicit concurrent mark sweep GC freed 8720(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 688us total 33.386ms
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 693us total 18.455ms
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
W/ContextImpl( 1019): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
D/TimaKeyStoreProvider( 3934): TimaSignature is unavailable
D/ActivityThread( 3934): Added TimaKeyStore provider
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 725us total 21.691ms
E/Zygote  ( 3949): MountEmulatedStorage()
E/Zygote  ( 3949): v2
I/libpersona( 3949): KNOX_SDCARD checking this for 1000
I/libpersona( 3949): KNOX_SDCARD not a persona
I/SELinux ( 3949): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3949 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3949): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3949): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
E/AffinityControl( 3828): AffinityControl: registerfunction enter
D/TimaKeyStoreProvider( 3949): TimaSignature is unavailable
D/ActivityThread( 3949): Added TimaKeyStore provider
E/BaseAppContext( 2012): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
E/AclDataUtils( 2810): Circle ID not found for type: 9
W/libprocessgroup( 1019): failed to open /acct/uid_10068/pid_1609/cgroup.procs: No such file or directory
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
W/libprocessgroup( 1019): failed to open /acct/uid_10082/pid_3057/cgroup.procs: No such file or directory
I/System.out( 3899): Inside onCreate() of WakeupTriggerProvide
I/System.out( 3899): Inside WakeupProvider
D/AndroidRuntime( 3828): Calling main entry com.android.commands.am.Am
I/art     ( 1019): Explicit concurrent mark sweep GC freed 41223(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 22MB/33MB, paused 2.722ms total 172.668ms
V/AlarmManager( 1019): waitForAlarm result :4
V/AlarmManager( 1019): waitForAlarm result :4
I/AuthZen ( 2012): Fetching signing key...
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/System.out( 3125): Thread-398(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3125): Thread-398(ApacheHTTPLog):isShipBuild true
I/System.out( 3125): Thread-398(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3125): Thread-398(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10088
D/GCM     ( 1741): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
V/GLSActivity( 1741): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GCoreUlr( 1741): DispatchingService.onCreate()
W/ContextImpl( 3949): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
D/GCMRegistrar( 3125): resetting backoff for com.dropbox.android
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
V/GCMRegistrar( 3125): Registering app com.dropbox.android of senders 735665981150
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3986): MountEmulatedStorage()
E/Zygote  ( 3986): v2
I/libpersona( 3986): KNOX_SDCARD checking this for 1000
I/libpersona( 3986): KNOX_SDCARD not a persona
I/SELinux ( 3986): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3986 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3986): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/AuthZen ( 2012): Signing key fetched successfully!
E/SELinux ( 3986): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/BaseAppContext( 2012): Using Auth Proxy for data requests.
I/DBG_DM  ( 3189): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
D/TimaKeyStoreProvider( 3986): TimaSignature is unavailable
D/ActivityThread( 3986): Added TimaKeyStore provider
D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1019): mDVFSHelper.acquire()
I/VlingoApplication( 3899): VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
D/FocusedStackFrame( 1019): Set to : 0
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 1489
D/AndroidRuntime( 3828): Shutting down VM
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.google.process.gapps
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1019): *FMB* installDecor flags : -2122120936
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.syncadapters.calendar, destAppInfo.processName = com.google.android.gms
D/Launcher.HomeView( 1489): onPause
D/Launcher( 1489): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=10 createSurf (1x1),1 flag=404, uhalitest
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 3986): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
E/Zygote  ( 4008): MountEmulatedStorage()
I/libpersona( 4008): KNOX_SDCARD checking this for 10167
E/Zygote  ( 4008): v2
I/libpersona( 4008): KNOX_SDCARD not a persona
I/SELinux ( 4008): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4008 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4008): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4008): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ContextImpl( 3986): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4020): MountEmulatedStorage()
I/libpersona( 4020): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4020): v2
I/libpersona( 4020): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4020 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 4020): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4020): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4020): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Killing 3125:com.dropbox.android/u0a88 (adj 15): empty #31
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
V/ActivityThread( 1489): updateVisibility : ActivityRecord{390e4bd token=android.os.BinderProxy@139557d7 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/a       ( 2012): Opening database auth.proximity.permit_store...
D/AuthZenTransactionCache( 2012): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2012): Clearing transaction cache
D/TimaKeyStoreProvider( 4008): TimaSignature is unavailable
D/ActivityThread( 4008): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 4020): TimaSignature is unavailable
D/ActivityThread( 4020): Added TimaKeyStore provider
D/SystemUpdateService( 2012): onDestroy
V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/Launcher.HomeView( 1489): onStop
V/ActivityThread( 1489): updateVisibility : ActivityRecord{390e4bd token=android.os.BinderProxy@139557d7 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/F_PHONE ( 3986): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
W/ContextImpl( 3986): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1019): isKioskContainerExistOnDevice
I/GCoreUlr( 1741): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
W/art     ( 3828): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
D/Launcher( 1489): onTrimMemory. Level: 20
I/VlingoAndroidCore( 3899): AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1019): [SO] activate (ident=0xb7ea2d18, enabled=0)
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
V/GLSActivity( 1741): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SensorManager( 1019): unregisterListener ::   
I/Sensors ( 1019): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1019): [SO] changed settle time [1]
D/SensorService( 1019): [SO] setDelay [66000000]
D/SensorService( 1019): [SO] activate (ident=0xb7c8b688, enabled=1)
D/SensorService( 1019): [SO] AR_init
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
I/GCM     ( 1741): GCM config loaded
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
V/GLSActivity( 1741): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SensorManager( 1019): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,E/Zygote  ( 4045): MountEmulatedStorage()
,E/Zygote  ( 4045): v2
I/libpersona( 4045): KNOX_SDCARD checking this for 1000
I/libpersona( 4045): KNOX_SDCARD not a persona
I/SELinux ( 4045): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4045): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4045): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=4045 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/F_PHONE ( 3986): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 3986): default registerAction()
I/F_PHONE ( 3986): [[com.sec.bcservice]] sendPendingMessage()
,E/KnoxSetupWizardClient( 4020): isShipMode : 1
I/KnoxSetupWizardClient( 4020): onReceive : android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4045): TimaSignature is unavailable
,D/ActivityThread( 4045): Added TimaKeyStore provider
,E/SQLiteLog( 2012): (10) POSIX Error : 11 SQLite Error : 3850
,D/SensorService( 1019): [SO] Reset Rotation Old [100], Init [1]
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1741): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,W/ResourcesManager( 4045): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/GCoreFlp( 1741): No location to return for getLastLocation()
,W/FusedLocationProvider( 1741): location=null
,D/SensorService( 1019): [SO] -0.383 0.153 9.922
D/SensorService( 1019): [SO] [100 -> 255]
,D/ShortcutReceiver( 4020):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,D/BluetoothBDAdrressReceiver( 4045): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 4045): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,W/GCoreFlp( 1741): No location to return for getLastLocation()
,W/FusedLocationProvider( 1741): location=null
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3949): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3949): Resource data:2131165186
,W/ResourcesManager( 3949): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3949): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3949): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 1455): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothBDTestService( 1455): onCreate()
,E/Zygote  ( 4073): MountEmulatedStorage()
I/libpersona( 4073): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4073): v2
I/libpersona( 4073): KNOX_SDCARD not a persona
I/SELinux ( 4073): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
E/BluetoothBDTestService( 1455): onStart(), extra_type: BOOT_COMPLETED,
E/BluetoothBDTestService( 1455): bd_address_path: /efs/bluetooth/bt_addr
E/BluetoothBDTestService( 1455): already exist!( /efs/bluetooth/bt_addr ), file length: 17
I/SELinux ( 4073): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4073): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1019): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=4073 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
I/ActivityManager( 1019): Killing 3075:com.sec.dsm.system/1000 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4073): TimaSignature is unavailable
,D/ActivityThread( 4073): Added TimaKeyStore provider
,I/WebViewFactory( 4008): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,W/libprocessgroup( 1019): failed to open /acct/uid_10088/pid_3125/cgroup.procs: No such file or directory
,I/LibraryLoader( 4008): Loading: webviewchromium
,I/AMMetaDataParserService( 3949): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3949): getResourceTypeNamexml
,I/LibraryLoader( 4008): Time to load native libraries: 5 ms (timestamps 2848-2853)
I/LibraryLoader( 4008): Expected native library version number "",actual native library version number ""
,W/Auth    ( 1741): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/AMMetaDataParserService( 3949): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,D/KnoxShortcutUtil( 4020): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4020):  KnoxContainerVersion 2.3.0
D/ShortcutReceiver( 4020):  shortcut migration not required 
,W/ResourcesManager( 4073): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/System.err( 4020): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/System.err( 4020): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4020): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4020): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 4020): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 4020): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4020): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
V/GLSActivity( 1741): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Zygote  ( 4092): MountEmulatedStorage(),
I/libpersona( 4092): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4092): v2
I/libpersona( 4092): KNOX_SDCARD not a persona
I/SELinux ( 4092): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4092 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4092): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Killing 3170:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
E/SELinux ( 4092): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Killing 3151:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
,D/VlingoApplication( 3899): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 3899): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/TimaKeyStoreProvider( 4092): TimaSignature is unavailable
,D/ActivityThread( 4092): Added TimaKeyStore provider
,I/System.out( 1741): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1741): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1741): (HTTPLog)-Static: isShipBuild true
I/System.out( 1741): (HTTPLog)-Thread-221-779895066: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1741): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,I/KnoxUsageLogPro( 4073): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,I/System.out( 1741): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/KnoxUsageLogPro( 4073): premStatus:2
,I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/8)
,I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/8)
,V/WebViewChromiumFactoryProvider( 4008): Binding Chromium to main looper Looper (main, tid 1) {79745ec}
,I/LibraryLoader( 4008): Expected native library version number "",actual native library version number ""
,I/KnoxUsageLogPro( 4073): savePreference: key = previous_sys_time value = 1457102595310
,I/KnoxUsageLogPro( 4073): isEulaShown : false
I/KnoxUsageLogPro( 4073): KnoxUsageReceiver onReceive : not Processible, just return
,I/chromium( 4008): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/DialogFlow( 3899): initQueue()
,I/AMMetaDataParserService( 3949): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,D/StatusChecker( 4092): onReceive : android.intent.action.BOOT_COMPLETED
,I/BrowserStartupController( 4008): Initializing chromium process, renderers=0
,W/art     ( 4008): Attempt to remove local handle scope entry from IRT, ignoring
,I/CalendarProvider2( 3875): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
I/AMMetaDataParserService( 3949): Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,I/KnoxUsageLogPro( 4073): savePreference: key = previous_elapsed_time value = 42978
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCr,eateAccountActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3075/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3170/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10088/pid_3151/cgroup.procs: No such file or directory
I/StatusChecker( 4092): onReceive : net.mt.init : DONE
W/ContextImpl( 3949): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/System.out( 1741): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1741): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1741): Tagging socket 92 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1741, getuid(): 10011
W/chromium( 4008): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 4008): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/chromium( 4008): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:assistant
I/AMMetaDataParserService( 3949): Resource data:2131034113
,W/ResourcesManager( 3949): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 3949): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/Zygote  ( 4126): MountEmulatedStorage()
E/Zygote  ( 4126): v2
,I/libpersona( 4126): KNOX_SDCARD checking this for 10029
I/libpersona( 4126): KNOX_SDCARD not a persona
,I/AMMetaDataParserService( 3949): getResourceName:com.android.contacts:xml/assistant_main,
I/AMMetaDataParserService( 3949): getResourceTypeNamexml
I/ActivityManager( 1019): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4126 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/Adreno-EGL( 4008): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
I/Adreno-EGL( 4008): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4008): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4008): Local Branch: 
I/Adreno-EGL( 4008): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4008): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4008):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
I/ActivityManager( 1019): Killing 3204:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31,
I/SELinux ( 4126): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4126): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4126): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3949): took 2.645521ms for 0*0 texture 0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/GFX generate_partition_tables( 3949): took 6.268959ms for 0*0 texture 0
I/GFX raster( 3949): took 10.178438ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7849ea0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7849e60 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4135): MountEmulatedStorage(),
E/Zygote  ( 4135): v2
I/libpersona( 4135): KNOX_SDCARD checking this for 10113
I/libpersona( 4135): KNOX_SDCARD not a persona
,I/AMMetaDataParserService( 3949): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533,
I/ActivityManager( 1019): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4135 uid=10113 gids={50113, 9997} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 3239:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,I/SELinux ( 4135): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/GCoreUlr( 1741): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/TimaKeyStoreProvider( 4126): TimaSignature is unavailable
D/ActivityThread( 4126): Added TimaKeyStore provider
E/SMD     (  294): DCD OFF
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
I/qtaguid ( 1741): Tagging socket 97 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1741, getuid(): 10011
,I/SELinux ( 4135): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/GAV2    ( 3278): Thread[GAThread,5,main]: No campaign data found.
E/SELinux ( 4135): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GFX raster( 3949): took 0.966770ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7849ea0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7849e60 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3949): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/GCoreUlr( 1741): Unbound from all location providers
D/PersistentNotificationBroadcastReceiver( 1741): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
I/GCoreUlr( 1741): Place inference reporting - stopped
,D/TimaKeyStoreProvider( 4135): TimaSignature is unavailable
,D/ActivityThread( 4135): Added TimaKeyStore provider
,I/ActivityManager( 1019): Killing 3312:com.policydm/1000 (adj 15): empty #31
,I/GCoreUlr( 1741): DispatchingService.onDestroy()
,I/GCoreUlr( 1741): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1741): Unbound from all location providers
I/GCoreUlr( 1741): Place inference reporting - stopped
,W/libprocessgroup( 1019): failed to open /acct/uid_10146/pid_3204/cgroup.procs: No such file or directory
,I/PageBuddyNotiSvc( 4135): Intent received : action=android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3239/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3312/cgroup.procs: No such file or directory
W/ContextImpl( 4135): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/PageBuddyNotiSvc( 4135): onCreate mCpBitFlag=0
,I/DBG_DM  ( 3189): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,E/Zygote  ( 4163): MountEmulatedStorage()
,E/Zygote  ( 4163): v2
I/libpersona( 4163): KNOX_SDCARD checking this for 10121
I/libpersona( 4163): KNOX_SDCARD not a persona
,I/SELinux ( 4163): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4163): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4163 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 4163): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PCWCLIENTTRACE_AccountAppFacade2_0( 3520): unregister AuthInfo UpdateReceiver v2.0
,D/TimaKeyStoreProvider( 4163): TimaSignature is unavailable
,D/ActivityThread( 4163): Added TimaKeyStore provider
,W/ResourcesManager( 4163): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
W/ResourcesManager( 4163): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4163): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/SSRM:n  ( 1019): SIOP:: AP = 420
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4181): MountEmulatedStorage()
,E/Zygote  ( 4181): v2
,I/libpersona( 4181): KNOX_SDCARD checking this for 10030
I/libpersona( 4181): KNOX_SDCARD not a persona,
,I/SELinux ( 4181): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4181): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4181 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 3325:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,E/SELinux ( 4181): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     (  315): Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 616us total 22.330ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/chromium( 4008): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,D/TimaKeyStoreProvider( 4181): TimaSignature is unavailable
,D/ActivityThread( 4181): Added TimaKeyStore provider
W/chromium( 4008): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 21.644ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 16.820ms
,E/Zygote  ( 4200): MountEmulatedStorage()
E/Zygote  ( 4200): v2
I/libpersona( 4200): KNOX_SDCARD checking this for 10026
I/libpersona( 4200): KNOX_SDCARD not a persona
,I/SELinux ( 4200): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4200): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 4200): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4200 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/QuickConnect( 4163): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1019): name = scon_is_running
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10121
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,D/TimaKeyStoreProvider( 4200): TimaSignature is unavailable
D/ActivityThread( 4200): Added TimaKeyStore provider
,W/libprocessgroup( 1019): failed to open /acct/uid_10090/pid_3325/cgroup.procs: No such file or directory
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/QuickConnect( 4163): Utils.setQCRunningSetting - set : 0
,I/QuickConnect( 4163): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/QuickConnect( 4163): PeriphStartReceiver.onReceive - no need to start
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/art     ( 4008): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 4008): onDetachedFromWindow called when already detached. Ignoring,
,E/Zygote  ( 4217): MountEmulatedStorage()
,E/Zygote  ( 4217): v2
I/libpersona( 4217): KNOX_SDCARD checking this for 10127
I/libpersona( 4217): KNOX_SDCARD not a persona
,I/ActivityManager( 1019): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4217 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 4217): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4217): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/PhoneWindow( 4008): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 4008): *FMB* installDecor flags : -2139027200
E/SELinux ( 4217): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SystemWebViewEngine( 4008): CordovaWebView is running on device made by: samsung
,W/art     ( 4008): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4008): Attempt to remove local handle scope entry from IRT, ignoring
,D/TimaKeyStoreProvider( 4217): TimaSignature is unavailable
,D/ActivityThread( 4217): Added TimaKeyStore provider
,W/ResourcesManager( 4217): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4217): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4217): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4217): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/OpenGLRenderer( 4008): Render dirty regions requested: true
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,D/PhoneWindow( 4008): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 4008): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  259): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1019): Focus entered window: 4008
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 4008): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 4008): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4008): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 4008): Enabling debug mode 0
,I/ActivityManager( 1019): Killing 3467:com.fmm.dm/1000 (adj 15): empty #31
,I/ActivityManager( 1019): Killing 3448:com.sec.factory.camera/1000 (adj 15): empty #32
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
,D/Finsky  ( 4200): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ActivityManager( 1019): Displayed Component not be shown by security: +1s723ms
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1019): mDVFSHelper.release()
I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{1d2a9545 u0 com.test.thalitest/.MainActivity t11} time:44095
,D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/GFX construct_block_size_descriptor_2d second part( 3949): took 2.563072ms for 0*0 texture 0
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/GFX generate_partition_tables( 3949): took 8.067914ms for 0*0 texture 0
,I/GFX raster( 3949): took 11.690205ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7849e60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb784eb18 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3949): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/Timeline( 4008): Timeline: Activity_idle id: android.os.BinderProxy@3e8435ab time:44126
,I/SamsungIME( 1833): getCurrentCandidateView
,I/System.out( 3899): INFO:Resource not found:/Common.properties Using default values
,V/AlarmManager( 1019): waitForAlarm result :8
,I/DBG_DM  ( 3189): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,D/SamsungIME( 1833): Dismiss ExpandCandiate
,W/ResourcesManager( 4181): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4181): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4181): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/SurfaceFlinger(  259): id=10 Removed uhalitest (7/8)
,I/SurfaceFlinger(  259): id=10 Removed uhalitest (-2/8)
,D/SBrowserFeatureFlag( 4217): initialized in static block : loadCscFeatureValue() succeed! 
,D/JsMessageQueue( 4008): Set native->JS mode to OnlineEventsBridgeMode
,W/ResourcesManager( 4181): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4181): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4181): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,D/Finsky  ( 4200): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3448/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3467/cgroup.procs: No such file or directory
,I/SamsungIME( 1833): getDebugLevel  : 0x4f4c
,W/ResourcesManager( 4181): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 4181): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ManifestProvider( 4217): onCreate()
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 3537): Thread[GAThread,5,main]: No campaign data found.
,W/Settings( 4200): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4200): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/NetworkSettingsReceiver( 4217): onReceive: android.intent.action.BOOT_COMPLETED
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 42274(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 22MB/33MB, paused 8.888ms total 189.814ms
,I/SamsungIME( 1833): getDebugLevel  : 0x4f4c
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3949): took 0.605052ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb78534f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78535c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3949): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/SamsungIME( 1833): KeybaordView init() : load resources
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3949): took 0.813906ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb784ff40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7850098 counterpartCT=4 counterpartW=96 counterparth=96
,I/Icing   ( 2012): updateResources: need to parse f{com.google.android.gms}
,I/AMMetaDataParserService( 3949): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/chromium( 4008): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 4008): 
,I/ActivityManager( 1019): Killing 3504:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,I/ActivityManager( 1019): Killing 3487:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #32
D/Volley  ( 4200): [628] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 4200): [621] DiskBasedCache.clear: Cache cleared.
,I/SamsungIME( 1833): getCurrentKeyboard
I/SamsungIME( 1833): getTextKeyboard
,I/System.out( 3834): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 3834): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 3834): (HTTPLog)-Static: isShipBuild true
I/System.out( 3834): (HTTPLog)-Thread-536-5547940: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 3834): (HTTPLog)-Static: isSBSettingEnabled false
,W/System.err( 4217): java.lang.NoSuchMethodException: isEnabled []
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10100
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/System.err( 4217): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 4217): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
W/System.err( 4217): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
W/System.err( 4217): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
W/System.err( 4217): 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
W/System.err( 4217): 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
W/System.err( 4217): 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
W/System.err( 4217): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 4217): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 4217): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 4217): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4217): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 4217): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 4217): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4217): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4217): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 4217): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,E/SBrowserFeatureFlag( 4217): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@5cca031
,D/SBrowserFeatureFlag( 4217): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 4217): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,I/System.out( 3834): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 3834): Tagging socket 28 with tag 1100000000000000{285212672,0} for uid -1, pid: 3834, getuid(): 10100
,D/Ads     ( 4200): Skipping gmscore version check
,D/SamsungIME( 1833): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 4200): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4200): [1] Libraries$2.run: Finished loading 1 libraries.
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4126): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Zygote  ( 4282): MountEmulatedStorage()
,E/Zygote  ( 4282): v2
I/libpersona( 4282): KNOX_SDCARD checking this for 10131
I/libpersona( 4282): KNOX_SDCARD not a persona
,I/SELinux ( 4282): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4282 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 4282): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4282): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4282): TimaSignature is unavailable
,D/ActivityThread( 4282): Added TimaKeyStore provider
,W/libprocessgroup( 1019): failed to open /acct/uid_10098/pid_3504/cgroup.procs: No such file or directory
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3949): took 0.662656ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb784ef60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb784f028 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1019): failed to open /acct/uid_10095/pid_3487/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3949): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/jxcore_app_log( 4008): JniHelper::setJavaVM(0xb7476448), pthread_self() = -1212361184
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3949): took 0.729167ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7851d30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7851e88 counterpartCT=4 counterpartW=96 counterparth=96,
,I/AMMetaDataParserService( 3949): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 4282): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4282): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4282): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4008): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4008):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4008):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4008):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4008):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4008): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11c1476 added. We now have 1 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4008): setBluetoothMacAddress: 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4008): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4008): setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,D/Finsky  ( 4200): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4008): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4008):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4008):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4008):     - Bluetooth MAC address: 08:EC:A9:50:76:27
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4008):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4008):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4008):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4008):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4008):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4008):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4008): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62d0202 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4008): addListener: New listener added - the number of listeners is now 1
,W/ResourcesManager( 4126): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4126): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4126): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4008): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4008): setDiscoveryMode: Discovery mode BLE is supported
,D/Finsky  ( 4200): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager( 1019): Killing 3553:com.fmm.ds/1000 (adj 15): empty #31
,I/chromium( 4008): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3949): took 0.528646ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb780e4d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7810f40 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3949): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{1df4f864 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:assistant
I/AMMetaDataParserService( 3949): Resource data:2131034113
,I/AMMetaDataParserService( 3949): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3949): getResourceTypeNamexml
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3949): took 0.812656ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7829f38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7810f40 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3949): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/daemonapp( 1791): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3949): took 0.810573ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7829f38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7810f40 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3949): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3553/cgroup.procs: No such file or directory
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4324): MountEmulatedStorage()
,E/Zygote  ( 4324): v2
I/libpersona( 4324): KNOX_SDCARD checking this for 10135
,I/libpersona( 4324): KNOX_SDCARD not a persona
,I/SELinux ( 4324): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4324): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4324): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4324 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
V/AlarmManager( 1019): waitForAlarm result :4
I/GFX raster( 3949): took 0.633437ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7810f40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7815718 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_DM  ( 3189): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,I/AMMetaDataParserService( 3949): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/TimaKeyStoreProvider( 4324): TimaSignature is unavailable
,D/ActivityThread( 4324): Added TimaKeyStore provider
,I/Process ( 4181): Sending signal. PID: 4181 SIG: 9
,W/ResourcesManager( 4324): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 4324): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4324): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4324): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,W/ResourcesManager( 4324): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/qtaguid ( 3834): Untagging socket 28
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 32066, reason: Periodic, SyncResult: syncAlreadyInProgress: true stats []
,I/ActivityManager( 1019): Process com.sec.android.app.sns3 (pid 4181)(adj 0) has died(24,606)
,I/art     ( 4008): Background sticky concurrent mark sweep GC freed 22063(2MB) AllocSpace objects, 10(1398KB) LOS objects, 23% free, 10MB/13MB, paused 10.187ms total 62.593ms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4345): MountEmulatedStorage()
E/Zygote  ( 4345): v2
I/libpersona( 4345): KNOX_SDCARD checking this for 10031
I/libpersona( 4345): KNOX_SDCARD not a persona
,I/SELinux ( 4345): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4345): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4345): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/ActivityManager( 1019): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4345 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,I/GFX raster( 3949): took 0.676147ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7815718 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7829ee0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3949): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,D/TimaKeyStoreProvider( 4345): TimaSignature is unavailable
,D/ActivityThread( 4345): Added TimaKeyStore provider
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3949): took 0.825677ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7851a38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7829ee0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3949): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3949): took 0.675468ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7829ee0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7809bc8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3949): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3949): took 0.682552ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7851d30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78536c8 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3949): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin,
D/SecContentProvider2( 1019): mCursor = null
,E/Zygote  ( 4362): MountEmulatedStorage()
I/libpersona( 4362): KNOX_SDCARD checking this for 10141
E/Zygote  ( 4362): v2
I/libpersona( 4362): KNOX_SDCARD not a persona
,I/ActivityManager( 1019): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4362 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,I/SELinux ( 4362): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4362): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4362): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3949): took 0.548698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb780e4d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78099e0 counterpartCT=4 counterpartW=96 counterparth=96
,W/Gmail   ( 3537): Sync started for account: account:61035162
,I/AMMetaDataParserService( 3949): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/Gmail   ( 3537): notifyAccountChanged
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3949): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3949): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3949): getResourcePackageName:assistant
I/AMMetaDataParserService( 3949): Resource data:2131034112,
D/TimaKeyStoreProvider( 4362): TimaSignature is unavailable
D/ActivityThread( 4362): Added TimaKeyStore provider
I/AMMetaDataParserService( 3949): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3949): getResourceTypeNamexml
E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3949): took 0.649322ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7815718 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb784bd60 counterpartCT=4 counterpartW=96 counterparth=96
I/Gmail   ( 3537): getAccountsCursor
I/AMMetaDataParserService( 3949): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
V/GLSActivity( 1741): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4298, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/iu.UploadsManager( 2012): End new media; added: 0, uploading: 0, time: 510 ms
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,W/ResourcesManager( 4362): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4362): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4362): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4362): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/PowerManagerService( 1019): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1019): getFinalBrightness : Summary is 15 -> 15
,D/DisplayPowerController( 1019): animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1019): [s] DisplayPowerCallbacks : onStateChanged()
,I/art     ( 1649): Explicit concurrent mark sweep GC freed 3888(162KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 766us total 51.562ms
,D/lights  ( 1019): lcd : 18 +
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/DisplayPowerController( 1019): getFinalBrightness : Summary is 15 -> 15
D/DisplayPowerController( 1019): animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/GFX raster( 3949): took 0.626563ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7815718 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78534e8 counterpartCT=4 counterpartW=96 counterparth=96
,D/lights  ( 1019): lcd : 18 -
D/lights  ( 1019): lcd : 15 +
,D/lights  ( 1019): lcd : 15 -
,D/DisplayPowerController( 1019): getFinalBrightness : Summary is 15 -> 15
D/DisplayPowerController( 1019): animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/HeadsetService( 2646): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2646): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,I/AMMetaDataParserService( 3949): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530,
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3949): took 0.659167ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7853228 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb78532f0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3949): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/CalendarSyncAdapter( 3834): Found 0 events marked dirty & lastSynced
,E/Zygote  ( 4379): MountEmulatedStorage()
,E/Zygote  ( 4379): v2
I/libpersona( 4379): KNOX_SDCARD checking this for 1000
I/libpersona( 4379): KNOX_SDCARD not a persona,
,I/SELinux ( 4379): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4379): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1019): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4379 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 4379): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3949): took 0.637292ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7829ee0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7849ee0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3949): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,I/art     ( 1741): Explicit concurrent mark sweep GC freed 35740(2MB) AllocSpace objects, 30(912KB) LOS objects, 39% free, 9MB/16MB, paused 1.998ms total 406.579ms
,D/TimaKeyStoreProvider( 4379): TimaSignature is unavailable
,D/ActivityThread( 4379): Added TimaKeyStore provider
,I/ActivityManager( 1019): Killing 3568:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,E/SMD     (  294): DCD OFF
,W/libprocessgroup( 1019): failed to open /acct/uid_10055/pid_3568/cgroup.procs: No such file or directory
,I/ActivityManager( 1019): Killing 3386:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,I/DBG_POLICYDM( 4379): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 4379): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_POLICYDM( 4379): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 4379): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 4379): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,W/libprocessgroup( 1019): failed to open /acct/uid_10008/pid_3386/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 4379): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 4379): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 4379): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 4379): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/Gmail   ( 3537): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 17987, normalSync: true
,I/DBG_POLICYDM( 4379): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,I/DBG_POLICYDM( 4379): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 4379): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 4379): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.s,amsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:assistant
I/AMMetaDataParserService( 3949): Resource data:2131034113
I/DBG_POLICYDM( 4379): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
I/AMMetaDataParserService( 3949): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3949): getResourceTypeNamexml
E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3949): took 0.826198ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7829f38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb78525b8 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_POLICYDM( 4379): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
I/DBG_POLICYDM( 4379): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
I/DBG_POLICYDM( 4379): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3949): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
I/DBG_DM  ( 3189): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3949): took 1.069635ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7829f38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb78525b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1019): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4401 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 4401): MountEmulatedStorage(),
E/Zygote  ( 4401): v2
I/libpersona( 4401): KNOX_SDCARD checking this for 10032
,I/libpersona( 4401): KNOX_SDCARD not a persona
,I/SELinux ( 4401): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4401): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4401): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
I/AMMetaDataParserService( 3949): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3949): took 0.595156ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7810f40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78525b8 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4401): TimaSignature is unavailable
,D/ActivityThread( 4401): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3949): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3949): took 1.042760ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7815718 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78525b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3949): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/Icing   ( 2012): Internal init done: storage state 0
,I/GFX raster( 3949): took 1.451874ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7851a38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78525b8 counterpartCT=4 counterpartW=96 counterparth=96
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,I/DBG_POLICYDM( 4379): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 4379): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3949): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/DBG_POLICYDM( 4379): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 4379): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 4379): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,W/jxcore-log( 4008): Initializing JXcore engine
,W/jxcore-log( 4008): JXcore engine is ready
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3949): took 0.733125ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb78525b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7810f40 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,I/AMMetaDataParserService( 3949): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/Icing   ( 2012): Post-init done
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3949): took 0.678802ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7810f40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7829f38 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,I/AMMetaDataParserService( 3949): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 4379): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 4379): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 4379): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3949): took 0.521563ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7829f38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb783ebc0 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4379): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected,
,I/DBG_POLICYDM( 4379): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/06/11:32:20
,I/AMMetaDataParserService( 3949): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/DBG_POLICYDM( 4379): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/04/15:43:18
,I/DBG_POLICYDM( 4379): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 4379): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 4379): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 4379): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 4379): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 4379): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 4379): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 4379): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 4379): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,E/SPPClientService( 4401): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 4401): [PushClientApplication] Push log off : This is Ship build version
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
,W/ContextImpl( 3949): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 ,
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity,
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/libpersona( 4428): KNOX_SDCARD checking this for 10068
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/libpersona( 4428): KNOX_SDCARD not a persona
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.sdk.cover.MODE,
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
E/Zygote  ( 4428): MountEmulatedStorage()
E/Zygote  ( 4428): v2
D/RCPManagerService( 1019): exchangeData() failure , invalid userId
I/SELinux ( 4428): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4428): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4428): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4428 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,E/SPPClientService( 4401): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:assistant
I/AMMetaDataParserService( 3949,): Resource data:2131165203
D/RCPManagerService( 1019): exchangeData() failure , invalid userId
W/ResourcesManager( 3949): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3949): getResourceName:com.android.email:xml/email_assistant_menu
I/DBG_POLICYDM( 4379): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
I/AMMetaDataParserService( 3949): getResourceTypeNamexml
E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
D/SPPClientService( 4401): PushLog.txt file is not deleted.
D/SPPClientService( 4401): PushLog.txt file is not deleted.
D/SPPClientService( 4401): ============PushLog. stop!
I/GFX construct_block_size_descriptor_2d second part( 3949): took 3.736145ms for 0*0 texture 0
I/DBG_POLICYDM( 4379): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
D/TimaKeyStoreProvider( 4428): TimaSignature is unavailable
D/ActivityThread( 4428): Added TimaKeyStore provider
I/DBG_POLICYDM( 4379): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,I/GFX generate_partition_tables( 3949): took 17.341926ms for 0*0 texture 0
,I/GFX raster( 3949): took 21.664113ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7827c78 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb79fc4e8 counterpartCT=4 counterpartW=80 counterparth=80
,E/audit   ( 1839): type=1400 msg=audit(1457102599.112:205): avc:  denied  { ioctl } for  pid=4311 comm="Thread-592" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1839):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1839): type=1300 msg=audit(1457102599.112:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=927678f8 items=0 ppid=315 ppcomm=main pid=4311 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-592" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1839): type=1320 msg=audit(1457102599.112:205): 
,I/AMMetaDataParserService( 3949): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,I/ActivityManager( 1019): Killing 3599:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX construct_block_size_descriptor_2d second part( 3949): took 2.310052ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3949): took 5.177084ms for 0*0 texture 0
,I/GFX raster( 3949): took 8.669115ms for 80*80 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7a00900 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7a009a8 counterpartCT=4 counterpartW=80 counterparth=80
,W/jxcore-log( 4008): Starting JXcore engine,
,W/ResourcesManager( 3537): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3537): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3949): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,E/Zygote  ( 4450): MountEmulatedStorage()
E/Zygote  ( 4450): v2
I/libpersona( 4450): KNOX_SDCARD checking this for 10036
I/libpersona( 4450): KNOX_SDCARD not a persona
,I/SELinux ( 4450): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4450): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4450): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4450 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 1522:com.android.defcontainer/u0a3 (adj 15): empty #31
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 4428): onCreate
,D/BadgeProvider( 4428): DatabaseHelper
,D/TimaKeyStoreProvider( 4450): TimaSignature is unavailable
,D/ActivityThread( 4450): Added TimaKeyStore provider,
,E/Zygote  ( 4466): MountEmulatedStorage()
,E/Zygote  ( 4466): v2
I/libpersona( 4466): KNOX_SDCARD checking this for 10142
,I/libpersona( 4466): KNOX_SDCARD not a persona
,I/SELinux ( 4466): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4466): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1019): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4466 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,E/SELinux ( 4466): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1019): Killing 3620:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3949): took 0.691041ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7a00900 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7a009a8 counterpartCT=4 counterpartW=80 counterparth=80
I/art     (  315): Explicit concurrent mark sweep GC freed 8701(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 619us total 29.870ms
,I/AMMetaDataParserService( 3949): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 17.291ms
,D/TimaKeyStoreProvider( 4466): TimaSignature is unavailable
,W/libprocessgroup( 1019): failed to open /acct/uid_10056/pid_3599/cgroup.procs: No such file or directory
D/ActivityThread( 4466): Added TimaKeyStore provider
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 19.727ms
,W/ResourcesManager( 4466): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/jxcore-log( 4008): Platform android
W/jxcore-log( 4008): 
W/jxcore-log( 4008): Process ARCH arm
W/jxcore-log( 4008): 
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3949): took 0.705885ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7a00900 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb784cce8 counterpartCT=4 counterpartW=80 counterparth=80
,W/libprocessgroup( 1019): failed to open /acct/uid_10003/pid_1522/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10013/pid_3620/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3949): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,W/BaseAppContext( 1741): Using Auth Proxy for data requests.
,I/ActivityManager( 1019): Killing 3361:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,V/JNIHelp ( 3537): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/libprocessgroup( 1019): failed to open /acct/uid_10014/pid_3361/cgroup.procs: No such file or directory
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3949): took 0.630885ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7a009a8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb784cce8 counterpartCT=4 counterpartW=80 counterparth=80
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,I/AMMetaDataParserService( 3949): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 28287(1366KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 22MB/33MB, paused 2.665ms total 162.633ms
I/art     ( 1019): WaitForGcToComplete blocked for 124.221ms for cause HeapTrim
,D/BadgeProvider( 4428): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/BaseAppContext( 1741): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,D/BadgeProvider( 4428): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 4428): sendNotify, [notify] : null
D/BadgeProvider( 4428): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4428): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4428): update, [UpdateCount] : 1
,W/ActivityManager( 1019): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/Launcher.Model( 1489): reloadBadges entered.
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,W/ActivityManager( 1019): getTasks: caller 10141 does not hold GET_TASKS; limiting output
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,E/Zygote  ( 4487): MountEmulatedStorage(),
I/libpersona( 4487): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4487): v2
I/libpersona( 4487): KNOX_SDCARD not a persona
I/SELinux ( 4487): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4487): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4487): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1019): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4487 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/        ( 3949): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3949): took 0.662135ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3949): Bitmap=0xb7a009a8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7829f38 counterpartCT=4 counterpartW=80 counterparth=80
,I/DBG_DM  ( 3189): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,I/Process ( 4362): Sending signal. PID: 4362 SIG: 9
,D/TimaKeyStoreProvider( 4487): TimaSignature is unavailable
,D/ActivityThread( 4487): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,I/AMMetaDataParserService( 3949): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1741): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,V/GLSActivity( 1741): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3949): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3949): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,W/ContextImpl( 3949): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,W/ActivityThread( 3537): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3537): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@23b4c9e6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3537): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1741): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity,
W/ResourcesManager( 3949): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
W/ResourcesManager( 3949): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity,
W/ResourcesManager( 3949): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
W/ResourcesManager( 3949): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer,
W/ResourcesManager( 3949): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3949): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3949): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3949): Resource data:2131099648
,E/Zygote  ( 4504): MountEmulatedStorage()
,E/Zygote  ( 4504): v2
I/libpersona( 4504): KNOX_SDCARD checking this for 1000
I/libpersona( 4504): KNOX_SDCARD not a persona
,I/SELinux ( 4504): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SA      ( 4450): [SSP] onCreated
I/SELinux ( 4504): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4504): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4504 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 3687:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,I/AMMetaDataParserService( 3949): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3949): getResourceTypeNamexml
,I/ActivityManager( 1019): Process com.android.email (pid 4362)(adj 11) has died(38,576)
,I/AMMetaDataParserService( 3949): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/TimaKeyStoreProvider( 4504): TimaSignature is unavailable
I/AMMetaDataParserService( 3949): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/ActivityThread( 4504): Added TimaKeyStore provider
,I/SA      ( 4450): [TPM] There is no property file
,I/AMMetaDataParserService( 3949): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1019): failed to open /acct/uid_10058/pid_3687/cgroup.procs: No such file or directory
,E/Zygote  ( 4524): MountEmulatedStorage(),
E/Zygote  ( 4524): v2
I/libpersona( 4524): KNOX_SDCARD checking this for 10141
I/libpersona( 4524): KNOX_SDCARD not a persona
,I/SELinux ( 4524): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4524): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4524 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/SELinux ( 4524): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SA      ( 4450): [SCU] isHaveSA() - false
,I/SA      ( 4450): [TPM] getModelProperty : null
I/SA      ( 4450): [TPM] getCSCProperty : null
,I/SA      ( 4450): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4450): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4450): [DM] TFT FEATURE: false
,I/SA      ( 4450): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4450): [DM] init START
,D/SecurityLogAgent( 4504): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4504): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4504): StateMachine : Current State = 1
D/SecurityLogAgent( 4504): BootReceiver : completed task. Failed to return wakelock . 
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3949): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/AMMetaDataParserService( 3949): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/TimaKeyStoreProvider( 4524): TimaSignature is unavailable
I/SA      ( 4450): [DM] This device is not a Vodafone
,D/ActivityThread( 4524): Added TimaKeyStore provider
,I/ActivityManager( 1019): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4539 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,E/Zygote  ( 4539): MountEmulatedStorage()
I/libpersona( 4539): KNOX_SDCARD checking this for 10148
E/Zygote  ( 4539): v2
I/libpersona( 4539): KNOX_SDCARD not a persona
,I/SELinux ( 4539): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/jxcore-log( 4008): JXcore Cordova bridge is ready!
I/jxcore-log( 4008): 
W/jxcore-log( 4008): JXcore engine is started
I/AMMetaDataParserService( 3949): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/SELinux ( 4539): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4539): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:assistant
I/AMMetaDataParserService( 3949): Resource data:2131099648
,I/org.thaliproject.p2p.ThaliPermissions( 4008): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/ActivityManager( 1019): Killing 3705:com.android.managedprovisioning/u0a20 (adj 15): empty #31
,I/AMMetaDataParserService( 3949): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3949): getResourceTypeNamexml
,I/AMMetaDataParserService( 3949): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ResourceType( 4450): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4450): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 4450): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4450): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,E/jxcore  ( 4008): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4008): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,D/TimaKeyStoreProvider( 4539): TimaSignature is unavailable
,W/ResourceType( 4450): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4450): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
D/ActivityThread( 4539): Added TimaKeyStore provider
W/ResourceType( 4450): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4450): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4450): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,I/System.out( 1741): (HTTPLog)-Static: isSBSettingEnabled false
,W/ResourceType( 4450): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,I/chromium( 4008): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/ResourceType( 4450): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 4450): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 4450): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4450): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
W/ResourceType( 4450): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4450): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4450): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75),
W/ResourceType( 4450): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75),
W/ResourceType( 4450): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 4450): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4450): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4450): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 4450): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75),
W/ResourceType( 4450): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 4450): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75),
W/ResourceType( 4450): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/System.out( 1741): KnoxVpnUidStorageknoxVpnSupported API value returned is false
W/ResourcesManager( 4524): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4524): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4524): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/qtaguid ( 1741): Tagging socket 72 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1741, getuid(): 10011
W/ResourcesManager( 4524): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/FocusedStackFrame( 1019): Set to : 0
,I/SA      ( 4450): [SCU] isHaveSA() - false
I/SA      ( 4450): support phone number id : false
I/SA      ( 4450): [DM] Supports Ref Jpn : true
I/SA      ( 4450): [DM] init END
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1019): Focused application set to: xxxx
,D/InputDispatcher( 1019): Focus left window: 4008
,I/AMMetaDataParserService( 3949): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (189 us)
,I/AMMetaDataParserService( 3949): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/PluginManager( 4008): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 56ms. Plugin should use CordovaInterface.getThreadPool().
,D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1019): mDVFSHelper.acquire()
,I/SA      ( 4450): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
E/SQLiteLog( 4539): (284) automatic index on shooting_modes(title_id)
I/SA      ( 4450): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowManager( 1019): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,I/AMMetaDataParserService( 3949): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/Launcher( 1489): onRestart, Launcher: 97296433
,I/AMMetaDataParserService( 3949): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/libprocessgroup( 1019): failed to open /acct/uid_10020/pid_3705/cgroup.procs: No such file or directory
,I/qtaguid ( 1741): Tagging socket 78 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1741, getuid(): 10011
,I/ActivityManager( 1019): Killing 3724:com.google.android.talk/u0a102 (adj 15): empty #31
,D/Launcher( 1489): onStart, Launcher: 97296433
D/Launcher.HomeView( 1489): onStart
,D/Launcher( 1489): onResume, Launcher: 97296433
,I/AMMetaDataParserService( 3949): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,D/SettingsProvider( 1019): name = kids_home_mode
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10006
W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
D/Launcher.HomeView( 1489): onResume
,I/SA      ( 4450): [OR] onReceive END
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,D/Launcher( 1489): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1019): [SO] activate (ident=0xb7c8b688, enabled=0)
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/SA      ( 4450): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4450): [ODM] queryOpenData(key= GEO_IP )
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:assistant
I/AMMetaDataParserService( 3949): Resource data:2131099648
,I/AMMetaDataParserService( 3949): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3949): getResourceTypeNamexml
,D/SensorManager( 1019): unregisterListener ::   
,I/Sensors ( 1019): AccelerometerSensor(0) setDelay : 200000000(ns)
,I/AMMetaDataParserService( 3949): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/SensorService( 1019): [SO] changed settle time [0]
D/SensorService( 1019): [SO] setDelay [200000000]
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/SensorService( 1019): [SO] activate (ident=0xb7e22798, enabled=1)
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/SensorService( 1019): [SO] AR_init
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/SA      ( 4450): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4450): [LBE] REF_JPN : true
I/SA      ( 4450): [BDC] create
D/SensorManager( 1019): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,E/Zygote  ( 4560): MountEmulatedStorage()
,I/libpersona( 4560): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4560): v2
I/libpersona( 4560): KNOX_SDCARD not a persona
I/SELinux ( 4560): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4560 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 4560): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4560): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/MenuAppsGridFragment( 1489): onResume,
,D/ActivityManager( 1019): handle home activity for 0,
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
I/WallpaperManagerService( 1019): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1019): post home show event for user 0
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/WallpaperManagerService( 1019):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1019): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/RCPManagerService( 1019): exchangeData() failure , invalid userId
I/SurfaceFlinger(  259): id=12 createSurf (540x960),1 flag=4, Mauncher
,D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/AMMetaDataParserService( 3949): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1019): Focus entered window: 1489
,I/SA      ( 4450): [DBMV2] getEmailID
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1489): log_dcs ThreadedRenderer::initialize entered! 
,I/SA      ( 4450): [DBMV2] getDataV02ForItems
,I/SA      ( 4450): [SSP] query invoked
,D/TimaKeyStoreProvider( 4560): TimaSignature is unavailable
,D/ActivityThread( 4560): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3949): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/AMMetaDataParserService( 3949): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/SA      ( 4450): [SCU] get signed id from samsung account2.0 DB.
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3949): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/Launcher( 1489): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/libprocessgroup( 1019): failed to open /acct/uid_10102/pid_3724/cgroup.procs: No such file or directory
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/SA      ( 4450): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4450): [BDC] destroy
,I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
,W/IInputConnectionWrapper( 4008): showStatusIcon on inactive InputConnection
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SamsungIME( 1833): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/ActivityManager( 1019): Killing 3748:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3949): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/AndroidHttpClient( 3537): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Android-GmailProvider/5010020 (sw360dp; 240dpi) (a3ulte LRX22G); gzip
D/AndroidHttpClient( 3537): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = POST
D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,I/ActivityManager( 1019): Killing 3764:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,I/System.out( 3537): Thread-498(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/ActivityManager( 1019): Killing 3788:com.wssnps/1000 (adj 15): empty #31
,I/System.out( 3537): Thread-498(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3537): Thread-498(ApacheHTTPLog):isShipBuild true
I/System.out( 3537): Thread-498(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3537): Thread-498(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10099
,I/Timeline( 1489): Timeline: Activity_idle id: android.os.BinderProxy@139557d7 time:47953
,D/PersonaManager( 1019): isKioskContainerExistOnDevice
,I/ActivityManager( 1019): Displayed Component not be shown by security: +236ms
,I/qtaguid ( 3537): Tagging socket 59 with tag 1010000000000000{269484032,0} for uid -1, pid: 3537, getuid(): 10099
,I/splitIntent( 1019): Queue : background intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart  false.
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:assistant
I/AMMetaDataParserService( 3949): Resource data:2131099648
,I/AMMetaDataParserService( 3949): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3949): getResourceTypeNamexml
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3949): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3949): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SensorService( 1019): [SO] Reset Rotation Old [100], Init [1]
,I/AMMetaDataParserService( 3949): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/BadgeProvider( 4428): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
I/AMMetaDataParserService( 3949): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1019): getTasks: caller 10142 does not hold GET_TASKS; limiting output
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/BadgeProvider( 4428): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4428): sendNotify, [notify] : null
D/BadgeProvider( 4428): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4428): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4428): update, [UpdateCount] : 1
,I/Process ( 4466): Sending signal. PID: 4466 SIG: 9
,D/Launcher.Model( 1489): reloadBadges entered.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/AMMetaDataParserService( 3949): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/NearbySettings( 1367): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 2140): Starting #5
,I/Hs20UtilService( 2140): Message received 5007
,I/qtaguid ( 3537): Tagging socket 63 with tag 1010000000000000{269484032,0} for uid -1, pid: 3537, getuid(): 10099
,I/NearbySettings( 1367): MountReceiver.onReceive - Keep current state
,I/AMMetaDataParserService( 3949): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:assistant
I/AMMetaDataParserService( 3949): Resource data:2131099648
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/AMMetaDataParserService( 3949): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3949): getResourceTypeNamexml
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3949): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1019): Process com.android.exchange (pid 4466)(adj 15) has died(35,581)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3949): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3949): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3949): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/AMMetaDataParserService( 3949): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/SensorService( 1019): [SO] currT = 48211099000, prevT = 47781103000, diff = 429996000, [-0.383 0.153 9.902]
,D/SensorService( 1019): [SO] -0.383 0.153 9.902
D/SensorService( 1019): [SO] [100 -> 255]
,D/accuweather( 1748): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionAPPWIDGET_UPDATE
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7,
,W/ActivityManager( 1019): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/daemonapp( 1791): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,I/AMMetaDataParserService( 3949): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/accuweather( 1748): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1748): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1748): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1748): [KK AccuPhone]>>> WCW:42 [0:0] weather widget id size = 1
,D/accuweather( 1748): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionAPPWIDGET_UPDATE
D/accuweather( 1748): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1748): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/daemonapp( 1791): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3949): getResourcePackageName:assistant
I/AMMetaDataParserService( 3949): Resource data:2131099648
,I/AMMetaDataParserService( 3949): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3949): getResourceTypeNamexml
,D/daemonapp( 1791): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 3949): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/daemonapp( 1791): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 3949): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/daemonapp( 1791): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1748): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,D/accuweather( 1748): [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,D/accuweather( 1748): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,D/accuweather( 1748): [KK AccuPhone]>>> UIM:964 [0:0]  cUI : cnt = 0
,D/accuweather( 1748): [KK AccuPhone]>>> UIM:983 [0:0]  composeEmptyCityUI : true
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/accuweather( 1748): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 15 43
,E/accuweather( 1748): [KK AccuPhone]>>> UIM:967 [0:0] ========>>> mRefreshManagerisRefreshCompleted() = true
,I/AMMetaDataParserService( 3949): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/DBG_DM  ( 3189): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/AMMetaDataParserService( 3949): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/accuweather( 1748): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionAPPWIDGET_UPDATE
,D/accuweather( 1748): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 1748): [KK AccuPhone]>>> UIMEM:89 [0:0] getInstance
,D/accuweather( 1748): [KK AccuPhone]>>> UIMEM:77 [0:0] UIManager : create ui manager
D/accuweather( 1748): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 1748): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1791): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 3949): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/accuweather( 1748): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1791): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/ActivityManager( 1019): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/accuweather( 1748): [KK AccuPhone]>>> DBH:3426 [0:0] gADWI : count = 0
,I/AMMetaDataParserService( 3949): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/daemonapp( 1791): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
W/ContextImpl( 3949): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3949): Reso,urce data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3949): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
D/accuweather( 1748): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{30706746 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t10} time:48386
D/accuweather( 1748): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
I/SurfaceFlinger(  259): id=11 Removed NainActivit (7/8)
I/SurfaceFlinger(  259): id=11 Removed NainActivit (-2/8)
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:assistant
I/AMMetaDataParserService( 3949): Resource data:2131165197
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ResourcesManager( 3949): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3949): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3949): getResourceTypeNamexml
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3788/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3748/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3764/cgroup.procs: No such file or directory
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.daemonapp
I/AMMetaDataParserService( 3949): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/daemonapp( 1791): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1791): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1791): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/AMMetaDataParserService( 3949): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/daemonapp( 1791): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1791): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/ScreenOrientationListener( 4008): Removing an inexistent observer!
,D/daemonapp( 1791): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,I/AMMetaDataParserService( 3949): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/comsamsunglog( 1791): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1791): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1791): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1791): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1791): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1791): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:widgetappapheroaccuweather, cp:Accuweather, aRS:false
,D/daemonapp( 1791): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1791): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,I/AMMetaDataParserService( 3949): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3949): getResourcePackageName:assistant
I/AMMetaDataParserService( 3949): Resource data:2131165197
,I/AMMetaDataParserService( 3949): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3949): getResourceTypeNamexml
,D/daemonapp( 1791): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1791): [MSC_Daemon]>>> WDSM:140 [0:0] Widget flag autoRefreshSet :  false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,I/AMMetaDataParserService( 3949): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/System.out( 1741): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,I/AMMetaDataParserService( 3949): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/System.out( 1741): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1741): Tagging socket 79 with tag 3000060200000000{805307906,0} for uid 10011, pid: 1741, getuid(): 10011
,E/Watchdog( 1019): !@Sync 1
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1367): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1367): DMSUtil.isNetworkConnected - flag-null, state-null
,D/SettingsProvider( 1019): name = audio_safe_volume_state
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/Hs20UtilService( 2140): Starting #6
I/NearbySettings( 1367): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/Hs20UtilService( 2140): Message received 5007
,I/NearbySettings( 1367): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1367): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1367): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1367): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1367): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 2140): Starting #7
,D/SIP     ( 1455): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,I/Hs20UtilService( 2140): Message received 5007
,E/File    ( 1455): fail readDirectory() errno=2
,D/WifiStateMachine( 1019): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1019): uri = 15 selection = getToastGravityEnabledState
D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1019): mCursor = null
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3949): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3949): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=4, Uoast
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/qtaguid ( 1741): Tagging socket 83 with tag 3000060200000000{805307906,0} for uid 10011, pid: 1741, getuid(): 10011
,D/PowerManagerService( 1019): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019
,D/DisplayPowerController( 1019): getFinalBrightness : Summary is 31 -> 31
,D/DisplayPowerController( 1019): animation target = 31, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1019): [s] DisplayPowerCallbacks : onStateChanged()
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SRIB_DCS( 1175): log_dcs ThreadedRenderer::initialize entered! 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:assistant
I/AMMetaDataParserService( 3949): Resource data:2131165197
,I/AMMetaDataParserService( 3949): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3949): getResourceTypeNamexml
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/lights  ( 1019): lcd : 31 +
D/DisplayPowerController( 1019): getFinalBrightness : Summary is 31 -> 31
D/DisplayPowerController( 1019): animation target = 31, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/splitIntent( 1019): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1019): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1019): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3949): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/lights  ( 1019): lcd : 31 -
,D/DisplayPowerController( 1019): getFinalBrightness : Summary is 31 -> 31
,D/DisplayPowerController( 1019): animation target = 31, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,I/AMMetaDataParserService( 3949): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1741): callingUid 10011, callindPid: 1741
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3949): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1741): [238] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3949): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1741): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
W/ContextImpl( 3949): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.Pho,toNote
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2012): Restart initialization of location
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3949): getResourcePackageName:assistant
I/AMMetaDataParserService( 3949): Resource data:2131099648
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 3949): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3949): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3949): getResourceTypeNamexml
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1741): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3949): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,W/GCoreFlp( 1741): No location to return for getLastLocation()
,W/FusedLocationProvider( 1741): location=null
,I/PCWCLIENTTRACE_PushUtil( 3520): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 3520): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 3520): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3520): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1019): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=15, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
I/splitIntent( 1019): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4599): MountEmulatedStorage()
,I/libpersona( 4599): KNOX_SDCARD checking this for 10108
E/Zygote  ( 4599): v2
I/libpersona( 4599): KNOX_SDCARD not a persona
I/SELinux ( 4599): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4599 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4599): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4599): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3664): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Mar 04 15:43:21 GMT+01:00 2016
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/accuweather( 1748): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3664): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3664): KLMSIntentService(): onCreate()
,D/daemonapp( 1791): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,D/accuweather( 1748): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1748): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1748): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
I/KLMS-2.5.123: ( 3664): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/AMMetaDataParserService( 3949): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
D/accuweather( 1748): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
D/TimaKeyStoreProvider( 4599): TimaSignature is unavailable
,D/ActivityThread( 4599): Added TimaKeyStore provider
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,I/KLMS-2.5.123: ( 3664): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/accuweather( 1748): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE,
,I/KLMS-2.5.123: ( 3664): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/accuweather( 1748): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
W/ContextImpl( 3949): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,I/KLMS-2.5.123: ( 3664): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,D/SecurityLogAgent( 4504): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4504): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 4504): StateMachine : Current State = 1
,D/SecurityLogAgent( 4504): StateMachine : Changed Current State = 1
,I/DBG_POLICYDM( 4379): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3664): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3664): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3664): NetworkChangeOperations(): uploadRequestLog().START 
,E/Zygote  ( 4615): MountEmulatedStorage()
I/libpersona( 4615): KNOX_SDCARD checking this for 10077
E/Zygote  ( 4615): v2
I/libpersona( 4615): KNOX_SDCARD not a persona
I/SELinux ( 4615): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4615 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4615): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4615): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3664): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3664): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3664): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 4615): TimaSignature is unavailable,
D/ActivityThread( 4615): Added TimaKeyStore provider
,I/DBG_POLICYDM( 4379): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4379): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 4379): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:assistant
I/AMMetaDataParserService( 3949): Resource data:2131165220
,W/ResourcesManager( 3949): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3949): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3949): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3949): getResourceTypeNamexml
,E/SPPClientService( 4401): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/AMMetaDataParserService( 3949): Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
,I/SA      ( 4450): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 4450): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 4450): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 4379): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,E/SMD     (  294): DCD OFF
,I/qtaguid ( 1741): Untagging socket 79
,I/DBG_POLICYDM( 4379): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/SA      ( 4450): [SLFUCHKMGR] constructor called
,W/art     ( 4379): Suspending all threads took: 51.629ms
,I/SA      ( 4450): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 4450): [OR] == isSIMCardReady false ==
,I/DBG_DM  ( 3189): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
,I/MusicStore( 4599): Database version: 104
,I/AMMetaDataParserService( 3949): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
I/iu.SyncManager( 2012): SYNC; picasa accounts
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts,
,D/NetworkLogImpl( 2012): Loaded NetworkSpeedPredictor
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
I/iu.Environment( 2012): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml,
I/SA      ( 4450): [SCU] == networkStateCheck == true
I/SA      ( 4450): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4450): isChinaCountryCode : false
I/SA      ( 4450): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 4450): [OR] == networkStateCheck true ==
,I/DBG_POLICYDM( 4379): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/iu.UploadsManager( 2012): num queued entries: 0
I/iu.UploadsManager( 2012): num updated entries: 0
I/iu.SyncManager( 2012): NEXT; no task
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/Zygote  ( 4639): MountEmulatedStorage()
E/Zygote  ( 4639): v2
I/libpersona( 4639): KNOX_SDCARD checking this for 10110
I/libpersona( 4639): KNOX_SDCARD not a persona
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4639 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4639): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SA      ( 4450): [OR] GetMyCountryZoneTask
E/DBG_POLICYDM( 4379): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
I/SA      ( 4450): [OR] onReceive END
,I/SELinux ( 4639): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4639): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,V/DownloadManager( 1230): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 4379): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2( 1019): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1019): mCursor = null
,I/SA      ( 4450): [SRS] prepareGetMyCountryZone
,E/Zygote  ( 4655): MountEmulatedStorage(),
E/Zygote  ( 4655): v2
I/libpersona( 4655): KNOX_SDCARD checking this for 10009
I/libpersona( 4655): KNOX_SDCARD not a persona
,I/SELinux ( 4655): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4655 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 4655): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4655): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/SA      ( 4450): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 4450): [SSP] query invoked
,I/ActivityManager( 1019): Killing 3808:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4639): TimaSignature is unavailable
,D/ActivityThread( 4639): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings,.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection,
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
W/ContextImpl( 3949): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications,
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParser,Service( 3949): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
D/TimaKeyStoreProvider( 4655): TimaSignature is unavailable
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings,.ChooseLockSignature
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
D/ActivityThread( 4655): Added TimaKeyStore provider
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3808/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Display
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.CryptKeeper
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
W/ResourcesManager( 4599): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
W/ResourcesManager( 4599): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SViewColor
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.SearchActivity
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
,I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
,I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3949): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3949): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3949): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
I/SA      ( 4450): [TPMU] GetMccFromDB : null
I/SA      ( 4450): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4450): [TPM] isNoProxy(default) : true
E/File    ( 4450): fail readDirectory() errno=2
,V/JNIHelp ( 4599): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/GCoreUlr( 1741): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1741): DispatchingService.onCreate()
,I/qtaguid ( 3537): Untagging socket 59
,I/System.out( 3537): SyncAdapterThread-1 calls detatch()
,W/ActivityThread( 4599): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4599): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12af58b9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4599): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4599): GMSCore installation verified
,I/DBG_POLICYDM( 4379): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/DBG_POLICYDM( 4379): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/ConfigStore( 4599): Config Database version: 1
,W/ContextImpl( 2907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{2ddcdadd u0 com.android.settings/.wifi.WifiCredService}
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 35017(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 24MB/36MB, paused 2.828ms total 180.024ms
,I/DBG_DM  ( 3189): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,V/GLSActivity( 1741): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Process ( 2907): Sending signal. PID: 2907 SIG: 9
,I/DBG_DM  ( 3189): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,E/DBG_DM  ( 3189): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,I/DBG_DM  ( 3189): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,I/GCoreUlr( 1741): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1741): Unbound from all location providers
,I/GCoreUlr( 1741): Place inference reporting - stopped
,I/GCoreUlr( 1741): DispatchingService.onDestroy()
,I/GCoreUlr( 1741): Stopping handler for UlrDispSvcFast
,I/ActivityManager( 1019): Process com.sec.android.app.sysscope (pid 2907)(adj 0) has died(24,579)
,I/GCoreUlr( 1741): Unbound from all location providers
,I/GCoreUlr( 1741): Place inference reporting - stopped
,D/WaitQueueForNetworkActivate( 4655): notifyNetworkActivated
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4599): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ContextImpl( 4655): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1019): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4599): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4599): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,V/GLSActivity( 1741): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4639): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4639): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/DBG_DM  ( 3189): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 12 sec
,I/DBG_DM  ( 3189): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3189): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1019): getStreamVolume 3 index 0
,I/MediaRouter( 4599): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4639): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4639): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/DBG_DM  ( 3189): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{394f24e u0 com.samsung.android.providers.context/.ContextService}
,I/DBG_DM  ( 3189): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/NetworkMonitor( 4599): type=WIFI subType= reason=null isConnected=true
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3189): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 3,
,E/Zygote  ( 4692): MountEmulatedStorage()
E/Zygote  ( 4692): v2
I/libpersona( 4692): KNOX_SDCARD checking this for 10001
I/libpersona( 4692): KNOX_SDCARD not a persona
,I/SELinux ( 4692): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4692 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4692): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 4692): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3189): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,I/DBG_DM  ( 3189): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,D/AndroidHttpClient( 1649): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Android-GData-Contacts/1.3 (a3ulte LRX22G); gzip
,D/AndroidHttpClient( 1649): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
I/System.out( 1649): Thread-138(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 1649): Thread-138(ApacheHTTPLog):isSBSettingEnabled false,
I/System.out( 1649): Thread-138(ApacheHTTPLog):isShipBuild true
I/System.out( 1649): Thread-138(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 1649): Thread-138(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/DBG_DM  ( 3189): [IlIlllIlllllIlIllllI(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [3]
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,D/TimaKeyStoreProvider( 4692): TimaSignature is unavailable
D/ActivityThread( 4692): Added TimaKeyStore provider
,I/qtaguid ( 1649): Tagging socket 33 with tag 1244000400000000{306446340,0} for uid -1, pid: 1649, getuid(): 10011
,D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor( 4599): type=WIFI subType= reason=null isConnected=true
,I/DBG_DM  ( 3189): [com.wssyncmldm.llIIllllIIlllIIIIlll(1140/handleMessage)] 
I/DBG_DM  ( 3189): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 3189): [com.wssyncmldm.XDMService(685/llIIlIlIIIllIIIIIllI)] 
,I/DBG_DM  ( 3189): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,I/ActivityManager( 1019): Killing 3850:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,I/DBG_DM  ( 3189): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 3189): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3189): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3189): [com.wssyncmldm.ui.XUIFotaPostponeActivity(501/llIIIIlllllIIllIIllI)] 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 4655): AutoUpdateManager:IDLE:execute
,I/DBG_DM  ( 3189): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,D/InitializeManagerStateMachine( 4655): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 4655): exit::IDLE
D/InitializeManagerStateMachine( 4655): entry::NETWORK_CHECK
,I/DBG_DM  ( 3189): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
,D/InitializeManagerStateMachine( 4655): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 4655): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4655): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4655): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4655): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4655): entry::SUCCESS
D/hcjo    ( 4655): AutoUpdateManager:INITCHECK:onInitializeSuccess
,W/libprocessgroup( 1019): failed to open /acct/uid_10065/pid_3850/cgroup.procs: No such file or directory
,D/hcjo    ( 4655): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 4655): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 4655): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/qtaguid ( 1649): Tagging socket 41 with tag 1244000400000000{306446340,0} for uid -1, pid: 1649, getuid(): 10011
,I/WebViewFactory( 4639): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,I/LibraryLoader( 4639): Loading: webviewchromium
,I/LibraryLoader( 4639): Time to load native libraries: 6 ms (timestamps 596-602)
,I/LibraryLoader( 4639): Expected native library version number "",actual native library version number ""
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 1019): showStatusBarByNotification() mOpenByNotification=false
,E/Zygote  ( 4726): MountEmulatedStorage()
,E/Zygote  ( 4726): v2
I/libpersona( 4726): KNOX_SDCARD checking this for 1000
I/libpersona( 4726): KNOX_SDCARD not a persona
,I/SELinux ( 4726): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4726): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1019): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4726 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
V/WebViewChromiumFactoryProvider( 4639): Binding Chromium to main looper Looper (main, tid 1) {3fcf477b}
I/ActivityManager( 1019): Killing 3934:com.samsung.helphub/1000 (adj 15): empty #31
I/LibraryLoader( 4639): Expected native library version number "",actual native library version number ""
I/chromium( 4639): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
W/ResourcesManager( 1175): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SELinux ( 4726): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  315): Explicit concurrent mark sweep GC freed 8710(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 736us total 39.815ms
I/BrowserStartupController( 4639): Initializing chromium process, renderers=0
I/art     ( 3537): Explicit concurrent mark sweep GC freed 46565(1494KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 970us total 56.728ms
W/art     ( 4639): Attempt to remove local handle scope entry from IRT, ignoring
,I/Gmail   ( 3537): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 18039, normalSync: true
,I/Gmail   ( 3537): lowestBackward conversation id 0
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 17.678ms
,W/chromium( 4639): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 4639): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium( 4639): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 4639): Requires BLUETOOTH permission
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 17.538ms,
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3934/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4726): TimaSignature is unavailable
,D/ActivityThread( 4726): Added TimaKeyStore provider
,I/Adreno-EGL( 4639): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4639): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4639): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4639): Local Branch: 
I/Adreno-EGL( 4639): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4639): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4639):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/KnoxNotification( 1175): ----- inflateViews : modified publicViewLocal -----
,D/InitializeManagerStateMachine( 4655): exit::SUCCESS
D/InitializeManagerStateMachine( 4655): entry::IDLE
,I/ActivityManager( 1019): Killing 3949:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,D/KnoxNotification( 1175): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1175): PersonaID is invalid or persona doesn't exists. : 0
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
,I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/NSApplication( 4639): Starting up...
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DIAGMON_AGENT( 4726): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,D/QuickConnect( 4163): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 4163): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 4163): PeriphStartReceiver.onReceive - no need to start
,I/ActivityManager( 1019): Killing 4045:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3949/cgroup.procs: No such file or directory
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 3537): notifyAccountChanged
,I/Gmail   ( 3537): getAccountsCursor
,I/Gmail   ( 3537): notifyAccountChanged
,V/GLSActivity( 1741): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Gmail   ( 3537): Sync complete for account: account:61035162
,I/Gmail   ( 3537): getAccountsCursor
,V/GLSActivity( 1741): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SensorService( 1019): [SO] -0.383 0.153 9.902
,I/ActivityManager( 1019): Killing 4020:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,I/DIAGMON_AGENT( 4726): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 4726): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4045/cgroup.procs: No such file or directory
I/DIAGMON_AGENT( 4726): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 4726): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 4726): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 4726): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4020/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 4379): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 4379): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 4379): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 4379): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 4450): [RC New] Execute method=[GET] start
,I/DBG_POLICYDM( 4379): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4767 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 4767): MountEmulatedStorage()
I/libpersona( 4767): KNOX_SDCARD checking this for 10008
E/Zygote  ( 4767): v2
I/libpersona( 4767): KNOX_SDCARD not a persona
,I/SELinux ( 4767): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4767): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4767): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/SA      ( 4450): [RC New] Security=[true],
,I/System.out( 4450): Thread-665(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 4450): Thread-665(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 4450): Thread-665(ApacheHTTPLog):isShipBuild true
I/System.out( 4450): Thread-665(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4450): Thread-665(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10036
,D/TimaKeyStoreProvider( 4767): TimaSignature is unavailable
,D/ActivityThread( 4767): Added TimaKeyStore provider
,I/qtaguid ( 1649): Untagging socket 33
,I/System.out( 1649): GDataFeedFetcher calls detatch()
,I/ActivityManager( 1019): Killing 4073:com.sec.knox.bridge/1000 (adj 15): empty #31
,I/FOTA_Client( 4767): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/ValidateNoPeople( 1019): mEvictionCount: 0,
,I/FOTA_Client( 4767): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 4767): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/FOTA_Client( 4767): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/splitIntent( 1019): Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,I/ActivityManager( 1019): Killing 4092:com.sec.android.app.mt/1000 (adj 15): empty #31
,D/AndroidHttpClient( 1649): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Android-GData-Contacts/1.3 (a3ulte LRX22G); gzip
D/AndroidHttpClient( 1649): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 1649): Thread-140(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 1649): Thread-140(ApacheHTTPLog):isShipBuild true
I/System.out( 1649): Thread-140(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 1649): Thread-140(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/qtaguid ( 1649): Tagging socket 33 with tag 1144000400000000{289669124,0} for uid -1, pid: 1649, getuid(): 10011
,I/splitIntent( 1019): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
,I/splitIntent( 1019): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4788): MountEmulatedStorage()
I/libpersona( 4788): KNOX_SDCARD checking this for 10058
E/Zygote  ( 4788): v2
I/libpersona( 4788): KNOX_SDCARD not a persona
I/SELinux ( 4788): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4788 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4788): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4788): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/FOTA_Client( 4767): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/daemonapp( 1791): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1791): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1791): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/daemonapp( 1791): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1791): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo,
,D/daemonapp( 1791): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/TimaKeyStoreProvider( 4788): TimaSignature is unavailable
,D/ActivityThread( 4788): Added TimaKeyStore provider
,I/FOTA_Client( 4767): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
D/comsamsunglog( 1791): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1791): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
D/comsamsunglog( 1791): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1791): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1791): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1791): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1791): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1791): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1791): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1791): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1791): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/KLMS-2.5.123: ( 3664): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Fri Mar 04 15:43:23 GMT+01:00 2016
,E/daemonapp( 1791): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/SecurityLogAgent( 4504): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4504): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4504): StateMachine : Current State = 1
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4073/cgroup.procs: No such file or directory
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4092/cgroup.procs: No such file or directory
,I/KLMS-2.5.123: ( 3664): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3664): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3664): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/Zygote  ( 4808): MountEmulatedStorage()
,E/Zygote  ( 4808): v2
I/libpersona( 4808): KNOX_SDCARD checking this for 10153
I/libpersona( 4808): KNOX_SDCARD not a persona,
,D/comdaemonstockapp( 1791): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
I/SELinux ( 4808): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/comdaemonstockapp( 1791): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,I/SELinux ( 4808): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4808): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3664): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/ActivityManager( 1019): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4808 uid=10153 gids={50153, 9997} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3664): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,I/KLMS-2.5.123: ( 3664): KLMSIntentService(): TIME_CHANGED
,I/KLMS-2.5.123: ( 3664): StateImplV2(): dateTimeChanged().START : Fri Mar 04 15:43:23 GMT+01:00 2016
I/SA      ( 4450): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/ExternalOEMControlProvider( 4788): onCreate
,D/TimaKeyStoreProvider( 4808): TimaSignature is unavailable
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 4808): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3664): StateImplV2(): dateTimeChanged().END
,D/accuweather( 1748): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1748): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KLMS-2.5.123: ( 3664): KLMSIntentService(): onDestroy()
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ Time Manager ( 4788): Time Difference not stored. TIME_DIFFERENCE
,W/ResourcesManager( 4808): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 4824): MountEmulatedStorage()
E/Zygote  ( 4824): v2
I/libpersona( 4824): KNOX_SDCARD checking this for 10081
I/libpersona( 4824): KNOX_SDCARD not a persona
I/SELinux ( 4824): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
D/PackageManager( 1019): [MSG] SEND_PENDING_BROADCAST
,I/ActivityManager( 1019): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4824 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4824): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4824): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4833): MountEmulatedStorage(),
E/Zygote  ( 4833): v2
,I/libpersona( 4833): KNOX_SDCARD checking this for 10041
I/SELinux ( 4833): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4833): KNOX_SDCARD not a persona
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4833 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
I/SELinux ( 4833): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4833): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/qtaguid ( 1649): Untagging socket 33
I/System.out( 1649): GDataFeedFetcher calls detatch()
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4824): TimaSignature is unavailable
,D/ActivityThread( 4824): Added TimaKeyStore provider
,E/Zygote  ( 4849): MountEmulatedStorage()
,E/Zygote  ( 4849): v2
I/libpersona( 4849): KNOX_SDCARD checking this for 1000
I/libpersona( 4849): KNOX_SDCARD not a persona
,I/SELinux ( 4849): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4849 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4849): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4849): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SQLiteLog( 1697): (284) automatic index on sqlite_sq_B7B19948(STAT_DATA_ID)
,E/SQLiteLog( 1697): (284) automatic index on sqlite_sq_B78B2CD8(STAT_DATA_ID)
,D/TimaKeyStoreProvider( 4833): TimaSignature is unavailable
,D/ActivityThread( 4833): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 4849): TimaSignature is unavailable
,D/ActivityThread( 4849): Added TimaKeyStore provider
,W/ResourcesManager( 4824): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 4824): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4824): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4824): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4824): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,W/IntentResolver( 1019): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.PACKAGE_CHANGED
,I/PageBuddyNotiSvc( 4135): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,I/CheckinService( 2012): Checkin interval check for package: unspecified last checkin: 1456599118758 min interval config: 0 actual interval: 503485166
,D/RegisteredServicesCache( 1443): empty dynamic service
,W/ResourcesManager( 4833): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4833): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4833): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4833): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4833): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1019): Killing 3899:com.vlingo.midas/u0a28 (adj 15): empty #31
,D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1019): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService( 1019): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager( 1019): Killing 4217:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
,D/WallpaperManager( 1489): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1489): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4871): MountEmulatedStorage()
E/Zygote  ( 4871): v2
I/libpersona( 4871): KNOX_SDCARD checking this for 10087
I/libpersona( 4871): KNOX_SDCARD not a persona
,I/SELinux ( 4871): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4871): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1019): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=4871 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4871): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimeService( 4849): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1457102604189
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/        ( 4849): TimeServiceNative: User Time to be set is 1457102604189
,D/QC-time-services( 4849): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4849): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4849): Lib:time_genoff_operation: pargs->ts_val = 1457102604189
,D/QC-time-services(  333): Daemon: Connection accepted:time_genoff
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/QC-time-services( 4849): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  333): Daemon:Received base = 2, unit = 1, operation = 0,value = 1457102604189
D/QC-time-services(  333): Daemon:genoff_opr: Base = 2, val = 1457102604189, operation = 0
,D/QC-time-services(  333): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/30/70 18:20:10
D/QC-time-services(  333): Daemon:Value read from RTC seconds = 20888410000
D/QC-time-services(  333): Daemon:new time 1457102604189 
D/QC-time-services(  333): Daemon: delta 1436214194189 genoff 1436214194189 
D/QC-time-services(  333): Daemon:genoff_persistent_update: Writing genoff = 1436214194189 to memory
D/QC-time-services(  333): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  333): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/PowerManagerService( 1019): [s] UserActivityState : 2 -> 4
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 4871): TimaSignature is unavailable
,D/ActivityThread( 4871): Added TimaKeyStore provider
,I/PowerManagerService( 1019): [PWL] On : 0 (51881 ms ago)
,I/PowerManagerService( 1019): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
,I/PowerManagerService( 1019): [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1019, ws=WorkSource{10049}) (elapsedTime=3169)
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/QC-time-services(  333): Updating the TOD offset
D/QC-time-services(  333): Daemon:genoff_persistent_update: Writing genoff = 1436214194189 to memory
D/QC-time-services(  333): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  333): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  333): Daemon:Update to modem bit set
D/QC-time-services(  333): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  333): Daemon: Base = 2, Value being sent to MODEM = 1120249394189
,E/QC-time-services( 4849): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  333): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  333): Daemon: Time-services: Waiting to acceptconnection
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 33374(1703KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 24MB/36MB, paused 2.682ms total 293.047ms,
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
,W/ResourceType( 1019): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Mms/MmsApp( 4833): [start]    onCreate() consume time = 0.0
,I/ActivityManager( 1019): Killing 4200:com.android.vending/u0a26 (adj 15): empty #31
,E/SQLiteLog( 1697): (284) automatic index on sqlite_sq_B7B35758(STAT_DATA_ID)
,E/SQLiteLog( 1697): (284) automatic index on sqlite_sq_B78C2080(STAT_DATA_ID)
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1019): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SettingsProvider( 1019): name = next_alarm_formatted
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10081
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
,V/BackupManagerService( 1019): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 1019): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@36880640
D/SettingsProvider( 1019): ret = -1
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/GCoreNlp( 1741): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/art     ( 4833): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 124.532ms
E/SMD     (  294): DCD OFF
,W/art     ( 4824): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 141.147ms
,D/PowerManagerService( 1019): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1019) eventTime = 52190
,D/PowerManagerService( 1019): [s] UserActivityState : 4 -> 1
,D/PowerManagerService( 1019): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019 (0x0)
,D/PowerManagerService( 1019): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1019, ws=WorkSource{10049}) (elapsedTime=3484)
,D/DocsApplication( 4871): Installing DEX configuration.
,I/SA      ( 4450): [RC New] [v2liruge] api execute + 1037
,I/SA      ( 4450): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 4450): AsyncTask #1 calls detatch()
,D/DexInstaller( 4871): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper( 4871): Provided clientMode=RELEASE, packageInfo=PackageInfo{35d500f2 com.google.android.apps.docs}
,I/SA      ( 4450): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 4450): [OCP] update openData : PL
,W/libprocessgroup( 1019): failed to open /acct/uid_10127/pid_4217/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10028/pid_3899/cgroup.procs: No such file or directory
,D/TAG     ( 4871): onCreate()
,I/SA      ( 4450): [TPMU] getNetworkMcc : 
,I/SA      ( 4450): [SCU] saveMccToPreferece Start
I/SA      ( 4450): [SCU] RegionMCC : 260
I/SA      ( 4450): [SSP] query invoked
,W/libprocessgroup( 1019): failed to open /acct/uid_10026/pid_4200/cgroup.procs: No such file or directory
D/LocationProviderProxy( 1019): applying state to connected service
,D/LocationProviderProxy( 1019): applying state to connected service
,I/SA      ( 4450): [TPMU] GetMccFromDB : null
I/SA      ( 4450): [SCU] getMccFromPreferece mcc = 260
W/art     ( 4833): Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 102.538ms
I/SA      ( 4450): [SCU] saveMccToPreferece End
,I/SA      ( 4450): [RC New] executeRequest [v2liruge] end. 1128
I/SA      ( 4450): [RC New] Execute end
,I/SA      ( 4450): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 4450): [OR] GetMyCountryZoneTask Success
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/CrossAppStateProvider( 4871): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/Mms/ArtClassLoader( 4833): init before art
,D/Mms/TelephonyPermission( 4833): start operation mode monitor
,E/Zygote  ( 4892): MountEmulatedStorage()
E/Zygote  ( 4892): v2
I/libpersona( 4892): KNOX_SDCARD checking this for 10090
I/libpersona( 4892): KNOX_SDCARD not a persona
,I/SELinux ( 4892): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=4892 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 4324:com.sec.android.app.camera/u0a135 (adj 15): empty #31
I/SELinux ( 4892): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4892): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4892): TimaSignature is unavailable
,D/ActivityThread( 4892): Added TimaKeyStore provider
,W/ResourcesManager( 4833): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission( 4833): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 4833): isDefault true
,D/Mms/MmsApp( 4833): onCreate() com.android.mms
,W/libprocessgroup( 1019): failed to open /acct/uid_10135/pid_4324/cgroup.procs: No such file or directory
,I/SyncAdapterService( 4639): Ignoring sync request for non-current account
,D/elm:15121( 4892): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15121( 4892): ELMEngine.ELMEngine( context ).
,D/elm:15121( 4892): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 4892): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/elm:15121( 4892): ElmAgentService : onCreate()
,D/elm:15121( 4892): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:15121( 4892): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:15121( 4892): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). ,
D/elm:15121( 4892): ModuleBase.ModifySetAlarm()
D/elm:15121( 4892): MDMBridge.getInstance()
D/elm:15121( 4892): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 4911): MountEmulatedStorage()
,I/libpersona( 4911): KNOX_SDCARD checking this for 10130
E/Zygote  ( 4911): v2
I/libpersona( 4911): KNOX_SDCARD not a persona
,I/SELinux ( 4911): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=4911 uid=10130 gids={50130, 9997} abi=armeabi-v7a
I/SELinux ( 4911): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1019): Killing 3834:com.google.android.syncadapters.calendar/u0a100 (adj 15): empty #31
E/SELinux ( 4911): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/elm:15121( 4892): ElmAgentService : onDestroy().,
,D/TimaKeyStoreProvider( 4911): TimaSignature is unavailable
,D/ActivityThread( 4911): Added TimaKeyStore provider
,W/ResourcesManager( 4911): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4911): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/Mms/MmsApp( 4833): [start]    initCountryIso consume time = 501.600312
,D/CountryDetector( 1019): The first listener is added
,W/libprocessgroup( 1019): failed to open /acct/uid_10100/pid_3834/cgroup.procs: No such file or directory
,D/Mms/MmsApp( 4833): [end]    initCountryIso consume time = 11.599844
,D/Mms/MmsConfig( 4833): [start]    MmsConfig.init() consume time = 2.346406
,D/DelayedSyncController( 4615): Delaying sync.
,I/ActivityManager( 1019): Killing 4487:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,D/Mms/MmsConfig( 4833): before partial update
,I/ActivityManager( 1019): Killing 4539:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,D/Mms/MmsConfig( 4833): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 4833): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 4833): isAuth is false
D/Mms/MmsConfig( 4833): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1455): query,matched:2117, calling pid = 4833
,D/TP/MmsSmsProvider( 1455): match 2117:Elapsed time : 6.445 ms
,D/EasySignUpManager_1.0.1( 4833): isAuth is false
,D/EasySignUpManager_1.0.1( 4833): getServiceStatus : serviceId (1) is OFF
,D/Mms/ArtClassLoader( 4833): init [DONE] art
,E/CscParser( 4833): mps_code.dat does not exist
,E/CscParser( 4833): customer_path =/system/csc/customer.xml
,E/CscParser( 4833): fileName + /system/csc/customer.xml
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GHttpClientFactory( 4599): Using the GMSCore's GoogleHttpClient
,E/CscParser( 4833): mps_code.dat does not exist
,E/CscParser( 4833): customer_path =/system/csc/customer.xml
E/CscParser( 4833): fileName + /system/csc/customer.xml
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4487/cgroup.procs: No such file or directory
,D/CscParser( 4833): getInstance fileName =/system/csc/customer.xml
,W/libprocessgroup( 1019): failed to open /acct/uid_10148/pid_4539/cgroup.procs: No such file or directory
,D/Mms/MmsConfig( 4833):  enable multiwindow = false
,E/Mms/MessageUtils( 4833): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 4833): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 4833): [end]    init() consume time = 155.846875
,D/Mms/Contact( 4833): [start]    init() consume time = 1.280156,
,D/TP/MmsSmsProvider( 1455): query,matched:13, calling pid = 4833
,D/Mms/Contact( 4833): [end]    init consume time = 11.271146
,D/TP/MmsSmsProvider( 1455): match 13:Elapsed time : 2.367 ms
,D/Mms/DraftCache( 4833): [start]    rebuildCache consume time = 3.786146,
,D/TP/MmsSmsProvider( 1455): query,matched:12, calling pid = 4833
,D/TP/MmsSmsProvider( 1455): match 12:Elapsed time : 1.925 ms
,D/Mms/MethodReflector( 4833): getSubId is called
D/Mms/TelephonyUtils( 4833): getLongSubId from simSlot 0, return Value = -1
,D/Mms/DraftCache( 4833): [end]    rebuildCache consume time = 8.60776
D/Mms/MethodReflector( 4833): getTelephonyProperty is called
D/Mms/DownloadManager( 4833): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4833): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4833): auto download without roaming -> true
D/Mms/DownloadManager( 4833): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,D/Mms/MethodReflector( 4833): getSubId is called
,D/Mms/MethodReflector( 4833): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 4833): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 4833): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 4833): getTelephonyProperty is called
D/Mms/DownloadManager( 4833): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 4833): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 4833): auto download without roaming -> true
D/Mms/DownloadManager( 4833): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 4833): auto download during roaming secondary -> false
D/Mms/DownloadManager( 4833): mAutoDownload ------> true
,I/art     ( 1649): Explicit concurrent mark sweep GC freed 19466(947KB) AllocSpace objects, 3(71KB) LOS objects, 29% free, 4MB/6MB, paused 767us total 45.152ms
,D/ComposerPerformance( 4833): 1457102605034 ms / [DONE] Composer constructor
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{316be332 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,D/Mms/Conversation( 4833): [start]    init() consume time = 44.222604
E/CII     ( 4833): CommonIMSInterface: VoLTE CSC feature disabled.
,D/TP/MmsSmsProvider( 1455): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1455): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1455): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1455): sUpgradeVersion = 0, db.getVersion() = 81
,I/Mms/ReservationManager( 4833): ReservationManager()
,I/Mms/ReservationManager( 4833): resetAfterConnected()
,E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1455): (284) automatic index on im_threads(normal_thread_id)
,D/TP/MmsSmsProvider( 1455): query,matched:7, calling pid = 4833
,I/SurfaceFlinger(  259): id=13 Removed Uoast (8/8)
,I/SurfaceFlinger(  259): id=13 Removed Uoast (-2/8)
,D/TP/MmsSmsProvider( 1455): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1455): need read changed broadcast:false
,D/TP/MmsSmsProvider( 1455): match 7:Elapsed time : 11.106 ms
,D/Mms/Conversation( 4833): [end]    init consume time = 31.909323
,D/Mms/MessagingNotification( 4833): [start]    init() consume time = 1.400209
,I/Mms/ReservationManager( 4833): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/MessagingNotification( 4833): [end]    init consume time = 2.515937
,D/TP/MmsSmsProvider( 1455): query,matched:0, calling pid = 4833
V/TP/MmsSmsProvider( 1455): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1455): match 0:Elapsed time : 1.272 ms
,D/Mms/Synchronizer( 4833): [start]    doSync consume time = 4.15349
,D/Mms/SpamFilter( 4833): [start]    SpamFilter fill() begin consume time = 3.646406
,D/Mms/MmsApp( 4833): [end]    onCreate() consume time = 1.145
,D/TP/MmsSmsProvider( 1455): update, matched:300, calling pid = 4833
V/TP/MmsSmsProvider( 1455): syncDBData start
,D/Mms/DownloadManager( 4833): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 4833): roaming ------> false, mSimSlot = 0
V/TP/MmsSmsProvider( 1455): syncDBData sms end
,I/splitIntent( 1019): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
V/TP/MmsSmsProvider( 1455): syncDBData mms end
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,V/TP/MmsSmsProvider( 1455): syncDBData end
D/TP/MmsSmsProvider( 1455): query,matched:400, calling pid = 4833
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/Mms/MethodReflector( 4833): getSubId is called
D/Mms/TelephonyUtils( 4833): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4833): getTelephonyProperty is called
D/Mms/DownloadManager( 4833): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4833): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4833): auto download without roaming -> true
D/Mms/DownloadManager( 4833): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/DownloadManager( 4833): mAutoDownload ------> true
D/Mms/Synchronizer( 4833): [end]    doSync consume time = 12.777448
,D/Mms/SpamFilter( 4833): [end]    SpamFilter fill() finished consume time = 3.9275
,D/Mms/MessagingNotification( 4833): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1455): query,matched:26, calling pid = 4833
,D/TP/SmsProvider( 1455): match 26:Elapsed time : 1.924 ms
,D/TP/MmsSmsProvider( 1455): query,matched:6, calling pid = 4833
,D/TP/MmsSmsProvider( 1455): match 6:Elapsed time : 1.504 ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,V/AlarmManager( 1019): waitForAlarm result :4
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4943): MountEmulatedStorage(),
,E/Zygote  ( 4943): v2
I/libpersona( 4943): KNOX_SDCARD checking this for 10023
I/SELinux ( 4943): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/libpersona( 4943): KNOX_SDCARD not a persona
,I/SELinux ( 4943): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4943): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1019): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4943 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4943): TimaSignature is unavailable,
D/ActivityThread( 4943): Added TimaKeyStore provider
,E/Zygote  ( 4958): MountEmulatedStorage()
,E/Zygote  ( 4958): v2
,I/libpersona( 4958): KNOX_SDCARD checking this for 1000
I/libpersona( 4958): KNOX_SDCARD not a persona
,I/SELinux ( 4958): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4958): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1019): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4958 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 4958): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  315): Explicit concurrent mark sweep GC freed 8677(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 635us total 24.668ms
,D/TimaKeyStoreProvider( 4958): TimaSignature is unavailable
,D/ActivityThread( 4958): Added TimaKeyStore provider
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 707us total 18.040ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 620us total 19.136ms
,V/GLSActivity( 1741): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1019): Killing 4560:com.sec.modem.settings/1000 (adj 15): empty #31
,I/System.out( 4599): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 4599): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 4599): (HTTPLog)-Static: isShipBuild true
,I/System.out( 4599): (HTTPLog)-Thread-708-449200712: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 4599): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10108
,E/MTPRx   ( 4958): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1019): uri = 14 selection = getSealedState
D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1019): mCursor = null
,V/MTPRx   ( 4958): sealedState: false
V/MTPRx   ( 4958): sealedUsbMassStorageState: false
E/MTPRx   ( 4958): check value of boot_completed is1
E/MTPRx   ( 4958): check booting is completed_sys.boot_completed
,I/OMACP   ( 4943): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,E/MTPRx   ( 4958): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4958): Status for mount/Unmount :removed
E/MTPRx   ( 4958): SDcard is not available
,W/MTPRx   ( 4958): value of connected istrue
,W/MTPRx   ( 4958): value of configured istrue
W/MTPRx   ( 4958): value of mtpEnabled istrue
W/MTPRx   ( 4958): value of ptpEnabled isfalse
E/MTPRx   ( 4958): Received USB_STATE with sdCardLaunch = 0
E/MTPRx   ( 4958): mFirstTime: false
,D/Mms/Omacp( 4833): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/        ( 4958): MTP: reading debug level property
,E/MTPJNIInterface( 4958): Getting CryptionKey from JAVA
E/MTPRx   ( 4958): currentUserId is 0
,E/MTPRx   ( 4958): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 4958): cannot open file : /sys/class/android_usb/android0/bcdUSB
,E/MTPRx   ( 4958): is_Privatemode is NOT 1
,I/OMACP   ( 4943): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
D/SettingsProvider( 1019): name = boot_time_connected
,I/OMACP   ( 4943): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 4943): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 4943): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 4943): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 4943): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,E/MTPRx   ( 4958): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 4958): noti = 17
,I/OMACP   ( 4943): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4560/cgroup.procs: No such file or directory
,I/OMACP   ( 4943): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,D/SettingsProvider( 1019): name = mtp_usb_conditions_met
,I/OMACP   ( 4943): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,D/SecContentProvider( 1019): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 4958): sending MTP_ICON_ENABLED to stack
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1019): name = mtp_running_status
,I/OMACP   ( 4943): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 4943): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 4943): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,D/SettingsProvider( 1019): name = mtp_usb_conditions_met
,I/OMACP   ( 4943): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,E/MTPRx   ( 4958): else part ... so first time!!!
,E/MTPPlaObsrvr( 4958): inside setContext()
,E/MTPPlaObsrvr( 4958):  inside createplafiles
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/Mms/Contact( 4833): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/ContactsCache( 4833): [start]    invalidate() consume time = 370.058541
D/Mms/ContactsCache( 4833): [end]    invalidate() consume time = 0.142605
,D/Mms/Contact( 4833): performUpdate:widgetCount=0
,I/System.out( 4599): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/MTPPlaObsrvr( 4958): playlist count is0
E/MTPPlaObsrvr( 4958):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4958):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4958): Inside registerContentObserver
,E/MtpAdbObserver( 4958): inside setContext()
E/MtpAdbObserver( 4958): Inside registerContentObserver
W/Settings( 4958): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1019): name = mtp_running_status
,D/SettingsProvider( 1019): name = mtp_usb_conditions_met
,E/MtpService( 4958): onCreate.
,V/MtpMediaDBManager( 4958): inside deleteAllDB
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/MtpService( 4958): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 4958): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 4958): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,D/MtpService( 1230): updating state; isCurrentUser=true, mMtpLocked=false
W/MTPRx   ( 4958): calling native method
E/MTPJNIInterface( 4958): < MTP > Registering BroadCast receiver :::::
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4980): MountEmulatedStorage(),
,I/libpersona( 4980): KNOX_SDCARD checking this for 1000
,E/Zygote  ( 4980): v2
I/libpersona( 4980): KNOX_SDCARD not a persona
I/SELinux ( 4980): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4980 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/MTPJNIInterface( 4958): < MTP > Registering BroadCast receiver :::::::
,I/SELinux ( 4980): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/MTPJNIInterface( 4958): noti = 10
E/MtpService( 4958): onStartCommand.
E/SELinux ( 4980): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/MTPRx   ( 4958): calling native method
E/MTPRx   ( 4958): Checking the driver time out
E/MTPJNIInterface( 4958): noti = 2
D/        ( 4958): deleting sockets before message queue initialization
D/        ( 4958): event handler thread is created, so set the flag
,E/MTPRx   ( 4958): called native method
,E/MTPJNIInterface( 4958): setting Media scanner status0
E/MTPJNIInterface( 4958): After setting Media scanner status0
E/MtpService( 4958): onStartCommand.
,E/MtpService( 4958): handleMessage. msg= { when=-8ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,W/MTPRx   ( 4958): notification from stack 1
,E/        ( 4958): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 4958): Getting media scanner status0
,V/MtpMediaDBManager( 4958): inside Thread updateDB
,E/MtpService( 4958): handleMessage. msg= { when=-11ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 4958): DeviceName is Thali Test (Galaxy A3)
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/MtpMediaDBManager( 4958): count : 26
,D/TimaKeyStoreProvider( 4980): TimaSignature is unavailable
,D/ActivityThread( 4980): Added TimaKeyStore provider
,W/MtpMediaDBManager( 4958): sending db update complete noti to stack
E/MTPJNIInterface( 4958): noti = 29
,E/SQLiteLog( 4958): (5) database is locked
,E/SQLiteLog( 4958): (5) database is locked
,E/SQLiteLog( 4958): (5) database is locked
,E/SQLiteLog( 4958): (5) database is locked
,E/MTPJNIInterface( 4958): Status for mount/Unmount :removed
E/MTPJNIInterface( 4958): SDcard is not available
,D/TMNetworkReceiver( 4980): TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
D/TMNetworkReceiver( 4980): TMNetworkReceiver.onReceive() Enter
,E/        ( 4958): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,D/TMNetworkReceiver( 4980): MirrorLink feauture level: using UEvent
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
I/ActivityManager( 1019): Killing 4428:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,E/MTPJNIInterface( 4958): Status for mount/Unmount :removed,
E/MTPJNIInterface( 4958): SDcard is not available
E/SQLiteLog( 4958): (21) API call with NULL database connection pointer,
E/SQLiteLog( 4958): (21) misuse at line 106108 of [9491ba7d73],
E/SQLiteLog( 4958): (21) API call with NULL database connection pointer,
E/SQLiteLog( 4958): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4958): (21) API call with NULL database connection pointer,
E/SQLiteLog( 4958): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4958): (21) API call with NULL database connection pointer
E/SQLiteLog( 4958): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 4958): notification from stack 2
D/        ( 4958): [mtp_init_device] Library open with 32 bits.
D/        ( 4958): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 4958): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 4958): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 4958):  [sua_support_present:1287] returning false 
D/        ( 4958): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms

```
