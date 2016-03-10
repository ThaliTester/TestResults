#### Test 62328822054c831_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
I/CrashAnrDetector( 1019): onPackageAdded : com.test.thalitest
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/IntelligenceServiceApplication( 3956): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 3956): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
I/DBG_POLICYDM( 3821): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
E/Gmail   ( 3856): Error finding the version of the Email provider.....
E/Gmail   ( 3856): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3856): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3856): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 3856): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3856): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3856): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3856): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3856): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 3856): We do not support migrating this version of the Email provider.
--------- beginning of system
W/libprocessgroup( 1019): failed to open /acct/uid_10032/pid_2745/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10037/pid_2973/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3009/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10130/pid_3053/cgroup.procs: No such file or directory
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_1731/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10131/pid_2924/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3143/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10077/pid_2638/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10141/pid_2622/cgroup.procs: No such file or directory
E/Zygote  ( 4022): MountEmulatedStorage()
E/Zygote  ( 4022): v2
I/SELinux ( 4022): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4022): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/libpersona( 4022): KNOX_SDCARD checking this for 10056
I/libpersona( 4022): KNOX_SDCARD not a persona
E/SELinux ( 4022): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/ActivityManager( 1019): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=4022 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/Gmail   ( 3856): getAccountsCursor
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/FileApkUtils( 2070): Optimizing (staging complete)
I/PCWCLIENTTRACE_LOG( 3996): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3996): DEFAULT_LOGLEVEL : 3
D/TimaKeyStoreProvider( 4022): TimaSignature is unavailable
D/ActivityThread( 4022): Added TimaKeyStore provider
I/PCWCLIENTTRACE_DMDBOpenHelper( 3996): new DMDBOpenHelper instance
D/FileApkUtils( 2070): Optimizing: DynamiteModules-prod.apk [1dad65bca29c108ad7dad5d3707435ff0555d8adf974340225c102890df71a23]
,I/art     ( 2070): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
D/PCWCLIENTTRACE_DMContentProvider( 3996): [URIMatcher] - result : 2
V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/IntelligenceServiceApplication( 3956): no applications having user consent for prediction
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
I/DBG_POLICYDM( 3821): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
I/WebViewFactory( 3734): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/DexOptUtils( 2070): Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk is already optimized. Bailing.
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 3821): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
I/GoogleHttpClient( 1631): GMS http client unavailable, use old client
I/DBG_DM  ( 3620): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
E/Zygote  ( 4045): MountEmulatedStorage()
E/Zygote  ( 4045): v2
I/libpersona( 4045): KNOX_SDCARD checking this for 10102
I/libpersona( 4045): KNOX_SDCARD not a persona
I/SELinux ( 4045): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4045 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/SELinux ( 4045): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4045): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
V/PlaceDetection v1.0.19 ( 3956): [PlaceDetection::stopService] Service stopped.
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 4045): TimaSignature is unavailable
D/ActivityThread( 4045): Added TimaKeyStore provider
W/ActivityManager( 1019): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1019): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/LibraryLoader( 3734): Loading: webviewchromium
W/ResourcesManager( 4045): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/ActivityThread( 3856): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@25a0158 that was originally bound here
E/ActivityThread( 3856): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@25a0158 that was originally bound here
E/ActivityThread( 3856): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3856): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3856): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3856): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3856): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3856): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 3856): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 3856): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 3856): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 3856): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 3856): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 3856): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 3856): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3856): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3856): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3856): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1019): Unbind failed: could not find connection for android.os.BinderProxy@24a6a898
I/ActivityManager( 1019): Killing 3186:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
I/LockPatternUtils( 1308): isSmartCardAuthenticationAvailable: false
I/DBG_FMMDM( 3976): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
I/DBG_FMMDM( 3976): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
I/DBG_FMMDM( 3976): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
I/ActivityManager( 1019): Killing 3317:flipboard.boxer.app/u0a97 (adj 15): empty #31
I/ActivityManager( 1019): Killing 3294:com.mobeam.barcodeService/1000 (adj 15): empty #32
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
W/art     ( 1308): Suspending all threads took: 8.756ms
E/Zygote  ( 4064): MountEmulatedStorage()
E/Zygote  ( 4064): v2
I/libpersona( 4064): KNOX_SDCARD checking this for 1000
I/libpersona( 4064): KNOX_SDCARD not a persona
I/SELinux ( 4064): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4064): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4064): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=4064 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
V/PlaceDetection v1.0.19 ( 3956): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/UserAnalysis.MyPlaceDbPreference( 3956): Constructor Preference
D/TimaKeyStoreProvider( 4064): TimaSignature is unavailable
D/ActivityThread( 4064): Added TimaKeyStore provider
E/SQLiteLog( 3856): (283) recovered 14 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
W/libprocessgroup( 1019): failed to open /acct/uid_10039/pid_3186/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10097/pid_3317/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3294/cgroup.procs: No such file or directory
I/DBG_POLICYDM( 3821): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
I/DBG_FMMDS( 4064): [50.18.150420][Line:56][onCreate] FMMDS Application Start
I/DBG_FMMDS( 4064): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
D/PCWCLIENTTRACE_DMContentProvider( 3996): [URIMatcher] - result : 2
E/DBG_FMMDS( 4064): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
I/DBG_FMMDS( 4064): [50.18.150420][Line:43][xdbDBInit] 
I/DBG_POLICYDM( 3821): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 3821): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
I/FactoryTestApp( 3100): [IPCWriterToSecPhoneService$disConnectSecPhoneService](3699)  
I/sCloudBackupApp( 4022): sCloudBackupApp Version Info : 4.04.7.KK_APP
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4084): MountEmulatedStorage()
E/Zygote  ( 4084): v2
I/libpersona( 4084): KNOX_SDCARD checking this for 10058
I/libpersona( 4084): KNOX_SDCARD not a persona
I/SELinux ( 4084): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4084): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4084): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4084 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/File    ( 3856): fail readDirectory() errno=2
D/TimaKeyStoreProvider( 4084): TimaSignature is unavailable
D/ActivityThread( 4084): Added TimaKeyStore provider
I/DBG_FMMDS( 4064): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
I/Gmail   ( 3856): notifyAccountChanged
I/System.out( 3580): pool-10-thread-1 calls detatch()
I/Gmail   ( 3856): getAccountsCursor
I/Gmail   ( 3856): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 3856): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/System.out( 3604): Thread-550 calls detatch()
I/DBG_FMMDS( 4064): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
I/DBG_FMMDS( 4064): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
I/DBG_FMMDS( 4064): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
I/DBG_FMMDS( 4064): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
I/DBG_FMMDS( 4064): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
I/DBG_FMMDS( 4064): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
I/ExternalOEMControlProvider( 4084): onCreate
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Zygote  ( 4110): MountEmulatedStorage()
E/Zygote  ( 4110): v2
I/libpersona( 4110): KNOX_SDCARD checking this for 1000
I/libpersona( 4110): KNOX_SDCARD not a persona
I/SELinux ( 4110): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4110): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=4110 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 2944:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
E/SELinux ( 4110): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Killing 3329:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
I/Gmail   ( 3856): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 3856): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/FOTA_Client( 3885): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
D/SettingsProvider( 1019): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10058
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 4110): TimaSignature is unavailable
D/ActivityThread( 4110): Added TimaKeyStore provider
V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SettingsProvider( 1019): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10058
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
I/FOTA_Client( 3885): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
I/FOTA_Client( 3885): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/FOTA_Client( 3885): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
W/ResourcesManager( 4110): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4129): MountEmulatedStorage()
I/ActivityManager( 1019): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=4129 uid=10013 gids={50013, 9997} abi=armeabi-v7a
E/Zygote  ( 4129): v2
I/libpersona( 4129): KNOX_SDCARD checking this for 10013
I/libpersona( 4129): KNOX_SDCARD not a persona
I/SELinux ( 4129): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4129): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4129): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 4129): TimaSignature is unavailable
D/ActivityThread( 4129): Added TimaKeyStore provider
I/ServiceMode( 4110): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 4110): setReferenceIsDumpState : 0
W/libprocessgroup( 1019): failed to open /acct/uid_1101/pid_3329/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10081/pid_2944/cgroup.procs: No such file or directory
W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
E/Zygote  ( 4146): MountEmulatedStorage()
E/Zygote  ( 4146): v2
I/libpersona( 4146): KNOX_SDCARD checking this for 1000
I/libpersona( 4146): KNOX_SDCARD not a persona
I/SELinux ( 4146): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4146): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4146): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=4146 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 3369:flipboard.app/u0a96 (adj 15): empty #31
I/art     (  319): Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 22.710ms
D/TimaKeyStoreProvider( 4146): TimaSignature is unavailable
D/ActivityThread( 4146): Added TimaKeyStore provider
I/LibraryLoader( 3734): Time to load native libraries: 680 ms (timestamps 3815-4495)
I/LibraryLoader( 3734): Expected native library version number "",actual native library version number ""
I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 617us total 16.816ms
W/art     ( 3734): Attempt to remove local handle scope entry from IRT, ignoring
I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 17.136ms
I/Babel   ( 4045): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 4045): MmsConfig.loadMmsSettings
I/Babel   ( 4045): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel   ( 4045): MmsConfig.loadFromDatabase
D/AndroidRuntime( 4054): 
D/AndroidRuntime( 4054): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4054): CheckJNI is OFF
D/AndroidRuntime( 4054): readGMSProperty: start
D/AndroidRuntime( 4054): readGMSProperty: already setted!!
D/AndroidRuntime( 4054): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4054): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4054): readGMSProperty: end
D/AndroidRuntime( 4054): addProductProperty: start
V/OneTimeInitializerReceiver( 4129): OneTimeInitializerReceiver.onReceive
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
W/art     ( 4045): Suspending all threads took: 50.037ms
V/OneTimeService( 4129): OneTimeService.onHandleIntent
W/libprocessgroup( 1019): failed to open /acct/uid_10096/pid_3369/cgroup.procs: No such file or directory
I/ActivityManager( 1019): Waited long enough for: ServiceRecord{293b55bb u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
D/NPS_WSSNPS( 4146): [] android.intent.action.BOOT_COMPLETED
W/ContextImpl( 4146): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/NPS_WSSNPS( 4146): [] Service onCreate!!
E/Zygote  ( 4169): MountEmulatedStorage()
E/Zygote  ( 4169): v2
I/libpersona( 4169): KNOX_SDCARD checking this for 1000
I/libpersona( 4169): KNOX_SDCARD not a persona
I/SELinux ( 4169): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4169): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4169): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     ( 1019): Explicit concurrent mark sweep GC freed 19100(1053KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 5.955ms total 173.901ms
W/InstanceID/Rpc( 2070): Found 10011
I/ActivityManager( 1019): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=4169 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/ContextImpl( 1308): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
W/ContextImpl( 1308): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
D/NPS_WSSNPS( 4146): [50.150321] NpsServiceTask Start
I/ActivityManager( 1019): Killing 2988:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
D/TimaKeyStoreProvider( 4169): TimaSignature is unavailable
D/ActivityThread( 4169): Added TimaKeyStore provider
I/SettingSearch/SearchIntentReceiver( 1308): InitSerachDBThread thread end!
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
E/Babel   ( 4045): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4045): MmsConfig.loadFromResources
E/Babel   ( 4045): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4045): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
D/NPS_WSSNPS( 4146): [50.150321] smlDBHelper
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
D/btif_config_util( 3124): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
I/DBG_DM  ( 3620): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
W/VideoCapabilities( 4045): Unrecognized profile 2130706433 for video/avc
W/libprocessgroup( 1019): failed to open /acct/uid_10153/pid_2988/cgroup.procs: No such file or directory
W/AudioCapabilities( 4045): Unsupported mime audio/evrc
I/Gmail   ( 3856): getAccountsCursor
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 1658): Starting #7
I/Hs20UtilService( 1658): Message received 5003
I/KLMS-2.5.123: ( 2605): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 10 21:37:34 GMT+01:00 2016
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/NPS_WSSNPS( 4146): [50.150321] AsyncBulkFlagCheck
I/KLMS-2.5.123: ( 2605): KLMSAbstractReciever(): onReceive().END.
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/AudioCapabilities( 4045): Unsupported mime audio/qcelp
I/NPS_WSSNPS( 4146): [50.150321] IsRemain_AsyncBulkCheck
I/NPS_WSSNPS( 4146): [50.150321] IsRemain_Asyncing nothing
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 4146): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
I/KLMS-2.5.123: ( 2605): KLMSIntentService(): onCreate()
I/KLMS-2.5.123: ( 2605): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.5.123: ( 2605): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/Zygote  ( 4204): MountEmulatedStorage()
E/Zygote  ( 4204): v2
I/libpersona( 4204): KNOX_SDCARD checking this for 10020
I/libpersona( 4204): KNOX_SDCARD not a persona
I/SELinux ( 4204): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/KLMS-2.5.123: ( 2605): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/ActivityManager( 1019): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=4204 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
I/SELinux ( 4204): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4204): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 2605): KLMSIntentService(): BOOT_COMPLETED
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
D/SettingsProvider( 1019): name = access_control_enabled
D/NPS_WSSNPS( 4146): [50.150321] Service onDestroy
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4217): MountEmulatedStorage()
E/Zygote  ( 4217): v2
I/libpersona( 4217): KNOX_SDCARD checking this for 10065
I/libpersona( 4217): KNOX_SDCARD not a persona
I/SELinux ( 4217): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=4217 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 3387:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
I/SELinux ( 4217): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4217): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 4204): TimaSignature is unavailable
D/ActivityThread( 4204): Added TimaKeyStore provider
I/NPS_WSSNPS( 4146): [50.150321] smlBRConfigurationDelete
I/NPS_WSSNPS( 4146): [50.150321] smlBRMessageDelete
I/NPS_WSSNPS( 4146): [50.150321] smlBREmailDelete
I/NPS_WSSNPS( 4146): [50.150321] smlBRNetworkDelete
I/NPS_WSSNPS( 4146): [50.150321] smlBRCallLogDelete
I/NPS_WSSNPS( 4146): [50.150321] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 4146): [50.150321] smlBRPenMemoMDelete
I/NPS_WSSNPS( 4146): [50.150321] smlBRSMemoDelete
I/NPS_WSSNPS( 4146): [50.150321] cpuBooster release : false
I/KLMS-2.5.123: ( 2605): KLMSIntentService(): onDestroy()
D/TimaKeyStoreProvider( 4217): TimaSignature is unavailable
D/ActivityThread( 4217): Added TimaKeyStore provider
W/Settings( 4045): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/NPS_WSSNPS( 4146): [50.150321] dsServerSocket close
I/ActivityManager( 1019): Killing 3404:com.sec.usbsettings/1000 (adj 15): empty #31
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
W/AudioCapabilities( 4045): Unsupported mime audio/mpeg-L1
W/AudioCapabilities( 4045): Unsupported mime audio/mpeg-L2
W/AudioCapabilities( 4045): Unsupported mime audio/x-ms-wma
I/RlzPingService( 3836): Setting next ping for 1458247054204
W/AudioCapabilities( 4045): Unsupported mime audio/x-ima
W/AudioCapabilities( 4045): Unsupported mime audio/qcelp
W/AudioCapabilities( 4045): Unsupported mime audio/evrc
W/VideoCapabilities( 4045): Unsupported mime video/wvc1
W/VideoCapabilities( 4045): Unsupported mime video/x-ms-wmv
D/FileShare-Server( 4217): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,W/VideoCapabilities( 4045): Unrecognized profile/level 32768/2 for video/mp4v-es
W/VideoCapabilities( 4045): Unsupported mime video/wvc1
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3387/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3404/cgroup.procs: No such file or directory
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/VideoCapabilities( 4045): Unsupported mime video/x-ms-wmv
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10052
I/art     ( 1631): Explicit concurrent mark sweep GC freed 3390(150KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 830us total 132.558ms
W/SQLiteConnectionPool( 1631): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/VideoCapabilities( 4045): Unsupported mime video/x-ms-wmv7
W/VideoCapabilities( 4045): Unsupported mime video/x-ms-wmv8
W/VideoCapabilities( 4045): Unsupported mime video/mp43
W/VideoCapabilities( 4045): Unsupported mime video/sorenson
I/Icing   ( 2070): Storage manager: low false usage 2.10MB avail 9.95GB capacity 11.63GB
W/VideoCapabilities( 4045): Unsupported mime video/mp4v-esdp
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4248): MountEmulatedStorage()
E/Zygote  ( 4248): v2
I/libpersona( 4248): KNOX_SDCARD checking this for 1000
I/SELinux ( 4248): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4248): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4248 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 2383:com.android.mms/u0a41 (adj 15): empty #31
I/SELinux ( 4248): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4248): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/VideoCapabilities( 4045): Unsupported profile 4 for video/mp4v-es
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/qtaguid ( 3734): Tagging socket 39 with tag 100000000{1,0} for uid -1, pid: 3734, getuid(): 10052
D/TimaKeyStoreProvider( 4248): TimaSignature is unavailable
D/ActivityThread( 4248): Added TimaKeyStore provider
E/AffinityControl( 4054): AffinityControl: registerfunction enter
V/Babel   ( 4045): babel boot account: SMS
V/Babel   ( 4045): babel boot account: thalitester@gmail.com
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4266): MountEmulatedStorage()
I/libpersona( 4266): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4266): v2
I/libpersona( 4266): KNOX_SDCARD not a persona
I/SELinux ( 4266): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/AndroidRuntime( 4054): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4266 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 3426:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
I/SELinux ( 4266): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4266): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/CountryDetector( 1019): No listener is left
V/AlarmManager( 1019): waitForAlarm result :4
D/TimaKeyStoreProvider( 4266): TimaSignature is unavailable
D/ActivityThread( 4266): Added TimaKeyStore provider
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
E/MTPRx   ( 4248): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/SecContentProvider2( 1019): uri = 14 selection = getSealedState
D/SecContentProvider2( 1019): mCursor = null
D/SecContentProvider2( 1019): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1019): mCursor = null
V/MTPRx   ( 4248): sealedState: false
V/MTPRx   ( 4248): sealedUsbMassStorageState: false
V/AlarmManager( 1019): waitForAlarm result :4
D/GCM     ( 2070): COMPAT: Multi user not supported
W/libprocessgroup( 1019): failed to open /acct/uid_10041/pid_2383/cgroup.procs: No such file or directory
I/qtaguid ( 3734): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3734, getuid(): 10052
I/qtaguid ( 3734): Untagging socket 43
I/qtaguid ( 3734): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3734, getuid(): 10052
I/qtaguid ( 3734): Untagging socket 43
I/qtaguid ( 3734): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3734, getuid(): 10052
I/qtaguid ( 3734): Untagging socket 43
I/qtaguid ( 3734): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3734, getuid(): 10052
I/qtaguid ( 3734): Untagging socket 43
I/qtaguid ( 3734): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3734, getuid(): 10052
I/qtaguid ( 3734): Untagging socket 43
I/qtaguid ( 3734): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3734, getuid(): 10052
I/qtaguid ( 3734): Untagging socket 43
I/qtaguid ( 3734): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3734, getuid(): 10052
I/qtaguid ( 3734): Untagging socket 43
I/qtaguid ( 3734): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3734, getuid(): 10052
I/qtaguid ( 3734): Untagging socket 43
I/qtaguid ( 3734): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3734, getuid(): 10052
I/qtaguid ( 3734): Untagging socket 43
I/qtaguid ( 3734): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3734, getuid(): 10052
I/qtaguid ( 3734): Untagging socket 43
I/qtaguid ( 3734): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3734, getuid(): 10052
I/qtaguid ( 3734): Untagging socket 43
I/qtaguid ( 3734): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3734, getuid(): 10052
I/qtaguid ( 3734): Untagging socket 43
I/qtaguid ( 3734): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3734, getuid(): 10052
I/qtaguid ( 3734): Untagging socket 43
W/SQLiteConnectionPool( 2070): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1019): mDVFSHelper.acquire()
D/FocusedStackFrame( 1019): Set to : 0
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1019): *FMB* installDecor flags : -2122120936
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 1497
D/Launcher.HomeView( 1497): onPause
D/AndroidRuntime( 4054): Shutting down VM
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, uhalitest
W/libprocessgroup( 1019): failed to open /acct/uid_10043/pid_3426/cgroup.procs: No such file or directory
D/Launcher( 1497): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/SettingsProvider( 1019): name = mtp_usb_connection_status
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SettingsProvider( 1019): name = media_player_mode
I/ActivityManager( 1019): Killing 3486:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
D/GCM     ( 1812): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/SettingsProvider( 1019): name = mtp_usb_conditions_met
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/SettingsProvider( 1019): name = mtp_running_status
E/Zygote  ( 4290): MountEmulatedStorage()
E/Zygote  ( 4290): v2
I/libpersona( 4290): KNOX_SDCARD checking this for 10167
I/libpersona( 4290): KNOX_SDCARD not a persona
I/SELinux ( 4290): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4290): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4290): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4290 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/SettingsProvider( 1019): name = media_mount_count
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/SettingsProvider( 1019): name = mtp_sync_alive
D/SettingsProvider( 1019): name = sdcard_launch
D/TimaKeyStoreProvider( 4290): TimaSignature is unavailable
D/ActivityThread( 4290): Added TimaKeyStore provider
I/art     ( 1812): Explicit concurrent mark sweep GC freed 19153(1372KB) AllocSpace objects, 23(367KB) LOS objects, 39% free, 9MB/16MB, paused 1.249ms total 81.495ms
D/SettingsProvider( 1019): name = boot_time_connected
E/Zygote  ( 4308): MountEmulatedStorage()
I/libpersona( 4308): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4308): v2
I/libpersona( 4308): KNOX_SDCARD not a persona
I/SELinux ( 4308): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4308 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 4308): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4308): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
I/ActivityManager( 1019): Killing 3446:com.google.android.configupdater/u0a82 (adj 15): empty #31
I/ActivityManager( 1019): Killing 3580:com.dropbox.android/u0a88 (adj 15): empty #31
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SettingsProvider( 1019): name = mtp_open_session
V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
I/art     ( 1172): Background sticky concurrent mark sweep GC freed 18289(751KB) AllocSpace objects, 1(16KB) LOS objects, 3% free, 21MB/22MB, paused 3.952ms total 100.080ms
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
W/ContextImpl( 1019): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
V/ActivityThread( 1497): updateVisibility : ActivityRecord{14945de9 token=android.os.BinderProxy@21847a76 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1497): onStop
V/ActivityThread( 1497): updateVisibility : ActivityRecord{14945de9 token=android.os.BinderProxy@21847a76 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/TimaKeyStoreProvider( 4308): TimaSignature is unavailable
D/ActivityThread( 4308): Added TimaKeyStore provider
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
D/PersonaManager( 1019): isKioskContainerExistOnDevice
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/art     ( 4054): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/Launcher( 1497): onTrimMemory. Level: 20
,I/PCWCLIENTTRACE_PushUtil( 3996): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 3996): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3996): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 3996): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3996): ACTION_BOOTUP - Version: 4.82
,D/PCWCLIENTTRACE_SYSTEMReceiver( 3996): ACTION_BOOTUP - Push type: [SPP, GCM]
,E/Zygote  ( 4325): MountEmulatedStorage()
I/libpersona( 4325): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4325): v2
I/libpersona( 4325): KNOX_SDCARD not a persona
I/SELinux ( 4325): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/PCWCLIENTTRACE_AccountUtil( 3996): [hasSamungAccount] - No Samsung Account
I/SELinux ( 4325): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=4325 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 4325): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SensorService( 1019): [SO] activate (ident=0xb8ac8d98, enabled=0)
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 3734): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3734, getuid(): 10052
,D/SensorManager( 1019): unregisterListener ::   
,I/Sensors ( 1019): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1019): [SO] changed settle time [1]
D/SensorService( 1019): [SO] setDelay [66000000]
D/SensorService( 1019): [SO] activate (ident=0xb8ac8d98, enabled=1)
D/SensorService( 1019): [SO] AR_init
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/ContactAccountLoggerTas( 3734): canRun() : Opted Out
,D/SensorManager( 1019): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/TimaKeyStoreProvider( 4325): TimaSignature is unavailable
,E/KnoxSetupWizardClient( 4308): isShipMode : 1
I/KnoxSetupWizardClient( 4308): onReceive : android.intent.action.BOOT_COMPLETED
D/ActivityThread( 4325): Added TimaKeyStore provider
I/PCWCLIENTTRACE_SecurePreferencesJNI( 3996): [GetString-S]
,I/CheckinService( 2070): Disabling old GoogleServicesFramework version
,W/libprocessgroup( 1019): failed to open /acct/uid_10068/pid_3486/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10082/pid_3446/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10088/pid_3580/cgroup.procs: No such file or directory
,I/GCoreUlr( 2070): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/ReactiveServiceManager( 3996): Supported : 1
,D/QSEECOMAPI: ( 1019): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 1019): App is not loaded in QSEE
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1812): DispatchingService.onCreate()
,D/QSEECOMAPI: ( 1019): Loaded image: APP id = 10
,I/DBG_DM  ( 3620): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,D/QSEECOMAPI: ( 1019): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1019): QSEECom_shutdown_app, app_id = 10
,E/terrier ( 1019): handleString: Failed to handle string(-4)
E/terrier ( 1019): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 3996): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 3996): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 3996): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3996): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3996): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 3996): [ensureRegistration] - No Samsung account
,D/SensorService( 1019): [SO] Reset Rotation Old [100], Init [1]
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4350): MountEmulatedStorage(),
I/libpersona( 4350): KNOX_SDCARD checking this for 10028
E/Zygote  ( 4350): v2
I/libpersona( 4350): KNOX_SDCARD not a persona,
,I/SELinux ( 4350): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4350): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1019): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=4350 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 3563:com.sec.dsm.system/1000 (adj 15): empty #31
,E/SELinux ( 4350): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4303, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,D/PowerUI ( 1172): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1172): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/WebViewFactory( 4290): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ShortcutReceiver( 4308):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,V/HeadsetService( 3124): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3124): Disconnected process message: 10
,D/SensorService( 1019): [SO] -0.421 0.172 9.902
D/SystemUpdateService( 2070): onCreate
D/SensorService( 1019): [SO] [100 -> 255]
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
I/LibraryLoader( 4290): Loading: webviewchromium
I/LibraryLoader( 4290): Time to load native libraries: 6 ms (timestamps 5858-5864)
I/LibraryLoader( 4290): Expected native library version number "",actual native library version number ""
,W/System.err( 4308): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,D/TimaKeyStoreProvider( 4350): TimaSignature is unavailable
D/ActivityThread( 4350): Added TimaKeyStore provider
,D/KnoxShortcutUtil( 4308): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4308):  KnoxContainerVersion 2.3.0
D/ShortcutReceiver( 4308):  shortcut migration not required 
,W/System.err( 4308): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4308): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4308): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 4308): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 4308): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4308): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,V/WebViewChromiumFactoryProvider( 4290): Binding Chromium to main looper Looper (main, tid 1) {349acc74}
,I/LibraryLoader( 4290): Expected native library version number "",actual native library version number ""
,E/Zygote  ( 4370): MountEmulatedStorage()
E/Zygote  ( 4370): v2
I/libpersona( 4370): KNOX_SDCARD checking this for 1000
I/libpersona( 4370): KNOX_SDCARD not a persona
I/SELinux ( 4370): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4370): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1019): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4370 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 3638:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
E/SELinux ( 4370): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GCoreUlr( 1812): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/CheckinService( 2070): Checking schedule, now: 1457642255197 next: 1457732977569
I/CheckinService( 2070): active receiver: disabled
,D/TimaKeyStoreProvider( 4370): TimaSignature is unavailable
,W/ContextImpl( 4325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
D/ActivityThread( 4370): Added TimaKeyStore provider
,I/chromium( 4290): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/SystemUpdateService( 2070): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/BrowserStartupController( 4290): Initializing chromium process, renderers=0
,W/art     ( 4290): Attempt to remove local handle scope entry from IRT, ignoring
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3563/cgroup.procs: No such file or directory
,W/chromium( 4290): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 4290): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 4290): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/8)
,I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/8)
,I/Adreno-EGL( 4290): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4290): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4290): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4290): Local Branch: 
I/Adreno-EGL( 4290): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4290): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4290):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4399): MountEmulatedStorage()
E/Zygote  ( 4399): v2
I/libpersona( 4399): KNOX_SDCARD checking this for 1000
I/libpersona( 4399): KNOX_SDCARD not a persona
,I/SELinux ( 4399): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4399): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4399): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4399 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/libprocessgroup( 1019): failed to open /acct/uid_10088/pid_3638/cgroup.procs: No such file or directory
,D/FactoryTestApp( 3100): [DummyFtClient$onDestroy](3100) Destroy DummyFtClient service
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/FactoryTestApp( 3100): [Support$Values.getString](3100) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 3100): [ModuleCommon$isConnectionModeNone](3100) mConnectionMode = gsm
,I/FactoryTestApp( 3100): [ModuleCommon$isRunningFtClient](3100) RUNNING_FTCLIENT : false
,I/art     (  319): Explicit concurrent mark sweep GC freed 8758(373KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 21.905ms
D/FactoryTestApp( 3100): [DummyFtClient$onDestroy](3100) kill process
I/Process ( 3100): Sending signal. PID: 3100 SIG: 9
,D/TimaKeyStoreProvider( 4399): TimaSignature is unavailable
,D/ActivityThread( 4399): Added TimaKeyStore provider
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 16.695ms
,E/SMD     (  292): DCD OFF
,I/SystemUpdateService( 2070): cancelUpdate (empty URL)
I/SystemUpdateService( 2070): active receiver: disabled
,W/ResourcesManager( 4399): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 16.973ms
,W/ContextImpl( 4399): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
D/StatusChecker( 4370): onReceive : android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4417): MountEmulatedStorage()
E/Zygote  ( 4417): v2
I/libpersona( 4417): KNOX_SDCARD checking this for 1000
I/libpersona( 4417): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=4417 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 4417): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4417): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4417): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/AuthZen ( 2070): Handling intent: android.intent.action.BOOT_COMPLETED
,I/StatusChecker( 4370): onReceive : net.mt.init : DONE
I/ActivityManager( 1019): Process com.sec.factory (pid 3100)(adj 0) has died(54,636)
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/F_PHONE ( 4399): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
W/ContextImpl( 4399): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,E/Zygote  ( 4432): MountEmulatedStorage()
,I/libpersona( 4432): KNOX_SDCARD checking this for 10113
E/Zygote  ( 4432): v2
I/libpersona( 4432): KNOX_SDCARD not a persona
,I/SELinux ( 4432): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1019): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4432 uid=10113 gids={50113, 9997} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 3658:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31,
,I/SELinux ( 4432): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
E/SELinux ( 4432): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 4417): TimaSignature is unavailable
,D/ActivityThread( 4417): Added TimaKeyStore provider
V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 4432): TimaSignature is unavailable
,D/ActivityThread( 4432): Added TimaKeyStore provider
,I/System.out( 4350): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 4350): Inside WakeupProvider
,D/BootCompletedReceiver( 2070): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 2070): Got an BootCompleted event.
,D/F_PHONE ( 4399): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 4399): default registerAction()
I/F_PHONE ( 4399): [[com.sec.bcservice]] sendPendingMessage()
,I/ActivityManager( 1019): Waited long enough for: ServiceRecord{1775eadd u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,D/AuthZenEventHandler( 2070): Handling event: android.intent.action.BOOT_COMPLETED
,D/BootCompletedReceiver( 2070): Will NOT schedule AdAttestation signal task because it's disabled.
,W/ResourcesManager( 4417): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/PageBuddyNotiSvc( 4432): Intent received : action=android.intent.action.BOOT_COMPLETED
,I/VlingoApplication( 4350): VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,W/BaseAppContext( 2070): Using Auth Proxy for data requests.
,D/BluetoothBDAdrressReceiver( 4417): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 4417): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
W/chromium( 4290): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,W/chromium( 4290): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3658/cgroup.procs: No such file or directory
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 4432): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,W/ResourcesManager( 1468): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothBDTestService( 1468): onCreate()
E/BluetoothBDTestService( 1468): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1468): bd_address_path: /efs/bluetooth/bt_addr
E/BluetoothBDTestService( 1468): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,E/Zygote  ( 4462): MountEmulatedStorage()
,E/Zygote  ( 4462): v2
I/libpersona( 4462): KNOX_SDCARD checking this for 1000
I/libpersona( 4462): KNOX_SDCARD not a persona
,I/SELinux ( 4462): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4462): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 4462): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=4462 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,I/PageBuddyNotiSvc( 4432): onCreate mCpBitFlag=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4474): MountEmulatedStorage()
E/Zygote  ( 4474): v2
I/libpersona( 4474): KNOX_SDCARD checking this for 10121
I/libpersona( 4474): KNOX_SDCARD not a persona
,I/SELinux ( 4474): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4474): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/art     ( 4290): Attempt to remove local handle scope entry from IRT, ignoring
E/SELinux ( 4474): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/AwContents( 4290): onDetachedFromWindow called when already detached. Ignoring,
D/TimaKeyStoreProvider( 4462): TimaSignature is unavailable
,D/ActivityThread( 4462): Added TimaKeyStore provider
I/ActivityManager( 1019): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4474 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SystemUpdateService( 2070): onDestroy
,D/PhoneWindow( 4290): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 4290): *FMB* installDecor flags : -2139027200
,D/SystemWebViewEngine( 4290): CordovaWebView is running on device made by: samsung
,W/art     ( 4290): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4290): Attempt to remove local handle scope entry from IRT, ignoring
,D/TimaKeyStoreProvider( 4474): TimaSignature is unavailable
,I/VlingoAndroidCore( 4350): AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
D/ActivityThread( 4474): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 4462): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 4474): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4474): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4474): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1019): Killing 3673:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,D/QuickConnect( 4474): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1019): name = scon_is_running
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10121
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,I/KnoxUsageLogPro( 4462): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
I/KnoxUsageLogPro( 4462): premStatus:2
I/KnoxUsageLogPro( 4462): isEulaShown : false
I/KnoxUsageLogPro( 4462): KnoxUsageReceiver onReceive : not Processible, just return
I/ActivityManager( 1019): Killing 3717:com.sec.android.diagmonagent/1000 (adj 15): empty #31
I/KnoxUsageLogPro( 4462): savePreference: key = previous_sys_time value = 1457642255907
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
,I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4325): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 4325): Resource data:2131165186
,I/AMMetaDataParserService( 4325): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist,
W/ResourcesManager( 4325): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 4325): getResourceTypeNamexml
W/ResourcesManager( 4325): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/VlingoApplication( 4350): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false,
,D/VlingoApplication( 4350): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/DialogFlow( 4350): initQueue(),
,I/AMMetaDataParserService( 4325): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,E/BaseAppContext( 2070): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/QuickConnect( 4474): Utils.setQCRunningSetting - set : 0
,I/QuickConnect( 4474): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,I/QuickConnect( 4474): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4511): MountEmulatedStorage(),
I/ActivityManager( 1019): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4511 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 3029:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,E/Zygote  ( 4511): v2
I/libpersona( 4511): KNOX_SDCARD checking this for 10127
I/libpersona( 4511): KNOX_SDCARD not a persona
,I/SELinux ( 4511): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4511): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4511): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3620): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,I/DBG_POLICYDM( 3821): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/TimaKeyStoreProvider( 4511): TimaSignature is unavailable
,D/ActivityThread( 4511): Added TimaKeyStore provider
,W/libprocessgroup( 1019): failed to open /acct/uid_10146/pid_3673/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 3821): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 3821): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 3821): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 3821): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3821): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 3821): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts,
,I/DBG_POLICYDM( 3821): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/AMMetaDataParserService( 4325): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3717/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10090/pid_3029/cgroup.procs: No such file or directory
,E/Zygote  ( 4526): MountEmulatedStorage()
E/Zygote  ( 4526): v2
I/libpersona( 4526): KNOX_SDCARD checking this for 10030
I/libpersona( 4526): KNOX_SDCARD not a persona
,I/SELinux ( 4526): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4526 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 4526): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ResourcesManager( 4511): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,E/SELinux ( 4526): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 4511): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4511): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4511): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 4526): TimaSignature is unavailable
,D/ActivityThread( 4526): Added TimaKeyStore provider
,D/OpenGLRenderer( 4290): Render dirty regions requested: true
,I/AMMetaDataParserService( 4325): Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCr,eateAccountActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,W/ContextImpl( 4325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,D/PhoneWindow( 4290): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 4290): *FMB* isFloatingMenuEnabled return false
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 35938(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 22MB/34MB, paused 10.333ms total 168.014ms
,I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1019): Focus entered window: 4290
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 4290): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 4290): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4290): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 4290): Enabling debug mode 0
,I/AuthZen ( 2070): Fetching signing key...
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:assistant
I/AMMetaDataParserService( 4325): Resource data:2131034113
,W/ResourcesManager( 4325): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.,
W/ResourcesManager( 4325): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SBrowserFeatureFlag( 4511): initialized in static block : loadCscFeatureValue() succeed! 
,I/ActivityManager( 1019): Displayed Component not be shown by security: +1s765ms
,I/AMMetaDataParserService( 4325): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 4325): getResourceTypeNamexml
,I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1019): mDVFSHelper.release()
I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{1664d02f u0 com.test.thalitest/.MainActivity t11} time:47238
,D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,W/Auth    ( 1812): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/Timeline( 4290): Timeline: Activity_idle id: android.os.BinderProxy@2ae60dd3 time:47256
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/GCoreFlp( 1812): No location to return for getLastLocation()
,W/FusedLocationProvider( 1812): location=null
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 4325): took 2.608646ms for 0*0 texture 0
,I/GCoreUlr( 1812): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/ActivityManager( 1019): Killing 3758:com.sec.factory.camera/1000 (adj 15): empty #31
,I/GFX generate_partition_tables( 4325): took 6.287031ms for 0*0 texture 0
,I/GFX raster( 4325): took 10.215624ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb8483d78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8484958 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4325): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/ManifestProvider( 4511): onCreate()
,I/GCoreUlr( 1812): Unbound from all location providers
I/GCoreUlr( 1812): Place inference reporting - stopped
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.836615ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb8483d78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8487ff8 counterpartCT=4 counterpartW=96 counterparth=96
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 4325): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3758/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/NetworkSettingsReceiver( 4511): onReceive: android.intent.action.BOOT_COMPLETED
,W/art     ( 3856): Suspending all threads took: 5.640ms
,I/SurfaceFlinger(  258): id=11 Removed uhalitest (7/8)
,I/SurfaceFlinger(  258): id=11 Removed uhalitest (-2/8)
,I/SamsungIME( 1885): getCurrentCandidateView
,I/KnoxUsageLogPro( 4462): savePreference: key = previous_elapsed_time value = 46654
,W/System.err( 4511): java.lang.NoSuchMethodException: isEnabled []
,W/System.err( 4511): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 4511): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
W/System.err( 4511): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
W/System.err( 4511): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
W/System.err( 4511): 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
W/System.err( 4511): 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
W/System.err( 4511): 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
W/System.err( 4511): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 4511): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 4511): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 4511): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4511): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 4511): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 4511): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4511): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4511): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 4511): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SBrowserFeatureFlag( 4511): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@3101ee99
,D/SBrowserFeatureFlag( 4511): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 4511): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4562): MountEmulatedStorage(),
E/Zygote  ( 4562): v2
I/libpersona( 4562): KNOX_SDCARD checking this for 10131
I/libpersona( 4562): KNOX_SDCARD not a persona
D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,I/SELinux ( 4562): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4562): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4562 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 3778:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
,D/SamsungIME( 1885): Dismiss ExpandCandiate
,E/SELinux ( 4562): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4562): TimaSignature is unavailable
,D/ActivityThread( 4562): Added TimaKeyStore provider
,I/GCoreUlr( 1812): DispatchingService.onDestroy()
,I/GCoreUlr( 1812): Stopping handler for UlrDispSvcFast
,D/JsMessageQueue( 4290): Set native->JS mode to OnlineEventsBridgeMode
,W/GCoreFlp( 1812): No location to return for getLastLocation()
,W/FusedLocationProvider( 1812): location=null
,W/ResourcesManager( 4526): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,I/GCoreUlr( 1812): Unbound from all location providers
I/GCoreUlr( 1812): Place inference reporting - stopped
,W/ResourcesManager( 4526): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4526): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 4562): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4562): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4562): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 4325): took 2.489688ms for 0*0 texture 0
,I/SamsungIME( 1885): getDebugLevel  : 0x4f4c
,I/GFX generate_partition_tables( 4325): took 7.579897ms for 0*0 texture 0
,I/GFX raster( 4325): took 11.054115ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb81dd988 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8484958 counterpartCT=4 counterpartW=96 counterparth=96
,I/AuthZen ( 2070): Signing key fetched successfully!
,I/AMMetaDataParserService( 4325): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/libprocessgroup( 1019): failed to open /acct/uid_10095/pid_3778/cgroup.procs: No such file or directory
,W/BaseAppContext( 2070): Using Auth Proxy for data requests.
,D/daemonapp( 1828): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ResourcesManager( 4526): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4526): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4526): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/DBG_DM  ( 3620): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.596718ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb84a3f38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84a54d8 counterpartCT=4 counterpartW=96 counterparth=96
,D/a       ( 2070): Opening database auth.proximity.permit_store...
,I/AMMetaDataParserService( 4325): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,D/AuthZenTransactionCache( 2070): Initialized cache in: /data/data/com.google.android.gms/files
,W/ResourcesManager( 4526): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 4526): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/AuthZenTransactionCache( 2070): Clearing transaction cache
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.939843ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb84a49d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8487ff8 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4582): MountEmulatedStorage()
E/Zygote  ( 4582): v2
I/libpersona( 4582): KNOX_SDCARD checking this for 10037
I/libpersona( 4582): KNOX_SDCARD not a persona
,I/SELinux ( 4582): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/AMMetaDataParserService( 4325): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532,
I/ActivityManager( 1019): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4582 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 4582): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4582): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/SamsungIME( 1885): getDebugLevel  : 0x4f4c
I/chromium( 4290): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 4290): 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1885): KeybaordView init() : load resources
,D/PersistentNotificationBroadcastReceiver( 1812): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/GAV2    ( 3734): Thread[GAThread,5,main]: No campaign data found.
,I/Icing   ( 2070): updateResources: need to parse f{com.google.android.gms}
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4602): MountEmulatedStorage()
E/Zygote  ( 4602): v2
I/libpersona( 4602): KNOX_SDCARD checking this for 10135
D/TimaKeyStoreProvider( 4582): TimaSignature is unavailable
I/libpersona( 4602): KNOX_SDCARD not a persona
D/ActivityThread( 4582): Added TimaKeyStore provider
I/SELinux ( 4602): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4602): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4602): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4602 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/SamsungIME( 1885): getCurrentKeyboard
I/SamsungIME( 1885): getTextKeyboard
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.633490ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb84a54d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8242f78 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 4602): TimaSignature is unavailable
,D/ActivityThread( 4602): Added TimaKeyStore provider
,I/AMMetaDataParserService( 4325): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,W/ResourcesManager( 4582): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.732396ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb8487ff8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8484958 counterpartCT=4 counterpartW=96 counterparth=96
,D/SamsungIME( 1885): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/AMMetaDataParserService( 4325): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.579323ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb8242f78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8484958 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4602): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 4602): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4602): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4602): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4602): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 4620): MountEmulatedStorage(),
E/Zygote  ( 4620): v2
I/libpersona( 4620): KNOX_SDCARD checking this for 10026
I/libpersona( 4620): KNOX_SDCARD not a persona
I/SELinux ( 4620): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4620 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 4620): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4620): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/CalendarProvider2( 4582): CalendarProvider2.onCreate() called
D/jxcore_app_log( 4290): JniHelper::setJavaVM(0xb80e9448), pthread_self() = -1199308200
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4290): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4290):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4290):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4290):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4290):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4290): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e88eabe added. We now have 1 listener(s)
,I/AMMetaDataParserService( 4325): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,D/TimaKeyStoreProvider( 4620): TimaSignature is unavailable
,D/ActivityThread( 4620): Added TimaKeyStore provider
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:assistant
I/AMMetaDataParserService( 4325): Resource data:2131034113
,I/AMMetaDataParserService( 4325): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 4325): getResourceTypeNamexml
E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.816667ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb8483d78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8484958 counterpartCT=4 counterpartW=96 counterparth=96
W/art     ( 4350): Suspending all threads took: 6.181ms
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4290): setBluetoothMacAddress: 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4290): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4290): setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,I/AMMetaDataParserService( 4325): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4290): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4290):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4290):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4290):     - Bluetooth MAC address: 08:EC:A9:50:76:27
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4290):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4290):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4290):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4290):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4290):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4290):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4290): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e64f4ca added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4290): addListener: New listener added - the number of listeners is now 1
,D/SensorService( 1019): [SO] -0.421 0.172 9.883
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4290): setDiscoveryMode: Discovery mode BLE is supported
,I/ActivityManager( 1019): Killing 3801:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4642): MountEmulatedStorage()
E/Zygote  ( 4642): v2
I/libpersona( 4642): KNOX_SDCARD checking this for 10141
I/libpersona( 4642): KNOX_SDCARD not a persona
,I/SELinux ( 4642): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1019): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4642 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 4642): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4642): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  319): Explicit concurrent mark sweep GC freed 8705(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 624us total 51.464ms
,W/art     ( 4290): Suspending all threads took: 14.936ms
D/TimaKeyStoreProvider( 4642): TimaSignature is unavailable
E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityThread( 4642): Added TimaKeyStore provider
,I/art     ( 4290): Background partial concurrent mark sweep GC freed 9999(840KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 8MB/14MB, paused 18.771ms total 88.854ms
I/chromium( 4290): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 19.436ms
I/GFX raster( 4325): took 0.987917ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb8483d78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8484958 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4642): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4642): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4642): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4642): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 611us total 24.658ms
,I/AMMetaDataParserService( 4325): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/GAV2    ( 3856): Thread[GAThread,5,main]: No campaign data found.
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,I/System.out( 4350): INFO:Resource not found:/Common.properties Using default values
,D/SSRM:n  ( 1019): SIOP:: AP = 420
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/PCWCLIENTTRACE_AccountAppFacade2_0( 3996): unregister AuthInfo UpdateReceiver v2.0
,W/libprocessgroup( 1019): failed to open /acct/uid_10098/pid_3801/cgroup.procs: No such file or directory
,E/Watchdog( 1019): !@Sync 1
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.659948ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb81dd988 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8484958 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4325): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/SettingsProvider( 1019): name = audio_safe_volume_state
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,I/DBG_DM  ( 3620): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,D/Finsky  ( 4620): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.602760ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb84a3f38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8484958 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4325): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.820781ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb84a49d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80f15a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4325): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/Process ( 4526): Sending signal. PID: 4526 SIG: 9
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4689): MountEmulatedStorage(),
E/Zygote  ( 4689): v2
I/libpersona( 4689): KNOX_SDCARD checking this for 10068
I/libpersona( 4689): KNOX_SDCARD not a persona
,I/SELinux ( 4689): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4689): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4689 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,E/SELinux ( 4689): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId,
,I/ActivityManager( 1019): Process com.sec.android.app.sns3 (pid 4526)(adj 0) has died(29,597)
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4697): MountEmulatedStorage(),
E/Zygote  ( 4697): v2
I/libpersona( 4697): KNOX_SDCARD checking this for 10031
I/SELinux ( 4697): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4697): KNOX_SDCARD not a persona,
,I/SELinux ( 4697): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 4697): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 4325): took 0.705781ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb84a54d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8484958 counterpartCT=4 counterpartW=96 counterparth=96
I/ActivityManager( 1019): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4697 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 4325): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/TimaKeyStoreProvider( 4689): TimaSignature is unavailable
,D/ActivityThread( 4689): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 4697): TimaSignature is unavailable
,D/ActivityThread( 4697): Added TimaKeyStore provider
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.689688ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb8487ff8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80f15a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4325): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.529010ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb8242f78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8484958 counterpartCT=4 counterpartW=96 counterparth=96
,D/BadgeProvider( 4689): onCreate
D/BadgeProvider( 4689): DatabaseHelper
,I/AMMetaDataParserService( 4325): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 4689): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge',
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 4325): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 4325): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
,I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4325): getResourcePackageName:assistant
I/AMMetaDataParserService( 4325): Resource data:2131034112
E/SMD     (  292): DCD OFF
,E/Zygote  ( 4725): MountEmulatedStorage()
I/libpersona( 4725): KNOX_SDCARD checking this for 10142
E/Zygote  ( 4725): v2
I/libpersona( 4725): KNOX_SDCARD not a persona
,I/SELinux ( 4725): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/AMMetaDataParserService( 4325): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 4325): getResourceTypeNamexml
E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.645990ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb84a3f38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b3918 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 4725): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1019): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4725 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/AMMetaDataParserService( 4325): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
I/ActivityManager( 1019): Killing 2723:com.google.android.apps.plus/u0a117 (adj 15): empty #31
,E/SELinux ( 4725): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4725): TimaSignature is unavailable
,D/ActivityThread( 4725): Added TimaKeyStore provider
,W/ResourcesManager( 4725): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/libprocessgroup( 1019): failed to kill pid 2723: No such process
,D/Launcher.Model( 1497): reloadBadges entered.
,D/BadgeProvider( 4689): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 4689): sendNotify, [notify] : null
D/BadgeProvider( 4689): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4689): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4689): update, [UpdateCount] : 1
,V/AlarmManager( 1019): waitForAlarm result :8
,W/libprocessgroup( 1019): failed to open /acct/uid_10117/pid_2723/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4756): MountEmulatedStorage()
E/Zygote  ( 4756): v2
,I/libpersona( 4756): KNOX_SDCARD checking this for 1000
I/libpersona( 4756): KNOX_SDCARD not a persona
,I/SELinux ( 4756): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4756): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1019): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4756 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 4756): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.840365ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb84a3f38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb80f15a0 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4756): TimaSignature is unavailable
,D/ActivityThread( 4756): Added TimaKeyStore provider
,I/ActivityManager( 1019): Killing 1719:com.android.defcontainer/u0a3 (adj 15): empty #31
,I/AMMetaDataParserService( 4325): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,I/DBG_POLICYDM( 3821): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_POLICYDM( 3821): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 4620): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.646875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb8484958 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb84b3918 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1019): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4776 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 4776): MountEmulatedStorage()
I/libpersona( 4776): KNOX_SDCARD checking this for 10032
E/Zygote  ( 4776): v2
I/libpersona( 4776): KNOX_SDCARD not a persona
,I/SELinux ( 4776): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1019): Killing 3956:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
I/SELinux ( 4776): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4776): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1019): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/art     ( 4290): Suspending all threads took: 8.381ms
,I/art     ( 4290): Background sticky concurrent mark sweep GC freed 31282(2MB) AllocSpace objects, 0(0B) LOS objects, 7% free, 18MB/19MB, paused 9.388ms total 43.699ms
,I/AMMetaDataParserService( 4325): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,W/Settings( 4620): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/jxcore-log( 4290): Initializing JXcore engine
W/jxcore-log( 4290): JXcore engine is ready
,D/TimaKeyStoreProvider( 4776): TimaSignature is unavailable
,D/ActivityThread( 4776): Added TimaKeyStore provider
,W/Settings( 4620): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.626979ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb80f15a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b3918 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1019): getTasks: caller 10142 does not hold GET_TASKS; limiting output
,W/ActivityManager( 1019): getTasks: caller 10141 does not hold GET_TASKS; limiting output
,I/Process ( 4642): Sending signal. PID: 4642 SIG: 9
,I/AMMetaDataParserService( 4325): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,I/Process ( 4725): Sending signal. PID: 4725 SIG: 9
,I/ActivityManager( 1019): Process com.android.exchange (pid 4725)(adj 11) has died(48,601)
,W/libprocessgroup( 1019): failed to open /acct/uid_10003/pid_1719/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10055/pid_3956/cgroup.procs: No such file or directory
,E/lowmemorykiller(  255): Error writing /proc/4642/oom_score_adj; errno=22
,I/ActivityManager( 1019): Killing 3856:com.google.android.gm/u0a99 (adj 15): empty #31
,I/ActivityManager( 1019): Killing 3976:com.fmm.dm/1000 (adj 15): empty #32
,D/Volley  ( 4620): [728] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 4620): [721] DiskBasedCache.clear: Cache cleared.
,D/Ads     ( 4620): Skipping gmscore version check
,I/ActivityManager( 1019): Process com.android.email (pid 4642)(adj 11) has died(58,603)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 4620): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4620): [1] Libraries$2.run: Finished loading 1 libraries.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3620): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,E/Zygote  ( 4796): MountEmulatedStorage()
,E/Zygote  ( 4796): v2
I/libpersona( 4796): KNOX_SDCARD checking this for 1000
I/libpersona( 4796): KNOX_SDCARD not a persona
,I/SELinux ( 4796): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4796): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1019): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4796 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 4796): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/audit   ( 2030): type=1400 msg=audit(1457642259.066:205): avc:  denied  { ioctl } for  pid=4640 comm="Thread-662" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 2030):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 2030): type=1300 msg=audit(1457642259.066:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=932878f8 items=0 ppid=319 ppcomm=main pid=4640 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-662" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 2030): type=1320 msg=audit(1457642259.066:205): 
,D/TimaKeyStoreProvider( 4796): TimaSignature is unavailable
,D/ActivityThread( 4796): Added TimaKeyStore provider
,W/jxcore-log( 4290): Starting JXcore engine
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3976/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10099/pid_3856/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.group.SubGrou,pDetailActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:assistant
I/AMMetaDataParserService( 4325): Resource data:2131034113
I/AMMetaDataParserService( 4325): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 4325): getResourceTypeNamexml
E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.819583ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb8483d78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb84a54d8 counterpartCT=4 counterpartW=96 counterparth=96
,E/SPPClientService( 4776): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4776): [PushClientApplication] Push log off : This is Ship build version
,I/AMMetaDataParserService( 4325): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/SPPClientService( 4776): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,D/SPPClientService( 4776): PushLog.txt file is not deleted.
,D/SPPClientService( 4776): PushLog.txt file is not deleted.
,D/SPPClientService( 4776): ============PushLog. stop!
,I/art     ( 1631): Explicit concurrent mark sweep GC freed 3452(139KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 4MB/6MB, paused 704us total 31.829ms
,D/SecurityLogAgent( 4796): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4796): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 4796): StateMachine : Current State = 1
,D/SecurityLogAgent( 4796): BootReceiver : completed task. Failed to return wakelock . 
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 4325): took 0.825208ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb8483d78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb81dd988 counterpartCT=4 counterpartW=96 counterparth=96
W/art     ( 4350): Suspending all threads took: 24.381ms
D/Finsky  ( 4620): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/AMMetaDataParserService( 4325): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
E/Zygote  ( 4815): MountEmulatedStorage()
E/Zygote  ( 4815): v2
I/libpersona( 4815): KNOX_SDCARD checking this for 10148
I/libpersona( 4815): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4815 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
I/SELinux ( 4815): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Killing 4022:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
I/SELinux ( 4815): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4815): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/TimaKeyStoreProvider( 4815): TimaSignature is unavailable
,D/Finsky  ( 4620): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/ActivityThread( 4815): Added TimaKeyStore provider
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.599479ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb84a49d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b8e30 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 4325): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.603490ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb84a3f38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b3918 counterpartCT=4 counterpartW=96 counterparth=96
,W/jxcore-log( 4290): Platform android
W/jxcore-log( 4290): 
W/jxcore-log( 4290): Process ARCH arm
W/jxcore-log( 4290): 
,I/AMMetaDataParserService( 4325): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 4325): took 0.816303ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb8487ff8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81dd988 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4833): MountEmulatedStorage(),
E/Zygote  ( 4833): v2
I/libpersona( 4833): KNOX_SDCARD checking this for 10036,
I/libpersona( 4833): KNOX_SDCARD not a persona
,I/SELinux ( 4833): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/AMMetaDataParserService( 4325): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532,
,I/SELinux ( 4833): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1019): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4833 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/SELinux ( 4833): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Killing 4045:com.google.android.talk/u0a102 (adj 15): empty #31
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.747448ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb80f15a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8242f78 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4325): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,W/libprocessgroup( 1019): failed to open /acct/uid_10056/pid_4022/cgroup.procs: No such file or directory
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.677239ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb84b8e30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84b28e8 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4833): TimaSignature is unavailable
D/ActivityThread( 4833): Added TimaKeyStore provider
,I/AMMetaDataParserService( 4325): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/SQLiteLog( 4815): (284) automatic index on shooting_modes(title_id)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4850): MountEmulatedStorage()
E/Zygote  ( 4850): v2
I/libpersona( 4850): KNOX_SDCARD checking this for 1000
I/libpersona( 4850): KNOX_SDCARD not a persona,
,I/ActivityManager( 1019): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4850 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 4850): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4850): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4850): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4850): TimaSignature is unavailable
,D/ActivityThread( 4850): Added TimaKeyStore provider
,W/libprocessgroup( 1019): failed to open /acct/uid_10102/pid_4045/cgroup.procs: No such file or directory
,I/ActivityManager( 1019): Killing 4064:com.fmm.ds/1000 (adj 15): empty #31
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4325): took 0.521615ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb84b3918 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84891b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4325): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 32914(1749KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 22MB/34MB, paused 2.802ms total 169.289ms
,V/AlarmManager( 1019): waitForAlarm result :4
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
W/ContextImpl( 4325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
I/CalendarProvider2( 4582): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,V/AlarmManager( 1019): waitForAlarm result :4
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4867): MountEmulatedStorage()
E/Zygote  ( 4867): v2
I/libpersona( 4867): KNOX_SDCARD checking this for 10117
I/libpersona( 4867): KNOX_SDCARD not a persona
,I/SELinux ( 4867): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4867): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 4867): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService: pid=4867 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:assistant
I/AMMetaDataParserService( 4325,): Resource data:2131165203
,W/ResourcesManager( 4325): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4325): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4325): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 4325): getResourceTypeNamexml
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,D/TimaKeyStoreProvider( 4867): TimaSignature is unavailable
,D/ActivityThread( 4867): Added TimaKeyStore provider
,I/ActivityManager( 1019): Killing 4084:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4064/cgroup.procs: No such file or directory
,I/GFX construct_block_size_descriptor_2d second part( 4325): took 3.462813ms for 0*0 texture 0
,I/ActivityManager( 1019): Killing 4110:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
W/ResourcesManager( 4867): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/GFX generate_partition_tables( 4325): took 18.005939ms for 0*0 texture 0
,I/GFX raster( 4325): took 22.176773ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb880a588 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb880b1e8 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 4325): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/SA      ( 4833): [SSP] onCreated
,I/GFX construct_block_size_descriptor_2d second part( 4325): took 2.556979ms for 0*0 texture 0
,I/GFX generate_partition_tables( 4325): took 5.344895ms for 0*0 texture 0
,I/GFX raster( 4325): took 9.145935ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb8814f60 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb88151a0 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 4325): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,I/Icing   ( 2070): Internal init done: storage state 0
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 4325): took 0.813698ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb8814f60 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb88151a0 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 4325): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,I/iu.UploadsManager( 2070): End new media; added: 0, uploading: 0, time: 189 ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Icing   ( 2070): Service broker callback failed: android.os.DeadObjectException
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 4325): took 0.692917ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb8814f60 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb88151a0 counterpartCT=4 counterpartW=80 counterparth=80
,W/libprocessgroup( 1019): failed to open /acct/uid_10058/pid_4084/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4110/cgroup.procs: No such file or directory
,I/SA      ( 4833): [TPM] There is no property file
,I/SA      ( 4833): [SCU] isHaveSA() - false
,I/SA      ( 4833): [TPM] getModelProperty : null
I/SA      ( 4833): [TPM] getCSCProperty : null
,I/SA      ( 4833): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4833): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4833): [DM] TFT FEATURE: false
,I/AMMetaDataParserService( 4325): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,I/SA      ( 4833): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4833): [DM] init START
,I/Icing   ( 2070): Post-init done
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 4325): took 0.629166ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb88151a0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb880aaf0 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 4325): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,I/SA      ( 4833): [DM] This device is not a Vodafone
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 4290): JXcore Cordova bridge is ready!
I/jxcore-log( 4290): 
,W/jxcore-log( 4290): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 4290): execute: REQUEST_ACCESS_COARSE_LOCATION
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ResourceType( 4833): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4833): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4833): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4833): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
W/ResourceType( 4833): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4833): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4833): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4833): No package identifier when getting value for resource number 0x00000000
,E/        ( 4325): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 4325): took 0.643646ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4325): Bitmap=0xb88151a0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8813360 counterpartCT=4 counterpartW=80 counterparth=80
,E/jxcore  ( 4290): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4290): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/AMMetaDataParserService( 4325): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,I/chromium( 4290): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,D/FocusedStackFrame( 1019): Set to : 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,W/ResourceType( 4833): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1019): Focused application set to: xxxx
W/ResourceType( 4833): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4833): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
D/InputDispatcher( 1019): Focus left window: 4290
W/ResourceType( 4833): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 4833): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 4833): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 4833): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 4833): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 4833): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 4833): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
,W/ResourceType( 4833): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4833): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4833): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 4833): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 4833): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 4833): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (154 us)
,W/ResourceType( 4833): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 4833): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
W/ContextImpl( 4325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4325): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/SA      ( 4833): [SCU] isHaveSA() - false
I/SA      ( 4833): support phone number id : false
I/SA      ( 4833): [DM] Supports Ref Jpn : true
I/SA      ( 4833): [DM] init END
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/PluginManager( 4290): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 52ms. Plugin should use CordovaInterface.getThreadPool().
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1019): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowManager( 1019): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,V/WindowOrientationListener( 1019): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,I/SA      ( 4833): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 4833): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1019): [SO] activate (ident=0xb8ac8d98, enabled=0)
,I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/SA      ( 4833): [OR] onReceive END
,D/Launcher( 1497): onRestart, Launcher: 822210201
,D/Launcher( 1497): onStart, Launcher: 822210201
,D/Launcher.HomeView( 1497): onStart
D/Launcher( 1497): onResume, Launcher: 822210201
,D/SettingsProvider( 1019): name = kids_home_mode
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10006
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,D/Launcher.HomeView( 1497): onResume
,D/SensorManager( 1019): unregisterListener ::   
,I/Sensors ( 1019): AccelerometerSensor(0) setDelay : 200000000(ns)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SensorService( 1019): [SO] changed settle time [0]
D/SensorService( 1019): [SO] setDelay [200000000]
D/SensorService( 1019): [SO] activate (ident=0xb8a2c470, enabled=1)
D/SensorService( 1019): [SO] AR_init
I/Sensors ( 1019): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1019): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/Launcher( 1497): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1497): onResume
D/ActivityManager( 1019): handle home activity for 0
I/WallpaperManagerService( 1019): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1019): post home show event for user 0
D/WallpaperManagerService( 1019):  force update = false; persona id = 0; current user =0; current persona = 0
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0,
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,I/SurfaceFlinger(  258): id=13 createSurf (540x960),1 flag=4, Mauncher
,D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/SA      ( 4833): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4833): [ODM] queryOpenData(key= GEO_IP )
,D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 4325): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4325): getResourcePackageName:assistant
I/AMMetaDataParserService( 4325): Resource data:2131099648
,D/InputDispatcher( 1019): Focus entered window: 1497
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1497): log_dcs ThreadedRenderer::initialize entered! 
,I/SA      ( 4833): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4833): [LBE] REF_JPN : true
I/SA      ( 4833): [BDC] create
,W/ResourcesManager( 4325): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4325): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4325): getResourceTypeNamexml
,I/DBG_DM  ( 3620): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,D/Launcher( 1497): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 4290): showStatusIcon on inactive InputConnection
,I/AMMetaDataParserService( 4325): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/SamsungIME( 1885): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/SA      ( 4833): [DBMV2] getEmailID
,I/SA      ( 4833): [DBMV2] getDataV02ForItems
,I/SA      ( 4833): [SSP] query invoked
,I/Timeline( 1497): Timeline: Activity_idle id: android.os.BinderProxy@21847a76 time:50866
,D/PersonaManager( 1019): isKioskContainerExistOnDevice
,I/SA      ( 4833): [SCU] get signed id from samsung account2.0 DB.
,I/AMMetaDataParserService( 4325): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 4325): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/ActivityManager( 1019): Displayed Component not be shown by security: +175ms
,I/SA      ( 4833): [SCU] get signed id from samsung account1.0 DB.
,I/splitIntent( 1019): Queue : background intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart  false.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1019): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1019): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1019): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/SA      ( 4833): [BDC] destroy
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4325): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1812): callingUid 10011, callindPid: 1812
,I/AMMetaDataParserService( 4325): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1812): [247] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 4325): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/SensorService( 1019): [SO] Reset Rotation Old [100], Init [1]
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:assistant
I/AMMetaDataParserService( 4325): Resource data:2131099648
,D/LocationInitializer( 2070): Restart initialization of location
,I/AMMetaDataParserService( 4325): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4325): getResourceTypeNamexml
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4325): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/AMMetaDataParserService( 4325): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/AuthorizationBluetoothService( 1812): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4325): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4325): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,V/GLSActivity( 1812): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,I/AMMetaDataParserService( 4325): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1812): No location to return for getLastLocation()
W/FusedLocationProvider( 1812): location=null
,I/ActivityManager( 1019): Killing 3885:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,I/AMMetaDataParserService( 4325): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:assistant
I/AMMetaDataParserService( 4325): Resource data:2131099648
,I/AMMetaDataParserService( 4325): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4325): getResourceTypeNamexml
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4325): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,I/AMMetaDataParserService( 4325): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,I/AMMetaDataParserService( 4325): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/SensorService( 1019): [SO] currT = 51161149000, prevT = 50681140000, diff = 480009000, [-0.421 0.172 9.883]
,D/SensorService( 1019): [SO] -0.421 0.172 9.883
D/SensorService( 1019): [SO] [100 -> 255]
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4915): MountEmulatedStorage()
,E/Zygote  ( 4915): v2
I/libpersona( 4915): KNOX_SDCARD checking this for 10041
I/libpersona( 4915): KNOX_SDCARD not a persona
,I/SELinux ( 4915): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4915): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/AMMetaDataParserService( 4325): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
E/SELinux ( 4915): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.widget.MmsWidgetProvider: pid=4915 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/AMMetaDataParserService( 4325): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1019): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/TimaKeyStoreProvider( 4915): TimaSignature is unavailable
,I/art     (  319): Explicit concurrent mark sweep GC freed 8703(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 26.159ms
D/ActivityThread( 4915): Added TimaKeyStore provider
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 18.905ms
W/ResourcesManager( 4915): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4915): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4915): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4915): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4915): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4325): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 16.817ms
,W/libprocessgroup( 1019): failed to open /acct/uid_10008/pid_3885/cgroup.procs: No such file or directory
,I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{12c835a7 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t10} time:51303,
,I/ActivityManager( 1019): Killing 4129:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,I/SurfaceFlinger(  258): id=12 Removed NainActivit (7/8)
,I/SurfaceFlinger(  258): id=12 Removed NainActivit (-2/8)
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:assistant
I/AMMetaDataParserService( 4325): Resource data:2131099648
,I/AMMetaDataParserService( 4325): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4325): getResourceTypeNamexml
,I/AMMetaDataParserService( 4325): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ScreenOrientationListener( 4290): Removing an inexistent observer!
,I/AMMetaDataParserService( 4325): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 4325): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/Mms/MmsApp( 4915): [start]    onCreate() consume time = 0.0
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/libprocessgroup( 1019): failed to open /acct/uid_10013/pid_4129/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/AMMetaDataParserService( 4325): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/AMMetaDataParserService( 4325): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/AMMetaDataParserService( 4325): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:assistant
I/AMMetaDataParserService( 4325): Resource data:2131099648
,I/AMMetaDataParserService( 4325): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4325): getResourceTypeNamexml
,I/AMMetaDataParserService( 4325): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/AMMetaDataParserService( 4325): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 4325): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/ValidateNoPeople( 1019): mEvictionCount: 0
,I/AMMetaDataParserService( 4325): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/AMMetaDataParserService( 4325): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/CustomFrequencyManagerService( 1019): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,W/art     ( 4915): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 143.740ms
,I/AMMetaDataParserService( 4325): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:assistant
I/AMMetaDataParserService( 4325): Resource data:2131099648
,I/AMMetaDataParserService( 4325): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4325): getResourceTypeNamexml
,I/AMMetaDataParserService( 4325): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/AMMetaDataParserService( 4325): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 4325): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/AMMetaDataParserService( 4325): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/AMMetaDataParserService( 4325): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/AMMetaDataParserService( 4325): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/Mms/ArtClassLoader( 4915): init before art
,D/Mms/TelephonyPermission( 4915): start operation mode monitor
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 4325): Resource data:Loop for running activ,itycom.android.mms.ui.MmsRetryActivity
W/ContextImpl( 4325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4325): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService,( 4325): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
W/ResourcesManager( 4915): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/Mms/TelephonyPermission( 4915): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 4915): isDefault true
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:assistant
I/AMMetaDataParserService( 4325): Resource data:2131165197
W/ResourcesManager( 4325): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/Mms/MmsApp( 4915): onCreate() com.android.mms
W/ResourcesManager( 4325): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 4325): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 4325): getResourceTypeNamexml
,D/Mms/MmsApp( 4915): [start]    initCountryIso consume time = 309.324114
D/CountryDetector( 1019): The first listener is added
I/AMMetaDataParserService( 4325): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
D/Mms/MmsApp( 4915): [end]    initCountryIso consume time = 8.818802
D/Mms/MmsConfig( 4915): [start]    MmsConfig.init() consume time = 0.570052
I/AMMetaDataParserService( 4325): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
D/Mms/MmsConfig( 4915): before partial update
,I/AMMetaDataParserService( 4325): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/Mms/MmsConfig( 4915): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 4915): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 4915): isAuth is false
,D/Mms/MmsConfig( 4915): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1468): query,matched:2117, calling pid = 4915,
,I/AMMetaDataParserService( 4325): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624,
,D/TP/MmsSmsProvider( 1468): match 2117:Elapsed time : 3.635 ms,
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4325): getResourcePackageName:assistant
I/AMMetaDataParserService( 4325): Resource data:2131165197
,I/AMMetaDataParserService( 4325): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 4325): getResourceTypeNamexml
,D/EasySignUpManager_1.0.1( 4915): isAuth is false
,D/EasySignUpManager_1.0.1( 4915): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 4915): mps_code.dat does not exist
,E/CscParser( 4915): customer_path =/system/csc/customer.xml
,E/CscParser( 4915): fileName + /system/csc/customer.xml
,E/CscParser( 4915): mps_code.dat does not exist
,E/CscParser( 4915): customer_path =/system/csc/customer.xml
E/CscParser( 4915): fileName + /system/csc/customer.xml
,I/AMMetaDataParserService( 4325): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/CscParser( 4915): getInstance fileName =/system/csc/customer.xml
,I/AMMetaDataParserService( 4325): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
D/Mms/MmsConfig( 4915):  enable multiwindow = false
,E/Mms/MessageUtils( 4915): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 4915): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 4915): [end]    init() consume time = 90.392188
,D/Mms/Contact( 4915): [start]    init() consume time = 0.636458
,I/AMMetaDataParserService( 4325): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/Mms/Contact( 4915): [end]    init consume time = 8.508698
,D/TP/MmsSmsProvider( 1468): query,matched:13, calling pid = 4915
,D/TP/MmsSmsProvider( 1468): match 13:Elapsed time : 1.396 ms
,I/AMMetaDataParserService( 4325): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.cooliris.media.Gallery
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:assistant
I/AMMetaDataParserService( 4325): Resource data:2131165197
,I/AMMetaDataParserService( 4325): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 4325): getResourceTypeNamexml
,D/Mms/DraftCache( 4915): [start]    rebuildCache consume time = 15.961562
,D/TP/MmsSmsProvider( 1468): query,matched:12, calling pid = 4915
,D/TP/MmsSmsProvider( 1468): match 12:Elapsed time : 2.208 ms
,D/Mms/DraftCache( 4915): [end]    rebuildCache consume time = 8.839375
,I/AMMetaDataParserService( 4325): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/Mms/MethodReflector( 4915): getSubId is called
,D/Mms/TelephonyUtils( 4915): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4915): getTelephonyProperty is called
D/Mms/DownloadManager( 4915): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4915): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4915): auto download without roaming -> true
,D/Mms/DownloadManager( 4915): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/MethodReflector( 4915): getSubId is called
,D/Mms/MethodReflector( 4915): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 4915): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 4915): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 4915): getTelephonyProperty is called
D/Mms/DownloadManager( 4915): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 4915): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 4915): auto download without roaming -> true
D/Mms/DownloadManager( 4915): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 4915): auto download during roaming secondary -> false
D/Mms/DownloadManager( 4915): mAutoDownload ------> true
,I/DBG_DM  ( 3620): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,I/AMMetaDataParserService( 4325): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/ComposerPerformance( 4915): 1457642261072 ms / [DONE] Composer constructor
,E/CII     ( 4915): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 4915): ReservationManager()
,I/Mms/ReservationManager( 4915): resetAfterConnected()
,D/TP/MmsSmsProvider( 1468): query,matched:7, calling pid = 4915
,D/TP/MmsSmsProvider( 1468): match 7:Elapsed time : 2.159 ms
,I/Mms/ReservationManager( 4915): getReservedSendMessageCount(): retMessageCount=0,
D/Mms/Conversation( 4915): [start]    init() consume time = 28.587136
I/AMMetaDataParserService( 4325): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/TP/MmsSmsProvider( 1468): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1468): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1468): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1468): sUpgradeVersion = 0, db.getVersion() = 81
,D/Mms/MmsApp( 4915): [end]    onCreate() consume time = 10.799948
,E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id),
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id),
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
,I/AMMetaDataParserService( 4325): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624,
D/TP/MmsSmsProvider( 1468): delete threadId: 9223372036854775807,
D/TP/MmsSmsProvider( 1468): need read changed broadcast:false
,D/Mms/Conversation( 4915): [end]    init consume time = 13.879218
D/Mms/MessagingNotification( 4915): [start]    init() consume time = 1.731407
,D/Mms/MessagingNotification( 4915): [end]    init consume time = 2.00401
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
W/ContextImpl( 4325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.Pho,toNote
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
D/Mms/DownloadManager( 4915): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 4915): roaming ------> false, mSimSlot = 0
,D/Mms/MethodReflector( 4915): getSubId is called
D/Mms/TelephonyUtils( 4915): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4915): getTelephonyProperty is called
D/Mms/DownloadManager( 4915): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4915): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4915): auto download without roaming -> true
D/Mms/DownloadManager( 4915): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/DownloadManager( 4915): mAutoDownload ------> true
,D/Mms/Synchronizer( 4915): [start]    doSync consume time = 7.318542
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 4325): getResourcePackageName:assistant
I/AMMetaDataParserService( 4325): Resource data:2131099648
,I/ActivityManager( 1019): Killing 4146:com.wssnps/1000 (adj 15): empty #31
,D/Mms/SpamFilter( 4915): [start]    SpamFilter fill() begin consume time = 2.774687
,D/TP/MmsSmsProvider( 1468): query,matched:0, calling pid = 4915
V/TP/MmsSmsProvider( 1468): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1468): match 0:Elapsed time : 1.748 ms
,W/ResourcesManager( 4325): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4325): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 4325): getResourceTypeNamexml
,D/TP/MmsSmsProvider( 1468): update, matched:300, calling pid = 4915
,V/TP/MmsSmsProvider( 1468): syncDBData start
,V/TP/MmsSmsProvider( 1468): syncDBData sms end
,V/TP/MmsSmsProvider( 1468): syncDBData mms end
,V/TP/MmsSmsProvider( 1468): syncDBData end
,D/Mms/Synchronizer( 4915): [end]    doSync consume time = 16.583386
,D/TP/MmsSmsProvider( 1468): query,matched:400, calling pid = 4915
,D/Mms/MessagingNotification( 4915): checkBadgeCount unreadCount=0 badgeCount=0
,D/Mms/SpamFilter( 4915): [end]    SpamFilter fill() finished consume time = 15.946875
,D/Mms/ArtClassLoader( 4915): init [DONE] art
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 4325): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,E/Zygote  ( 4947): MountEmulatedStorage(),
I/libpersona( 4947): KNOX_SDCARD checking this for 10130
E/Zygote  ( 4947): v2
I/libpersona( 4947): KNOX_SDCARD not a persona
I/SELinux ( 4947): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=4947 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,I/SELinux ( 4947): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/TP/SmsProvider( 1468): query,matched:26, calling pid = 4915
,D/TP/SmsProvider( 1468): match 26:Elapsed time : 1.161 ms
E/SELinux ( 4947): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TP/MmsSmsProvider( 1468): query,matched:6, calling pid = 4915
,D/TP/MmsSmsProvider( 1468): match 6:Elapsed time : 1.148 ms
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4146/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4947): TimaSignature is unavailable
D/ActivityThread( 4947): Added TimaKeyStore provider
,I/AMMetaDataParserService( 4325): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,W/ResourcesManager( 4947): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4947): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4962): MountEmulatedStorage()
I/libpersona( 4962): KNOX_SDCARD checking this for 10023
E/Zygote  ( 4962): v2
I/libpersona( 4962): KNOX_SDCARD not a persona
I/SELinux ( 4962): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4962 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
W/ContextImpl( 4325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,I/SELinux ( 4962): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4962): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4962): TimaSignature is unavailable
D/ActivityThread( 4962): Added TimaKeyStore provider
,I/ActivityManager( 1019): Killing 4169:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/MTPRx   ( 4248): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1019): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1019): mCursor = null
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:assistant
I/AMMetaDataParserService( 4325): Resource data:2131165220
,D/SecContentProvider2( 1019): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1019): mCursor = null
,V/MTPRx   ( 4248): sealedState: false
V/MTPRx   ( 4248): sealedUsbMassStorageState: false
E/MTPRx   ( 4248): check value of boot_completed is1
E/MTPRx   ( 4248): check booting is completed_sys.boot_completed
,E/MTPRx   ( 4248): Sd-Card path/storage/extSdCard
W/ResourcesManager( 4325): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4325): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/MTPRx   ( 4248): Status for mount/Unmount :removed
E/MTPRx   ( 4248): SDcard is not available
,W/MTPRx   ( 4248): value of connected istrue
W/MTPRx   ( 4248): value of configured istrue
W/MTPRx   ( 4248): value of mtpEnabled istrue
W/MTPRx   ( 4248): value of ptpEnabled isfalse
,E/MTPRx   ( 4248): Received USB_STATE with sdCardLaunch = 0
,I/AMMetaDataParserService( 4325): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 4325): getResourceTypeNamexml
,E/MTPRx   ( 4248): mFirstTime: false
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4169/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 4325): Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
,D/        ( 4248): MTP: reading debug level property
,E/MTPJNIInterface( 4248): Getting CryptionKey from JAVA
,E/MTPRx   ( 4248): currentUserId is 0
,E/MTPRx   ( 4248): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 4248): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 4248): is_Privatemode is NOT 1
,I/AMMetaDataParserService( 4325): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,D/SettingsProvider( 1019): name = boot_time_connected
,E/SMD     (  292): DCD OFF
,E/MTPRx   ( 4248): Sending NORMAL_BOOT to stack
,E/MTPJNIInterface( 4248): noti = 17
,D/SettingsProvider( 1019): name = mtp_usb_conditions_met
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings,.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
,I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
,I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
,I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
W/ContextImpl( 4325): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity,
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED,
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity,
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.HomeSettings
,I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
,I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
,I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
,I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
,I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
,I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 4325): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4325): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 4325): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
I/art     ( 1019): Explicit concurrent mark sweep GC freed 25696(1511KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 2.687ms total 145.196ms
D/SecContentProvider( 1019): uri = 18 selection = isUsbMediaPlayerAvailable
E/MTPRx   ( 4248): sending MTP_ICON_ENABLED to stack
I/ActivityManager( 1019): Killing 4204:com.android.managedprovisioning/u0a20 (adj 15): empty #31
I/OMACP   ( 4962): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1019): name = mtp_running_status
,D/SettingsProvider( 1019): name = mtp_usb_conditions_met
,E/MTPRx   ( 4248): else part ... so first time!!!
,E/MTPPlaObsrvr( 4248): inside setContext()
E/MTPPlaObsrvr( 4248):  inside createplafiles
,D/Mms/Omacp( 4915): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 4248): playlist count is0
E/MTPPlaObsrvr( 4248):  inside try branch createplafiles
E/MTPPlaObsrvr( 4248):  inside deleteing plas createplafiles
E/MTPPlaObsrvr( 4248): Inside registerContentObserver
,E/MtpAdbObserver( 4248): inside setContext()
,E/MtpAdbObserver( 4248): Inside registerContentObserver
W/Settings( 4248): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1019): name = mtp_running_status
,D/SettingsProvider( 1019): name = mtp_usb_conditions_met
,E/MtpService( 4248): onCreate.
,I/OMACP   ( 4962): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,V/MtpMediaDBManager( 4248): inside deleteAllDB
,I/OMACP   ( 4962): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 4962): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
I/OMACP   ( 4962): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 4962): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 4962): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 4962): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 4962): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 4962): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,D/MtpService( 1221): updating state; isCurrentUser=true, mMtpLocked=false
,I/OMACP   ( 4962): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
E/MtpService( 4248): < MTP > Registering BroadCast receiver :::::
I/OMACP   ( 4962): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 4962): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false,
I/OMACP   ( 4962): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,E/MtpService( 4248): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4983): MountEmulatedStorage()
I/libpersona( 4983): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4983): v2
I/libpersona( 4983): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4983 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 4983): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
V/MtpMediaDBManager( 4248): inside Thread updateDB
E/MtpService( 4248): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
I/SELinux ( 4983): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/MtpService( 4248): onStartCommand.
W/MTPRx   ( 4248): calling native method
E/MTPJNIInterface( 4248): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 4248): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/SELinux ( 4983): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/MtpMediaDBManager( 4248): count : 26
,E/MTPJNIInterface( 4248): < MTP > Registering BroadCast receiver :::::::
E/MTPJNIInterface( 4248): noti = 10
W/MTPRx   ( 4248): calling native method
E/MTPRx   ( 4248): Checking the driver time out
E/MTPJNIInterface( 4248): noti = 2
D/        ( 4248): deleting sockets before message queue initialization
D/        ( 4248): event handler thread is created, so set the flag
E/MTPRx   ( 4248): called native method
E/MTPJNIInterface( 4248): setting Media scanner status0
E/MTPJNIInterface( 4248): After setting Media scanner status0
E/MtpService( 4248): onStartCommand.
E/MtpService( 4248): handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
E/        ( 4248): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 4248): Getting media scanner status0
,W/MTPRx   ( 4248): notification from stack 1
,E/MTPJNIInterface( 4248): DeviceName is Thali Test (Galaxy A3)
,W/MtpMediaDBManager( 4248): sending db update complete noti to stack
E/MTPJNIInterface( 4248): noti = 29
,W/libprocessgroup( 1019): failed to open /acct/uid_10020/pid_4204/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4983): TimaSignature is unavailable
D/ActivityThread( 4983): Added TimaKeyStore provider
E/SQLiteLog( 4248): (5) database is locked
,E/MTPJNIInterface( 4248): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4248): SDcard is not available
,E/        ( 4248): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface( 4248): Status for mount/Unmount :removed,
E/MTPJNIInterface( 4248): SDcard is not available
E/SQLiteLog( 4248): (21) API call with NULL database connection pointer,
E/SQLiteLog( 4248): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4248): (21) API call with NULL database connection pointer
E/SQLiteLog( 4248): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4248): (21) API call with NULL database connection pointer
,E/SQLiteLog( 4248): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4248): (21) API call with NULL database connection pointer
E/SQLiteLog( 4248): (21) misuse at line 106108 of [9491ba7d73]
W/MTPRx   ( 4248): notification from stack 2
,D/        ( 4248): [mtp_init_device] Library open with 32 bits.
D/        ( 4248): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 4248): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 4248): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 4248):  [sua_support_present:1287] returning false 
D/        ( 4248): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
