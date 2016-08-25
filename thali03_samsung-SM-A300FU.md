#### Test 797638306764640_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-25 15:24:41.593  6598  6598 D Mms/MethodReflector: getTelephonyProperty is called
08-25 15:24:41.593  6598  6598 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-25 15:24:41.593  6598  6598 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-25 15:24:41.593  6598  6598 D Mms/DownloadManager: auto download without roaming -> true
08-25 15:24:41.593  6598  6598 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-25 15:24:41.593  6598  6598 D Mms/DownloadManager: mAutoDownload ------> true
08-25 15:24:41.593  6598  6598 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-25 15:24:41.603  6598  6815 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 28.702605
--------- beginning of system
08-25 15:24:41.603  1019  1487 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
08-25 15:24:41.603  1019  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:41.603  1019  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:41.603  1019  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:41.603  1019  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:41.613  6598  6816 D Mms/Synchronizer: [start]    doSync consume time = 11.297083
08-25 15:24:41.613  1459  2495 D TP/MmsSmsProvider: query,matched:400, calling pid = 6598
08-25 15:24:41.613  6817  6817 E Zygote  : MountEmulatedStorage()
08-25 15:24:41.613  6817  6817 E Zygote  : v2
08-25 15:24:41.613  6817  6817 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 15:24:41.613  6817  6817 I libpersona: KNOX_SDCARD checking this for 10068
08-25 15:24:41.613  6817  6817 I libpersona: KNOX_SDCARD not a persona
08-25 15:24:41.623  6817  6817 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 15:24:41.623  6817  6817 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-25 15:24:41.623  1019  3774 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:24:41.623  1019  3774 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:41.623  1019  3774 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-25 15:24:41.623  1019  1487 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6817 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-25 15:24:41.623  1019  3774 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-25 15:24:41.623  1019  3774 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-25 15:24:41.633  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:24:41.633  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:24:41.633  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
08-25 15:24:41.633  1019  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-25 15:24:41.643  6598  6815 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 27.582135
08-25 15:24:41.643  1459  1861 D TP/MmsSmsProvider: update, matched:300, calling pid = 6598
08-25 15:24:41.643  1459  1861 V TP/MmsSmsProvider: syncDBData start
08-25 15:24:41.643  1459  1861 V TP/MmsSmsProvider: syncDBData sms end
08-25 15:24:41.643  1459  1861 V TP/MmsSmsProvider: syncDBData mms end
08-25 15:24:41.643  1459  1861 V TP/MmsSmsProvider: syncDBData end
08-25 15:24:41.643  6817  6817 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 15:24:41.643  1019  1308 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-25 15:24:41.643  1019  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:41.643  1019  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:41.643  1019  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:41.643  1019  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:41.653  6587  6643 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 300 ms] updated apps [took 300 ms] 
08-25 15:24:41.653  6817  6817 D ActivityThread: Added TimaKeyStore provider
08-25 15:24:41.653  1019  1308 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6835 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
08-25 15:24:41.663  6835  6835 E Zygote  : MountEmulatedStorage()
08-25 15:24:41.663  6835  6835 E Zygote  : v2
08-25 15:24:41.663  6835  6835 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 15:24:41.663  6598  6733 D Mms/ArtClassLoader: init [DONE] art
08-25 15:24:41.663  6598  6816 D Mms/Synchronizer: [end]    doSync consume time = 27.780052
08-25 15:24:41.663  6835  6835 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 15:24:41.663  6835  6835 I libpersona: KNOX_SDCARD checking this for 10042
08-25 15:24:41.663  6835  6835 I libpersona: KNOX_SDCARD not a persona
08-25 15:24:41.673  6835  6835 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-25 15:24:41.673  1019  1081 I ActivityManager: Killing 6281:com.google.android.music:main/u0a108 (adj 15): empty #21
,08-25 15:24:41.683  6598  6842 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-25 15:24:41.683  6598  6842 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-25 15:24:41.693  1019  1485 I ActivityManager: Killing 6458:com.android.defcontainer/u0a3 (adj 15): empty #21
08-25 15:24:41.693  6835  6835 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 15:24:41.693  1019  1485 I ActivityManager: Killing 6377:com.android.calendar/u0a131 (adj 15): empty #22
08-25 15:24:41.693  6835  6835 D ActivityThread: Added TimaKeyStore provider
08-25 15:24:41.713  6835  6835 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-25 15:24:41.713  6835  6835 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-25 15:24:41.713  6835  6835 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-25 15:24:41.713  6817  6817 D BadgeProvider: onCreate
08-25 15:24:41.713  6817  6817 D BadgeProvider: DatabaseHelper
08-25 15:24:41.873  1019  1492 I art     : Explicit concurrent mark sweep GC freed 141188(7MB) AllocSpace objects, 4(1863KB) LOS objects, 33% free, 23MB/34MB, paused 2.519ms total 158.576ms
08-25 15:24:41.893  6835  6835 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-25 15:24:41.903  1019  1368 I ActivityManager: Killing 6210:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-25 15:24:41.903  1019  1059 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-25 15:24:41.903  1019  1059 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-25 15:24:41.913  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:41.913  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:41.913  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:41.913  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:41.923  6853  6853 E Zygote  : MountEmulatedStorage()
08-25 15:24:41.923  6853  6853 E Zygote  : v2
08-25 15:24:41.923  6853  6853 I libpersona: KNOX_SDCARD checking this for 10003
08-25 15:24:41.923  6853  6853 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 15:24:41.923  6853  6853 I libpersona: KNOX_SDCARD not a persona
08-25 15:24:41.923  1019  1059 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6853 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-25 15:24:41.923  6853  6853 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 15:24:41.923  6598  6810 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-25 15:24:41.933  6853  6853 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 15:24:41.943  1459  1489 D TP/SmsProvider: query,matched:26, calling pid = 6598
08-25 15:24:41.943  6851  6851 D AndroidRuntime: 
08-25 15:24:41.943  6851  6851 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-25 15:24:41.943  1459  1489 D TP/SmsProvider: match 26:Elapsed time : 0.845 ms
08-25 15:24:41.953  6851  6851 D AndroidRuntime: CheckJNI is OFF
08-25 15:24:41.953  6851  6851 D AndroidRuntime: readGMSProperty: start
08-25 15:24:41.953  6851  6851 D AndroidRuntime: readGMSProperty: already setted!!
08-25 15:24:41.953  6851  6851 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-25 15:24:41.953  6851  6851 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-25 15:24:41.953  6851  6851 D AndroidRuntime: readGMSProperty: end
08-25 15:24:41.953  6851  6851 D AndroidRuntime: addProductProperty: start
08-25 15:24:41.963  1459  2494 D TP/MmsSmsProvider: query,matched:6, calling pid = 6598
08-25 15:24:41.963  6853  6853 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 15:24:41.963  1459  2494 D TP/MmsSmsProvider: match 6:Elapsed time : 2.036 ms
08-25 15:24:41.963  6853  6853 D ActivityThread: Added TimaKeyStore provider
08-25 15:24:42.003   284   284 E installd: system dir 0 : /system/app/
08-25 15:24:42.003   284   284 E installd: system dir 1 : /system/priv-app/
08-25 15:24:42.003   284   284 E installd: system dir 2 : /vendor/app/
08-25 15:24:42.003   284   284 E installd: system dir 3 : /oem/app/
08-25 15:24:42.023  1019  3774 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-25 15:24:42.023  1019  3774 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:42.023  1019  3774 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:42.023  1019  3774 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:42.023  1019  3774 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:42.033  6875  6875 E Zygote  : MountEmulatedStorage()
08-25 15:24:42.043  6875  6875 E Zygote  : v2
08-25 15:24:42.043  6875  6875 I libpersona: KNOX_SDCARD checking this for 10023
08-25 15:24:42.043  6875  6875 I libpersona: KNOX_SDCARD not a persona
08-25 15:24:42.053  6875  6875 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 15:24:42.053  6875  6875 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 15:24:42.053  6875  6875 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 15:24:42.063  1019  1059 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-25 15:24:42.073  1019  3774 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6875 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-25 15:24:42.073  6875  6875 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 15:24:42.073  6875  6875 D ActivityThread: Added TimaKeyStore provider
08-25 15:24:42.083  1019  1368 I ActivityManager: Killing 6504:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-25 15:24:42.113  1019  1308 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-25 15:24:42.113  1019  1308 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4195, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-25 15:24:42.113  1019  1308 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-25 15:24:42.113  1019  1308 D BatteryService: stay LED for charging
08-25 15:24:42.113  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-25 15:24:42.123  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-25 15:24:42.123  1019  1019 I MotionRecognitionService: Plugged
08-25 15:24:42.123  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
08-25 15:24:42.123  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
08-25 15:24:42.133  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-25 15:24:42.133  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-25 15:24:42.143  6851  6851 E AffinityControl: AffinityControl: registerfunction enter
08-25 15:24:42.143  3215  3215 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-25 15:24:42.153  3215  3357 D HeadsetStateMachine: Disconnected process message: 10
08-25 15:24:42.153  1182  1182 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-25 15:24:42.153  1182  1182 D SViewCoverView: level :100 plugged : 2
08-25 15:24:42.153  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-25 15:24:42.163  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-25 15:24:42.163  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-25 15:24:42.163  6851  6851 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-25 15:24:42.183  1019  1081 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-25 15:24:42.203  1019  1032 E PersonaManagerService: inState():  stateMachine is null !!
08-25 15:24:42.203  6875  6875 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-25 15:24:42.213  1019  1032 I PersonaManagerService: PersonaId don't exist
08-25 15:24:42.213  1019  1032 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-25 15:24:42.213  1907  6672 I qtaguid : Untagging socket 98
08-25 15:24:42.213  1907  1907 I ConfigFetchService: fetch service done; releasing wakelock
08-25 15:24:42.213  1907  1907 I ConfigFetchService: stopping self
08-25 15:24:42.213  1019  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-25 15:24:42.243  6598  6810 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-25 15:24:42.243  1019  1032 W ActivityManager: mDVFSHelper.acquire()
08-25 15:24:42.243  1019  1032 D FocusedStackFrame: Set to : 0
08-25 15:24:42.253  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:42.253  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:42.253  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:42.253  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:42.253  1019  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-25 15:24:42.253  1019  1050 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-25 15:24:42.273  1019  1032 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6896 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-25 15:24:42.273  1019  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-25 15:24:42.273  1019  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-25 15:24:42.273  1019  1032 D InputDispatcher: Focused application set to: xxxx
08-25 15:24:42.273  1019  1032 D InputDispatcher: Focus left window: 1493
08-25 15:24:42.273  6896  6896 E Zygote  : MountEmulatedStorage()
08-25 15:24:42.273  6896  6896 E Zygote  : v2
08-25 15:24:42.273  6896  6896 I libpersona: KNOX_SDCARD checking this for 10170
08-25 15:24:42.273  6896  6896 I libpersona: KNOX_SDCARD not a persona
08-25 15:24:42.273  6896  6896 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 15:24:42.283  1019  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-25 15:24:42.283  1019  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-25 15:24:42.283  6896  6896 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 15:24:42.283  6896  6896 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-25 15:24:42.283   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-25 15:24:42.283  6851  6851 D AndroidRuntime: Shutting down VM
08-25 15:24:42.293  6875  6875 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-25 15:24:42.293  6875  6875 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-25 15:24:42.293  6875  6875 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-25 15:24:42.293  6875  6875 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-25 15:24:42.293  6875  6875 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-25 15:24:42.303  6875  6875 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-25 15:24:42.303  6875  6875 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-25 15:24:42.303  6875  6875 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-25 15:24:42.303  6875  6875 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-25 15:24:42.303  6875  6875 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-25 15:24:42.303  6875  6875 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-25 15:24:42.303  6896  6896 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 15:24:42.303  6875  6875 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-25 15:24:42.313  6896  6896 D ActivityThread: Added TimaKeyStore provider
08-25 15:24:42.313  6875  6875 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-25 15:24:42.313  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-25 15:24:42.323  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
08-25 15:24:42.323  1019  4326 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-25 15:24:42.323  1019  1019 V ActivityManager: Display changed displayId=0
08-25 15:24:42.333  1019  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-25 15:24:42.353  1019  4326 D PersonaManager: isKioskContainerExistOnDevice
08-25 15:24:42.373  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-25 15:24:42.413   258   434 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
08-25 15:24:42.413   258  1041 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
08-25 15:24:42.423  1493  1493 V ActivityThread: updateVisibility : ActivityRecord{19f754a0 token=android.os.BinderProxy@3be96c50 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-25 15:24:42.423  1493  1493 D Launcher: onTrimMemory. Level: 20
08-25 15:24:42.503  6851  6851 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-25 15:24:42.523  6896  6896 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-25 15:24:42.533  6690  6751 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-25 15:24:42.533  6690  6751 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-25 15:24:42.533  6690  6751 I GAv4    :   adb logcat -s GAv4
,08-25 15:24:42.543  6896  6896 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 6313-6316)
,08-25 15:24:42.543  6896  6896 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-25 15:24:42.583  6896  6896 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d9b8a6a}
,08-25 15:24:42.593  6690  6751 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-25 15:24:42.593  1019  3856 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-25 15:24:42.613  6896  6896 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-25 15:24:42.623  6690  6751 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-25 15:24:42.623  6896  6896 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 15:24:42.653  1907  4002 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
,08-25 15:24:42.673  6690  6918 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-25 15:24:42.673  6690  6751 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
,08-25 15:24:42.733  1907  4002 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-25 15:24:42.733  6896  6896 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-25 15:24:42.743  6896  6896 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 15:24:42.753  6896  6896 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-25 15:24:42.783  1907  4002 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
,08-25 15:24:42.793  1019  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-25 15:24:42.793  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:24:42.793  1019  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:24:42.793  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:24:42.813  1019  1032 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
,08-25 15:24:42.813  6896  6896 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-25 15:24:42.813  6896  6896 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 15:24:42.813  6896  6896 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 15:24:42.813  6896  6896 I Adreno-EGL: Local Branch: 
08-25 15:24:42.813  6896  6896 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 15:24:42.813  6896  6896 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 15:24:42.813  6896  6896 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-25 15:24:42.823  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:42.823  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:42.823  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:42.823  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:42.833  6928  6928 E Zygote  : MountEmulatedStorage(),
08-25 15:24:42.833  6928  6928 E Zygote  : v2
08-25 15:24:42.833  6928  6928 I libpersona: KNOX_SDCARD checking this for 1000,
08-25 15:24:42.833  6928  6928 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 15:24:42.833  6928  6928 I libpersona: KNOX_SDCARD not a persona
,08-25 15:24:42.833  1019  1032 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6928 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-25 15:24:42.833  6928  6928 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:24:42.833  1019  1032 I ActivityManager: Killing 6520:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-25 15:24:42.843  6928  6928 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 15:24:42.853  1019  1045 W ActivityManager: Activity pause timeout for ActivityRecord{f66aad0 u0 com.test.thalitest/.MainActivity t163}
,08-25 15:24:42.873  6928  6928 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 15:24:42.873  6928  6928 D ActivityThread: Added TimaKeyStore provider
,08-25 15:24:42.893  6928  6928 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,08-25 15:24:42.893  6928  6928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,08-25 15:24:42.893  1019  1492 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
,08-25 15:24:42.893  1019  1492 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,08-25 15:24:42.893  1019  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:24:42.903  1019  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 15:24:42.903  1019  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,08-25 15:24:42.903  1019  3856 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-25 15:24:42.903  1019  1019 I splitIntent: intent=android.intent.action.TIME_SET will be not split. because same process=com.google.android.gms is in other queue. index=4
08-25 15:24:42.903  1019  1019 I splitIntent: base  index=4, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$Receiver
08-25 15:24:42.903  1019  1019 I splitIntent: other index=7, name=com.google.android.gms com.google.android.gms.reminders.notification.NotificationReceiver
08-25 15:24:42.903  1019  1019 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.TIME_SET !! do not split it!!
,08-25 15:24:42.903  6928  6928 I FilterInstaller: FilterPackageService : ACTION_CHANGED
,08-25 15:24:42.913  1019  1019 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-25 15:24:42.913  6690  6926 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-25 15:24:42.913  6690  6926 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-25 15:24:42.913  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:42.913  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:42.913  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:42.913  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:42.933  6928  6944 E FilterInstaller: installFilters
,08-25 15:24:42.933  6945  6945 E Zygote  : MountEmulatedStorage()
08-25 15:24:42.933  6945  6945 E Zygote  : v2
08-25 15:24:42.933  6945  6945 I libpersona: KNOX_SDCARD checking this for 10008
08-25 15:24:42.933  6945  6945 I libpersona: KNOX_SDCARD not a persona
,08-25 15:24:42.933  6945  6945 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:24:42.933  6928  6944 E FilterInstaller: There is no requred permission
08-25 15:24:42.933  1019  1019 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6945 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 15:24:42.933  6945  6945 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:24:42.933  6945  6945 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-25 15:24:42.943  1019  1490 I ActivityManager: Killing 6551:com.samsung.helphub/1000 (adj 15): empty #21
,08-25 15:24:42.953   304   304 I art     : Explicit concurrent mark sweep GC freed 8687(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 23.892ms
,08-25 15:24:42.963  6945  6945 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:24:42.963  6945  6945 D ActivityThread: Added TimaKeyStore provider
,08-25 15:24:42.973   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.570ms
,08-25 15:24:42.993  6690  6926 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-25 15:24:42.993   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 640us total 17.240ms
,08-25 15:24:43.003  6896  6896 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 15:24:43.023  6896  6896 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-25 15:24:43.023  6896  6896 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-25 15:24:43.033  6896  6896 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-25 15:24:43.033  6896  6896 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-25 15:24:43.083  6945  6945 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-25 15:24:43.103  6690  6926 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-25 15:24:43.103  6690  6926 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@291649a9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-25 15:24:43.103  6690  6926 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-25 15:24:43.103  1019  1308 I ActivityManager: Killing 5097:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
,08-25 15:24:43.133  1019  1032 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 15:24:43.133  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
08-25 15:24:43.133  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:24:43.143  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:24:43.143  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:24:43.163  6896  6896 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 15:24:43.183  6896  6896 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-25 15:24:43.183  1019  4326 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 15:24:43.183  1019  4326 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,08-25 15:24:43.183  1019  4326 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:24:43.183  1019  4326 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 15:24:43.183  1019  4326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:24:43.193  6896  6896 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-25 15:24:43.193  6896  6896 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-25 15:24:43.193  2816  2816 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Aug 25 15:24:43 GMT+02:00 2016
08-25 15:24:43.193  1019  3856 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-25 15:24:43.193  1019  3856 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-25 15:24:43.193  1019  3856 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:24:43.193  1019  3856 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:43.193  1019  3856 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-25 15:24:43.203  2816  2816 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-25 15:24:43.203  6896  6896 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-25 15:24:43.203  1019  1485 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-25 15:24:43.203  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:43.203  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:43.203  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:43.203  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:43.213  2816  2816 I KLMS-2.5.123: : KLMSIntentService(): onCreate(),
,08-25 15:24:43.223  6977  6977 E Zygote  : MountEmulatedStorage(),
08-25 15:24:43.223  2816  2816 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-25 15:24:43.223  6977  6977 E Zygote  : v2
,08-25 15:24:43.223  6977  6977 I libpersona: KNOX_SDCARD checking this for 10036
08-25 15:24:43.223  6977  6977 I libpersona: KNOX_SDCARD not a persona
,08-25 15:24:43.223  6977  6977 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:24:43.223  1019  1485 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=6977 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-25 15:24:43.223  6896  6896 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 15:24:43.223  6896  6896 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 15:24:43.223  2816  2816 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-25 15:24:43.233  6977  6977 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:24:43.233  6977  6977 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-25 15:24:43.233  2816  6976 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,08-25 15:24:43.233  1019  1487 I ActivityManager: Killing 6532:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-25 15:24:43.253  2816  6976 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
,08-25 15:24:43.253  6977  6977 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:24:43.253  6977  6977 D ActivityThread: Added TimaKeyStore provider
08-25 15:24:43.253  2816  6976 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Thu Aug 25 15:24:43 GMT+02:00 2016
,08-25 15:24:43.263  2816  6976 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
,08-25 15:24:43.263  2816  2816 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-25 15:24:43.273  6896  6995 D OpenGLRenderer: Render dirty regions requested: true
,08-25 15:24:43.283  1019  1492 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-25 15:24:43.283  1019  1492 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-25 15:24:43.283  1019  1492 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-25 15:24:43.283  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-25 15:24:43.283  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,08-25 15:24:43.283  6896  6896 V ActivityThread: updateVisibility : ActivityRecord{127edd35 token=android.os.BinderProxy@2ed6f41f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-25 15:24:43.293  6896  6957 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-25 15:24:43.303  6977  6977 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@30b9ab12
,08-25 15:24:43.313  6896  6896 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-25 15:24:43.313  6896  6896 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-25 15:24:43.313  6977  6977 I SA      : [SSP] onCreated
,08-25 15:24:43.333   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-25 15:24:43.333  6977  6977 I SA      : [TPM] There is no property file
,08-25 15:24:43.343  6977  6977 I SA      : [SCU] isHaveSA() - false
,08-25 15:24:43.343  6977  6977 I SA      : [TPM] getModelProperty : null
,08-25 15:24:43.343  6977  6977 I SA      : [TPM] getCSCProperty : null
,08-25 15:24:43.343  1019  1032 D InputDispatcher: Focus entered window: 6896
,08-25 15:24:43.343  6977  6977 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-25 15:24:43.343  6977  6977 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-25 15:24:43.343  6977  6977 I SA      : [DM] TFT FEATURE: false
,08-25 15:24:43.353  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-25 15:24:43.353  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-25 15:24:43.353  6896  6896 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-25 15:24:43.353  6896  6995 I OpenGLRenderer: Initialized EGL, version 1.4
08-25 15:24:43.353  6896  6995 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-25 15:24:43.353  6896  6995 D OpenGLRenderer: Enabling debug mode 0
,08-25 15:24:43.363  6977  6977 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
08-25 15:24:43.363  6977  6977 I SA      : [DM] init START
,08-25 15:24:43.363  6977  6977 I SA      : [DM] This device is not a Vodafone
,08-25 15:24:43.373  6977  6977 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-25 15:24:43.373  6977  6977 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-25 15:24:43.373  6977  6977 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-25 15:24:43.373  6977  6977 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-25 15:24:43.373  6977  6977 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-25 15:24:43.373  6977  6977 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-25 15:24:43.373  6977  6977 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-25 15:24:43.373  6977  6977 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 15:24:43.373  6977  6977 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-25 15:24:43.373  6977  6977 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-25 15:24:43.373  6977  6977 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-25 15:24:43.373  6977  6977 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-25 15:24:43.373  6977  6977 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-25 15:24:43.383  6977  6977 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-25 15:24:43.383  6977  6977 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-25 15:24:43.383  6977  6977 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-25 15:24:43.383  6977  6977 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-25 15:24:43.383  6977  6977 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-25 15:24:43.383  6977  6977 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-25 15:24:43.383  6977  6977 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-25 15:24:43.383  1019  3774 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-25 15:24:43.383  6977  6977 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-25 15:24:43.383  6977  6977 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-25 15:24:43.383  6977  6977 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-25 15:24:43.383  6977  6977 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75),
08-25 15:24:43.383  6977  6977 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-25 15:24:43.383  6977  6977 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-25 15:24:43.383  6977  6977 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-25 15:24:43.383  1019  7003 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-25 15:24:43.383  6977  6977 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75),
,08-25 15:24:43.383  1182  1182 D PanelView: There is/are notification(s) 
,08-25 15:24:43.393  6977  6977 I SA      : [SCU] isHaveSA() - false
08-25 15:24:43.393  6977  6977 I SA      : support phone number id : false
08-25 15:24:43.393  6977  6977 I SA      : [DM] Supports Ref Jpn : true
,08-25 15:24:43.393  6977  6977 I SA      : [DM] init END
,08-25 15:24:43.403  1019  1050 I ActivityManager: Displayed Component not be shown by security: +1s45ms (total +1s150ms)
08-25 15:24:43.403  1019  1050 W ActivityManager: mDVFSHelper.release()
08-25 15:24:43.403  1019  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f66aad0 u0 com.test.thalitest/.MainActivity t163} time:97173
08-25 15:24:43.403   258   434 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-25 15:24:43.403   258  1041 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-25 15:24:43.413  6896  6896 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-25 15:24:43.413  6896  6896 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2ed6f41f time:97186
08-25 15:24:43.423  1879  1879 I SamsungIME: getCurrentCandidateView
08-25 15:24:43.433   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb89aa7c8
08-25 15:24:43.433   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-25 15:24:43.433   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
08-25 15:24:43.433   273   350 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1197823864)
08-25 15:24:43.483   273   350 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-25 15:24:43.483   273   350 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-25 15:24:43.483   273   350 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1197823864) wakelock released: 1, error no: 0
08-25 15:24:43.483   273   350 I rmt_storage: 
08-25 15:24:43.483   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb89aa7c8
08-25 15:24:43.533  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
08-25 15:24:43.533  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:43.533  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:43.533  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:43.533  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:43.553  6598  6598 I Mms/MmsApp:  start initViewCache mms
08-25 15:24:43.553  6598  6598 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1882.372083
08-25 15:24:43.553  6598  6598 D Mms/ComposeMessageFragment: fillCache, easy = false
08-25 15:24:43.553  7011  7011 E Zygote  : MountEmulatedStorage()
08-25 15:24:43.563  7011  7011 E Zygote  : v2
08-25 15:24:43.563  7011  7011 I libpersona: KNOX_SDCARD checking this for 10058
08-25 15:24:43.563  7011  7011 I libpersona: KNOX_SDCARD not a persona
08-25 15:24:43.563  7011  7011 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 15:24:43.563  7011  7011 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 15:24:43.563  7011  7011 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 15:24:43.563  1019  1031 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=7011 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 15:24:43.563  1019  1031 I ActivityManager: Killing 6234:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
08-25 15:24:43.593  7011  7011 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 15:24:43.593  7011  7011 D ActivityThread: Added TimaKeyStore provider
08-25 15:24:43.623  6896  6896 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6896
08-25 15:24:43.643  1879  1879 D SamsungIME: Dismiss ExpandCandiate
08-25 15:24:43.663  7011  7011 I ExternalOEMControlProvider: onCreate
08-25 15:24:43.683  1019  1368 I ActivityManager: Killing 6160:com.google.android.apps.plus/u0a117 (adj 15): empty #21
08-25 15:24:43.693  1789  1789 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
08-25 15:24:43.693  1789  1789 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
08-25 15:24:43.693  1019  4326 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
08-25 15:24:43.703  1019  4326 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:43.703  1019  4326 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:43.703  1019  4326 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:43.703  7011  7027 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
08-25 15:24:43.703  1019  4326 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:43.713  1019  4326 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=7028 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 15:24:43.713  7028  7028 E Zygote  : MountEmulatedStorage()
08-25 15:24:43.713  7028  7028 E Zygote  : v2
08-25 15:24:43.713  7028  7028 I libpersona: KNOX_SDCARD checking this for 10081
08-25 15:24:43.713  7028  7028 I libpersona: KNOX_SDCARD not a persona
08-25 15:24:43.713  7028  7028 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 15:24:43.723  7028  7028 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 15:24:43.723  7028  7028 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 15:24:43.723  6598  6598 D AbsListView: Get MotionRecognitionManager
08-25 15:24:43.723  1019  1308 D MotionRecognitionService:  ssp status : false
08-25 15:24:43.733  6598  6598 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 184.75276
08-25 15:24:43.743  7028  7028 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 15:24:43.743  7028  7028 D ActivityThread: Added TimaKeyStore provider
08-25 15:24:43.763  7028  7028 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-25 15:24:43.763  7028  7028 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-25 15:24:43.773  7028  7028 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 15:24:43.773  7028  7028 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-25 15:24:43.773  7028  7028 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
08-25 15:24:43.853  6598  6598 D Mms/BubbleViewCache: fillCache bubble = 1
08-25 15:24:43.863  1019  1308 D SettingsProvider: name = next_alarm_formatted
08-25 15:24:43.863  1019  1308 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 15:24:43.863  1019  1308 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 15:24:43.863  1019  1308 D SettingsProvider: selectionArgs: false
08-25 15:24:43.863  1019  1308 D SettingsProvider: selectionArgs: 10081
08-25 15:24:43.863  1019  1308 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 15:24:43.863  1019  1308 D SettingsProvider: ret = -1
08-25 15:24:43.903  1879  1879 I SamsungIME: getDebugLevel  : 0x4f4c
08-25 15:24:43.933  6896  6896 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-25 15:24:43.963  1879  1879 I SamsungIME: getDebugLevel  : 0x4f4c
08-25 15:24:43.983  1879  1879 I SamsungIME: KeybaordView init() : load resources
08-25 15:24:43.993  7028  7028 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 124.318ms
08-25 15:24:44.013  1879  1879 I SamsungIME: getCurrentKeyboard
08-25 15:24:44.013  1879  1879 I SamsungIME: getTextKeyboard
08-25 15:24:44.023  6896  7008 D jxcore_app_log: JniHelper::setJavaVM(0xb848a2b0), pthread_self() = -1197372384
08-25 15:24:44.023  6896  7008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 15:24:44.023  6896  7008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 15:24:44.023  6896  7008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 15:24:44.023  6896  7008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 15:24:44.023  6896  7008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-25 15:24:44.033  6896  7008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d023c70 added. We now have 1 listener(s)
08-25 15:24:44.033  6896  7008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
08-25 15:24:44.033  6896  7008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-25 15:24:44.033  6896  7008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:24:44.033  6896  7008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:24:44.043  1879  1879 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
08-25 15:24:44.043  6896  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 15:24:44.043  6896  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 15:24:44.043  6896  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 15:24:44.043  6896  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-25 15:24:44.043  6896  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 15:24:44.043  6896  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 15:24:44.043  6896  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 15:24:44.043  6896  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 15:24:44.043  6896  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 15:24:44.043  6896  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 15:24:44.043  6896  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 15:24:44.043  6896  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 15:24:44.043  6896  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 15:24:44.043  6896  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-25 15:24:44.043  6896  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10ab230f added. We now have 1 listener(s)
08-25 15:24:44.043  6896  7008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:24:44.053  6896  7008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 15:24:44.053  6896  7008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-25 15:24:44.053  6896  7008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-25 15:24:44.053  6896  7008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-25 15:24:44.053  6896  7008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-25 15:24:44.053  6896  7008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:24:44.063  6896  7008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
08-25 15:24:44.063  6896  7008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-25 15:24:44.063  6896  7008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:24:44.063  6896  7008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:24:44.063  6896  7008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:24:44.063  6896  7008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:24:44.063  6896  7008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:24:44.063  6896  7008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:24:44.063  6896  7008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:24:44.063  6896  7008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:24:44.063  6896  7008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-25 15:24:44.063  6896  7008 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 15:24:44.063  6896  7008 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 15:24:44.073  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:24:44.073  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:24:44.103  6896  6896 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-25 15:24:44.103  1019  3856 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
08-25 15:24:44.103  1019  3856 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:44.103  1019  3856 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:44.103  1019  3856 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:44.113  1019  3856 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:44.123  7048  7048 E Zygote  : MountEmulatedStorage()
08-25 15:24:44.123  7048  7048 E Zygote  : v2
08-25 15:24:44.123  7048  7048 I libpersona: KNOX_SDCARD checking this for 10090
08-25 15:24:44.123  7048  7048 I libpersona: KNOX_SDCARD not a persona
,08-25 15:24:44.123  7048  7048 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:24:44.123  7048  7048 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:24:44.123  7048  7048 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 15:24:44.133  1019  3856 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7048 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-25 15:24:44.133  1019  3856 I ActivityManager: Killing 6587:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-25 15:24:44.163  7048  7048 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:24:44.173  7048  7048 D ActivityThread: Added TimaKeyStore provider
,08-25 15:24:44.193  7048  7048 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,08-25 15:24:44.193  7048  7048 D elm:15121: ELMEngine.ELMEngine( context ).
,08-25 15:24:44.203  7048  7048 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-25 15:24:44.203  1019  1032 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-25 15:24:44.203  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-25 15:24:44.203  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:24:44.203  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:44.203  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-25 15:24:44.203  7048  7048 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,08-25 15:24:44.203  1019  1081 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,08-25 15:24:44.213  1019  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:44.213  1019  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:44.213  1019  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:44.213  1019  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:44.223  7048  7048 D elm:15121: ElmAgentService : onCreate()
,08-25 15:24:44.223  7048  7063 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,08-25 15:24:44.223  7064  7064 E Zygote  : MountEmulatedStorage()
,08-25 15:24:44.223  7064  7064 E Zygote  : v2
08-25 15:24:44.223  7064  7064 I libpersona: KNOX_SDCARD checking this for 10130,
08-25 15:24:44.223  7064  7064 I libpersona: KNOX_SDCARD not a persona
,08-25 15:24:44.223  7064  7064 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:24:44.223  1019  1081 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7064 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,08-25 15:24:44.223  7064  7064 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 15:24:44.233  7064  7064 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
08-25 15:24:44.233  7048  7063 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
08-25 15:24:44.233   288   288 E SMD     : DCD OFF
08-25 15:24:44.233  7048  7048 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
08-25 15:24:44.233  7048  7048 D elm:15121: ModuleBase.ModifySetAlarm()
08-25 15:24:44.233  7048  7048 D elm:15121: MDMBridge.getInstance()
08-25 15:24:44.233  7048  7048 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK(),
,08-25 15:24:44.243  7048  7048 D elm:15121: ElmAgentService : onDestroy().
,08-25 15:24:44.243  1019  4325 I ActivityManager: Killing 6633:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-25 15:24:44.273  7064  7064 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:24:44.273  7064  7064 D ActivityThread: Added TimaKeyStore provider
,08-25 15:24:44.283  7064  7064 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-25 15:24:44.283  7064  7064 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-25 15:24:44.303  1019  1308 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,08-25 15:24:44.303  1019  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:44.303  1019  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:44.303  1019  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:44.303  1019  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:44.333  7081  7081 E Zygote  : MountEmulatedStorage()
,08-25 15:24:44.333  7081  7081 E Zygote  : v2
08-25 15:24:44.333  7081  7081 I libpersona: KNOX_SDCARD checking this for 10131
08-25 15:24:44.333  7081  7081 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 15:24:44.333  7081  7081 I libpersona: KNOX_SDCARD not a persona
,08-25 15:24:44.333  7081  7081 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 15:24:44.333  1019  1308 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7081 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-25 15:24:44.333  7081  7081 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 15:24:44.333  1019  1308 I ActivityManager: Killing 6650:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-25 15:24:44.353  7081  7081 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:24:44.353  7081  7081 D ActivityThread: Added TimaKeyStore provider
,08-25 15:24:44.373  7081  7081 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-25 15:24:44.373  7081  7081 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 15:24:44.373  7081  7081 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-25 15:24:44.413  2681  2689 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-25 15:24:44.413  1019  1308 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-25 15:24:44.413  1019  1308 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-25 15:24:44.413  1019  1308 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:24:44.413  1019  1308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:44.413  1019  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-25 15:24:44.433  1019  3774 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-25 15:24:44.433  1019  3774 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-25 15:24:44.433  1019  3774 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:24:44.433  1019  3774 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:44.433  1019  3774 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-25 15:24:44.443  1019  4326 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,08-25 15:24:44.443  1019  4326 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:44.443  1019  4326 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:44.443  1019  4326 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:44.443  1019  4326 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:44.453  7102  7102 E Zygote  : MountEmulatedStorage(),
08-25 15:24:44.453  7102  7102 I libpersona: KNOX_SDCARD checking this for 10037
08-25 15:24:44.453  7102  7102 E Zygote  : v2
08-25 15:24:44.453  7102  7102 I libpersona: KNOX_SDCARD not a persona
08-25 15:24:44.453  7102  7102 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 15:24:44.453  1019  4326 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7102 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-25 15:24:44.453  1019  1487 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-25 15:24:44.453  7102  7102 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:24:44.463  1019  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:44.463  1019  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:44.463  1019  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:44.463  1019  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:44.463  7102  7102 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-25 15:24:44.483  1019  1487 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=7111 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-25 15:24:44.483  7111  7111 E Zygote  : MountEmulatedStorage()
08-25 15:24:44.483  7111  7111 E Zygote  : v2
08-25 15:24:44.483  7111  7111 I libpersona: KNOX_SDCARD checking this for 1000
08-25 15:24:44.483  7111  7111 I libpersona: KNOX_SDCARD not a persona
,08-25 15:24:44.483  7111  7111 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:24:44.483  7111  7111 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:24:44.493  7111  7111 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 15:24:44.493  7102  7102 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 15:24:44.493  7102  7102 D ActivityThread: Added TimaKeyStore provider
,08-25 15:24:44.513  7102  7102 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-25 15:24:44.523  7111  7111 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:24:44.523  7111  7111 D ActivityThread: Added TimaKeyStore provider
,08-25 15:24:44.543  7102  7102 I CalendarProvider2: CalendarProvider2.onCreate() called
,08-25 15:24:44.573  7111  7111 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-25 15:24:44.573  7111  7111 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 15:24:44.573  7111  7111 D SecurityLogAgent: StateMachine : Current State = 1
,08-25 15:24:44.583  1019  3856 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,08-25 15:24:44.583  1019  3856 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:44.583  1019  3856 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:44.583  1019  3856 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:44.583  1019  3856 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:44.593  1019  3856 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=7134 uid=10153 gids={50153, 9997} abi=armeabi-v7a
,08-25 15:24:44.603  1019  3376 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-25 15:24:44.603  1019  3856 I ActivityManager: Killing 6666:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-25 15:24:44.603  7134  7134 E Zygote  : MountEmulatedStorage()
08-25 15:24:44.603  7134  7134 E Zygote  : v2
08-25 15:24:44.603  7134  7134 I libpersona: KNOX_SDCARD checking this for 10153
08-25 15:24:44.603  7134  7134 I libpersona: KNOX_SDCARD not a persona
,08-25 15:24:44.603  7134  7134 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:24:44.613  7134  7134 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:24:44.613  7134  7134 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 15:24:44.643  7134  7134 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:24:44.643  7134  7134 D ActivityThread: Added TimaKeyStore provider
,08-25 15:24:44.783  1019  1081 I art     : Explicit concurrent mark sweep GC freed 17780(970KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.447ms total 139.065ms
,08-25 15:24:44.803  1019  4326 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
08-25 15:24:44.803  1019  4326 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-25 15:24:44.803  1019  4326 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:24:44.803  1019  4326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:44.803  1019  4326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-25 15:24:44.803  7134  7134 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-25 15:24:44.813  6896  7047 W jxcore-log: Initializing JXcore engine
08-25 15:24:44.813  6896  7047 W jxcore-log: JXcore engine is ready
,08-25 15:24:44.833  1019  1492 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,08-25 15:24:44.833  1019  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:44.833  1019  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:44.833  1019  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:44.833  1019  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:44.843  7153  7153 E Zygote  : MountEmulatedStorage()
,08-25 15:24:44.843  7153  7153 E Zygote  : v2
08-25 15:24:44.843  7153  7153 I libpersona: KNOX_SDCARD checking this for 1000
08-25 15:24:44.843  7153  7153 I libpersona: KNOX_SDCARD not a persona
,08-25 15:24:44.843  7153  7153 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-25 15:24:44.853  7153  7153 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:24:44.853  1019  1492 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7153 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-25 15:24:44.853  1019  1492 I ActivityManager: Killing 6690:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-25 15:24:44.853  7153  7153 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 15:24:44.873  7153  7153 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:24:44.873  7153  7153 D ActivityThread: Added TimaKeyStore provider
,08-25 15:24:44.883  2007  2007 E audit   : type=1400 msg=audit(1472131484.883:205): avc:  denied  { ioctl } for  pid=7047 comm="Thread-1286" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
08-25 15:24:44.883  2007  2007 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-25 15:24:44.883  2007  2007 E audit   : type=1300 msg=audit(1472131484.883:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f2fd8f8 items=0 ppid=304 ppcomm=main pid=7047 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1286" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-25 15:24:44.883  2007  2007 E audit   : type=1320 msg=audit(1472131484.883:205): 
,08-25 15:24:44.903  6896  7047 W jxcore-log: Starting JXcore engine
,08-25 15:24:44.913  1019  4326 I ActivityManager: Killing 6725:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-25 15:24:44.923  7153  7153 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1472131484934
08-25 15:24:44.923  7153  7153 D         : TimeServiceNative: User Time to be set is 1472131484934
08-25 15:24:44.923  7153  7153 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-25 15:24:44.923  7153  7153 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-25 15:24:44.923  7153  7153 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1472131484934
,08-25 15:24:44.923   322   558 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-25 15:24:44.923  7153  7153 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-25 15:24:44.923   322  7168 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1472131484934
08-25 15:24:44.923   322  7168 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1472131484934, operation = 0
08-25 15:24:44.923   322  7168 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/20/71 7:7:36
08-25 15:24:44.923   322  7168 D QC-time-services: Daemon:Value read from RTC seconds = 35881656000
08-25 15:24:44.923   322  7168 D QC-time-services: Daemon:new time 1472131484934 
08-25 15:24:44.923   322  7168 D QC-time-services: Daemon: delta 1436249828934 genoff 1436249828934 
08-25 15:24:44.923   322  7168 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249828934 to memory
08-25 15:24:44.923   322  7168 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-25 15:24:44.923   322  7168 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-25 15:24:44.943   322  7168 D QC-time-services: Updating the TOD offset
08-25 15:24:44.943   322  7168 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249828934 to memory
08-25 15:24:44.943   322  7168 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-25 15:24:44.943   322  7168 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-25 15:24:44.943   322  7168 E QC-time-services: Daemon:Update to modem bit set
08-25 15:24:44.943   322  7168 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-25 15:24:44.943   322  7168 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120285028934
,08-25 15:24:44.943  7153  7153 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,08-25 15:24:44.943  1019  1032 I ActivityManager: Killing 6710:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-25 15:24:44.943   322   555 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
08-25 15:24:44.943   322   558 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
08-25 15:24:44.953  6569  6626 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
08-25 15:24:44.953  2681  2681 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
08-25 15:24:44.953  2681  2681 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-25 15:24:44.953  2681  2681 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
08-25 15:24:44.963  2681  2681 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
08-25 15:24:44.963  2681  2681 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
08-25 15:24:44.963  2681  2681 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,08-25 15:24:44.973  2681  2681 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-25 15:24:44.973  2681  2681 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,08-25 15:24:44.973  2681  2681 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-25 15:24:44.973  2681  2681 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-25 15:24:44.973  2681  2681 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
08-25 15:24:44.973  2681  2681 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-25 15:24:44.973  6569  6626 I AcmsKeyStoreHelper: Key Store exist
08-25 15:24:44.973  6569  6626 I AcmsKeyStoreHelper: Hence loading the keystore file
,08-25 15:24:44.973  2681  2681 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5,
,08-25 15:24:44.983  2681  2681 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
08-25 15:24:44.983  2681  2681 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-25 15:24:44.983  2681  2681 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,08-25 15:24:44.983  2681  2681 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-25 15:24:44.983  2681  2681 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,08-25 15:24:44.993  2681  2681 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
08-25 15:24:44.993  2681  2681 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,08-25 15:24:45.023  6896  7047 W jxcore-log: Platform android
08-25 15:24:45.023  6896  7047 W jxcore-log: 
08-25 15:24:45.023  6896  7047 W jxcore-log: Process ARCH arm
08-25 15:24:45.023  6896  7047 W jxcore-log: 
,08-25 15:24:45.033  6569  6626 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-25 15:24:45.033  6569  6626 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-25 15:24:45.033  6569  6626 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-25 15:24:45.033  6569  6626 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-25 15:24:45.033  6569  6626 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-25 15:24:45.033  6569  6626 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,08-25 15:24:45.033  6569  6626 D AcmsCore: This is NOT a valid MirrorLink app
08-25 15:24:45.033  6569  6626 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-25 15:24:45.033  6569  6626 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-25 15:24:45.033  6569  6626 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-25 15:24:45.033  6569  6626 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,08-25 15:24:45.033  6569  6569 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,08-25 15:24:45.033  6569  6569 D AcmsService: Enter onDestroy
,08-25 15:24:45.033  6569  6569 I AcmsService: cleanUp(): inside service clean up
08-25 15:24:45.033  6569  6569 D AcmsCore: AcmsCore: inside DeInit
08-25 15:24:45.033  6569  6569 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
,08-25 15:24:45.033  6569  6569 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-25 15:24:45.033  6569  6569 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-25 15:24:45.033  6569  6569 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-25 15:24:45.033  6569  6569 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,08-25 15:24:45.033  6569  6569 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-25 15:24:45.033  6569  6569 D AcmsService: killing acms process
08-25 15:24:45.033  6569  6569 I Process : Sending signal. PID: 6569 SIG: 9
,08-25 15:24:45.113  1019  1031 I ActivityManager: Process ACMS.Process (pid 6569)(adj 0) has died(30,768)
,08-25 15:24:45.233  6896  7047 I jxcore-log: JXcore Cordova bridge is ready!
08-25 15:24:45.233  6896  7047 I jxcore-log: 
,08-25 15:24:45.233  6896  7047 W jxcore-log: JXcore engine is started
,08-25 15:24:45.243  6896  7008 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-25 15:24:45.243  6896  6896 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 15:24:45.803  7102  7102 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,08-25 15:24:45.813  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:24:45.813  1019  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:45.813  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,08-25 15:24:45.813  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:24:45.813  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:45.813  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-25 15:24:45.823  1019  4326 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-25 15:24:45.823  1019  4326 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:24:45.823  1019  4326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:45.823  1019  4326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-25 15:24:45.823  1019  4325 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-25 15:24:45.823  1019  4325 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-25 15:24:45.823  1019  4325 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:24:45.823  1019  4325 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:45.823  1019  4325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-25 15:24:45.833  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:24:45.833  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:45.833  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-25 15:24:45.843  1019  1081 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-25 15:24:45.843  1019  1081 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-25 15:24:45.843  1019  1081 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:24:45.843  1019  1081 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:45.843  1019  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-25 15:24:45.853  1019  1487 I ActivityManager: Killing 6761:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-25 15:24:47.233   288   288 E SMD     : DCD OFF
,08-25 15:24:47.323  1681  1681 I ConfigService: onDestroy
,08-25 15:24:49.603  1019  3376 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-25 15:24:49.863  1019  3351 D SSRM:n  : SIOP:: AP = 400
,08-25 15:24:50.233   288   288 E SMD     : DCD OFF
,08-25 15:24:52.123  1019  1059 D PackageManager: [MSG] MCS_UNBIND
,08-25 15:24:52.123  1019  1031 I ActivityManager: Killing 6782:com.sec.pcw.device/1000 (adj 15): empty #21
,08-25 15:24:52.163  1019  1368 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-25 15:24:52.163  1019  1368 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-25 15:24:52.163  1019  1368 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-25 15:24:52.163  1019  1368 D BatteryService: stay LED for charging
,08-25 15:24:52.163  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-25 15:24:52.173  1019  1019 I MotionRecognitionService: Plugged
,08-25 15:24:52.173  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,08-25 15:24:52.173  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-25 15:24:52.173  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-25 15:24:52.173  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-25 15:24:52.173  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-25 15:24:52.193  3215  3215 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-25 15:24:52.193  3215  3357 D HeadsetStateMachine: Disconnected process message: 10
,08-25 15:24:52.203  1182  1182 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-25 15:24:52.213  1182  1182 D SViewCoverView: level :100 plugged : 2
,08-25 15:24:52.213  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
08-25 15:24:52.213  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-25 15:24:52.213  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-25 15:24:52.253  1019  1059 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-25 15:24:53.243   288   288 E SMD     : DCD OFF
,08-25 15:24:54.653  1019  1307 E Watchdog: !@Sync 3
,08-25 15:24:55.223   317   317 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-25 15:24:55.223   317   317 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-25 15:24:56.243   288   288 E SMD     : DCD OFF
,08-25 15:24:56.383  1019  1099 V AlarmManager: waitForAlarm result :4
,08-25 15:24:56.383  1019  1099 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-25 15:24:56.613  6089  6205 D Finsky  : [1104] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-25 15:24:56.613  6089  6089 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-25 15:24:57.463  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 15:24:57.463  6896  7047 I jxcore-log: 
,08-25 15:24:57.463  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 15:24:57.463  6896  7047 I jxcore-log: 
,08-25 15:24:57.473  6896  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:24:57.473  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:24:57.473  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:24:57.473  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:24:57.473  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:24:57.473  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:24:57.473  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:24:57.473  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:24:57.473  6896  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 15:24:57.473  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 15:24:57.473  6896  7047 I jxcore-log: 
,08-25 15:24:57.473  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 15:24:57.473  6896  7047 I jxcore-log: 
,08-25 15:24:58.123  6896  7047 D executeNativeTests: Running unit tests,
,08-25 15:24:58.213  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 15:24:58.213  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 added. We now have 2 listener(s)
,08-25 15:24:58.213  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-25 15:24:58.213  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:24:58.213  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:24:58.213  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:24:58.213  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 added. We now have 2 listener(s)
08-25 15:24:58.213  6896  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:24:58.213  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 15:24:58.213  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 15:24:58.223  6896  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:24:58.223  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:24:58.223  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:24:58.223  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:24:58.223  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:24:58.223  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:24:58.223  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:24:58.223  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:24:58.223  6896  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 15:24:58.223  6896  7047 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 15:24:58.223  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:24:58.223  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:24:58.233  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-25 15:24:58.233  6896  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 15:24:58.233  6896  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 15:24:58.233  6896  7047 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-25 15:24:58.233  6896  7047 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 15:24:58.233  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 15:24:58.233  6896  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 15:24:58.233  6896  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 15:24:58.233  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 15:24:58.233  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:24:58.233  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:24:58.233  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.233  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.233  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:24:58.233  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:24:58.233  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 removed from the list
08-25 15:24:58.233  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.233  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 removed from the list
08-25 15:24:58.233  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.233  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:24:58.233  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 15:24:58.243  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:24:58.243  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:24:58.243  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:24:58.243  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.243  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
,08-25 15:24:58.243  6896  7047 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-25 15:24:58.243  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 15:24:58.243  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:24:58.243  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 15:24:58.243  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.243  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.243  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.243  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
08-25 15:24:58.243  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.243  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.243  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.243  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.243  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.243  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.243  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:24:58.243  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 15:24:58.243  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:24:58.243  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.243  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
,08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no pe,er name> 36:2610:2610:2610:2610:2610]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 15:24:58.253  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:24:58.253  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:24:58.253  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:24:58.253  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.253  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.253  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:24:58.253  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
08-25 15:24:58.253  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.253  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.253  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.253  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.253  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:24:58.253  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.253  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.253  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:24:58.253  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:24:58.253  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.253  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
,08-25 15:24:58.253  6896  7047 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 15:24:58.253  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 15:24:58.263  6896  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:24:58.263  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:24:58.263  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:24:58.263  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:24:58.263  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:24:58.263  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:24:58.263  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:24:58.263  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:24:58.263  6896  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 15:24:58.263  6896  7047 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 15:24:58.263  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:24:58.263  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 15:24:58.263  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 15:24:58.263  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:24:58.263  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 15:24:58.263  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 15:24:58.263  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:24:58.263  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:24:58.273  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 15:24:58.273  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 15:24:58.283  6896  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-25 15:24:58.283  6896  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-25 15:24:58.283  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 15:24:58.283  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 15:24:58.283  6896  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 15:24:58.293  3215  3230 D BtGatt.GattService: registerClient() - UUID=f8e2afe3-0425-4b1c-b8df-c93a7a1cea2f
,08-25 15:24:58.343  3215  3298 D BtGatt.GattService: onClientRegistered() - UUID=f8e2afe3-0425-4b1c-b8df-c93a7a1cea2f, clientIf=6
,08-25 15:24:58.343  6896  6904 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-25 15:24:58.343  3215  3227 D BtGatt.GattService: start scan with filters
,08-25 15:24:58.343  3215  3355 D BtGatt.ScanManager: handling starting scan
,08-25 15:24:58.343  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 15:24:58.343  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-25 15:24:58.343  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 15:24:58.343  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 15:24:58.353  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 15:24:58.353  3215  3355 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
,08-25 15:24:58.353  6896  6896 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 15:24:58.363  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,08-25 15:24:58.363  3215  3298 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-25 15:24:58.363  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:24:58.363  3215  3355 D BtGatt.ScanManager: allow scan with filters
,08-25 15:24:58.363  3215  3355 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-25 15:24:58.363  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 15:24:58.363  3215  3355 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-25 15:24:58.373  6896  7047 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 15:24:58.373  3215  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-25 15:24:58.373  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:24:58.373  3215  3355 D BtGatt.ScanManager: Starting BLE batch scan
08-25 15:24:58.373  3215  3355 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 15:24:58.383  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 15:24:58.383  6896  7047 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 15:24:58.383  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 15:24:58.383  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 15:24:58.383  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.383  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 15:24:58.383  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 15:24:58.383  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 15:24:58.383  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 15:24:58.383  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 15:24:58.383  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 15:24:58.383  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 15:24:58.383  3215  3230 D BtGatt.GattService: stopScan() - queue size =1
,08-25 15:24:58.383  3215  3227 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 15:24:58.383  3215  3298 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-25 15:24:58.383  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:24:58.383  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:24:58.383  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 15:24:58.383  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 15:24:58.383  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 15:24:58.383  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 15:24:58.393  3215  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-25 15:24:58.393  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:24:58.393  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 15:24:58.393  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 15:24:58.393  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 15:24:58.393  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 15:24:58.393  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 15:24:58.393  6896  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 15:24:58.393  6896  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 15:24:58.393  6896  6896 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 15:24:58.393  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.393  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.393  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:24:58.393  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
08-25 15:24:58.393  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.393  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.393  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.393  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.403  3215  3355 D BtGatt.ScanManager: filter size is 1
08-25 15:24:58.403  3215  3355 D BtGatt.ScanManager: delete FilterIndex - 3
,08-25 15:24:58.403  6896  7047 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 15:24:58.403  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 15:24:58.403  3215  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-25 15:24:58.403  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:24:58.403  3215  3355 D BtGatt.ScanManager: stopping BLe Batch
,08-25 15:24:58.413  6896  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:24:58.413  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:24:58.413  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:24:58.413  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:24:58.413  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:24:58.413  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:24:58.413  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:24:58.413  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:24:58.413  3215  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-25 15:24:58.413  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:24:58.413  3215  3355 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 15:24:58.413  6896  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 15:24:58.423  6896  7047 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 15:24:58.423  3215  3298 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-25 15:24:58.423  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:24:58.423  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:24:58.423  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:24:58.423  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 15:24:58.433  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-25 15:24:58.433  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 15:24:58.433  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 15:24:58.433  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 15:24:58.433  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 15:24:58.443  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 15:24:58.443  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 15:24:58.443  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 15:24:58.443  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 15:24:58.443  6896  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 15:24:58.453  3215  3227 D BtGatt.GattService: registerClient() - UUID=fa087f15-f5be-41e5-866f-db2d4d9e64b9
,08-25 15:24:58.503  3215  3298 D BtGatt.GattService: onClientRegistered() - UUID=fa087f15-f5be-41e5-866f-db2d4d9e64b9, clientIf=6
,08-25 15:24:58.503  6896  6908 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-25 15:24:58.503  3215  3352 D BtGatt.GattService: start scan with filters
,08-25 15:24:58.503  3215  3355 D BtGatt.ScanManager: handling starting scan
,08-25 15:24:58.503  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 15:24:58.503  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-25 15:24:58.503  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 15:24:58.503  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 15:24:58.503  3215  3298 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-25 15:24:58.503  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:24:58.503  3215  3355 D BtGatt.ScanManager: allow scan with filters
,08-25 15:24:58.503  3215  3355 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-25 15:24:58.503  3215  3355 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-25 15:24:58.503  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 15:24:58.503  6896  6896 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 15:24:58.503  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 15:24:58.513  3215  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-25 15:24:58.513  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:24:58.513  3215  3355 D BtGatt.ScanManager: Starting BLE batch scan
08-25 15:24:58.513  3215  3355 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 15:24:58.513  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 15:24:58.523  6896  7047 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 15:24:58.523  3215  3298 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-25 15:24:58.523  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:24:58.523  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 15:24:58.523  6896  7047 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 15:24:58.523  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 15:24:58.523  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 15:24:58.523  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 15:24:58.523  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 15:24:58.523  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 15:24:58.523  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-25 15:24:58.523  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 15:24:58.523  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 15:24:58.523  3215  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-25 15:24:58.523  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:24:58.523  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 15:24:58.523  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 15:24:58.533  3215  3230 D BtGatt.GattService: stopScan() - queue size =1
,08-25 15:24:58.533  3215  3355 D BtGatt.ScanManager: filter size is 1
,08-25 15:24:58.533  3215  3355 D BtGatt.ScanManager: delete FilterIndex - 4
,08-25 15:24:58.533  3215  3227 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 15:24:58.533  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:24:58.533  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 15:24:58.533  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 15:24:58.533  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 15:24:58.533  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 15:24:58.533  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 15:24:58.533  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 15:24:58.533  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 15:24:58.533  3215  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-25 15:24:58.533  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 15:24:58.533  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 15:24:58.533  3215  3355 D BtGatt.ScanManager: stopping BLe Batch
,08-25 15:24:58.543  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 15:24:58.543  6896  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 15:24:58.543  6896  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 15:24:58.543  6896  6896 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 15:24:58.543  3215  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-25 15:24:58.543  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 15:24:58.543  3215  3355 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-25 15:24:58.543  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.543  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.543  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:24:58.543  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
,08-25 15:24:58.543  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.543  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.543  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.543  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.543  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.543  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:24:58.543  3215  3298 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-25 15:24:58.543  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:24:58.553  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:24:58.553  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:24:58.553  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.553  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.553  6896  7047 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 15:24:58.553  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 15:24:58.553  6896  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:24:58.553  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:24:58.553  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:24:58.553  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:24:58.553  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:24:58.553  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:24:58.553  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:24:58.553  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:24:58.553  6896  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 15:24:58.553  6896  7047 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 15:24:58.553  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:24:58.553  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 15:24:58.553  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 15:24:58.553  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:24:58.553  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 15:24:58.563  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 15:24:58.563  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:24:58.563  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:24:58.563  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 15:24:58.563  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 15:24:58.573  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 15:24:58.573  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 15:24:58.573  6896  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 15:24:58.573  3215  3352 D BtGatt.GattService: registerClient() - UUID=dd5bc271-904e-4b7b-b296-49a0e28f344f
,08-25 15:24:58.623  3215  3298 D BtGatt.GattService: onClientRegistered() - UUID=dd5bc271-904e-4b7b-b296-49a0e28f344f, clientIf=6,
,08-25 15:24:58.623  6896  7006 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-25 15:24:58.623  3215  3381 D BtGatt.GattService: start scan with filters
,08-25 15:24:58.623  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 15:24:58.623  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 15:24:58.623  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 15:24:58.623  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 15:24:58.623  3215  3355 D BtGatt.ScanManager: handling starting scan
,08-25 15:24:58.623  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-25 15:24:58.623  6896  6896 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 15:24:58.623  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 15:24:58.623  3215  3298 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-25 15:24:58.623  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 15:24:58.623  3215  3355 D BtGatt.ScanManager: allow scan with filters
08-25 15:24:58.623  3215  3355 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-25 15:24:58.623  3215  3355 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-25 15:24:58.633  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 15:24:58.633  6896  7047 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 15:24:58.633  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 15:24:58.633  3215  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-25 15:24:58.633  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:24:58.633  3215  3355 D BtGatt.ScanManager: Starting BLE batch scan
,08-25 15:24:58.633  3215  3355 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 15:24:58.633  6896  7047 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 15:24:58.643  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 15:24:58.643  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 15:24:58.643  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.643  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 15:24:58.643  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 15:24:58.643  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-25 15:24:58.643  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 15:24:58.643  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 15:24:58.643  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 15:24:58.643  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 15:24:58.643  3215  3352 D BtGatt.GattService: stopScan() - queue size =1
,08-25 15:24:58.643  3215  3381 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 15:24:58.643  3215  3298 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-25 15:24:58.643  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:24:58.653  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-25 15:24:58.653  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 15:24:58.653  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 15:24:58.653  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 15:24:58.653  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 15:24:58.653  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 15:24:58.653  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 15:24:58.653  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 15:24:58.653  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 15:24:58.653  3215  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-25 15:24:58.653  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:24:58.653  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 15:24:58.663  6896  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 15:24:58.663  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:24:58.663  6896  7047 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 15:24:58.663  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:24:58.663  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:24:58.663  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.663  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.663  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:24:58.663  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
08-25 15:24:58.663  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.663  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.663  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.663  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.663  6896  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 15:24:58.663  6896  6896 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 15:24:58.663  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.663  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:24:58.663  3215  3355 D BtGatt.ScanManager: filter size is 1
08-25 15:24:58.663  3215  3355 D BtGatt.ScanManager: delete FilterIndex - 5
,08-25 15:24:58.663  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:24:58.663  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:24:58.663  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.663  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
,08-25 15:24:58.663  6896  7047 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-25 15:24:58.663  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 15:24:58.663  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:24:58.663  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:24:58.663  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.663  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.663  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.663  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
08-25 15:24:58.663  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.663  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.663  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.663  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.663  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.663  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.663  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:24:58.663  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:24:58.663  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:24:58.663  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 15:24:58.663  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.663  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-25 15:24:58.663  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:24:58.663  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:24:58.663  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:24:58.663  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 15:24:58.663  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.663  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.663  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
08-25 15:24:58.663  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 15:24:58.663  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.663  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.663  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-25 15:24:58.663  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.663  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.663  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:24:58.673  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:24:58.673  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:24:58.673  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.673  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list,
08-25 15:24:58.673  3215  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-25 15:24:58.673  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 15:24:58.673  3215  3355 D BtGatt.ScanManager: stopping BLe Batch
,08-25 15:24:58.673  6896  7047 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-25 15:24:58.673  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:24:58.673  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 15:24:58.673  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:24:58.673  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.673  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.673  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:24:58.673  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
08-25 15:24:58.673  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.673  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.673  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.673  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 15:24:58.673  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.673  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.673  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.673  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:24:58.673  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 15:24:58.673  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.673  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list,
08-25 15:24:58.673  6896  7047 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-25 15:24:58.673  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 15:24:58.673  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-25 15:24:58.673  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:24:58.673  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.673  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.673  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.673  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
08-25 15:24:58.673  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.673  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.673  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.673  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.673  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.673  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.673  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.673  3215  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-25 15:24:58.673  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 15:24:58.673  3215  3355 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-25 15:24:58.673  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 15:24:58.673  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:24:58.673  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.673  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.673  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 15:24:58.673  6896  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 15:24:58.673  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 15:24:58.673  6896  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 15:24:58.673  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 15:24:58.673  6896  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 15:24:58.673  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:24:58.673  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:24:58.673  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:24:58.673  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.673  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.673  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.673  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
,08-25 15:24:58.673  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.673  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.673  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.673  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.673  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.673  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.673  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.683  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 15:24:58.683  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:24:58.683  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.683  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.683  6896  7047 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 15:24:58.683  6896  7047 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 15:24:58.683  6896  7047 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 15:24:58.683  6896  7047 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 15:24:58.683  3215  3298 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-25 15:24:58.683  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 15:24:58.683  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-25 15:24:58.683  6896  7047 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 15:24:58.683  6896  7047 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 15:24:58.683  6896  7047 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 15:24:58.683  6896  7047 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 15:24:58.683  6896  7047 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 15:24:58.683  6896  7047 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 15:24:58.683  6896  7047 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-25 15:24:58.683  6896  7047 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 15:24:58.683  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 15:24:58.683  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 15:24:58.683  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 15:24:58.683  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-25 15:24:58.693  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 15:24:58.693  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 15:24:58.693  6896  7047 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 15:24:58.693  6896  7047 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 15:24:58.693  6896  7047 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 15:24:58.693  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:24:58.693  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:24:58.693  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:24:58.693  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.693  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.693  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.693  6896  7179 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1350)
08-25 15:24:58.693  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-25 15:24:58.693  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
08-25 15:24:58.693  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.693  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.693  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.693  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.693  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.693  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.693  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:24:58.693  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:24:58.693  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:24:58.693  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.693  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.693  6896  7047 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 15:24:58.693  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:24:58.693  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:24:58.693  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:24:58.693  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.693  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.693  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:24:58.693  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
08-25 15:24:58.693  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.693  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.693  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.693  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.693  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.693  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.693  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.693  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:24:58.693  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:24:58.693  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.693  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
,08-25 15:24:58.693  6896  7180 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1350
08-25 15:24:58.693  6896  7047 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 15:24:58.693  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:24:58.693  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:24:58.693  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:24:58.693  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.693  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.693  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.693  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
08-25 15:24:58.693  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.693  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.693  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.693  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.693  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.693  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.693  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:24:58.703  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:24:58.703  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:24:58.703  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.703  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.703  6896  7047 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 15:24:58.703  6896  7047 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 15:24:58.703  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 15:24:58.703  6896  7047 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 15:24:58.703  6896  7047 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 15:24:58.703  6896  7047 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 15:24:58.703  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 15:24:58.703  6896  7047 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-25 15:24:58.703  6896  7047 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 15:24:58.703  6896  7047 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 15:24:58.703  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 15:24:58.703  6896  7047 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 15:24:58.703  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:24:58.703  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:24:58.703  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:24:58.703  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-25 15:24:58.703  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.703  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.703  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
08-25 15:24:58.703  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.703  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.703  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.703  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 15:24:58.703  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.703  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.703  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.703  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:24:58.703  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:24:58.703  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 15:24:58.703  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.703  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.703  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.703  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.703  6896  7179 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-25 15:24:58.703  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
08-25 15:24:58.703  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.703  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.703  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.703  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.703  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.703  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.703  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.703  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.703  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.703  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.703  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
08-25 15:24:58.703  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 15:24:58.703  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:24:58.703  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:24:58.703  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.703  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.703  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:24:58.703  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
08-25 15:24:58.703  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.703  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.703  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.703  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.703  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.703  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.703  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.703  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:24:58.703  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-25 15:24:58.703  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.703  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.703  6896  7179 D BluetoothSocket: connect(): myUserId = 0
08-25 15:24:58.703  6896  7179 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 15:24:58.703  6896  7047 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 15:24:58.713  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:24:58.713  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 15:24:58.713  3215  3230 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:24:58.713  6896  7047 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 15:24:58.713  6896  7047 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 15:24:58.713  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 15:24:58.713  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 15:24:58.713  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.713  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 15:24:58.713  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 15:24:58.713  6896  6896 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 15:24:58.713  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 15:24:58.713  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.713  6896  7047 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 15:24:58.713  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
08-25 15:24:58.713  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.713  6896  6896 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 15:24:58.713  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 15:24:58.713  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 15:24:58.713  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 15:24:58.713  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.713  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.713  6896  7179 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
08-25 15:24:58.713  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 15:24:58.713  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.713  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:24:58.713  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 15:24:58.713  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:24:58.713  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.713  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.713  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.713  6896  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 15:24:58.713  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
08-25 15:24:58.713  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.713  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.713  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.713  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.713  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.713  6896  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 15:24:58.713  6896  6896 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 15:24:58.713  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.713  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.713  6896  7181 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 15:24:58.713  6896  7181 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 15:24:58.713  6896  6896 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 15:24:58.713  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:24:58.713  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:24:58.713  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 15:24:58.713  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.713  6896  7047 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 15:24:58.713  6896  7047 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 15:24:58.713  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 15:24:58.713  6896  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 15:24:58.713  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:24:58.713  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 15:24:58.713  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:24:58.713  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.713  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.713  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.713  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
08-25 15:24:58.713  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.723  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.723  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.723  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-25 15:24:58.723  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.723  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.723  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.723  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:24:58.723  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:24:58.723  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.723  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
,08-25 15:24:58.723  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:24:58.723  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:24:58.723  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 15:24:58.723  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.723  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.723  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.723  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
08-25 15:24:58.723  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.723  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.723  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.723  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.723  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.723  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.723  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:24:58.723  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:24:58.723  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:24:58.723  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.723  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
,08-25 15:24:58.723  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:24:58.723  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 15:24:58.723  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:24:58.723  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:24:58.723  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.723  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.723  6896  7047 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51740 not in the list
08-25 15:24:58.723  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.723  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
,08-25 15:24:58.723  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:24:58.723  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.723  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.723  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:24:58.723  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:24:58.723  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:24:58.723  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:24:58.723  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:24:58.723  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b09679 not in the list
08-25 15:24:58.723  6896  7047 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 15:24:58.723  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 15:24:58.723  6896  7047 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 15:24:58.723  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 15:24:58.723  6896  7047 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 15:24:58.723  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-25 15:24:58.733  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-25 15:24:58.733  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 15:24:58.733  6896  7047 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-25 15:24:58.733  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 15:24:58.733  6896  7047 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 15:24:58.733  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 15:24:58.733  6896  7047 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 15:24:58.733  6896  7047 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-25 15:24:58.733  6896  7047 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 15:24:58.733  6896  7047 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-25 15:24:58.733  6896  7047 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 15:24:58.733  6896  7047 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 15:24:58.733  6896  7047 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 15:24:58.733  6896  7047 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-25 15:24:58.733  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 15:24:58.733  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2adcb2b3 added. We now have 2 listener(s)
08-25 15:24:58.733  6896  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:24:58.733  6896  7047 D BluetoothAdapter: enable()
,08-25 15:24:58.733  6896  7047 D BluetoothAdapter: enable(): BT is already enabled..!
,08-25 15:24:58.743  1019  1492 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-25 15:24:58.743  1019  1492 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 15:24:58.743  1019  1492 D SecContentProvider2: mCursor = null
08-25 15:24:58.743  1019  1492 D WifiService: setWifiEnabled: true pid=6896, uid=10170
08-25 15:24:58.743  1019  1492 W ActivityManager: Permission Denial: getCurrentUser() from pid=6896, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-25 15:24:58.743  1019  1492 W WifiService: Failed getting userId using ActivityManagerNative
08-25 15:24:58.743  1019  1492 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6896, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-25 15:24:58.743  1019  1492 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 15:24:58.743  1019  1492 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-25 15:24:58.743  1019  1492 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-25 15:24:58.743  1019  1492 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-25 15:24:58.743  1019  1492 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-25 15:24:58.743  1019  1492 D SettingsProvider: name = wifi_on
,08-25 15:24:58.743  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:24:58.743  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27dcd070 added. We now have 3 listener(s)
08-25 15:24:58.743  6896  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:24:58.753  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:24:58.753  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27270fe9 added. We now have 4 listener(s)
08-25 15:24:58.753  6896  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:24:58.753  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:24:58.753  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9b0f46e added. We now have 5 listener(s)
08-25 15:24:58.753  6896  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:24:58.753  1019  1032 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-25 15:24:58.753  1019  1032 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 15:24:58.753  1019  1032 D SecContentProvider2: mCursor = null
,08-25 15:24:58.753  1019  1032 D WifiService: setWifiEnabled: false pid=6896, uid=10170
,08-25 15:24:58.753  1019  1032 D SettingsProvider: name = wifi_on
,08-25 15:24:58.773  6896  7047 D BluetoothAdapter: disable(),
08-25 15:24:58.773  1019  1130 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 15:24:58.773  1379  1379 I wpa_supplicant: reset timer : RESET_TIMER 0
08-25 15:24:58.773  1379  1379 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-25 15:24:58.773  1379  1379 I wpa_supplicant: P2P: Current p2p state = IDLE
08-25 15:24:58.773  1019  1308 D SettingsProvider: name = bluetooth_on
,08-25 15:24:58.773  1379  1379 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-25 15:24:58.783  1019  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 15:24:58.793  3215  3295 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-25 15:24:58.793  3215  3295 D BluetoothAdapterProperties: Setting state to 13
08-25 15:24:58.793  3215  3295 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-25 15:24:58.793  3215  3295 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 15:24:58.793  3215  3295 D BluetoothAdapterService: updateAdapterState state is 13
,08-25 15:24:58.793  1019  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 15:24:58.793  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 15:24:58.803  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:24:58.803  1019  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:58.803  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:24:58.803  1379  1379 I wpa_supplicant: Scan aborted because the firmware maybe busy.,
08-25 15:24:58.803  1379  1379 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
08-25 15:24:58.803  1379  1379 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
,08-25 15:24:58.803  3215  3215 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-25 15:24:58.803  1019  1130 E WifiNative-wlan0: do suspend true
08-25 15:24:58.803  3215  3295 D BluetoothAdapterService: Autoconnection is available 
,08-25 15:24:58.803  3215  3295 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,08-25 15:24:58.803  3215  3295 D BluetoothAdapterService: terminating service from this receiver
08-25 15:24:58.803  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-25 15:24:58.803  1019  1019 I InputMethodManagerService: [BT Setting State] State =13
,08-25 15:24:58.803  3215  3215 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@25e71a15, channel: 19, state: LISTENING
08-25 15:24:58.803  3215  3215 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@25e71a15, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d19b9d2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@e96b12amSocket: android.net.LocalSocket@10a06b1b impl:android.net.LocalSocketImpl@26d204b8 fd:FileDescriptor[82],
08-25 15:24:58.803  3215  3215 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@10a06b1b impl:android.net.LocalSocketImpl@26d204b8 fd:FileDescriptor[82]
,08-25 15:24:58.813  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,08-25 15:24:58.813  1879  1879 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0,
08-25 15:24:58.813  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 15:24:58.813  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:24:58.813  1182  1182 D BluetoothTile:  getBluetoothState : 13
08-25 15:24:58.813  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 15:24:58.823  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 15:24:58.823  4780  4780 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:24:58.823  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-25 15:24:58.823  1019  1081 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-25 15:24:58.823  1019  1081 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:24:58.823  1019  1081 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:58.823  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:24:58.823  1019  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:24:58.833  6896  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:24:58.833  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:24:58.833  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:24:58.833  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:24:58.833  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:24:58.833  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:24:58.833  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:24:58.833  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:24:58.833  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 15:24:58.833  6896  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:24:58.833  6896  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 15:24:58.833  3215  3295 D BluetoothAdapterProperties: onBluetoothDisable(),
08-25 15:24:58.833  3215  3295 D BluetoothAdapterProperties: mDiscovering is false
08-25 15:24:58.833  1019  1032 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-25 15:24:58.833  3215  3295 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-25 15:24:58.833  1019  1490 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ),
08-25 15:24:58.833  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:24:58.833  1019  1487 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-25 15:24:58.833  6896  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:24:58.833  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:24:58.833  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:24:58.833  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:24:58.833  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:24:58.833  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 15:24:58.833  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 15:24:58.833  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:24:58.833  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-25 15:24:58.833  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:24:58.833  6896  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 15:24:58.833  6896  7047 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 15:24:58.843  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:24:58.843  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:24:58.843  3215  3298 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-25 15:24:58.843  3215  3298 D BluetoothAdapterProperties: Scan Mode:20
,08-25 15:24:58.853  3215  3295 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-25 15:24:58.853  3215  3295 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-25 15:24:58.853  3215  3295 E bt-btif : cmd socket is not created
,08-25 15:24:58.853  3215  3299 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-25 15:24:58.853  6896  7179 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@a16839c, channel: -1, state: INIT
,08-25 15:24:58.853  6896  7179 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@a16839c, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e57c1a5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2fbe97amSocket: android.net.LocalSocket@14c1c52b impl:android.net.LocalSocketImpl@ad63d88 fd:FileDescriptor[105]
,08-25 15:24:58.853  6896  7179 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@14c1c52b impl:android.net.LocalSocketImpl@ad63d88 fd:FileDescriptor[105]
,08-25 15:24:58.853  3215  3295 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-25 15:24:58.853  3215  5335 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-25 15:24:58.853  6896  7179 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1350)
,08-25 15:24:58.853  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:24:58.863  3215  3215 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@232c4291, channel: 5, state: LISTENING
08-25 15:24:58.863  3215  3215 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@232c4291, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39f3bc5d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@346b5f6mSocket: android.net.LocalSocket@22d09df7 impl:android.net.LocalSocketImpl@6feb464 fd:FileDescriptor[80]
08-25 15:24:58.863  4780  4780 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 15:24:58.863  3215  3215 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@22d09df7 impl:android.net.LocalSocketImpl@6feb464 fd:FileDescriptor[80]
,08-25 15:24:58.863  1019  1032 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-25 15:24:58.863  3215  3299 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
,08-25 15:24:58.863  3215  3299 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
08-25 15:24:58.863  3215  3299 W bt-btif : invalid rfc slot id: 4
,08-25 15:24:58.863  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:24:58.863  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 15:24:58.863  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:24:58.863  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:58.863  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 15:24:58.873  3215  3215 I BtOppRfcommListener: stopping Accept Thread
,08-25 15:24:58.873  3215  3215 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3ec176cd, channel: 12, state: LISTENING
,08-25 15:24:58.873  3215  3215 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3ec176cd, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34c337cc, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1a203b82mSocket: android.net.LocalSocket@3a672293 impl:android.net.LocalSocketImpl@1b24b2d0 fd:FileDescriptor[86]
08-25 15:24:58.873  3215  3215 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3a672293 impl:android.net.LocalSocketImpl@1b24b2d0 fd:FileDescriptor[86]
,08-25 15:24:58.873  3215  5335 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-25 15:24:58.873  4780  4780 D BluetoothPbap: Proxy object disconnected
08-25 15:24:58.873  4780  4780 D PbapServerProfile: Bluetooth service disconnected
,08-25 15:24:58.873  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 15:24:58.883  1019  1129 D WifiP2pService: InactiveState{ what=143375 }
,08-25 15:24:58.883  1019  1129 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-25 15:24:58.883  3215  3299 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 15:24:58.883  3215  3299 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 15:24:58.883  3215  3299 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 15:24:58.883  3215  3299 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 15:24:58.883  3215  3299 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 15:24:58.883  3215  3299 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-25 15:24:58.883   278  1008 D CommandListener: Clearing all IP addresses on wlan0
,08-25 15:24:58.893  3215  3215 V BluetoothOppManager: cleanUp...
08-25 15:24:58.893  4780  4780 D DockEventReceiver: finishStartingService: stopping service
08-25 15:24:58.893  1681  2548 V NativeCrypto: Read error: ssl=0xb89cd2c8: I/O error during system call, Connection timed out
08-25 15:24:58.893  1019  1132 E ConnectivityService: updateNetworkInfo()
,08-25 15:24:58.893  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 15:24:58.893  1019  1132 E ConnectivityService: updateNetworkInfo()
08-25 15:24:58.893  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,08-25 15:24:58.893  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:24:58.893  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-25 15:24:58.893  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:58.893  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:58.893  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:58.893  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:24:58.893  4780  4780 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 15:24:58.893  1681  2548 V NativeCrypto: SSL shutdown failed: ssl=0xb89cd2c8: I/O error during system call, Broken pipe
,08-25 15:24:58.903  1019  1129 D WifiP2pService: InactiveState{ what=131204 }
,08-25 15:24:58.903  1019  1129 D WifiP2pService: P2pEnabledState{ what=131204 }
08-25 15:24:58.903  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-25 15:24:58.903  1019  1485 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
08-25 15:24:58.903  1019  1129 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-25 15:24:58.903  1019  1130 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-25 15:24:58.913  1019  1777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-4ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 15:24:58.913  1019  1777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 15:24:58.913  1019  1777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-25 15:24:58.913  1019  1777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:24:58.913  1019  1777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-25 15:24:58.913  1019  1777 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-25 15:24:58.913  1019  1777 I qtaguid : Tagging socket 355 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1019, getuid(): 1000
,08-25 15:24:58.913  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 15:24:58.913  1019  1153 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 15:24:58.913  1019  1019 D RttService: SCAN_AVAILABLE : 1
08-25 15:24:58.913  1019  1154 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 15:24:58.923  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
,08-25 15:24:58.923  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
08-25 15:24:58.923  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-25 15:24:58.923  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:24:58.923  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 15:24:58.933  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:24:58.933  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:24:58.933  1019  1129 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-25 15:24:58.933  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-25 15:24:58.933  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:24:58.933  1019  1129 D WifiP2pService: P2pDisablingState
,08-25 15:24:58.933  1019  1129 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-25 15:24:58.933  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:58.933  1019  1129 D WifiP2pService: p2p socket connection lost
08-25 15:24:58.933  1019  1130 E WifiNative-wlan0: do suspend true
08-25 15:24:58.933  1019  1129 D WifiP2pService: P2pDisabledState
08-25 15:24:58.933  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:24:58.933  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-25 15:24:58.933  1019  4324 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-25 15:24:58.943  1019  4324 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:58.943  1019  4324 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:58.943  1019  4324 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-25 15:24:58.943  1019  4324 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:58.953  1019  1777 I qtaguid : Untagging socket 355
,08-25 15:24:58.953  1019  1777 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 15:24:58.953  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 15:24:58.953  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
08-25 15:24:58.953  1019  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-25 15:24:58.953  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
08-25 15:24:58.953  1019  1050 D WifiDisplayController: disconnect
08-25 15:24:58.953  1019  1050 D WifiDisplayController: updateConnection
08-25 15:24:58.953  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 15:24:58.953  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 15:24:58.953  1019  1050 D WifiDisplayAdapter: onP2pDisconnected,
08-25 15:24:58.953  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 15:24:58.953  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
08-25 15:24:58.953  1019  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-25 15:24:58.953  7192  7192 E Zygote  : MountEmulatedStorage()
,08-25 15:24:58.953  7192  7192 I libpersona: KNOX_SDCARD checking this for 10055
08-25 15:24:58.953  7192  7192 E Zygote  : v2
08-25 15:24:58.953  7192  7192 I libpersona: KNOX_SDCARD not a persona
,08-25 15:24:58.963  1019  4324 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7192 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-25 15:24:58.963  7192  7192 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:24:58.963  7192  7192 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 15:24:58.963  1019  1129 D WifiP2pService: P2pDisabledState{ what=143375 }
08-25 15:24:58.963  7192  7192 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 15:24:58.963  1019  1129 D WifiP2pService: DefaultState{ what=143375 }
08-25 15:24:58.963  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-25 15:24:58.963  1019  3856 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-25 15:24:58.963  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-25 15:24:58.973   278  1008 D CommandListener: Clearing all IP addresses on wlan0,
08-25 15:24:58.973   278  1003 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 15:24:58.973   278  1003 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-25 15:24:58.973  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
,08-25 15:24:58.973  1019  1132 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-25 15:24:58.973  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:24:58.973  1019  1132 V NetworkStats: updateIfacesLocked()
08-25 15:24:58.973  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 15:24:58.973  1019  1132 V NetworkStats: performPollLocked(flags=0x1)
08-25 15:24:58.973  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:24:58.973  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:58.973  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:58.973  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:58.973  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:58.973  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 15:24:58.973  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 15:24:58.983  1019  1777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-25 15:24:58.983  1019  1777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-25 15:24:58.983  1379  1379 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-25 15:24:58.983  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-25 15:24:58.983   304   304 I art     : Explicit concurrent mark sweep GC freed 8673(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 3.200ms total 25.331ms
08-25 15:24:58.983  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:24:58.983  1019  1132 V NetworkStats: performPollLocked() took 7ms
,08-25 15:24:58.993  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 15:24:58.993  1019  1130 D SecContentProvider2: mCursor = null
,08-25 15:24:58.993  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-25 15:24:58.993  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:24:58.993  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 15:24:58.993  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:58.993  4780  4780 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-25 15:24:58.993  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:58.993  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:58.993  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:24:59.003  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:24:59.003  1019  1132 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-25 15:24:59.003  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:24:59.003  1182  1708 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 15:24:59.003  1019  1777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 15:24:59.003   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 16.588ms
,08-25 15:24:59.003  6896  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:24:59.003  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:24:59.003  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:24:59.003  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:24:59.003  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:24:59.003  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:24:59.003  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:24:59.003  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:24:59.003  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:24:59.003  1019  1049 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-25 15:24:59.003  6896  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:24:59.003  6896  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:24:59.003  1019  1132 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ],
08-25 15:24:59.003  1459  1459 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-25 15:24:59.003  1019  1132 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-25 15:24:59.003  1019  1129 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false,
08-25 15:24:59.003  1019  1132 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-25 15:24:59.003  1459  1459 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 15:24:59.003  1019  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 15:24:59.003  7192  7192 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 15:24:59.013  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 15:24:59.003  7192  7192 D ActivityThread: Added TimaKeyStore provider
08-25 15:24:59.013  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-25 15:24:59.003  1019  1130 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-25 15:24:59.013  1182  1182 D HotspotTile: onReceive : 0, 0
08-25 15:24:59.013  6896  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:24:59.013  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:24:59.013  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-25 15:24:59.013  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:24:59.013  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:24:59.013  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false,
08-25 15:24:59.013  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:24:59.013  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:24:59.013  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 15:24:59.013  6896  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:24:59.013  6896  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:24:59.013  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-25 15:24:59.013  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:24:59.013  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 15:24:59.013  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:59.013  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:59.013  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:59.013  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:59.013  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 15:24:59.013  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-25 15:24:59.023  1019  1132 D ConnectivityService: nai.networkMonitor.doQuit()
08-25 15:24:59.023  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-25 15:24:59.023  1019  1132 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-25 15:24:59.023  1019  1132 E ConnectivityService: updateNetworkInfo()
08-25 15:24:59.023  1019  1132 E ConnectivityService: updateNetworkInfo()
08-25 15:24:59.023   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 17.586ms
,08-25 15:24:59.023  1019  1049 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-25 15:24:59.023  1019  1019 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-25 15:24:59.023  1019  1133 D Tethering: MasterInitialState.processMessage what=3
,08-25 15:24:59.023  1019  1127 V NetworkStats: updateIfacesLocked()
08-25 15:24:59.023  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:24:59.023  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-25 15:24:59.023  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 15:24:59.023  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 15:24:59.023  1182  1182 D StatusBar.NetworkController: EthernetConnected: false
08-25 15:24:59.023  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-25 15:24:59.023  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-25 15:24:59.023  1182  1182 D StatusBar.NetworkController: updateDataNetType()
,08-25 15:24:59.023  1019  1127 V NetworkStats: performPollLocked() took 4ms
08-25 15:24:59.023  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:24:59.023  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:24:59.023  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:24:59.023  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:24:59.023  1019  1128 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-25 15:24:59.023  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:24:59.023  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-25 15:24:59.023  1182  1182 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-25 15:24:59.033  1182  1182 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-25 15:24:59.033  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-25 15:24:59.033  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,08-25 15:24:59.033  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-25 15:24:59.033  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:24:59.033  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:24:59.033  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-25 15:24:59.033  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:24:59.033  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 15:24:59.033  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:59.033  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:59.033  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:59.033  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:24:59.043  7192  7192 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-25 15:24:59.053  3215  3295 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
08-25 15:24:59.053  3215  3295 D BtConfig.SecureMode: isSecureModeOn:false
08-25 15:24:59.053  3215  3295 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-25 15:24:59.053  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-25 15:24:59.053  3215  3295 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-25 15:24:59.053  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-25 15:24:59.053  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-25 15:24:59.053  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-25 15:24:59.053  1019  3856 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:24:59.053  1019  3856 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-25 15:24:59.053  1019  3856 W ActivityManager: userId = 0, bbcId = -10000,
08-25 15:24:59.053  1019  3856 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 15:24:59.053  1019  3856 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 15:24:59.053  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-25 15:24:59.053  1019  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:24:59.053  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-25 15:24:59.053  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-25 15:24:59.053  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-25 15:24:59.053  3215  3215 D HeadsetService: Received stop request...Stopping profile...
08-25 15:24:59.053  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:24:59.053  1019  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:59.053  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
08-25 15:24:59.053  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:24:59.063  4780  4780 D HeadsetProfile: Bluetooth service disconnected
08-25 15:24:59.063  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-25 15:24:59.063  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 15:24:59.063  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-25 15:24:59.063  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 15:24:59.063  1019  3856 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:24:59.063  1379  1379 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 15:24:59.063  1019  3856 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 15:24:59.063  1019  3856 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:24:59.063  1019  3856 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:59.063  1019  3856 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:24:59.063  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-25 15:24:59.063  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-25 15:24:59.063  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-25 15:24:59.063  1019  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:24:59.063  1019  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-25 15:24:59.063  1019  1487 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:24:59.063  1019  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:59.063  1019  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:24:59.073  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-25 15:24:59.073  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-25 15:24:59.073  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-25 15:24:59.073  1019  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 15:24:59.073  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 15:24:59.073  7192  7192 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-25 15:24:59.073  7192  7192 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() ,
08-25 15:24:59.073  7192  7192 D UserAnalysis: Create SecureDbHelper
,08-25 15:24:59.073  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:24:59.073  1019  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:59.073  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:24:59.073  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-25 15:24:59.073  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 15:24:59.073  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-25 15:24:59.073  1019  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:24:59.073  1019  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 15:24:59.083  1019  1492 W ActivityManager: userId = 0, bbcId = -10000,
08-25 15:24:59.083  1019  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:59.083  1019  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 15:24:59.083  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-25 15:24:59.083  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 15:24:59.083  3215  3295 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-25 15:24:59.083  1019  3856 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 15:24:59.083  1019  3856 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-25 15:24:59.083  1019  3856 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:24:59.083  1019  3856 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 15:24:59.083  1019  3856 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 15:24:59.083  7192  7192 D IntelligenceServiceApplication: onCreate()
08-25 15:24:59.083  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-25 15:24:59.083  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 15:24:59.083  3215  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 15:24:59.083  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-25 15:24:59.083  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-25 15:24:59.083  3215  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-25 15:24:59.083  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-25 15:24:59.083  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-25 15:24:59.083  3215  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-25 15:24:59.083  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-25 15:24:59.083  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 15:24:59.083  3215  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-25 15:24:59.083  1019  4324 I ActivityManager: Killing 6817:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
08-25 15:24:59.083  3215  3295 D BluetoothAdapterState: Stopping profile services that were post enabled
08-25 15:24:59.083  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-25 15:24:59.083  3215  3215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 15:24:59.083  3215  3215 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-25 15:24:59.083  3215  3215 D A2dpService: Received stop request...Stopping profile...
08-25 15:24:59.083  3215  3363 D A2dpStateMachine: Exit Disconnected: -1
,08-25 15:24:59.093  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055,
,08-25 15:24:59.093  1019  1019 D BluetoothA2dp: Proxy object disconnected
08-25 15:24:59.093  7192  7192 D IntelligenceServiceApplication: no applications having user consent for prediction
08-25 15:24:59.093  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-25 15:24:59.093  4780  4780 D BluetoothA2dp: Proxy object disconnected
08-25 15:24:59.093  4780  4780 D A2dpProfile: Bluetooth service disconnected
,08-25 15:24:59.093  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-25 15:24:59.103  3215  3215 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 15:24:59.103  3215  3215 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 15:24:59.103  7192  7192 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-25 15:24:59.103  3215  3215 D HidService: Received stop request...Stopping profile...
08-25 15:24:59.103  3215  3215 D HidService: Stopping Bluetooth HidService
08-25 15:24:59.103  3215  3215 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 15:24:59.103  3215  3215 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-25 15:24:59.103  3215  3215 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 15:24:59.103  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
,08-25 15:24:59.103  3215  3215 D HealthService: Received stop request...Stopping profile...
,08-25 15:24:59.103  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
,08-25 15:24:59.103  4780  4780 D BluetoothInputDevice: Proxy object disconnected
08-25 15:24:59.103  4780  4780 D HidProfile: Bluetooth service disconnected
,08-25 15:24:59.113  3215  3215 D PanService: Received stop request...Stopping profile...
08-25 15:24:59.113  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
,08-25 15:24:59.113  1019  1019 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-25 15:24:59.113  3215  3215 D BluetoothMapService: Received stop request...Stopping profile...
,08-25 15:24:59.113  4780  4780 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 15:24:59.113  4780  4780 D PanProfile: Bluetooth service disconnected
,08-25 15:24:59.113  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055,
08-25 15:24:59.113  3215  3215 D SapService: Received stop request...Stopping profile...
08-25 15:24:59.113  3215  3215 D SapService: Stopping Bluetooth SapService
08-25 15:24:59.113  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
08-25 15:24:59.113  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 15:24:59.113  4780  4780 D BluetoothMap: Proxy object disconnected
,08-25 15:24:59.113  4780  4780 D MapProfile: Bluetooth service disconnected
08-25 15:24:59.113  7192  7192 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-25 15:24:59.123  1379  1379 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-25 15:24:59.123  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 15:24:59.123  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-25 15:24:59.123  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 15:24:59.123  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 15:24:59.123  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-25 15:24:59.123  3215  3215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 15:24:59.123  3215  3215 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-25 15:24:59.123  3215  3215 D BluetoothA2dp: Proxy object disconnected
08-25 15:24:59.123  3215  3215 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-25 15:24:59.123  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 15:24:59.123  4780  4780 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-25 15:24:59.123  4780  4780 D SapProfile: Bluetooth service disconnected
,08-25 15:24:59.123  1019  1491 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-25 15:24:59.123  3215  3366 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 15:24:59.123  3215  3215 I GKI_LINUX: GKI_exit_task 2 done
08-25 15:24:59.123  3215  3215 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-25 15:24:59.123  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-25 15:24:59.123  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 15:24:59.133  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 15:24:59.133  1019  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:59.133  3215  3215 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-25 15:24:59.133  1019  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:59.133  3215  3215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 15:24:59.133  1019  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:59.133  3215  3215 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-25 15:24:59.133  1019  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:59.133  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-25 15:24:59.133  3215  3215 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-25 15:24:59.133  3215  3215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 15:24:59.133  3215  3215 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-25 15:24:59.133  3215  3215 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 15:24:59.133  3215  3215 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 15:24:59.133  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-25 15:24:59.133  3215  3215 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-25 15:24:59.133  3215  3215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 15:24:59.133  3215  3215 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-25 15:24:59.133  3215  3215 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 15:24:59.133  3215  3215 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-25 15:24:59.133  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 15:24:59.133  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 15:24:59.133  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-25 15:24:59.133  3215  3215 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-25 15:24:59.133  3215  3215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-25 15:24:59.133  3215  3215 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-25 15:24:59.133  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-25 15:24:59.133  3215  3215 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-25 15:24:59.133  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 15:24:59.133  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 15:24:59.133  3215  3215 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-25 15:24:59.133  3215  3215 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-25 15:24:59.143  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 15:24:59.143  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 15:24:59.143  7215  7215 I libpersona: KNOX_SDCARD checking this for 10105
08-25 15:24:59.143  7215  7215 E Zygote  : MountEmulatedStorage()
08-25 15:24:59.143  7215  7215 I libpersona: KNOX_SDCARD not a persona
08-25 15:24:59.143  7215  7215 E Zygote  : v2
,08-25 15:24:59.143  7215  7215 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 15:24:59.143  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 15:24:59.143  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 15:24:59.143  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-25 15:24:59.143  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 15:24:59.143  1379  1379 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-25 15:24:59.143  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-25 15:24:59.143  1019  1133 D Tethering: InitialState.processMessage what=4
08-25 15:24:59.143  1379  1379 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-25 15:24:59.143  1379  1379 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-25 15:24:59.143  1379  1379 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,08-25 15:24:59.143  1379  1379 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-25 15:24:59.153  1019  1491 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7215 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-25 15:24:59.143  7215  7215 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 15:24:59.143  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 15:24:59.143  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 15:24:59.143  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 15:24:59.143  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-25 15:24:59.153  7215  7215 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-25 15:24:59.153  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 15:24:59.153  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 15:24:59.153  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 15:24:59.153  1019  1133 E Tethering: No numeric data,
08-25 15:24:59.153  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 15:24:59.153  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 15:24:59.153  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-25 15:24:59.153  3215  3295 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-25 15:24:59.153  3215  3295 D BluetoothAdapterProperties: Setting state to 10
08-25 15:24:59.153  3215  3295 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 15:24:59.153  3215  3295 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 15:24:59.153  3215  3295 D BluetoothAdapterService: updateAdapterState state is 10
08-25 15:24:59.153  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 15:24:59.153  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 15:24:59.153  3215  3295 D BluetoothAdapterService: Autoconnection is available 
08-25 15:24:59.153  3215  3295 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-25 15:24:59.153  3215  3295 I BluetoothAdapterState: Entering OffState
08-25 15:24:59.153  6896  6908 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 15:24:59.153  6896  6908 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 15:24:59.153  6896  6908 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-25 15:24:59.153  6896  6908 D BluetoothLeAdvertiser: Exit stop advertising
08-25 15:24:59.153  6896  6908 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-25 15:24:59.153  6896  6908 D BluetoothLeScanner: Exiting stopAllScan
08-25 15:24:59.153  1019  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 15:24:59.153  1019  1133 D Tethering: clearTetheredNotification()
,08-25 15:24:59.153  1431  1457 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 15:24:59.153  1431  1457 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 15:24:59.163  4780  4788 D Bluetoothsap: onBluetoothStateChange: up=false
08-25 15:24:59.163  4780  4788 D Bluetoothsap: Unbinding service...
08-25 15:24:59.163  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 15:24:59.163  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 15:24:59.163  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:24:59.163  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
08-25 15:24:59.163  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 15:24:59.163  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 15:24:59.163  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 15:24:59.163  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 15:24:59.163  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 15:24:59.163  1182  1182 D HotspotTile: updateTetherState():false, false
08-25 15:24:59.163  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 15:24:59.163  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 15:24:59.163  4780  4797 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 15:24:59.163  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 15:24:59.163  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:24:59.163  1019  1127 V NetworkStats: performPollLocked() took 8ms
,08-25 15:24:59.173  1459  1861 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 15:24:59.173  1459  1861 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 15:24:59.173  4780  4788 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 15:24:59.173  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:24:59.173  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:24:59.173  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 15:24:59.173  1681  4271 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 15:24:59.173  1681  4271 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 15:24:59.173  1182  3293 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 15:24:59.173  1182  3293 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 15:24:59.173  4780  4797 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 15:24:59.173  4780  4797 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 15:24:59.173  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 15:24:59.173  1445  1460 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 15:24:59.173  1445  1460 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 15:24:59.173  1751  2292 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 15:24:59.173  1751  2292 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 15:24:59.173  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 15:24:59.173  7215  7215 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:24:59.173  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 15:24:59.173  4780  4788 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 15:24:59.173  7215  7215 D ActivityThread: Added TimaKeyStore provider
,08-25 15:24:59.173  3215  3381 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 15:24:59.173  3215  3381 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 15:24:59.183  3215  3230 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 15:24:59.183  4780  4788 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 15:24:59.183  1019  1049 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 15:24:59.183  1019  1049 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 15:24:59.183  1019  1049 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan,
,08-25 15:24:59.183  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:24:59.183  1019  1019 I InputMethodManagerService: [BT Setting State] State =10
08-25 15:24:59.183  1019  1019 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-25 15:24:59.193  1879  1879 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 15:24:59.193  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:24:59.193  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 15:24:59.193  1182  1182 D BluetoothTile:  getBluetoothState : 10
,08-25 15:24:59.203  4780  4780 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:24:59.203  1019  1031 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 15:24:59.203  1019  1081 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-25 15:24:59.203  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-25 15:24:59.203  6896  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:24:59.203  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:24:59.203  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:24:59.203  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:24:59.203  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:24:59.203  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:24:59.203  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:24:59.203  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:24:59.203  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:24:59.213  6896  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:24:59.213  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:24:59.213  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:24:59.213  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:24:59.213  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:24:59.213  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:24:59.213  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:24:59.213  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:24:59.213  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:24:59.213  6896  6896 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-25 15:24:59.243   288   288 E SMD     : DCD OFF
,08-25 15:24:59.293   257   532 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-25 15:24:59.293   257   532 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 15:24:59.293  7215  7244 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files,
,08-25 15:24:59.303   257   532 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-25 15:24:59.303   257   532 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 15:24:59.313  7215  7244 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-25 15:24:59.323  1379  1379 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 15:24:59.383  1379  1379 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-25 15:24:59.383  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 15:24:59.383  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-25 15:24:59.393  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 15:24:59.473  7215  7215 D StrictMode: StrictMode policy violation; ~duration=173 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-25 15:24:59.473  7215  7215 D StrictMode: StrictMode policy violation; ~duration=171 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 15:24:59.473  7215  7215 D StrictMode: StrictMode policy violation; ~duration=170 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 15:24:59.473  7215  7215 D StrictMode: StrictMode policy violation; ~duration=168 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.q.e.b(PG:170)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 15:24:59.473  7215  7215 D StrictMode: StrictMode policy violation; ~duration=164 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.q.k.d(PG:583)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.q.e.b(PG:170)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 15:24:59.473  7215  7215 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 15:24:59.473  7215  7215 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 15:24:59.473  1019  4325 I ActivityManager: Killing 6835:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
08-25 15:24:59.473  7215  7215 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:24:59.473  7215  7215 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 15:24:59.483  1019  1485 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 15:24:59.483  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-25 15:24:59.483  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:24:59.483  1019  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:24:59.483  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 15:24:59.483  1630  1630 I Hs20UtilService: Starting #8
08-25 15:24:59.483  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-25 15:24:59.493  1019  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-25 15:24:59.493  4780  4780 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-25 15:24:59.493  1630  1651 I Hs20UtilService: Message received 5007
08-25 15:24:59.493  4780  4780 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-25 15:24:59.493  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-25 15:24:59.493  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-25 15:24:59.493  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:24:59.493  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 15:24:59.493  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:59.503  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:59.503  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:59.503  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:24:59.503  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 15:24:59.503  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-25 15:24:59.503  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 15:24:59.503  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 15:24:59.503  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 15:24:59.503  1182  1182 D HotspotTile: onReceive : 1, 0
08-25 15:24:59.503  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 15:24:59.503  4780  4780 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 15:24:59.503  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:24:59.503  4780  4873 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-25 15:24:59.503  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:24:59.503  4780  4780 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-25 15:24:59.503  1751  2204 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 15:24:59.513  4780  4780 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-25 15:24:59.513  4780  4780 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-25 15:24:59.513  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-25 15:24:59.513  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 15:24:59.513  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 15:24:59.513  4780  4780 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 15:24:59.513  4780  4873 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-25 15:24:59.513  1019  1081 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-25 15:24:59.513  1019  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 15:24:59.523  1019  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:59.523  1019  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:59.523  1019  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:59.523  1019  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:59.533  7255  7255 E Zygote  : MountEmulatedStorage()
08-25 15:24:59.533  7255  7255 I libpersona: KNOX_SDCARD checking this for 10064
08-25 15:24:59.533  7255  7255 E Zygote  : v2
08-25 15:24:59.533  7255  7255 I libpersona: KNOX_SDCARD not a persona
08-25 15:24:59.533  7255  7255 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 15:24:59.533  7255  7255 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 15:24:59.533  1019  1081 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7255 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 15:24:59.533  7255  7255 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 15:24:59.543  1019  1019 I ApplicationPolicy: updateDataUsageMap
,08-25 15:24:59.553  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:24:59.553  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:24:59.563  7215  7253 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-25 15:24:59.563  7255  7255 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:24:59.563  7255  7255 D ActivityThread: Added TimaKeyStore provider
,08-25 15:24:59.583  1019  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 15:24:59.583  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:24:59.583  1019  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:24:59.583  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-25 15:24:59.583  7255  7255 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-25 15:24:59.593  1019  1044 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:24:59.603  7255  7255 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 15:24:59.603  7255  7255 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-25 15:24:59.633  7255  7255 D FileShare-Client: Outbound.stopDelayTimer - 
,08-25 15:24:59.633  1019  3774 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-25 15:24:59.633  1019  3774 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:59.633  1019  3774 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:59.633  1019  3774 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:59.643  1019  3774 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:59.653  1019  3774 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7273 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 15:24:59.653  1019  3774 I ActivityManager: Killing 6875:com.wsomacp/u0a23 (adj 15): empty #21
,08-25 15:24:59.653  7273  7273 E Zygote  : MountEmulatedStorage()
08-25 15:24:59.653  7273  7273 I libpersona: KNOX_SDCARD checking this for 10065
08-25 15:24:59.653  7273  7273 E Zygote  : v2
08-25 15:24:59.653  7273  7273 I libpersona: KNOX_SDCARD not a persona
08-25 15:24:59.653  7273  7273 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:24:59.653  7273  7273 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:24:59.663  7273  7273 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 15:24:59.673  7273  7273 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:24:59.673  7273  7273 D ActivityThread: Added TimaKeyStore provider
,08-25 15:24:59.693  7273  7273 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 15:24:59.703  1019  1052 I PowerManagerService: [PWL] Off : 50s ago
,08-25 15:24:59.703  1019  1052 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-25 15:24:59.703  1019  1052 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-25 15:24:59.703  1019  1052 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1019, ws=null) (elapsedTime=684)
,08-25 15:24:59.703  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:24:59.703  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:24:59.703  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
08-25 15:24:59.703  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-25 15:24:59.703  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:59.703  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:59.703  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:24:59.703  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:24:59.713  1019  1031 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7288 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-25 15:24:59.713  7288  7288 E Zygote  : MountEmulatedStorage()
08-25 15:24:59.713  7288  7288 I libpersona: KNOX_SDCARD checking this for 10102
08-25 15:24:59.713  7288  7288 E Zygote  : v2
,08-25 15:24:59.713  7288  7288 I libpersona: KNOX_SDCARD not a persona
08-25 15:24:59.723  7288  7288 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 15:24:59.723  1019  1031 I ActivityManager: Killing 6928:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-25 15:24:59.723  7288  7288 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:24:59.723  7288  7288 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 15:24:59.733  7288  7288 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:24:59.733  7288  7288 D ActivityThread: Added TimaKeyStore provider
,08-25 15:24:59.753  7288  7288 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-25 15:24:59.813  1019  1099 V AlarmManager: waitForAlarm result :4
,08-25 15:24:59.873  1019  3351 D SSRM:n  : SIOP:: AP = 370
,08-25 15:24:59.963  7288  7309 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-25 15:24:59.963  7288  7309 I Babel_SMS: MmsConfig.loadMmsSettings
,08-25 15:24:59.973  7288  7309 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-25 15:24:59.973  7288  7309 I Babel_SMS: MmsConfig.loadFromDatabase
,08-25 15:24:59.983  1019  1099 V AlarmManager: waitForAlarm result :8
,08-25 15:24:59.993  7288  7309 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-25 15:24:59.993  7288  7309 I Babel_SMS: MmsConfig.loadFromResources
,08-25 15:24:59.993  7288  7309 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-25 15:24:59.993  7288  7309 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-25 15:25:00.033  1019  1031 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-25 15:25:00.033  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-25 15:25:00.033  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:00.033  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:00.033  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-25 15:25:00.053  7288  7288 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 15:25:00.063  7288  7288 I Babel_Crash: startup - clean
,08-25 15:25:00.093  1019  4324 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 15:25:00.093  1019  4324 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 15:25:00.093  1019  4324 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:00.093  1019  4324 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:00.093  1019  4324 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 15:25:00.093  1630  1630 I Hs20UtilService: Starting #9
,08-25 15:25:00.093  4780  4780 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-25 15:25:00.093  4780  4780 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 15:25:00.093  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 15:25:00.093  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 15:25:00.093  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 15:25:00.093  4780  4780 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 15:25:00.093  4780  4873 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 15:25:00.103  7288  7288 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 15:25:00.103  1630  1651 I Hs20UtilService: Message received 5007,
,08-25 15:25:00.103  7288  7288 W AudioCapabilities: Unsupported mime audio/evrc
,08-25 15:25:00.103  7288  7288 W AudioCapabilities: Unsupported mime audio/qcelp
,08-25 15:25:00.113  1019  4325 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 15:25:00.113  1019  4325 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 15:25:00.113  1019  4325 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:00.113  1019  4325 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 15:25:00.113  1019  4325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 15:25:00.113  1019  1047 D Tethering: interfaceRemoved wlan0
08-25 15:25:00.113  1019  1047 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-25 15:25:00.113  1630  1630 I Hs20UtilService: Starting #10
,08-25 15:25:00.113  7111  7111 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 15:25:00.113  7111  7111 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 15:25:00.113  7111  7111 D SecurityLogAgent: StateMachine : Current State = 1
,08-25 15:25:00.123  1630  1651 I Hs20UtilService: Message received 5011
,08-25 15:25:00.123  7111  7111 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 15:25:00.123  7288  7288 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-25 15:25:00.123  7288  7288 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-25 15:25:00.133  1019  4324 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:00.133  1019  4324 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:00.133  1019  4324 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 15:25:00.133  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:00.133  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:00.133  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
08-25 15:25:00.133  7288  7288 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-25 15:25:00.133  7288  7288 W AudioCapabilities: Unsupported mime audio/x-ima
,08-25 15:25:00.133  7288  7288 W AudioCapabilities: Unsupported mime audio/qcelp
,08-25 15:25:00.133  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:00.133  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-25 15:25:00.133  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
08-25 15:25:00.133  7288  7288 W AudioCapabilities: Unsupported mime audio/evrc,
,08-25 15:25:00.143  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:00.143  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:00.143  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
08-25 15:25:00.143  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:00.143  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:00.143  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
08-25 15:25:00.143  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:00.143  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:00.143  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 15:25:00.153  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:00.153  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:00.153  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 15:25:00.153  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:00.153  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:00.153  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 15:25:00.153  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:00.153  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:00.153  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 15:25:00.163  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:00.163  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:00.163  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 15:25:00.163  7288  7288 W VideoCapabilities: Unsupported mime video/wvc1
,08-25 15:25:00.163  7288  7288 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-25 15:25:00.163  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:00.163  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:00.163  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 15:25:00.163  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:00.163  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:00.163  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 15:25:00.173  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:00.173  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:00.173  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 15:25:00.173  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:00.173  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:00.173  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 15:25:00.183  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:00.183  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:00.183  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 15:25:00.183  7288  7288 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-25 15:25:00.183  7288  7288 W VideoCapabilities: Unsupported mime video/wvc1
08-25 15:25:00.183  4780  4780 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 15:25:00.193  1019  1031 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-25 15:25:00.193  7288  7288 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-25 15:25:00.193  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0,
08-25 15:25:00.193  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:00.193  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:00.193  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 15:25:00.193  7288  7288 W VideoCapabilities: Unsupported mime video/x-ms-wmv7,
,08-25 15:25:00.193  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 15:25:00.193  7288  7288 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-25 15:25:00.203  7288  7288 W VideoCapabilities: Unsupported mime video/mp43
,08-25 15:25:00.203  4780  4780 D DockEventReceiver: finishStartingService: stopping service
,08-25 15:25:00.203  4780  4780 D BluetoothNotiBroadcastReceiver: onReceive
08-25 15:25:00.203  7288  7288 W VideoCapabilities: Unsupported mime video/sorenson
,08-25 15:25:00.203  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:25:00.203  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-25 15:25:00.213  7288  7288 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-25 15:25:00.223  1019  3856 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 15:25:00.223  1019  3856 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-25 15:25:00.223   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 15:25:00.223  1019  3856 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:00.223  1019  1047 D Tethering: interfaceRemoved p2p0
08-25 15:25:00.223  1019  1047 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-25 15:25:00.223  1019  3856 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:00.223  1019  3856 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 15:25:00.223  1630  1630 I Hs20UtilService: Starting #11
,08-25 15:25:00.223  1630  1651 I Hs20UtilService: Message received 5011
,08-25 15:25:00.233  7111  7111 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 15:25:00.233  7111  7111 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 15:25:00.233  7111  7111 D SecurityLogAgent: StateMachine : Current State = 1
08-25 15:25:00.233  7111  7111 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 15:25:00.233  1019  1487 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
08-25 15:25:00.233  7288  7288 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-25 15:25:00.243  1019  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:00.243  1019  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:00.243  1019  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:00.243  1019  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:00.253  7314  7314 E Zygote  : MountEmulatedStorage()
,08-25 15:25:00.253  7314  7314 E Zygote  : v2
08-25 15:25:00.253  7314  7314 I libpersona: KNOX_SDCARD checking this for 1000
08-25 15:25:00.253  7314  7314 I libpersona: KNOX_SDCARD not a persona
,08-25 15:25:00.253  7314  7314 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:25:00.253  1019  1487 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7314 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-25 15:25:00.253  7314  7314 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:25:00.253  7314  7314 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 15:25:00.273  7288  7288 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-25 15:25:00.273  7288  7288 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 15:25:00.283  7288  7288 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 15:25:00.283  7288  7288 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,08-25 15:25:00.283  1019  1492 I ActivityManager: Killing 6945:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-25 15:25:00.293  7314  7314 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 15:25:00.293  7288  7288 I vclib   : onServiceConnected
,08-25 15:25:00.293  7314  7314 D ActivityThread: Added TimaKeyStore provider
,08-25 15:25:00.323  7314  7314 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true,
08-25 15:25:00.323  7314  7314 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-25 15:25:00.323  7314  7314 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-25 15:25:00.333  7314  7314 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-25 15:25:00.333  7314  7314 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-25 15:25:00.333  7314  7314 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-25 15:25:00.333  7314  7314 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:25:00.343  1019  3856 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-25 15:25:00.343  1019  3856 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-25 15:25:00.343  1019  3856 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-25 15:25:00.343  1019  3856 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-25 15:25:00.343  7314  7329 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-25 15:25:00.343  1019  3856 I ActivityManager: Killing 1907:com.google.android.gms/u0a11 (adj 15): empty #21
,08-25 15:25:00.353  1019  1019 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-25 15:25:00.353  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:00.353  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:00.353  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:00.353  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:00.363  7331  7331 E Zygote  : MountEmulatedStorage(),
08-25 15:25:00.363  7331  7331 E Zygote  : v2
08-25 15:25:00.363  7331  7331 I libpersona: KNOX_SDCARD checking this for 10001,
08-25 15:25:00.363  7331  7331 I libpersona: KNOX_SDCARD not a persona
08-25 15:25:00.363  7331  7331 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:25:00.363  7331  7331 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:25:00.373  1019  1019 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7331 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 15:25:00.373  7331  7331 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 15:25:00.393  7331  7331 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:25:00.403  7331  7331 D ActivityThread: Added TimaKeyStore provider
,08-25 15:25:00.483  1019  1081 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-25 15:25:00.483  1019  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:00.483  1019  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:00.483  1019  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:00.483  1019  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:00.493  1019  1081 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7348 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-25 15:25:00.493  7348  7348 E Zygote  : MountEmulatedStorage()
08-25 15:25:00.493  7348  7348 E Zygote  : v2
08-25 15:25:00.493  7348  7348 I libpersona: KNOX_SDCARD checking this for 1000
08-25 15:25:00.493  7348  7348 I libpersona: KNOX_SDCARD not a persona
,08-25 15:25:00.493  7348  7348 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:25:00.503  1019  1081 I ActivityManager: Killing 6977:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-25 15:25:00.503  7348  7348 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:25:00.503  7348  7348 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 15:25:00.513  7348  7348 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:25:00.523  7348  7348 D ActivityThread: Added TimaKeyStore provider
,08-25 15:25:00.553  7348  7348 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-25 15:25:00.683  7348  7348 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-25 15:25:00.683  7348  7348 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-25 15:25:00.693  7348  7348 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:25:00.693  7348  7348 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-25 15:25:00.693  7348  7348 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-25 15:25:00.693  7348  7348 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything,
08-25 15:25:00.693  1019  1485 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-25 15:25:00.693  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:00.693  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:00.693  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:00.693  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:00.713  7363  7363 E Zygote  : MountEmulatedStorage()
,08-25 15:25:00.713  7363  7363 I libpersona: KNOX_SDCARD checking this for 10008
08-25 15:25:00.713  7363  7363 E Zygote  : v2
08-25 15:25:00.713  7363  7363 I libpersona: KNOX_SDCARD not a persona
08-25 15:25:00.713  1019  1485 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7363 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 15:25:00.713  7363  7363 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:25:00.713  1019  1485 I ActivityManager: Killing 6598:com.android.mms/u0a41 (adj 15): empty #21
,08-25 15:25:00.713  7363  7363 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 15:25:00.713  7363  7363 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-25 15:25:00.733  7363  7363 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:25:00.733  7363  7363 D ActivityThread: Added TimaKeyStore provider,
,08-25 15:25:00.763  1019  1368 D CountryDetector: No listener is left
,08-25 15:25:00.793  1019  1487 D ActivityManager: startProcessLocked calleePkgName: com.google.android.gms, hostingType: broadcast
,08-25 15:25:00.793  1019  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:00.793  1019  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:00.793  1019  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:00.793  1019  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:00.813  1019  1487 I ActivityManager: Start proc com.google.android.gms for broadcast com.google.android.gms/.gcm.gmsproc.GmsAutoStarter: pid=7378 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,08-25 15:25:00.813  1019  1487 I ActivityManager: Killing 7011:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21,
,08-25 15:25:00.813  7378  7378 E Zygote  : MountEmulatedStorage()
08-25 15:25:00.813  7378  7378 E Zygote  : v2
08-25 15:25:00.813  7378  7378 I libpersona: KNOX_SDCARD checking this for 10011
08-25 15:25:00.813  7378  7378 I libpersona: KNOX_SDCARD not a persona
,08-25 15:25:00.813  7378  7378 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:25:00.823  7378  7378 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 15:25:00.823  7378  7378 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 15:25:00.843  7378  7378 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:25:00.843  7378  7378 D ActivityThread: Added TimaKeyStore provider
,08-25 15:25:00.873  7378  7378 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-25 15:25:00.873  7378  7378 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-25 15:25:00.903  7378  7378 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-25 15:25:00.913  7378  7378 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-25 15:25:00.913  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-25 15:25:00.923  7378  7378 I MultiDex: VM with version 2.1.0 has multidex support
,08-25 15:25:00.923  7378  7378 I MultiDex: install
,08-25 15:25:00.923  7378  7378 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-25 15:25:01.033  7378  7378 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-25 15:25:01.083  7378  7378 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-25 15:25:01.083  7378  7378 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1fe688a6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-25 15:25:01.083  7378  7378 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-25 15:25:01.093  1019  1485 I ActivityManager: Killing 6260:com.samsung.android.sm/1000 (adj 15): empty #21
,08-25 15:25:01.093  1019  1492 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-25 15:25:01.093  1019  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-25 15:25:01.093  1019  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:01.093  1019  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:01.093  1019  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-25 15:25:01.133  7378  7396 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,08-25 15:25:01.143  7378  7400 I iu.SyncManager: SYNC; picasa accounts
,08-25 15:25:01.183  7378  7378 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-25 15:25:01.203  1019  1490 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 15:25:01.203  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-25 15:25:01.203  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:01.203  1019  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:01.203  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:01.223   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 15:25:01.233  7378  7378 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 15:25:01.253  7378  7378 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-25 15:25:01.263  2816  2816 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Aug 25 15:25:01 GMT+02:00 2016
,08-25 15:25:01.263  1019  4325 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-25 15:25:01.263  1019  4325 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-25 15:25:01.263  1019  4325 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:01.263  1019  4325 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:01.263  1019  4325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-25 15:25:01.273  2816  2816 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-25 15:25:01.273  1019  1308 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-25 15:25:01.273  1019  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:01.273  1019  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:01.273  1019  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:01.273  1019  1308 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:01.273  2816  2816 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-25 15:25:01.283  2816  2816 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-25 15:25:01.283  2816  2816 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-25 15:25:01.283  2816  7404 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-25 15:25:01.283  2816  7404 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-25 15:25:01.283  2816  7404 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
08-25 15:25:01.293  7405  7405 E Zygote  : MountEmulatedStorage()
08-25 15:25:01.293  7405  7405 E Zygote  : v2
08-25 15:25:01.293  7405  7405 I libpersona: KNOX_SDCARD checking this for 10031
08-25 15:25:01.293  7405  7405 I libpersona: KNOX_SDCARD not a persona
08-25 15:25:01.293  7405  7405 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 15:25:01.293  7405  7405 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:25:01.293  1019  1308 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7405 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
08-25 15:25:01.293  2816  7404 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END,
,08-25 15:25:01.293  7405  7405 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 15:25:01.303  2816  2816 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-25 15:25:01.313  7405  7405 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:25:01.313  7405  7405 D ActivityThread: Added TimaKeyStore provider
,08-25 15:25:01.343  7405  7405 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-25 15:25:01.343  1019  4325 I ActivityManager: Killing 7028:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-25 15:25:01.363  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-25 15:25:01.363  2752  7420 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
08-25 15:25:01.363  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:01.363  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:01.363  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:01.363  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:01.363  2752  7420 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-25 15:25:01.363  2752  7420 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-25 15:25:01.363  2752  7420 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-25 15:25:01.373  2752  7420 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-25 15:25:01.373  7421  7421 E Zygote  : MountEmulatedStorage()
08-25 15:25:01.373  7421  7421 E Zygote  : v2
,08-25 15:25:01.373  7421  7421 I libpersona: KNOX_SDCARD checking this for 10032
08-25 15:25:01.373  7421  7421 I libpersona: KNOX_SDCARD not a persona
,08-25 15:25:01.373  1019  1031 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7421 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 15:25:01.373  7421  7421 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:25:01.383  7421  7421 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 15:25:01.383  7421  7421 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-25 15:25:01.393   304   304 I art     : Explicit concurrent mark sweep GC freed 8710(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 573us total 23.325ms
,08-25 15:25:01.423   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 573us total 16.245ms
,08-25 15:25:01.423  7421  7421 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 15:25:01.423  7421  7421 D ActivityThread: Added TimaKeyStore provider
,08-25 15:25:01.433   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 16.333ms
,08-25 15:25:01.473  7421  7436 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-25 15:25:01.473  7421  7436 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-25 15:25:01.473  7421  7421 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-25 15:25:01.473  1019  1491 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-25 15:25:01.473  1019  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:01.473  1019  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:01.473  1019  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:01.473  1019  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:01.483  7421  7436 D SPPClientService: PushLog.txt file is not deleted.
08-25 15:25:01.483  7421  7436 D SPPClientService: PushLog.txt file is not deleted.
08-25 15:25:01.483  7421  7436 D SPPClientService: ============PushLog. stop!
,08-25 15:25:01.493  7438  7438 E Zygote  : MountEmulatedStorage(),
,08-25 15:25:01.493  7438  7438 E Zygote  : v2
08-25 15:25:01.493  7438  7438 I libpersona: KNOX_SDCARD checking this for 10036
08-25 15:25:01.493  7438  7438 I libpersona: KNOX_SDCARD not a persona
,08-25 15:25:01.493  7438  7438 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:25:01.493  7438  7438 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-25 15:25:01.493  1019  1491 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7438 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 15:25:01.493  1019  1491 I ActivityManager: Killing 7048:com.sec.esdk.elm/u0a90 (adj 15): empty #21
08-25 15:25:01.503  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:01.503  1019  1490 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-25 15:25:01.503  1019  1490 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-25 15:25:01.503  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
08-25 15:25:01.503  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-25 15:25:01.503  7438  7438 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-25 15:25:01.523  7438  7438 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:25:01.523  7438  7438 D ActivityThread: Added TimaKeyStore provider
,08-25 15:25:01.533  7421  7444 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-25 15:25:01.563  7438  7438 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@30b9ab12
,08-25 15:25:01.573  7438  7438 I SA      : [SSP] onCreated
,08-25 15:25:01.583  7438  7438 I SA      : [TPM] There is no property file
,08-25 15:25:01.583  7438  7438 I SA      : [SCU] isHaveSA() - false
,08-25 15:25:01.583  7438  7438 I SA      : [TPM] getModelProperty : null
,08-25 15:25:01.583  7438  7438 I SA      : [TPM] getCSCProperty : null
,08-25 15:25:01.583  7438  7438 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-25 15:25:01.583  7438  7438 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-25 15:25:01.583  7438  7438 I SA      : [DM] TFT FEATURE: false
,08-25 15:25:01.593  7438  7438 I SA      : [DM] init START
,08-25 15:25:01.593  7438  7438 I SA      : [DM] This device is not a Vodafone
,08-25 15:25:01.593  7438  7438 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-25 15:25:01.593  7438  7438 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-25 15:25:01.603  7438  7438 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-25 15:25:01.603  7438  7438 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-25 15:25:01.603  7438  7438 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-25 15:25:01.603  7438  7438 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-25 15:25:01.603  7438  7438 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-25 15:25:01.603  7438  7438 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-25 15:25:01.603  7438  7438 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-25 15:25:01.603  7438  7438 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-25 15:25:01.603  7438  7438 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-25 15:25:01.603  7438  7438 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-25 15:25:01.603  7438  7438 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-25 15:25:01.613  7438  7438 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-25 15:25:01.613  7438  7438 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-25 15:25:01.613  7438  7438 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-25 15:25:01.613  7438  7438 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-25 15:25:01.613  7438  7438 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-25 15:25:01.613  7438  7438 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-25 15:25:01.613  7438  7438 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-25 15:25:01.613  7438  7438 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-25 15:25:01.613  7438  7438 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-25 15:25:01.613  7438  7438 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-25 15:25:01.613  7438  7438 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-25 15:25:01.613  7438  7438 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-25 15:25:01.613  7438  7438 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-25 15:25:01.613  7438  7438 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-25 15:25:01.613  7438  7438 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-25 15:25:01.623  7438  7438 I SA      : [SCU] isHaveSA() - false
08-25 15:25:01.623  7438  7438 I SA      : support phone number id : false
08-25 15:25:01.623  7438  7438 I SA      : [DM] Supports Ref Jpn : true
,08-25 15:25:01.623  7438  7438 I SA      : [DM] init END
08-25 15:25:01.623  7438  7438 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-25 15:25:01.623  7438  7438 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-25 15:25:01.623  7438  7438 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-25 15:25:01.623  7438  7438 I SA      : [SLFUCHKMGR] constructor called,
,08-25 15:25:01.633  7438  7438 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-25 15:25:01.633  7438  7438 I SA      : [OR] == isSIMCardReady false ==
,08-25 15:25:01.643  7438  7438 I SA      : [SCU] == networkStateCheck == false
08-25 15:25:01.643  7438  7438 I SA      : [OR] onReceive END
,08-25 15:25:01.643  1019  4325 I ActivityManager: Killing 7134:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-25 15:25:01.643  1232  1232 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:25:01.653  1789  1789 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-25 15:25:01.673  2681  2690 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,08-25 15:25:01.673  1789  1789 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-25 15:25:01.673  1789  1789 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-25 15:25:01.673  1789  1789 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-25 15:25:01.673  1789  1789 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-25 15:25:01.673  1789  1789 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-25 15:25:01.683  1789  1789 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-25 15:25:01.683  1019  4325 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-25 15:25:01.683  1019  4325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:01.683  1019  4325 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:01.683  1019  4325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:01.683  1019  4325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:01.693  7460  7460 E Zygote  : MountEmulatedStorage(),
08-25 15:25:01.693  7460  7460 E Zygote  : v2
08-25 15:25:01.693  7460  7460 I libpersona: KNOX_SDCARD checking this for 10077
08-25 15:25:01.693  7460  7460 I libpersona: KNOX_SDCARD not a persona
,08-25 15:25:01.693  7460  7460 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-25 15:25:01.693  1019  4325 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7460 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-25 15:25:01.703  7460  7460 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:25:01.703  7460  7460 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-25 15:25:01.713  7460  7460 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:25:01.713  7460  7460 D ActivityThread: Added TimaKeyStore provider
,08-25 15:25:01.843  1019  1308 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-25 15:25:01.843  1019  1308 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 15:25:01.843  1019  1308 D SecContentProvider2: mCursor = null
,08-25 15:25:01.843  1019  1308 D WifiService: setWifiEnabled: true pid=6896, uid=10170
,08-25 15:25:01.843  1019  1308 W ActivityManager: Permission Denial: getCurrentUser() from pid=6896, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-25 15:25:01.843  1019  1308 W WifiService: Failed getting userId using ActivityManagerNative
08-25 15:25:01.843  1019  1308 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6896, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-25 15:25:01.843  1019  1308 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 15:25:01.843  1019  1308 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-25 15:25:01.843  1019  1308 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-25 15:25:01.843  1019  1308 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-25 15:25:01.843  1019  1308 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-25 15:25:01.843  1019  1308 D SettingsProvider: name = wifi_on
,08-25 15:25:01.863  1019  1130 E WifiHW  : ##################### set firmware type 0 #####################
,08-25 15:25:01.883  1019  3856 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-25 15:25:01.883  1019  3856 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-25 15:25:01.883  1019  3856 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:01.883  1019  3856 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:01.883  1019  3856 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-25 15:25:01.893  1019  4325 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-25 15:25:01.893  1019  4325 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:01.893  1019  4325 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:01.893  1019  4325 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:01.893  1019  4325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:01.903  1019  4325 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7479 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 15:25:01.903  1019  1487 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-25 15:25:01.903  1019  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-25 15:25:01.903  1019  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:01.903  1019  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:01.903  1019  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-25 15:25:01.913  7479  7479 E Zygote  : MountEmulatedStorage()
08-25 15:25:01.913  7479  7479 E Zygote  : v2
08-25 15:25:01.913  7479  7479 I libpersona: KNOX_SDCARD checking this for 10110
08-25 15:25:01.913  7479  7479 I libpersona: KNOX_SDCARD not a persona
,08-25 15:25:01.913  7479  7479 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:25:01.913  7288  7478 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-25 15:25:01.913  7479  7479 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:25:01.913  7479  7479 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 15:25:01.923  1019  1491 I ActivityManager: Killing 7102:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-25 15:25:01.933  7479  7479 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:25:01.933  7479  7479 D ActivityThread: Added TimaKeyStore provider
,08-25 15:25:02.033  1019  1492 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-25 15:25:02.143   257   532 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-25 15:25:02.143   257   532 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 15:25:02.143  7479  7503 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-25 15:25:02.143   257   532 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-25 15:25:02.143   257   532 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 15:25:02.143  7479  7503 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-25 15:25:02.153   257   532 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-25 15:25:02.153   257   532 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 15:25:02.153  7479  7504 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-25 15:25:02.153   257   532 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-25 15:25:02.153   257   532 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 15:25:02.153  7479  7504 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-25 15:25:02.213  7479  7479 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-25 15:25:02.213  7479  7479 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-25 15:25:02.213  7479  7479 I GAv4    :   adb logcat -s GAv4
,08-25 15:25:02.213  1019  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-25 15:25:02.213  1019  1490 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4258, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-25 15:25:02.213  1019  1490 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-25 15:25:02.213  1019  1490 D BatteryService: stay LED for charging
08-25 15:25:02.213  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-25 15:25:02.213  1019  1019 I MotionRecognitionService: Plugged
,08-25 15:25:02.213  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,08-25 15:25:02.223  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-25 15:25:02.223  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-25 15:25:02.223  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-25 15:25:02.223  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-25 15:25:02.223   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 15:25:02.243   288   288 E SMD     : DCD OFF
,08-25 15:25:02.243  7479  7479 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
08-25 15:25:02.243  1019  1491 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-25 15:25:02.253  1182  1182 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
08-25 15:25:02.253  1182  1182 D SViewCoverView: level :100 plugged : 2
08-25 15:25:02.253  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-25 15:25:02.253  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
08-25 15:25:02.253  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-25 15:25:02.253  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,08-25 15:25:02.253  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-25 15:25:02.263  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 15:25:02.263  7479  7479 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
08-25 15:25:02.263  1019  1047 D Tethering: interfaceAdded wlan0
,08-25 15:25:02.263  1019  1047 D Tethering: interfaceAdded p2p0
,08-25 15:25:02.263  1019  1133 E Tethering: No numeric data
,08-25 15:25:02.273   278  1008 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
08-25 15:25:02.273   278  1008 D SoftapController: Softap fwReload - Ok
,08-25 15:25:02.273  7479  7506 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-25 15:25:02.273  1019  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 15:25:02.273  1019  1133 D Tethering: clearTetheredNotification()
08-25 15:25:02.273  1019  1047 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-25 15:25:02.273  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 15:25:02.273  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
08-25 15:25:02.283  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 15:25:02.283   278  1008 D CommandListener: Setting iface cfg,
,08-25 15:25:02.283   278  1008 D CommandListener: Trying to bring down wlan0
08-25 15:25:02.283  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 15:25:02.283   278  1008 D CommandListener: Clearing all IP addresses on wlan0
08-25 15:25:02.283  1182  1182 D HotspotTile: updateTetherState():false, false
08-25 15:25:02.283  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit,
08-25 15:25:02.283  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
08-25 15:25:02.283  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 15:25:02.283  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 15:25:02.283  1019  1130 E WifiHW  : supplicant_name : p2p_supplicant,
08-25 15:25:02.283  1019  1127 V NetworkStats: performPollLocked() took 6ms
08-25 15:25:02.283  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:25:02.293  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:02.293  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:25:02.293  1019  1130 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-25 15:25:02.293  1019  1130 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-25 15:25:02.303  4780  4780 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 15:25:02.303  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-25 15:25:02.303  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 15:25:02.303  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:25:02.303  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 15:25:02.303  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 15:25:02.303  1182  1182 D HotspotTile: onReceive : 2, 0
08-25 15:25:02.303  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:02.303  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:02.303  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:02.303  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:02.303  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 15:25:02.303  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-25 15:25:02.313  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:02.313  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:02.363  7509  7509 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-25 15:25:02.363  7509  7509 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-25 15:25:02.363  7509  7509 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-25 15:25:02.383  7509  7509 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-25 15:25:02.383   362   362 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7509
08-25 15:25:02.383   362   362 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,08-25 15:25:02.383  7509  7509 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-25 15:25:02.383  7509  7509 I wpa_supplicant: ssSupport state is = 1
08-25 15:25:02.383  7509  7509 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,08-25 15:25:02.383  7509  7509 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-25 15:25:02.393   362   362 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7509
08-25 15:25:02.393   362   362 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-25 15:25:02.543  1019  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 15:25:02.553  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:02.553  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:02.553  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-25 15:25:02.583   362   362 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-25 15:25:02.583  7509  7509 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-25 15:25:02.593  7479  7479 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-25 15:25:02.603  7479  7479 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6373-6375)
08-25 15:25:02.603  7479  7479 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-25 15:25:02.613  7479  7479 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {25e71a15}
08-25 15:25:02.613  7479  7479 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-25 15:25:02.613  7479  7479 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 15:25:02.633  7479  7479 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-25 15:25:02.633  7479  7479 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 15:25:02.633  7479  7479 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-25 15:25:02.643  7509  7509 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-25 15:25:02.643  7509  7509 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-25 15:25:02.653  7479  7479 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-25 15:25:02.653  7479  7479 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 15:25:02.653  7479  7479 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 15:25:02.653  7479  7479 I Adreno-EGL: Local Branch: 
08-25 15:25:02.653  7479  7479 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 15:25:02.653  7479  7479 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 15:25:02.653  7479  7479 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-25 15:25:02.653  7509  7509 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-25 15:25:02.653   362   362 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7509
08-25 15:25:02.653   362   362 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-25 15:25:02.653  7509  7509 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
,08-25 15:25:02.653  7509  7509 I wpa_supplicant: ssSupport state is = 1
08-25 15:25:02.653  7509  7509 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-25 15:25:02.653  7509  7509 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 15:25:02.653  7509  7509 E wpa_supplicant: SIM READ ERROR
08-25 15:25:02.653  7509  7509 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 15:25:02.653  7509  7509 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 15:25:02.653  7509  7509 E wpa_supplicant: SIM READ ERROR,
08-25 15:25:02.653  7509  7509 I wpa_supplicant: Blacklist: Clear (all) 
08-25 15:25:02.653  7509  7509 I wpa_supplicant: wpa_default_ap_write_once
08-25 15:25:02.653  7509  7509 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-25 15:25:02.653  7509  7509 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-25 15:25:02.653  7509  7509 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-25 15:25:02.653  7509  7509 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 15:25:02.653  7509  7509 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-25 15:25:02.663  7509  7509 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-25 15:25:02.663  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
08-25 15:25:02.663  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 15:25:02.663  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-25 15:25:02.663  1019  1133 D Tethering: InitialState.processMessage what=4
08-25 15:25:02.663  1019  1133 E Tethering: No numeric data
08-25 15:25:02.663  1019  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 15:25:02.663  1019  1133 D Tethering: clearTetheredNotification()
08-25 15:25:02.673  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:02.673  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
08-25 15:25:02.673  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 15:25:02.673  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 15:25:02.673  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 15:25:02.673  1182  1182 D HotspotTile: updateTetherState():false, false
,08-25 15:25:02.673  1019  1127 V NetworkStats: performPollLocked() took 3ms
08-25 15:25:02.673  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:25:02.673  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:25:02.673  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:25:02.723  7509  7509 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-25 15:25:02.723  7479  7479 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 15:25:02.733  7479  7539 W cr.media: Requires BLUETOOTH permission
,08-25 15:25:02.743  7479  7479 I NSApplication: Starting up...
,08-25 15:25:02.743  1019  1031 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output,
,08-25 15:25:02.753  1019  4326 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-25 15:25:02.753  1019  1485 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-25 15:25:02.753  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:02.753  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:02.753  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:02.753  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:02.773  7544  7544 E Zygote  : MountEmulatedStorage(),
08-25 15:25:02.773  7544  7544 E Zygote  : v2
08-25 15:25:02.773  7544  7544 I libpersona: KNOX_SDCARD checking this for 10117
08-25 15:25:02.773  7544  7544 I libpersona: KNOX_SDCARD not a persona
,08-25 15:25:02.773  7544  7544 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:25:02.773  7544  7544 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 15:25:02.773  1019  1485 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7544 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-25 15:25:02.773  7544  7544 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-25 15:25:02.773  1019  1485 I ActivityManager: Killing 7153:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-25 15:25:02.803  7544  7544 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:25:02.803  7544  7544 D ActivityThread: Added TimaKeyStore provider
,08-25 15:25:02.823  7544  7544 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 15:25:02.903  7509  7509 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-25 15:25:02.903  7509  7509 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-25 15:25:02.923  7509  7509 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-25 15:25:02.923   362   362 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7509
08-25 15:25:02.923   362   362 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-25 15:25:02.923  7509  7509 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-25 15:25:02.923  7509  7509 I wpa_supplicant: ssSupport state is = 1
,08-25 15:25:02.923  7509  7509 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-25 15:25:02.923  7509  7509 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-25 15:25:02.933  7509  7509 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-25 15:25:02.933   362   362 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7509
08-25 15:25:02.933   362   362 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-25 15:25:02.933  7509  7509 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-25 15:25:02.933  7509  7509 I wpa_supplicant: ssSupport state is = 1
08-25 15:25:02.933  7509  7509 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 15:25:02.933  7509  7509 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 15:25:02.933  7509  7509 E wpa_supplicant: SIM READ ERROR
08-25 15:25:02.933  7509  7509 I wpa_supplicant: wpa_default_ap_write_once,
08-25 15:25:02.933  7509  7509 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-25 15:25:02.933  7509  7509 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 15:25:02.933  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 15:25:02.933  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 15:25:02.933  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-25 15:25:02.943  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 15:25:02.943  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-25 15:25:02.943  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 15:25:02.983  7509  7509 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-25 15:25:02.983  7509  7509 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-25 15:25:03.083  7509  7509 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-25 15:25:03.083  7509  7509 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-25 15:25:03.083  7509  7509 I wpa_supplicant: Skip scan - bUseNetwork false
,08-25 15:25:03.173  1019  1492 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-25 15:25:03.173  1019  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:03.173  1019  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:03.173  1019  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:03.173  1019  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:03.193  7568  7568 E Zygote  : MountEmulatedStorage(),
08-25 15:25:03.193  7568  7568 E Zygote  : v2
08-25 15:25:03.193  7568  7568 I libpersona: KNOX_SDCARD checking this for 10121
,08-25 15:25:03.193  7568  7568 I libpersona: KNOX_SDCARD not a persona
,08-25 15:25:03.193  7568  7568 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:25:03.193  1019  1492 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7568 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,08-25 15:25:03.193  1019  1492 I ActivityManager: Killing 7064:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
08-25 15:25:03.193  7568  7568 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:25:03.203  7568  7568 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 15:25:03.223  7568  7568 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:25:03.223  7568  7568 D ActivityThread: Added TimaKeyStore provider
,08-25 15:25:03.223   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 15:25:03.233  7568  7568 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 15:25:03.233  7568  7568 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-25 15:25:03.233  7568  7568 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 15:25:03.253  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 15:25:03.253  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-25 15:25:03.253  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 15:25:03.253  7568  7568 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:25:03.253  7568  7568 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-25 15:25:03.253  7568  7568 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-25 15:25:03.263  1019  1368 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-25 15:25:03.263  1019  1368 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:03.263  1019  1368 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:03.263  1019  1368 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:03.263  1019  1368 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:03.273  1019  1368 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7585 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-25 15:25:03.273  1019  1368 I ActivityManager: Killing 7081:com.android.calendar/u0a131 (adj 15): empty #21
08-25 15:25:03.273  7585  7585 E Zygote  : MountEmulatedStorage()
08-25 15:25:03.273  7585  7585 E Zygote  : v2
08-25 15:25:03.273  7585  7585 I libpersona: KNOX_SDCARD checking this for 10141
08-25 15:25:03.273  7585  7585 I libpersona: KNOX_SDCARD not a persona
,08-25 15:25:03.273  7585  7585 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:25:03.283  7585  7585 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:25:03.283  7585  7585 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 15:25:03.293  7585  7585 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:25:03.293  7585  7585 D ActivityThread: Added TimaKeyStore provider
,08-25 15:25:03.303  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-25 15:25:03.303  1019  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-25 15:25:03.303  7509  7509 I wpa_supplicant: HOTSPOT20_ENABLE called
08-25 15:25:03.303  7509  7509 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 15:25:03.303  7509  7509 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 15:25:03.303  7509  7509 E wpa_supplicant: SIM READ ERROR
08-25 15:25:03.303  7509  7509 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 15:25:03.333  7509  7509 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-25 15:25:03.333  7585  7585 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-25 15:25:03.333  7585  7585 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 15:25:03.333  7585  7585 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-25 15:25:03.333  7585  7585 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-25 15:25:03.343  7509  7509 I wpa_supplicant: Skip scan - bUseNetwork false
,08-25 15:25:03.343  1019  1130 D WifiConfigStore: Loading config and enabling all networks 
,08-25 15:25:03.353  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-25 15:25:03.353  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:25:03.353  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 15:25:03.353  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:03.353  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:03.353  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:03.363  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:03.363  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 15:25:03.363  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 15:25:03.363  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-25 15:25:03.363  4780  4780 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-25 15:25:03.363  1182  1182 D HotspotTile: onReceive : 3, 0
,08-25 15:25:03.363  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-25 15:25:03.363  6896  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 15:25:03.363  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:03.363  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:03.363  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:03.363  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:03.363  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:03.363  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:03.363  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:03.363  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:25:03.363  1019  1130 E WifiConfigStore: Not a HS20
,08-25 15:25:03.363  6896  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 15:25:03.363  6896  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:25:03.363  6896  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 15:25:03.363  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:03.363  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:03.363  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:03.363  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:03.363  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:03.363  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:03.363  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:03.363  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:25:03.373  1019  1130 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-25 15:25:03.373  6896  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:03.373  6896  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:25:03.373  1019  1130 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-25 15:25:03.373  7509  7509 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-25 15:25:03.373  7509  7509 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-25 15:25:03.373  7509  7509 I wpa_supplicant: reset timer : RESET_TIMER 0
08-25 15:25:03.373  7509  7509 I wpa_supplicant: P2P: Current p2p state = IDLE
08-25 15:25:03.373  7509  7509 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-25 15:25:03.373  7509  7509 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-25 15:25:03.373  7509  7509 I wpa_supplicant: First Scan Start
,08-25 15:25:03.373  7509  7509 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-25 15:25:03.373  1019  1130 D WifiNative-wlan0: Setting external_sim to 1
,08-25 15:25:03.373  1019  1130 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 15:25:03.373  1019  1130 I WifiNative-HAL: startHal
08-25 15:25:03.373  1019  1130 E wifi    : getStaticLongField sWifiHalHandle 0x9f49c88c
08-25 15:25:03.373  1019  1130 I WifiNative-HAL: Could not start hal
,08-25 15:25:03.373  7288  7288 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 15:25:03.383  1019  1130 E WifiNative-wlan0: do suspend true
,08-25 15:25:03.383  1019  1129 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-25 15:25:03.383  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-25 15:25:03.383  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 3
,08-25 15:25:03.383  1019  1153 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:25:03.383  1019  1153 I WifiNative-HAL: startHal
08-25 15:25:03.383  1019  1153 E wifi    : getStaticLongField sWifiHalHandle 0x9e45c9bc
08-25 15:25:03.383  1019  1153 I WifiNative-HAL: Could not start hal
,08-25 15:25:03.383  1019  1153 E WifiScanningService: could not start HAL
,08-25 15:25:03.383  1019  1019 D RttService: SCAN_AVAILABLE : 3
,08-25 15:25:03.383  1019  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-25 15:25:03.383  1019  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-25 15:25:03.383  1019  1130 E WifiNative-wlan0: invaild command id : 215
08-25 15:25:03.383   278  1008 D CommandListener: Setting iface cfg
08-25 15:25:03.383   278  1008 D CommandListener: Trying to bring up p2p0
,08-25 15:25:03.393  1019  1129 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 15:25:03.393  7509  7509 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-25 15:25:03.393  1019  1129 D WifiP2pService: P2pEnablingState
,08-25 15:25:03.393  7509  7509 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-25 15:25:03.393  1019  1129 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-25 15:25:03.393  1019  1154 D RttService: DefaultState got{ when=-5ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:25:03.393  7509  7509 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-25 15:25:03.393  1019  1129 D WifiP2pService: P2p socket connection successful
08-25 15:25:03.393  1019  1132 E ConnectivityService: updateNetworkInfo()
08-25 15:25:03.393  1019  1129 D WifiP2pService: P2pEnabledState
08-25 15:25:03.393  1019  1130 E WifiStateMachine: Failed to set frequency band 0
08-25 15:25:03.393  1019  1129 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-25 15:25:03.393  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 15:25:03.393  1019  1130 D SecContentProvider2: mCursor = null
,08-25 15:25:03.393  1019  1129 D WifiNative-p2p0: p2pGetDeviceAddress
08-25 15:25:03.393  1019  1129 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-25 15:25:03.393  1019  1031 D RCPManagerService: exchangeData() failure , invalid userId
08-25 15:25:03.393  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-25 15:25:03.393  1019  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-25 15:25:03.393  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 15:25:03.393  1019  1050 D WifiDisplayController: disconnect
08-25 15:25:03.393  1019  1050 D WifiDisplayController: updateConnection
08-25 15:25:03.393  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 15:25:03.393  1019  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-25 15:25:03.403  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:25:03.403  1019  1129 D WifiP2pService: DeviceAddress: 0a:75:42
,08-25 15:25:03.403  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
,08-25 15:25:03.403  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 15:25:03.403  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
08-25 15:25:03.403  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 15:25:03.403  1019  1130 D SecContentProvider2: mCursor = null
,08-25 15:25:03.403  1019  1050 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-25 15:25:03.403  1019  1050 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-25 15:25:03.403  1019  1050 D WifiDisplayController:  primary type: 10-0050F204-5
08-25 15:25:03.403  1019  1050 D WifiDisplayController:  secondary type: null
08-25 15:25:03.403  1019  1050 D WifiDisplayController:  wps: 0
08-25 15:25:03.403  1019  1050 D WifiDisplayController:  grpcapab: 0
08-25 15:25:03.403  1019  1050 D WifiDisplayController:  devcapab: 0
08-25 15:25:03.403  1019  1050 D WifiDisplayController:  status: 3
08-25 15:25:03.403  1019  1050 D WifiDisplayController:  wfdInfo: null
08-25 15:25:03.403  1019  1050 D WifiDisplayController:  groupownerAddress: null
08-25 15:25:03.403  1019  1050 D WifiDisplayController:  GOdeviceName: null
08-25 15:25:03.403  1019  1050 D WifiDisplayController:  interfaceAddress: 
08-25 15:25:03.403  1019  1050 D WifiDisplayController:  SConnectInfo : null
,08-25 15:25:03.413  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-25 15:25:03.413  1019  4326 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-25 15:25:03.413  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-25 15:25:03.413  1019  3774 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 15:25:03.423  1019  1129 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-25 15:25:03.423  1019  1129 D WifiP2pService: InactiveState
,08-25 15:25:03.423  1019  1129 D WifiP2pService: InactiveState{ what=143376 }
08-25 15:25:03.423  1019  1129 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-25 15:25:03.423  7509  7509 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-25 15:25:03.423  1019  1129 D WifiP2pService: InactiveState{ what=143376 }
,08-25 15:25:03.423  1019  1129 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-25 15:25:03.453  1019  3856 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 15:25:03.463  1019  1487 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 15:25:03.503  1019  1491 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-25 15:25:03.513  1019  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:03.513  1019  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:03.513  1019  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:03.513  1019  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:03.513  1019  1031 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 15:25:03.523  7613  7613 E Zygote  : MountEmulatedStorage()
08-25 15:25:03.523  7613  7613 E Zygote  : v2
08-25 15:25:03.523  7613  7613 I libpersona: KNOX_SDCARD checking this for 10068
08-25 15:25:03.523  7613  7613 I libpersona: KNOX_SDCARD not a persona
08-25 15:25:03.523  1019  1491 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7613 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-25 15:25:03.523  7613  7613 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:25:03.533  7613  7613 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 15:25:03.533  7613  7613 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-25 15:25:03.533  1019  1308 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 15:25:03.553  7613  7613 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:25:03.553  7613  7613 D ActivityThread: Added TimaKeyStore provider
,08-25 15:25:03.563  1019  4326 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 15:25:03.573  1019  4325 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-25 15:25:03.573  1019  4325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:03.573  1019  4325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:03.573  1019  4325 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:03.573  1019  4325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:03.573  7613  7613 D BadgeProvider: onCreate
,08-25 15:25:03.573  7613  7613 D BadgeProvider: DatabaseHelper
,08-25 15:25:03.583  7628  7628 E Zygote  : MountEmulatedStorage()
08-25 15:25:03.583  7628  7628 I libpersona: KNOX_SDCARD checking this for 10009
08-25 15:25:03.583  7628  7628 E Zygote  : v2
08-25 15:25:03.583  7628  7628 I libpersona: KNOX_SDCARD not a persona
08-25 15:25:03.583  7628  7628 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 15:25:03.583  1019  4325 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7628 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-25 15:25:03.583  1019  4325 I ActivityManager: Killing 6089:com.android.vending/u0a26 (adj 15): empty #21
,08-25 15:25:03.583  1019  4325 I ActivityManager: Killing 6853:com.android.defcontainer/u0a3 (adj 15): empty #22
,08-25 15:25:03.593  7628  7628 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:25:03.593  7628  7628 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-25 15:25:03.633  7628  7628 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 15:25:03.633  7628  7628 D ActivityThread: Added TimaKeyStore provider
,08-25 15:25:03.703  1019  4324 I ActivityManager: Killing 7255:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-25 15:25:03.713  1019  4326 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:03.713  1019  4326 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 15:25:03.713  1019  4326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:03.713   278  1003 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 15:25:03.713   278  1003 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-25 15:25:03.723  1019  1490 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-25 15:25:03.723  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-25 15:25:03.723  1019  1490 W ActivityManager: userId = 0, bbcId = -10000,
,08-25 15:25:03.723  1019  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:03.723  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
08-25 15:25:03.723  1681  5094 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-25 15:25:03.723  1019  1485 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
08-25 15:25:03.723  1019  1485 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
08-25 15:25:03.723  1019  1485 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
08-25 15:25:03.723  1019  1485 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,08-25 15:25:03.733  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:03.733  1019  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:03.733  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:03.743  1019  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:03.753  1019  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:03.753  1019  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:03.753  1681  1681 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-25 15:25:03.753  1019  1491 I art     : Explicit concurrent mark sweep GC freed 69624(3MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 23MB/34MB, paused 4.013ms total 164.548ms
,08-25 15:25:03.763  1019  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-25 15:25:03.763  1019  1487 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-25 15:25:03.763  1019  1308 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-25 15:25:03.763  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:03.763  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:03.763  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:03.763  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-25 15:25:03.773  7613  7622 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-25 15:25:03.773  1019  1368 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-25 15:25:03.773  1019  1368 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-25 15:25:03.773  1019  1368 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:03.773  1019  1368 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:03.773  1019  1368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-25 15:25:03.783  1019  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:03.783  1019  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:03.783  1019  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:03.783  1681  1681 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 15:25:03.783  1681  1681 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 15:25:03.793  1019  3774 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:03.793  1019  3774 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:03.793  1019  3774 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:03.793  1493  1493 D Launcher.Model: reloadBadges entered.
,08-25 15:25:03.793  7613  7622 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-25 15:25:03.793  7613  7622 D BadgeProvider: sendNotify, [notify] : null
08-25 15:25:03.793  7613  7622 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-25 15:25:03.793  7613  7622 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-25 15:25:03.793  7613  7622 D BadgeProvider: update, [UpdateCount] : 1
,08-25 15:25:03.793  7378  7378 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-25 15:25:03.803  1019  4326 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 15:25:03.803  1019  4326 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,08-25 15:25:03.813  1019  4326 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:03.813  1019  4326 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:03.813  1019  4326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:03.813  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:03.813  1019  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:03.813  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:03.823  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:03.823  1019  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:03.823  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:03.833  1019  1368 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:03.833  1019  1368 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:03.833  1019  1368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:03.833  1019  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 15:25:03.833  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:03.833  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:03.833  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:03.843  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:03.843  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:03.843  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:03.843  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:03.853  1019  1031 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7648 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-25 15:25:03.853  1019  1368 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:03.853  1019  1368 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 15:25:03.853  1019  1368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:03.853  7648  7648 E Zygote  : MountEmulatedStorage()
08-25 15:25:03.853  7648  7648 I libpersona: KNOX_SDCARD checking this for 10011
08-25 15:25:03.853  7648  7648 E Zygote  : v2
08-25 15:25:03.853  7648  7648 I libpersona: KNOX_SDCARD not a persona
08-25 15:25:03.853  7648  7648 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:25:03.863  7648  7648 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:25:03.863  7648  7648 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 15:25:03.863  1019  1081 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:03.863  1019  1081 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:03.863  1019  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:03.893  7648  7648 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:25:03.903  7648  7648 D ActivityThread: Added TimaKeyStore provider
,08-25 15:25:03.923  7648  7648 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-25 15:25:03.923  7648  7648 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-25 15:25:03.963  1459  1861 D TP/SmsProvider: query,matched:0, calling pid = 7378
,08-25 15:25:03.963  7648  7648 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-25 15:25:03.963  7648  7648 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-25 15:25:03.963  1459  1861 D TP/SmsProvider: match 0:Elapsed time : 3.062 ms
,08-25 15:25:03.973  1019  4325 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:03.973  1019  4325 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 15:25:03.973  1019  4325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-25 15:25:03.973  7648  7648 I MultiDex: VM with version 2.1.0 has multidex support
,08-25 15:25:03.973  7648  7648 I MultiDex: install
08-25 15:25:03.973  7648  7648 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-25 15:25:03.983  1019  4325 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:03.983  1019  4325 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 15:25:03.983  1019  4325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:03.983  1459  1489 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 7378
,08-25 15:25:03.983  1019  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 15:25:03.983  1019  1492 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:03.983  1019  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:03.983  1019  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:03.993  1019  1308 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:03.993  1019  1308 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:03.993  1019  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.003  1019  1490 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 15:25:04.003  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-25 15:25:04.003  7648  7648 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-25 15:25:04.003  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:04.003  1019  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:04.003  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 15:25:04.003  1630  1630 I Hs20UtilService: Starting #12
,08-25 15:25:04.003  1459  2495 D TP/SmsProvider: query,matched:0, calling pid = 7378
,08-25 15:25:04.013  1459  2495 D TP/SmsProvider: match 0:Elapsed time : 1.126 ms
,08-25 15:25:04.013  7111  7111 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 15:25:04.013  7111  7111 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 15:25:04.013  7111  7111 D SecurityLogAgent: StateMachine : Current State = 1
08-25 15:25:04.013  7111  7111 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 15:25:04.013  1019  1490 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 15:25:04.013  1019  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,08-25 15:25:04.013  1630  1651 I Hs20UtilService: Message received 5011
,08-25 15:25:04.013  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:04.013  1019  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:04.013  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.023  7378  7667 D LocationInitializer: Restart initialization of location
,08-25 15:25:04.023  1459  2494 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 7378
,08-25 15:25:04.023  1019  4325 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 15:25:04.023  1019  4325 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 15:25:04.023  1019  4325 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:04.023  1019  4325 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:04.033  1019  4325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 15:25:04.033  1019  3856 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 15:25:04.033  1019  3856 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
08-25 15:25:04.033  1630  1630 I Hs20UtilService: Starting #13
,08-25 15:25:04.033  1630  1651 I Hs20UtilService: Message received 5011
,08-25 15:25:04.033  1019  3856 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:04.033  1019  3856 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 15:25:04.033  1019  3856 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.033  1019  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-25 15:25:04.033  1019  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-25 15:25:04.033  1019  1130 E WifiNative-wlan0: invaild command id : 215
,08-25 15:25:04.043  1019  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 15:25:04.043  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:04.043  7111  7111 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 15:25:04.043  7111  7111 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 15:25:04.043  7111  7111 D SecurityLogAgent: StateMachine : Current State = 1
08-25 15:25:04.043  7111  7111 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-25 15:25:04.043  1019  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:04.043  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.063  4780  4780 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-25 15:25:04.063  4780  4780 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 15:25:04.063  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 15:25:04.063  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 15:25:04.063  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 15:25:04.063  4780  4780 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 15:25:04.063  1019  1492 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-25 15:25:04.073  4780  4873 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 15:25:04.073  1019  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:04.073  1019  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:04.073  1019  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:04.073  1019  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:04.073  7648  7648 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-25 15:25:04.073  7648  7648 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@257def46: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-25 15:25:04.073  7648  7648 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-25 15:25:04.083  7669  7669 E Zygote  : MountEmulatedStorage()
08-25 15:25:04.083  7669  7669 I libpersona: KNOX_SDCARD checking this for 10064
08-25 15:25:04.083  7669  7669 E Zygote  : v2
08-25 15:25:04.083  7669  7669 I libpersona: KNOX_SDCARD not a persona
08-25 15:25:04.083  7669  7669 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:25:04.093  7669  7669 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:25:04.093  7669  7669 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 15:25:04.093  1019  1492 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7669 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 15:25:04.123  7648  7648 D WearableService: callingUid 10011, callindPid: 7648
,08-25 15:25:04.123  7669  7669 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:25:04.123  7669  7669 D ActivityThread: Added TimaKeyStore provider
,08-25 15:25:04.143  7648  7677 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,08-25 15:25:04.143  7669  7669 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-25 15:25:04.153  7669  7669 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 15:25:04.163  7669  7669 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-25 15:25:04.163  1751  3158 E MDM     : [181] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-25 15:25:04.183  7669  7669 D FileShare-Client: Outbound.stopDelayTimer - 
,08-25 15:25:04.193  7273  7273 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 15:25:04.193  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:04.193  1019  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:04.193  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-25 15:25:04.203  1019  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:04.203  1019  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:04.203  1019  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.203  1019  3774 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-25 15:25:04.203  1019  3774 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-25 15:25:04.203  1019  3774 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:04.203  1019  3774 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:04.203  1019  3774 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.203  1019  4326 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
08-25 15:25:04.203  1019  4326 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
08-25 15:25:04.203  1019  4326 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
08-25 15:25:04.203  1019  4326 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,08-25 15:25:04.203  1681  5151 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-25 15:25:04.203  1019  4326 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:04.203  1019  4326 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 15:25:04.203  1019  4326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.213  1019  4326 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:04.213  1019  4326 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:04.213  1019  4326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.213  1681  1681 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-25 15:25:04.223  1019  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:04.223  1019  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:04.223  1019  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.223  1019  3774 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-25 15:25:04.223  1019  3774 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-25 15:25:04.223  1019  3774 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:04.223  1019  3774 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:04.223  1019  3774 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.223   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 15:25:04.233  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:04.233  1019  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:04.233  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.233  1681  1681 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 15:25:04.243  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:04.243  1019  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:04.243  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.243  7378  7378 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
08-25 15:25:04.243  1019  1492 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 15:25:04.243  1019  1492 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:04.243  1019  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
08-25 15:25:04.243  1019  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 15:25:04.243  1019  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-25 15:25:04.243  1019  1490 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:04.243  1019  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:04.243  1019  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.253  1019  1308 W ActivityManager: userId = 0, bbcId = -10000,
08-25 15:25:04.253  1019  1308 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:04.253  1019  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.253  1019  1081 W ActivityManager: userId = 0, bbcId = -10000,
08-25 15:25:04.253  1019  1081 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
08-25 15:25:04.253  1019  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.263  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:04.263  1019  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:04.263  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.263  1751  5096 E MDM     : [187] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-25 15:25:04.263  1019  3774 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:04.263  1019  3774 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:04.263  1019  3774 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.273  1019  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:04.273  1019  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:04.273  1019  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.273  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:04.273  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:04.273  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.283  1019  1081 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 15:25:04.283  1019  1081 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:04.283  1019  1081 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:04.283  1019  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.283  1019  4326 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:04.283  1019  4326 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 15:25:04.283  1019  4326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.293  1019  1492 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 15:25:04.293  1019  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,08-25 15:25:04.293  1019  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:04.293  1019  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:04.293  1019  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.293  7378  7688 D LocationInitializer: Restart initialization of location
,08-25 15:25:04.303  1019  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 15:25:04.303  1019  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,08-25 15:25:04.303  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:04.303  1019  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:04.303  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 15:25:04.513  7509  7509 I wpa_supplicant: nl80211: Received scan results (26 BSSes)
08-25 15:25:04.513  7509  7509 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-25 15:25:04.513  7509  7509 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-25 15:25:04.513  7509  7509 I wpa_supplicant: Trying to associate with  'G700'
08-25 15:25:04.513  7509  7509 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-25 15:25:04.513  7509  7509 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-25 15:25:04.513  1019  7598 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-25 15:25:04.523  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 15:25:04.533  1019  1130 D SecContentProvider2: mCursor = null
,08-25 15:25:04.633  7509  7509 E wpa_supplicant: Cmd 35605 not handled
,08-25 15:25:04.633  7509  7509 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
08-25 15:25:04.633  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 15:25:04.633  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-25 15:25:04.633  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 15:25:04.633  7509  7509 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00),
08-25 15:25:04.633  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 15:25:04.633  7509  7509 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-25 15:25:04.633  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 15:25:04.633  7509  7509 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030,
08-25 15:25:04.633  7509  7509 I wpa_supplicant: Associated with F4.99.3E
08-25 15:25:04.633  7509  7509 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-25 15:25:04.633  7509  7509 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE,
08-25 15:25:04.633  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-25 15:25:04.633  7509  7509 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-25 15:25:04.633  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 15:25:04.633  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-25 15:25:04.633  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 15:25:04.633  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-25 15:25:04.633  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, true
,08-25 15:25:04.633  1019  1047 D Tethering: interfaceStatusChanged wlan0, true
08-25 15:25:04.643  1019  1133 E Tethering: No numeric data
08-25 15:25:04.643  1019  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 15:25:04.643  1019  1133 D Tethering: clearTetheredNotification()
,08-25 15:25:04.643  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-25 15:25:04.643  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-25 15:25:04.643  7509  7509 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-25 15:25:04.643  1182  1182 D HotspotTile: updateTetherState():false, false
08-25 15:25:04.643  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:25:04.643  7509  7509 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-25 15:25:04.643  7509  7509 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
08-25 15:25:04.643  7509  7509 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-25 15:25:04.643  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 15:25:04.643  7509  7509 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 15:25:04.643  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 15:25:04.643  7509  7509 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-25 15:25:04.643  7509  7509 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-25 15:25:04.653  7509  7509 I wpa_supplicant: Blacklist: Clear (temp) 
08-25 15:25:04.653  7509  7509 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-25 15:25:04.653  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-25 15:25:04.653  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, true
08-25 15:25:04.653  1019  1047 D Tethering: interfaceStatusChanged wlan0, true
08-25 15:25:04.653  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 15:25:04.653  1019  1130 D SecContentProvider2: mCursor = null
,08-25 15:25:04.653  1019  1127 V NetworkStats: performPollLocked() took 10ms
,08-25 15:25:04.653  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:25:04.663  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:25:04.663  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:25:04.663  1019  1130 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-25 15:25:04.663  1019  1130 E WifiConfigStore: setLastSelectedConfiguration -1
,08-25 15:25:04.673  1019  1130 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} },
,08-25 15:25:04.673  1019  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 15:25:04.673  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 15:25:04.673  1019  1132 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,08-25 15:25:04.673  1019  1132 E ConnectivityService: updateNetworkInfo()
08-25 15:25:04.673  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-25 15:25:04.683  1019  4324 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 15:25:04.673  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:25:04.683  1019  4324 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-25 15:25:04.673  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 15:25:04.683  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-25 15:25:04.683  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:04.683  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:04.683  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:04.683  1019  4324 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:04.683  1019  4324 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:04.683  1019  4324 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 15:25:04.683  1630  1630 I Hs20UtilService: Starting #14
,08-25 15:25:04.693  1630  1651 I Hs20UtilService: Message received 5007
,08-25 15:25:04.693  4780  4780 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-25 15:25:04.693  4780  4780 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 15:25:04.693  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-25 15:25:04.693  1019  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 15:25:04.693  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 15:25:04.693  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 15:25:04.693  4780  4780 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 15:25:04.693  4780  4873 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 15:25:04.703   278  1008 D CommandListener: Setting iface cfg
,08-25 15:25:04.713  1019  1130 E WifiStateMachine: Start Dhcp Watchdog 2
,08-25 15:25:04.713  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 15:25:04.713  1019  1130 D SecContentProvider2: mCursor = null
,08-25 15:25:04.723  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 15:25:04.723  1019  1130 D SecContentProvider2: mCursor = null
,08-25 15:25:04.733  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-25 15:25:04.733  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 15:25:04.733  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-25 15:25:04.733  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:04.733  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:04.733  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:04.743  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:04.743  1019  1130 E WifiNative-wlan0: do suspend false
,08-25 15:25:04.753  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 15:25:04.753  1019  1130 D SecContentProvider2: mCursor = null
,08-25 15:25:04.753  1019  1129 D WifiP2pService: InactiveState{ what=143375 }
,08-25 15:25:04.753  1019  1129 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-25 15:25:04.863  1019  1031 D SecContentProvider: uri = 18 selection = isWifiEnabled,
,08-25 15:25:04.863  1019  1031 D WifiService: setWifiEnabled: false pid=6896, uid=10170
08-25 15:25:04.863  1019  1031 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 15:25:04.863  1019  1031 D SecContentProvider2: mCursor = null
08-25 15:25:04.863  1019  1031 D SettingsProvider: name = wifi_on
,08-25 15:25:04.873  1019  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 15:25:04.883  1019  1130 E WifiNative-wlan0: do suspend true,
,08-25 15:25:04.913  1019  1129 D WifiP2pService: InactiveState{ what=143375 },
,08-25 15:25:04.913  1019  1129 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-25 15:25:04.913   278  1008 D CommandListener: Clearing all IP addresses on wlan0
,08-25 15:25:04.913  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-25 15:25:04.913  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:25:04.913  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 15:25:04.913  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:04.913  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:04.913  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:04.913  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:04.913  1019  1132 E ConnectivityService: updateNetworkInfo()
,08-25 15:25:04.913  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
08-25 15:25:04.913  1019  1132 E ConnectivityService: updateNetworkInfo()
08-25 15:25:04.913  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,08-25 15:25:04.913   278  1008 E Netd    : no such netId 503
08-25 15:25:04.923  1019  1132 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-25 15:25:04.913  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-25 15:25:04.923  1019  1132 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-25 15:25:04.923  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:04.923  1019  1132 V NetworkStats: updateIfacesLocked()
08-25 15:25:04.923  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 15:25:04.923  1019  1132 V NetworkStats: performPollLocked(flags=0x1),
08-25 15:25:04.923  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 15:25:04.933  1019  1132 V NetworkStats: performPollLocked() took 8ms
08-25 15:25:04.933  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:25:04.933  1019  1129 D WifiP2pService: InactiveState{ what=131204 },
08-25 15:25:04.933  1019  1129 D WifiP2pService: P2pEnabledState{ what=131204 }
08-25 15:25:04.943  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 15:25:04.943  1019  1153 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:25:04.943  1019  1129 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-25 15:25:04.943  1019  1019 D RttService: SCAN_AVAILABLE : 1
,08-25 15:25:04.943  1019  1081 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 15:25:04.943  1019  1154 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:25:04.943  1019  1081 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-25 15:25:04.943  1019  1081 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:04.943  1019  1081 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:04.943  1019  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 15:25:04.943  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-25 15:25:04.943  1019  1130 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost,
08-25 15:25:04.943  1019  1132 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,08-25 15:25:04.943  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:25:04.943  1019  1132 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-25 15:25:04.943  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 15:25:04.943  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-25 15:25:04.943  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:04.943  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:04.943  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:04.943  1019  7690 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 15:25:04.943  1019  7690 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-25 15:25:04.943  1019  1132 D ConnectivityService: nai.networkMonitor.doQuit()
08-25 15:25:04.943  1019  1132 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-25 15:25:04.943  1019  1132 E ConnectivityService: updateNetworkInfo()
08-25 15:25:04.953  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:04.953  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:25:04.953  1630  1630 I Hs20UtilService: Starting #15
,08-25 15:25:04.953  1630  1651 I Hs20UtilService: Message received 5007
,08-25 15:25:04.953  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:25:04.953  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
08-25 15:25:04.953  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 15:25:04.953  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-25 15:25:04.953  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-25 15:25:04.953  1019  1129 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-25 15:25:04.953  1019  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-25 15:25:04.953  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 15:25:04.953  1019  1050 D WifiDisplayController: disconnect
08-25 15:25:04.953  1019  1050 D WifiDisplayController: updateConnection
08-25 15:25:04.953  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 15:25:04.953  1019  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-25 15:25:04.953  1019  1132 E ConnectivityService: updateNetworkInfo()
,08-25 15:25:04.963  1019  1129 D WifiP2pService: P2pDisablingState
08-25 15:25:04.963  1019  1129 D WifiP2pService: P2pDisablingState{ what=147458 }
08-25 15:25:04.973  1019  1129 D WifiP2pService: p2p socket connection lost
,08-25 15:25:04.973  4780  4780 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-25 15:25:04.973  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-25 15:25:04.973  4780  4780 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-25 15:25:04.973  1019  4326 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-25 15:25:04.973  1019  1130 E WifiNative-wlan0: do suspend true
08-25 15:25:04.973  1019  1129 D WifiP2pService: P2pDisabledState
08-25 15:25:04.973  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-25 15:25:04.973  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-25 15:25:04.973  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 15:25:04.973  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
08-25 15:25:04.973  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 15:25:04.973  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-25 15:25:04.973  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 15:25:04.973  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 15:25:04.973  4780  4780 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 15:25:04.973  7693  7693 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-25 15:25:04.973  4780  4873 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 15:25:04.983  7693  7693 I dhcpcd  : version 5.5.6 starting
,08-25 15:25:04.983  4780  4780 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-25 15:25:04.983  4780  4780 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 15:25:04.983  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 15:25:04.983  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 15:25:04.983  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 15:25:04.983  4780  4780 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 15:25:04.993  4780  4873 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 15:25:04.993  7669  7669 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 15:25:04.993  7669  7669 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-25 15:25:04.993  7669  7669 D FileShare-Client: Outbound.stopDelayTimer - 
,08-25 15:25:05.003  7273  7273 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 15:25:05.003  7693  7693 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-25 15:25:05.003  1019  1129 D WifiP2pService: P2pDisabledState{ what=143375 }
08-25 15:25:05.003   278  1008 D CommandListener: Clearing all IP addresses on wlan0
08-25 15:25:05.003  1019  1129 D WifiP2pService: DefaultState{ what=143375 }
,08-25 15:25:05.013  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling,
08-25 15:25:05.013  7509  7509 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-25 15:25:05.013  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-25 15:25:05.013  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:25:05.013  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 15:25:05.013  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:05.013  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:05.023  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:05.023  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:05.023  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 15:25:05.023  1019  1130 D SecContentProvider2: mCursor = null
,08-25 15:25:05.033  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-25 15:25:05.033  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:25:05.033  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 15:25:05.033  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:05.033  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:05.033  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-25 15:25:05.033  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:05.043  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-25 15:25:05.043  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 15:25:05.043  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:25:05.043  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-25 15:25:05.043  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 15:25:05.043  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:05.043  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:05.043  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:05.043  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:05.043  1182  1182 D HotspotTile: onReceive : 0, 0
08-25 15:25:05.043  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 15:25:05.043  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-25 15:25:05.043  1019  1491 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 15:25:05.043  4780  4780 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
08-25 15:25:05.043  1019  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-25 15:25:05.043  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:05.043  1019  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:05.043  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 15:25:05.043  1630  1630 I Hs20UtilService: Starting #16,
08-25 15:25:05.043  1630  1651 I Hs20UtilService: Message received 5007
,08-25 15:25:05.043  6896  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-25 15:25:05.043  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:05.043  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:05.043  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:05.043  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:25:05.043  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
,08-25 15:25:05.043  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:05.043  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:05.043  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:25:05.053  6896  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:05.053  6896  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:25:05.053  4780  4780 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 15:25:05.053  4780  4780 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 15:25:05.053  6896  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:05.053  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:05.053  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:05.053  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:05.053  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:25:05.053  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:05.053  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:05.053  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:05.053  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:25:05.053  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 15:25:05.063  6896  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:05.063  6896  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:25:05.063  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 15:25:05.063  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 15:25:05.063  4780  4780 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 15:25:05.063  4780  4873 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 15:25:05.073  7693  7693 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
,08-25 15:25:05.073  7693  7693 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-25 15:25:05.073  7693  7693 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-25 15:25:05.073  1019  4324 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 15:25:05.073  7693  7693 I dhcpcd  : bssid match
,08-25 15:25:05.073  1019  4324 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-25 15:25:05.073  7693  7693 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
08-25 15:25:05.073  1019  4324 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:05.073  1019  4324 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:05.073  1019  4324 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 15:25:05.073  1630  1630 I Hs20UtilService: Starting #17,
08-25 15:25:05.073  1630  1651 I Hs20UtilService: Message received 5011
08-25 15:25:05.073  7111  7111 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-25 15:25:05.073  7111  7111 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 15:25:05.073  7111  7111 D SecurityLogAgent: StateMachine : Current State = 1
,08-25 15:25:05.073  7111  7111 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 15:25:05.193  7509  7509 I wpa_supplicant: Blacklist: Clear (all) ,
08-25 15:25:05.193  7693  7693 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-25 15:25:05.223   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-25 15:25:05.243   288   288 E SMD     : DCD OFF,
,08-25 15:25:05.303  7693  7693 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,08-25 15:25:05.343  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 15:25:05.343  7509  7509 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-25 15:25:05.343  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-25 15:25:05.343  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
,08-25 15:25:05.373  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
08-25 15:25:05.373  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-25 15:25:05.373  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-25 15:25:05.373  1019  1133 D Tethering: InitialState.processMessage what=4,
,08-25 15:25:05.373  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 15:25:05.373  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-25 15:25:05.373  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 15:25:05.373  1019  1133 E Tethering: No numeric data
08-25 15:25:05.383  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
08-25 15:25:05.373  1019  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 15:25:05.383  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 15:25:05.373  1019  1133 D Tethering: clearTetheredNotification()
08-25 15:25:05.383  1182  1182 D HotspotTile: updateTetherState():false, false
08-25 15:25:05.383  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:05.383  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 15:25:05.383  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 15:25:05.383  7509  7509 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-25 15:25:05.383  7509  7509 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-25 15:25:05.383  7509  7509 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,08-25 15:25:05.383  7509  7509 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-25 15:25:05.383  7509  7509 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-25 15:25:05.393  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 15:25:05.393  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-25 15:25:05.393  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:05.393  1019  1127 V NetworkStats: performPollLocked() took 10ms
08-25 15:25:05.393  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 15:25:05.393  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:05.393  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:25:05.433  5970  5970 D FactoryTest: Not factory mode
08-25 15:25:05.433  5970  5970 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-25 15:25:05.433  5970  5970 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-25 15:25:05.433  5970  5970 D MTPRx   : still no open session command from host, so toast
,08-25 15:25:05.443  5970  5970 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-25 15:25:05.443  5970  5970 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-25 15:25:05.443  5970  5970 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:119213
,08-25 15:25:05.443  1019  1031 E PersonaManagerService: inState():  stateMachine is null !!
08-25 15:25:05.443  1019  1031 I PersonaManagerService: PersonaId don't exist
08-25 15:25:05.443  1019  1031 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-25 15:25:05.443  1019  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-25 15:25:05.443  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:05.443  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:05.443  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-25 15:25:05.453  1019  1031 W ActivityManager: mDVFSHelper.acquire(),
,08-25 15:25:05.473  1019  1031 D PersonaManager: isKioskContainerExistOnDevice,
,08-25 15:25:05.483  1019  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-25 15:25:05.483  1019  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
08-25 15:25:05.483  1019  1031 D InputDispatcher: Focused application set to: xxxx
08-25 15:25:05.483  1019  1031 D InputDispatcher: Focus left window: 6896
,08-25 15:25:05.483  5970  5970 E MTPRx   : started activity for popup
,08-25 15:25:05.483  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
08-25 15:25:05.483  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-25 15:25:05.523  5970  5970 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-25 15:25:05.533  5970  5970 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-25 15:25:05.533  5970  5970 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-25 15:25:05.533  5970  5970 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 15:25:05.533  5970  5970 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-25 15:25:05.533  5970  5970 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 15:25:05.533  1019  1099 V AlarmManager: waitForAlarm result :4
,08-25 15:25:05.543  1019  1019 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-25 15:25:05.543  1019  1019 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-25 15:25:05.543  1019  1019 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-25 15:25:05.553  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-25 15:25:05.553  1182  1182 D KeyguardUpdateMonitor: handleTimeUpdate
,08-25 15:25:05.553  1182  1182 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-25 15:25:05.553  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:05.553  1019  1045 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:05.553  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk,
08-25 15:25:05.563  1182  1182 D SecKeyguardClockView: HomeTimezone(): 1
,08-25 15:25:05.563  1182  1182 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-25 15:25:05.563  1182  1182 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-25 15:25:05.563  1182  1182 I KeyguardEffectViewController: *** don't update sliding image ***
,08-25 15:25:05.573  1182  1182 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-25 15:25:05.573  5970  5970 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-25 15:25:05.583  1019  4326 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-25 15:25:05.583  1019  4326 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-25 15:25:05.583  1019  4326 D InputDispatcher: Focused application set to: xxxx
,08-25 15:25:05.583  1019  4326 D InputDispatcher: Focus entered window: 6896
,08-25 15:25:05.583  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-25 15:25:05.583  1019  3856 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-25 15:25:05.583  1019  3856 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@30872770 attribute=null, token = android.os.BinderProxy@2c609648
,08-25 15:25:05.593  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-25 15:25:05.613  7509  7509 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 15:25:05.613  1182  1182 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-25 15:25:05.623  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
08-25 15:25:05.623  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 15:25:05.623  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-25 15:25:05.623  1182  1182 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-25 15:25:05.623  1182  1182 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-25 15:25:05.633  5970  5970 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-25 15:25:05.633  1182  1182 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-25 15:25:05.633  5970  5970 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-25 15:25:05.633  5970  5970 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-25 15:25:05.663  6896  6896 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-25 15:25:05.663  6896  6896 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
08-25 15:25:05.663  6896  6896 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-25 15:25:05.663  6896  6896 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-25 15:25:05.663  1019  4324 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-25 15:25:05.663  1019  4324 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-25 15:25:05.663  1019  4324 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-25 15:25:05.663  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-25 15:25:05.663  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,08-25 15:25:05.673  6896  6896 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 15:25:05.673  6896  6896 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-25 15:25:05.683  6896  6896 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2ed6f41f time:119451
,08-25 15:25:05.683  6896  6896 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9d0e14b Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@327d321, 16908290=android.view.AbsSavedState$1@327d321}, android:focusedViewId=100}]}]
08-25 15:25:05.683  6896  6896 V ActivityThread: updateVisibility : ActivityRecord{127edd35 token=android.os.BinderProxy@2ed6f41f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-25 15:25:05.683  6896  6896 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-25 15:25:05.683  6896  6896 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 15:25:05.683  6896  6896 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-25 15:25:05.683  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 15:25:05.683  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 15:25:05.683  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,08-25 15:25:05.683  7509  7509 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-25 15:25:05.693  1019  4326 D PersonaManager: isKioskContainerExistOnDevice
,08-25 15:25:05.793  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-25 15:25:05.793  1019  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-25 15:25:05.793  7288  7288 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 15:25:05.803  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-25 15:25:05.803  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:25:05.803  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 15:25:05.803  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:05.803  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:05.803  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:05.803  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 15:25:05.803  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:05.803  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 15:25:05.803  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-25 15:25:05.803  1182  1182 D HotspotTile: onReceive : 1, 0
,08-25 15:25:05.803  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-25 15:25:05.803  4780  4780 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 15:25:05.803  1019  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 15:25:05.803  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-25 15:25:05.803  1751  2204 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 15:25:05.803  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:05.803  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:05.803  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 15:25:05.813  1630  1630 I Hs20UtilService: Starting #18
08-25 15:25:05.813  1630  1651 I Hs20UtilService: Message received 5011
,08-25 15:25:05.813  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:05.813  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:05.813  7111  7111 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-25 15:25:05.813  7111  7111 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 15:25:05.813  7111  7111 D SecurityLogAgent: StateMachine : Current State = 1
08-25 15:25:05.813  7111  7111 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 15:25:06.533   278  1001 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-25 15:25:06.533  1019  1047 D Tethering: interfaceRemoved wlan0
,08-25 15:25:06.533  1019  1047 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-25 15:25:06.693  1019  1047 D Tethering: interfaceRemoved p2p0
08-25 15:25:06.693  1019  1047 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-25 15:25:07.493  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-25 15:25:07.883  6896  7047 D BluetoothAdapter: enable()
,08-25 15:25:07.883  1019  1485 W ActivityManager: Permission Denial: getCurrentUser() from pid=6896, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-25 15:25:07.883  1019  1485 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-25 15:25:07.883  1019  1485 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6896, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-25 15:25:07.883  1019  1485 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 15:25:07.883  1019  1485 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-25 15:25:07.883  1019  1485 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-25 15:25:07.883  1019  1485 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-25 15:25:07.883  1019  1485 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-25 15:25:07.883  1019  1485 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-25 15:25:07.883  1019  1485 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 15:25:07.893  1019  1485 D SettingsProvider: name = bluetooth_on,
,08-25 15:25:07.893  1019  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-25 15:25:07.893  1019  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,08-25 15:25:07.893  1019  1049 D SecContentProvider: uri = 3 selection = isBluetoothEnabled,
08-25 15:25:07.893  3215  3295 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-25 15:25:07.893  3215  3295 D BluetoothAdapterProperties: Setting state to 11
08-25 15:25:07.893  3215  3295 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-25 15:25:07.893  3215  3295 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 15:25:07.893  3215  3295 D BluetoothAdapterService: updateAdapterState state is 11
08-25 15:25:07.893  3215  3295 D BluetoothAdapterService: Autoconnection is available 
08-25 15:25:07.893  3215  3295 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11,
08-25 15:25:07.893  3215  3295 D BtConfig.SecureMode: isSecureModeOn:false
08-25 15:25:07.893  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-25 15:25:07.903  1019  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:25:07.903  3215  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-25 15:25:07.903  1019  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-25 15:25:07.903  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService,
,08-25 15:25:07.903  3215  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-25 15:25:07.903  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-25 15:25:07.903  3215  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-25 15:25:07.903  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService,
08-25 15:25:07.903  3215  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-25 15:25:07.903  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-25 15:25:07.903  3215  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-25 15:25:07.903  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-25 15:25:07.903  3215  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-25 15:25:07.903  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-25 15:25:07.903  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 15:25:07.903  1019  1019 I InputMethodManagerService: [BT Setting State] State =11
08-25 15:25:07.903  3215  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-25 15:25:07.903  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 15:25:07.903  3215  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-25 15:25:07.903  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 15:25:07.903  3215  3295 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 15:25:07.903  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-25 15:25:07.903  3215  3295 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-25 15:25:07.903  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-25 15:25:07.903  3215  3295 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-25 15:25:07.903  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 15:25:07.903  3215  3295 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-25 15:25:07.903  3215  3295 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
,08-25 15:25:07.903  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-25 15:25:07.903  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-25 15:25:07.903  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-25 15:25:07.903  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:07.903  1019  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:07.903  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 15:25:07.903  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-25 15:25:07.903  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-25 15:25:07.903  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-25 15:25:07.913  3215  3215 D HeadsetService: Received start request. Starting profile...
08-25 15:25:07.913  3215  3215 D HeadsetService: start()
08-25 15:25:07.913  3215  3215 D HeadsetStateMachine: make
,08-25 15:25:07.913  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 15:25:07.913  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:25:07.913  1182  1182 D BluetoothTile:  getBluetoothState : 11
08-25 15:25:07.913  1879  1879 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 15:25:07.923  3215  3215 E HeadsetStateMachine: # of Max HF connection is 2
,08-25 15:25:07.923  1019  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:25:07.923  1019  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 15:25:07.923  4780  4780 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:25:07.923  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
08-25 15:25:07.923  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-25 15:25:07.923  1019  1492 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:07.923  1019  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 15:25:07.923  1019  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 15:25:07.933  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:07.933  1019  4326 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-25 15:25:07.933  1019  4326 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-25 15:25:07.933  1019  4326 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:07.933  1019  4326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:07.933  1019  4326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-25 15:25:07.933  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-25 15:25:07.933  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 15:25:07.933  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-25 15:25:07.933  1019  1308 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:25:07.933  1019  1308 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 15:25:07.933  1019  4325 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 15:25:07.933  1019  3774 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false,
08-25 15:25:07.933  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-25 15:25:07.933  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:07.933  1019  1308 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:07.933  1019  1308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:07.933  1019  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 15:25:07.943  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-25 15:25:07.943  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-25 15:25:07.943  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-25 15:25:07.943  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 15:25:07.943  1019  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:25:07.943  1019  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-25 15:25:07.943  1019  1492 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:07.943  1019  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 15:25:07.943  1019  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
08-25 15:25:07.953  1019  3856 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-25 15:25:07.953  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-25 15:25:07.953  1019  3856 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-25 15:25:07.953  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService,
08-25 15:25:07.953  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-25 15:25:07.953  1019  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:25:07.953  1019  3856 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:07.953  1019  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-25 15:25:07.953  1019  3856 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-25 15:25:07.953  1019  3856 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-25 15:25:07.953  3215  3215 I bluedroid: get_profile_interface handsfree
08-25 15:25:07.953  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:07.953  1019  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 15:25:07.953  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:07.953  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-25 15:25:07.953  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 15:25:07.953  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-25 15:25:07.963  1019  1081 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-25 15:25:07.963  1019  1081 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-25 15:25:07.963  4780  4780 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 15:25:07.963  1019  1081 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:07.963  1019  1081 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:07.963  1019  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:07.963  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-25 15:25:07.963  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 15:25:07.963  3215  3295 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-25 15:25:07.963  1019  1081 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:25:07.963  1019  1081 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 15:25:07.973  3215  3215 E DualScoManager: Dual Sco Manager already instantiated
08-25 15:25:07.973  3215  3215 I DualScoManager: Set HeadsetServiceHelper
08-25 15:25:07.973  3215  3215 D BluetoothAtMessage: createCMTIContentObservers
08-25 15:25:07.973  1019  1081 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:07.973  1019  1081 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:07.973  1019  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 15:25:07.973  1019  3774 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-25 15:25:07.973  1019  3774 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 15:25:07.973  1019  3774 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 15:25:07.973  1019  3774 D SettingsProvider: selectionArgs: false
08-25 15:25:07.973  1019  3774 D SettingsProvider: selectionArgs: 1002
08-25 15:25:07.973  1019  3774 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 15:25:07.973  1019  3774 D SettingsProvider: ret = -1
08-25 15:25:07.973  3215  7727 D HeadsetStateMachine: Enter Disconnected: -2
,08-25 15:25:07.973  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-25 15:25:07.973  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 15:25:07.973  3215  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-25 15:25:07.973  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-25 15:25:07.973  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-25 15:25:07.973  3215  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-25 15:25:07.973  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-25 15:25:07.973  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-25 15:25:07.973  3215  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-25 15:25:07.973  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-25 15:25:07.973  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 15:25:07.973  3215  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-25 15:25:07.973  3215  3295 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 15:25:07.973  3215  3215 D HeadsetService: mStartError = false
08-25 15:25:07.973  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
08-25 15:25:07.973  3215  3215 D A2dpService: Received start request. Starting profile...
08-25 15:25:07.973  3215  3215 D A2dpService: start()
,08-25 15:25:07.973  3215  3215 I bluedroid: get_profile_interface avrcp
,08-25 15:25:07.973  3215  7727 D HeadsetStateMachine: Clear mHeadsetBrsf
08-25 15:25:07.973  3215  7727 D HeadsetStateMachine: map size, before remove : 0
08-25 15:25:07.973  3215  7727 D HeadsetStateMachine: map size, after remove: 0
,08-25 15:25:07.973  3215  3215 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 15:25:07.973  3215  3215 D Avrcp   : Initialize Media Controller
08-25 15:25:07.973  3215  3215 D Avrcp   : Get the Context Package Name: com.android.bluetooth,
08-25 15:25:07.983  3215  3215 E Avrcp   : getActiveSessions
08-25 15:25:07.983  3215  3215 D Avrcp   : pick active media Controller
08-25 15:25:07.983  3215  3215 D Avrcp   : Get the active Media Controller 
,08-25 15:25:07.983  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:25:07.983  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-25 15:25:07.983  3215  3215 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-25 15:25:07.983  3215  3215 D A2dpStateMachine: make
08-25 15:25:07.983  3215  7728 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-25 15:25:07.993  3215  3215 I bluedroid: get_profile_interface a2dp
08-25 15:25:07.993  3215  7730 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-25 15:25:07.993  3215  3215 E bt-btif : warning : media task started media_task_refcnt 1 
08-25 15:25:07.993  3215  3215 D A2dpService: mStartError = false
08-25 15:25:07.993  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
08-25 15:25:07.993  3215  3215 D HeadsetStateMachine: Try to query the phonestate on bind
,08-25 15:25:07.993  1431  3356 I Telecom : BluetoothPhoneService: queryPhoneState
08-25 15:25:07.993  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-25 15:25:07.993  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-25 15:25:07.993  3215  7729 D A2dpStateMachine: Enter Disconnected: -2
08-25 15:25:07.993  1431  3356 I Telecom : BluetoothPhoneService: Result of Message : true
,08-25 15:25:07.993  3215  3215 D HidService: Received start request. Starting profile...
08-25 15:25:07.993  3215  3215 D HidService: start()
08-25 15:25:07.993  3215  3215 I bluedroid: get_profile_interface hidhost
08-25 15:25:07.993  3215  3215 D HidService: setHidService(): set to: null
08-25 15:25:07.993  3215  3215 D HidService: mStartError = false
08-25 15:25:07.993  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
08-25 15:25:07.993  3215  3215 D HeadsetStateMachine: Proxy object connected
,08-25 15:25:07.993  3215  3215 D HealthService: Received start request. Starting profile...
08-25 15:25:07.993  3215  3215 D HealthService: start()
,08-25 15:25:07.993  3215  3215 I bluedroid: get_profile_interface health
08-25 15:25:07.993  3215  3215 D HealthService: mStartError = false
08-25 15:25:07.993  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
,08-25 15:25:07.993  3215  3215 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-25 15:25:08.003  3215  7727 D HeadsetStateMachine: Disconnected process message: 11
,08-25 15:25:08.003  3215  3215 D PanService: Received start request. Starting profile...
08-25 15:25:08.003  3215  3215 D PanService: start()
08-25 15:25:08.003  3215  3215 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 15:25:08.003  3215  3215 I bluedroid: get_profile_interface pan
08-25 15:25:08.003  3215  3215 D PanService: mStartError = false
08-25 15:25:08.003  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
08-25 15:25:08.003  3215  3215 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-25 15:25:08.003  3215  3215 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-25 15:25:08.003  3215  7727 D HeadsetStateMachine: Disconnected process message: 18
,08-25 15:25:08.003  3215  3215 D BluetoothMapService: Received start request. Starting profile...
08-25 15:25:08.003  3215  3215 D BluetoothMapService: start()
,08-25 15:25:08.003  3215  3215 D BluetoothMapService: mStartError = false
08-25 15:25:08.003  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
08-25 15:25:08.003  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-25 15:25:08.003  3215  3215 D SapService: Received start request. Starting profile...
08-25 15:25:08.003  3215  3215 D SapService: start()
08-25 15:25:08.003  3215  3215 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-25 15:25:08.003  3215  3215 I bluedroid: get_profile_interface sap
08-25 15:25:08.003  3215  3215 D SapService: mStartError = false
08-25 15:25:08.003  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
08-25 15:25:08.003  3215  3215 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-25 15:25:08.003  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-25 15:25:08.003  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-25 15:25:08.003  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-25 15:25:08.003  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-25 15:25:08.003  3215  7727 D HeadsetStateMachine: Disconnected process message: 10
08-25 15:25:08.003  3215  7727 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 15:25:08.003  3215  7727 D HeadsetStateMachine: Disconnected process message: 11
,08-25 15:25:08.013  3215  7728 D BluetoothMediaBrowser: no now playing list
,08-25 15:25:08.023  3215  7728 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-25 15:25:08.023  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-25 15:25:08.023  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-25 15:25:08.023  3215  3295 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-25 15:25:08.023  3215  3295 I bluedroid: enable
,08-25 15:25:08.033  3215  3298 E bt-btif : Calling BTA_HhEnable
,08-25 15:25:08.033  3215  3298 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-25 15:25:08.033  3215  3298 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-25 15:25:08.033  3215  3298 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-25 15:25:08.033  3215  3298 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,08-25 15:25:08.033  3215  3298 E BluetoothServiceJni: populateRssiValuesNative
08-25 15:25:08.033  3215  3298 I bluedroid: getModelRssiValues
,08-25 15:25:08.033  3215  3298 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-25 15:25:08.033  3215  3298 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-25 15:25:08.043  1019  1019 D SettingsProvider: name = bluetooth_name
,08-25 15:25:08.043  3215  3298 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-25 15:25:08.043  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:08.043  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:08.053  3215  3298 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-25 15:25:08.053  3215  3298 D BluetoothAdapterProperties: Scan Mode:20
08-25 15:25:08.053  3215  3298 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 15:25:08.053  3215  3298 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,08-25 15:25:08.053  3215  3298 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-25 15:25:08.053  3215  3298 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-25 15:25:08.053  3215  3298 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-25 15:25:08.053  3215  3298 E bt-btif : JVenable fails
,08-25 15:25:08.053  3215  3298 D bte_conf: Device ID record 1 : primary
,08-25 15:25:08.053  3215  3298 D bte_conf:   vendorId            = 0075
08-25 15:25:08.053  3215  3298 D bte_conf:   vendorIdSource      = 0001
08-25 15:25:08.053  3215  3298 D bte_conf:   product             = 0100
,08-25 15:25:08.053  3215  3298 D bte_conf:   version             = 0200
08-25 15:25:08.053  3215  3298 D bte_conf:   clientExecutableURL = 
08-25 15:25:08.053  3215  3298 D bte_conf:   serviceDescription  = 
08-25 15:25:08.053  3215  3298 D bte_conf:   documentationURL    = 
08-25 15:25:08.053  3215  3298 D bte_conf: bte_load_did_conf no section named DID2.
08-25 15:25:08.053  3215  3298 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-25 15:25:08.053  3215  3298 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 15:25:08.053  3215  3295 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-25 15:25:08.053  3215  3295 D BluetoothAdapterProperties: ScanMode =  20
,08-25 15:25:08.053  3215  3295 D BluetoothAdapterProperties: State =  11
,08-25 15:25:08.053  1019  1032 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-25 15:25:08.063  3215  3295 D BluetoothAdapterProperties: Setting state to 12
08-25 15:25:08.063  3215  3295 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-25 15:25:08.063  3215  3298 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-25 15:25:08.063  3215  3298 D BluetoothAdapterProperties: Scan Mode:21
08-25 15:25:08.063  3215  3298 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 15:25:08.063  1019  4326 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-25 15:25:08.063  1019  4326 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 15:25:08.063  1019  4326 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 15:25:08.063  1019  4326 D SettingsProvider: selectionArgs: false
08-25 15:25:08.063  1019  4326 D SettingsProvider: selectionArgs: 1002
08-25 15:25:08.063  1019  4326 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 15:25:08.063  1019  4326 D SettingsProvider: ret = -1
08-25 15:25:08.063  3215  3295 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 15:25:08.063  3215  3295 D BluetoothAdapterService: updateAdapterState state is 12
08-25 15:25:08.063  1019  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,08-25 15:25:08.063  1019  1492 W ActivityManager: userId = 0, bbcId = -10000,
08-25 15:25:08.063  1019  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-25 15:25:08.063  1019  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:08.063  1019  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:08.063  3215  3295 D BluetoothAdapterService: Autoconnection is available 
08-25 15:25:08.063  3215  3295 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-25 15:25:08.063  3215  3295 D BluetoothAdapterService: starting service from this receiver
,08-25 15:25:08.073  1019  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:25:08.073  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-25 15:25:08.073  6896  6904 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 15:25:08.073  6896  6904 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 15:25:08.073  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:08.073  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:08.073  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 15:25:08.073  1431  1449 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 15:25:08.073  1431  1449 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 15:25:08.073  3215  3295 I BluetoothAdapterState: Entering On State from state = 11
,08-25 15:25:08.073  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:08.073  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:08.073  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:08.073  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:25:08.073  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:08.073  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:08.073  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:08.073  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:25:08.073  4780  4797 D Bluetoothsap: onBluetoothStateChange: up=true
08-25 15:25:08.073  4780  4797 D Bluetoothsap: Binding service...
,08-25 15:25:08.073  3215  3215 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-25 15:25:08.083  6896  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:25:08.083  3215  3215 I BluetoothPbapService: Handler(): got msg=1
,08-25 15:25:08.083  1019  1081 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-25 15:25:08.093  4780  4797 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-25 15:25:08.093  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:08.093  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:08.093  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:08.093  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:25:08.093  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:08.093  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:08.093  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:08.093  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:25:08.093  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-25 15:25:08.093  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 15:25:08.093  6896  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:25:08.093  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:08.093  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 15:25:08.093  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:08.093  4780  4797 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-25 15:25:08.093  4780  4788 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 15:25:08.093  3215  7735 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-25 15:25:08.093  4780  4780 D Bluetoothsap: BluetoothSAP Proxy object connected
08-25 15:25:08.093  4780  4780 D SapProfile: Bluetooth service connected
08-25 15:25:08.093  4780  4780 D Bluetoothsap: getConnectedDevices()
,08-25 15:25:08.103  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-25 15:25:08.103  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-25 15:25:08.103  3215  7735 D BluetoothSocket: bindListen(): myUserId = 0
08-25 15:25:08.103  3215  7735 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 15:25:08.103  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:08.103  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:08.103  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:08.103  4780  4780 D BluetoothMap: Proxy object connected
,08-25 15:25:08.103  4780  4780 D MapProfile: Bluetooth service connected
08-25 15:25:08.103  4780  4780 D BluetoothMap: getConnectedDevices()
08-25 15:25:08.103  3215  7735 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-25 15:25:08.103  3215  7735 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 15:25:08.103  3215  7735 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 15:25:08.103  3215  7735 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29d75206
08-25 15:25:08.103  3215  7735 D BluetoothSocket: channel: 19
08-25 15:25:08.103  3215  7735 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-25 15:25:08.103  1431  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0,
,08-25 15:25:08.103  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 15:25:08.103  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 15:25:08.103  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:08.103  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:08.103  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:08.113  1431  1457 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 15:25:08.113  1459  1861 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 15:25:08.113  1459  1861 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 15:25:08.113  4780  7736 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 15:25:08.113  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-25 15:25:08.113  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 15:25:08.113  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:08.113  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:08.113  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:08.123  4780  4780 D BluetoothPbap: Proxy object connected
,08-25 15:25:08.123  4780  4780 D PbapServerProfile: Bluetooth service connected
08-25 15:25:08.123  1681  1771 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 15:25:08.123  1681  1771 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 15:25:08.123  1182  3294 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 15:25:08.123  1182  3294 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 15:25:08.123  4780  4788 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 15:25:08.123  4780  4788 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 15:25:08.123  1445  1460 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 15:25:08.123  1445  1460 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 15:25:08.123  1751  1759 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 15:25:08.123  1751  1759 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 15:25:08.123  1019  1049 D BluetoothPan: Binding service...
,08-25 15:25:08.123  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-25 15:25:08.123  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 15:25:08.123  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
,08-25 15:25:08.123  1431  1449 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 15:25:08.123  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 15:25:08.133  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 15:25:08.133  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:08.133  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 15:25:08.133  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:08.133  1431  1449 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 15:25:08.133  1459  1479 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 15:25:08.133  1019  1049 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 15:25:08.133  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 15:25:08.133  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:08.133  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:08.133  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:08.133  1459  1479 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 15:25:08.133  7215  7237 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 15:25:08.133  7215  7237 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 15:25:08.143  4780  4797 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 15:25:08.143  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-25 15:25:08.143  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 15:25:08.143  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:08.143  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:08.143  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:08.143  3215  3352 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 15:25:08.143  3215  3352 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 15:25:08.143  3215  7240 D BluetoothA2dp: onBluetoothStateChange: up=true,
08-25 15:25:08.143  3215  7240 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 15:25:08.143  4780  4780 D BluetoothInputDevice: Proxy object connected
08-25 15:25:08.143  4780  4780 D HidProfile: Bluetooth service connected
,08-25 15:25:08.143  1019  1049 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-25 15:25:08.143  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 15:25:08.143  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:08.143  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:08.143  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:08.153  3215  3215 D BluetoothA2dp: Proxy object connected
,08-25 15:25:08.153  4780  4788 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-25 15:25:08.153  3215  3215 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-25 15:25:08.153  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 15:25:08.153  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 15:25:08.153  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:08.153  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:08.153  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:08.153  4780  4788 E BluetoothHeadset: BluetoothHeadset service is binded
08-25 15:25:08.153  1019  1049 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 15:25:08.153  1019  1049 E BluetoothHeadset: BluetoothHeadset service is binded
08-25 15:25:08.153  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 15:25:08.153  4780  7736 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 15:25:08.153  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-25 15:25:08.153  4780  4780 D HeadsetProfile: Bluetooth service connected
,08-25 15:25:08.153  4780  7736 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 15:25:08.153  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-25 15:25:08.153  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:08.153  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-25 15:25:08.153  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:08.153  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:08.153  1019  1049 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 15:25:08.153  1019  1049 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 15:25:08.153  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-25 15:25:08.153  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 15:25:08.153  1431  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 15:25:08.153  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 15:25:08.153  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 15:25:08.153  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:08.153  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:08.153  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-25 15:25:08.153  4780  4780 D BluetoothA2dp: Proxy object connected
08-25 15:25:08.153  4780  4780 D A2dpProfile: Bluetooth service connected
,08-25 15:25:08.153  1431  1457 E BluetoothHeadset: BluetoothHeadset service is binded
08-25 15:25:08.153  4780  4797 D BluetoothPan: Binding service...
08-25 15:25:08.163  1019  1019 D BluetoothA2dp: Proxy object connected
,08-25 15:25:08.163  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan,
08-25 15:25:08.163  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 15:25:08.163  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:08.163  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:08.163  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:08.163  1019  1049 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 15:25:08.163  1019  1049 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 15:25:08.163  4780  4780 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 15:25:08.163  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-25 15:25:08.163  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-25 15:25:08.163  4780  4780 D PanProfile: Bluetooth service connected
,08-25 15:25:08.163  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:25:08.163  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
,08-25 15:25:08.163  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-25 15:25:08.173  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,08-25 15:25:08.173  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-25 15:25:08.173  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 15:25:08.173  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 15:25:08.173  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:25:08.173  1182  1182 D BluetoothTile:  getBluetoothState : 12
,08-25 15:25:08.173  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 15:25:08.183  1431  1431 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1d023c70, true,
,08-25 15:25:08.183  1879  1879 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 15:25:08.183  1431  1431 D BluetoothHeadset: registerMessageListener
,08-25 15:25:08.183  1019  3774 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 15:25:08.183  1019  1368 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-25 15:25:08.183  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 15:25:08.193  3215  3381 D HeadsetService: registerMessageListener
,08-25 15:25:08.193  4780  4780 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:25:08.193  3215  3381 D HeadsetService: registerMessageListener
08-25 15:25:08.193  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:08.193  3215  7727 D HeadsetStateMachine: Disconnected process message: 70
08-25 15:25:08.193  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-25 15:25:08.193  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-25 15:25:08.193  3215  7727 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@224ff0c7
,08-25 15:25:08.193  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:08.193  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-25 15:25:08.193  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-25 15:25:08.193  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-25 15:25:08.193  4780  4780 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-25 15:25:08.193  4780  4780 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-25 15:25:08.193  4780  4780 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,08-25 15:25:08.193  4780  4780 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-25 15:25:08.203  3215  7727 D HeadsetStateMachine: Disconnected process message: 9
08-25 15:25:08.203  3215  7727 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-25 15:25:08.203  3215  7737 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-25 15:25:08.203   283   676 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-25 15:25:08.203   283   676 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-25 15:25:08.203   283   676 V voice   : voice_set_parameters: exit with code(-2)
,08-25 15:25:08.203   283   676 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-25 15:25:08.203   283   676 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-25 15:25:08.203   283   676 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
,08-25 15:25:08.203   283   676 V audio_hw_primary: adev_set_parameters: exit
08-25 15:25:08.203  3215  7727 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-25 15:25:08.203  3215  7737 D BluetoothSocket: bindListen(): myUserId = 0
,08-25 15:25:08.203  3215  7737 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 15:25:08.203  3215  7737 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
,08-25 15:25:08.213  3215  7737 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 15:25:08.213  3215  7737 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 15:25:08.213  3215  7737 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@385056f4
08-25 15:25:08.213  3215  7737 D BluetoothSocket: channel: 5
,08-25 15:25:08.213  4780  4780 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 15:25:08.213  1019  4326 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-25 15:25:08.213  1019  4326 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 15:25:08.213  1019  4326 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:08.213  1019  4326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:08.213  1019  4326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 15:25:08.223  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 15:25:08.223  4780  4780 D DockEventReceiver: finishStartingService: stopping service
,08-25 15:25:08.223  4780  4780 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 15:25:08.233  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:25:08.233  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-25 15:25:08.233  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
,08-25 15:25:08.233  3215  3215 D BtConfig.SecureMode: isSecureModeOn:false
,08-25 15:25:08.243  1019  3856 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 15:25:08.243  1019  3856 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-25 15:25:08.243  1019  3856 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:08.243  1019  3856 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 15:25:08.243  1019  3856 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:08.243   288   288 E SMD     : DCD OFF
,08-25 15:25:08.253  1019  1032 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-25 15:25:08.263  3215  7742 D BluetoothSocket: bindListen(): myUserId = 0
08-25 15:25:08.263  3215  7742 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 15:25:08.263  3215  7742 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
08-25 15:25:08.263  3215  7742 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 15:25:08.263  3215  7742 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 15:25:08.263  3215  7742 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1095ee60
08-25 15:25:08.263  3215  7742 D BluetoothSocket: channel: 12
08-25 15:25:08.263  3215  7742 I BtOppRfcommListener: Accept thread started.
,08-25 15:25:08.463  1019  1045 W ActivityManager: mDVFSHelper.release(),
,08-25 15:25:09.183  1019  1099 V AlarmManager: waitForAlarm result :4,
,08-25 15:25:09.183   278  1003 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 15:25:09.183   278  1003 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-25 15:25:09.193  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:09.193  1019  1045 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 15:25:09.193  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-25 15:25:09.273  1019  4325 I ActivityManager: Killing 7314:com.sec.pcw.device/1000 (adj 15): empty #21
,08-25 15:25:09.313  1019  3856 I ActivityManager: Killing 7331:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-25 15:25:09.603  1019  3376 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-25 15:25:09.903  1019  3351 D SSRM:n  : SIOP:: AP = 350
,08-25 15:25:10.233   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 15:25:10.903  6896  7047 D BluetoothAdapter: disable()
,08-25 15:25:10.903  1019  1308 D SettingsProvider: name = bluetooth_on
,08-25 15:25:10.903  3215  3295 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-25 15:25:10.903  3215  3295 D BluetoothAdapterProperties: Setting state to 13
08-25 15:25:10.903  3215  3295 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 15:25:10.913  3215  3295 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 15:25:10.913  3215  3295 D BluetoothAdapterService: updateAdapterState state is 13
,08-25 15:25:10.913  1019  3856 W ActivityManager: userId = 0, bbcId = -10000,
08-25 15:25:10.913  1019  3856 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:25:10.913  1019  3856 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:10.913  1019  3856 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 15:25:10.913  1019  3856 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 15:25:10.913  3215  3295 D BluetoothAdapterService: Autoconnection is available 
08-25 15:25:10.913  3215  3295 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-25 15:25:10.913  3215  3295 D BluetoothAdapterService: terminating service from this receiver
,08-25 15:25:10.913  3215  3215 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-25 15:25:10.913  3215  3215 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3cb7ef19, channel: 19, state: LISTENING
08-25 15:25:10.913  3215  3215 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3cb7ef19, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29d75206, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2b809bdemSocket: android.net.LocalSocket@20f431bf impl:android.net.LocalSocketImpl@27db908c fd:FileDescriptor[80]
08-25 15:25:10.913  3215  3215 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@20f431bf impl:android.net.LocalSocketImpl@27db908c fd:FileDescriptor[80]
08-25 15:25:10.913  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-25 15:25:10.913  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:10.913  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:10.913  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:10.923  3215  3295 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 15:25:10.923  3215  3295 D BluetoothAdapterProperties: mDiscovering is false
,08-25 15:25:10.923  1019  4325 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-25 15:25:10.923  3215  3295 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-25 15:25:10.923  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:25:10.923  1019  1019 I InputMethodManagerService: [BT Setting State] State =13
,08-25 15:25:10.933  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,08-25 15:25:10.933  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 15:25:10.933  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:25:10.933  1182  1182 D BluetoothTile:  getBluetoothState : 13
,08-25 15:25:10.943  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 15:25:10.943  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 15:25:10.943  1019  1368 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 15:25:10.943  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-25 15:25:10.943  1019  3856 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-25 15:25:10.953  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ),
,08-25 15:25:10.953  1879  1879 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 15:25:10.953  4780  4780 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:25:10.963  6896  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 15:25:10.963  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:10.963  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:10.963  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:10.963  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:25:10.963  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:10.963  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:10.963  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:10.963  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:25:10.963  6896  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 15:25:10.963  6896  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:25:10.973  6896  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:10.973  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:10.973  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:10.973  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:10.973  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:25:10.973  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 15:25:10.973  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:10.973  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:10.973  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:25:10.973  6896  6896 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 15:25:10.973  6896  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:25:10.973  3215  3298 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-25 15:25:10.973  3215  3298 D BluetoothAdapterProperties: Scan Mode:20
08-25 15:25:10.973  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:10.973  3215  3295 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-25 15:25:10.973  3215  3295 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-25 15:25:10.973  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:10.973  3215  3295 E bt-btif : BTM_SEC_CLR[17]: id 57
08-25 15:25:10.973  3215  7742 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 15:25:10.983  3215  3299 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
08-25 15:25:10.983  3215  3295 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-25 15:25:10.983  3215  3215 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@36cf63d5, channel: 5, state: LISTENING
08-25 15:25:10.983  3215  3215 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@36cf63d5, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@385056f4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@127697eamSocket: android.net.LocalSocket@27c42adb impl:android.net.LocalSocketImpl@33f72978 fd:FileDescriptor[82]
,08-25 15:25:10.983  3215  3215 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@27c42adb impl:android.net.LocalSocketImpl@33f72978 fd:FileDescriptor[82]
08-25 15:25:10.983  3215  3215 I BtOppRfcommListener: stopping Accept Thread
08-25 15:25:10.983  3215  3215 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@39af6851, channel: 12, state: LISTENING
,08-25 15:25:10.983  3215  3215 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@39af6851, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1095ee60, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@11e48b6mSocket: android.net.LocalSocket@26d099b7 impl:android.net.LocalSocketImpl@30316524 fd:FileDescriptor[85]
08-25 15:25:10.983  4780  4780 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 15:25:10.983  3215  3215 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@26d099b7 impl:android.net.LocalSocketImpl@30316524 fd:FileDescriptor[85]
,08-25 15:25:10.983  3215  7742 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-25 15:25:10.983  1019  1492 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-25 15:25:10.993  1019  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 15:25:10.993  3215  3299 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 15:25:10.993  3215  3299 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 15:25:10.993  3215  3299 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 15:25:10.993  3215  3299 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 15:25:10.993  3215  3299 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 15:25:10.993  3215  3299 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-25 15:25:10.993  1019  1492 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:10.993  1019  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:10.993  1019  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 15:25:11.003  4780  4780 D BluetoothPbap: Proxy object disconnected
08-25 15:25:11.003  4780  4780 D PbapServerProfile: Bluetooth service disconnected
,08-25 15:25:11.003  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 15:25:11.003  3215  3215 V BluetoothOppManager: cleanUp...
,08-25 15:25:11.013  4780  4780 D DockEventReceiver: finishStartingService: stopping service
,08-25 15:25:11.013  4780  4780 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 15:25:11.023  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 15:25:11.023  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-25 15:25:11.183  3215  3295 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-25 15:25:11.183  3215  3295 D BtConfig.SecureMode: isSecureModeOn:false
,08-25 15:25:11.183  3215  3295 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-25 15:25:11.183  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-25 15:25:11.183  3215  3295 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
,08-25 15:25:11.183  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-25 15:25:11.183  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-25 15:25:11.183  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-25 15:25:11.183  1019  3856 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 15:25:11.183  1019  3856 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-25 15:25:11.183  1019  3856 W ActivityManager: userId = 0, bbcId = -10000,
08-25 15:25:11.183  1019  3856 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 15:25:11.183  1019  3856 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:11.193  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-25 15:25:11.193  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-25 15:25:11.193  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-25 15:25:11.193  1019  1081 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-25 15:25:11.193  1019  1081 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0,
,08-25 15:25:11.193  1019  1081 W ActivityManager: userId = 0, bbcId = -10000,
08-25 15:25:11.193  1019  1081 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:11.193  1019  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,08-25 15:25:11.193  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-25 15:25:11.193  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-25 15:25:11.203  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-25 15:25:11.203  1019  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:25:11.203  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-25 15:25:11.203  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:11.203  1019  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:11.203  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:11.203  3215  3215 D HeadsetService: Received stop request...Stopping profile...
,08-25 15:25:11.203  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-25 15:25:11.203  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-25 15:25:11.203  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-25 15:25:11.203  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
,08-25 15:25:11.203  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:25:11.203  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-25 15:25:11.203  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:11.203  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:11.203  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:11.203  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-25 15:25:11.203  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-25 15:25:11.203  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-25 15:25:11.213  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-25 15:25:11.213  4780  4780 D HeadsetProfile: Bluetooth service disconnected
,08-25 15:25:11.213  1019  3774 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 15:25:11.213  1019  3774 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 15:25:11.213  1019  3774 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:11.213  3215  3215 D A2dpService: Received stop request...Stopping profile...
08-25 15:25:11.213  3215  7729 D A2dpStateMachine: Exit Disconnected: -1
,08-25 15:25:11.213  1019  3774 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:11.213  1019  3774 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:11.213  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-25 15:25:11.213  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 15:25:11.213  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-25 15:25:11.213  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
,08-25 15:25:11.213  1019  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 15:25:11.213  1019  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 15:25:11.223  1019  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:11.223  1019  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:11.223  1019  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:11.223  1019  1019 D BluetoothA2dp: Proxy object disconnected
08-25 15:25:11.223  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-25 15:25:11.223  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 15:25:11.223  3215  3295 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-25 15:25:11.223  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 15:25:11.223  1019  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:25:11.223  1019  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 15:25:11.223  4780  4780 D BluetoothA2dp: Proxy object disconnected
08-25 15:25:11.223  4780  4780 D A2dpProfile: Bluetooth service disconnected
08-25 15:25:11.223  1019  1487 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:11.223  1019  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:11.223  1019  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:11.223  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-25 15:25:11.223  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 15:25:11.223  3215  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-25 15:25:11.223  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-25 15:25:11.223  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-25 15:25:11.223  3215  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-25 15:25:11.223  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-25 15:25:11.223  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-25 15:25:11.223  3215  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-25 15:25:11.223  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-25 15:25:11.223  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 15:25:11.223  3215  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-25 15:25:11.223  3215  3295 D BluetoothAdapterState: Stopping profile services that were post enabled
08-25 15:25:11.223  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-25 15:25:11.223  3215  3215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 15:25:11.223  3215  3215 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-25 15:25:11.223  3215  3215 D HidService: Received stop request...Stopping profile...
08-25 15:25:11.223  3215  3215 D HidService: Stopping Bluetooth HidService
08-25 15:25:11.223  3215  3215 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 15:25:11.223  3215  3215 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,08-25 15:25:11.223  3215  3215 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 15:25:11.223  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
,08-25 15:25:11.233  3215  3215 D HealthService: Received stop request...Stopping profile...
,08-25 15:25:11.233  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
,08-25 15:25:11.233  4780  4780 D BluetoothInputDevice: Proxy object disconnected
,08-25 15:25:11.233   317   317 I ServiceManager: Waiting for service AtCmdFwd...
08-25 15:25:11.233  4780  4780 D HidProfile: Bluetooth service disconnected
,08-25 15:25:11.233  3215  3215 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-25 15:25:11.233  3215  3215 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-25 15:25:11.233  3215  3215 D PanService: Received stop request...Stopping profile...
,08-25 15:25:11.233  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
,08-25 15:25:11.233  1019  1019 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-25 15:25:11.233  4780  4780 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-25 15:25:11.233  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-25 15:25:11.233  3215  3215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 15:25:11.233  3215  3215 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-25 15:25:11.233  4780  4780 D PanProfile: Bluetooth service disconnected
,08-25 15:25:11.233  3215  3215 D BluetoothMapService: Received stop request...Stopping profile...
,08-25 15:25:11.243  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
,08-25 15:25:11.243  3215  3215 D BluetoothA2dp: Proxy object disconnected
08-25 15:25:11.243  3215  3215 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-25 15:25:11.243  3215  7730 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 15:25:11.243  3215  3215 I GKI_LINUX: GKI_exit_task 2 done
08-25 15:25:11.243  3215  3215 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-25 15:25:11.243  4780  4780 D BluetoothMap: Proxy object disconnected
,08-25 15:25:11.243  3215  3215 D SapService: Received stop request...Stopping profile...
08-25 15:25:11.243  4780  4780 D MapProfile: Bluetooth service disconnected
08-25 15:25:11.243  3215  3215 D SapService: Stopping Bluetooth SapService
08-25 15:25:11.243  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
,08-25 15:25:11.243  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,08-25 15:25:11.243  3215  3215 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-25 15:25:11.243  3215  3215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 15:25:11.243  3215  3215 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-25 15:25:11.243  4780  4780 D Bluetoothsap: BluetoothSAP Proxy object disconnected
,08-25 15:25:11.243  4780  4780 D SapProfile: Bluetooth service disconnected
08-25 15:25:11.243  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-25 15:25:11.243  3215  3215 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-25 15:25:11.243  3215  3215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 15:25:11.243  3215  3215 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-25 15:25:11.243  3215  3215 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 15:25:11.243  3215  3215 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 15:25:11.243  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-25 15:25:11.243  3215  3215 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-25 15:25:11.243  3215  3215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 15:25:11.243  3215  3215 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-25 15:25:11.243  3215  3215 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 15:25:11.243  3215  3215 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-25 15:25:11.253  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-25 15:25:11.253   288   288 E SMD     : DCD OFF
08-25 15:25:11.253  3215  3215 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-25 15:25:11.253  3215  3215 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 15:25:11.253  3215  3215 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-25 15:25:11.253  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-25 15:25:11.253  3215  3215 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-25 15:25:11.253  3215  3215 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-25 15:25:11.253  3215  3215 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-25 15:25:11.253  3215  3295 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-25 15:25:11.253  3215  3295 D BluetoothAdapterProperties: Setting state to 10
08-25 15:25:11.253  3215  3295 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 15:25:11.253  3215  3295 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 15:25:11.253  3215  3295 D BluetoothAdapterService: updateAdapterState state is 10
,08-25 15:25:11.253  3215  3295 D BluetoothAdapterService: Autoconnection is available 
,08-25 15:25:11.253  3215  3295 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-25 15:25:11.253  3215  3295 I BluetoothAdapterState: Entering OffState
,08-25 15:25:11.253  6896  6904 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 15:25:11.253  6896  6904 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 15:25:11.253  6896  6904 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-25 15:25:11.253  6896  6904 D BluetoothLeAdvertiser: Exit stop advertising
08-25 15:25:11.253  6896  6904 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-25 15:25:11.253  6896  6904 D BluetoothLeScanner: Exiting stopAllScan
,08-25 15:25:11.253  1431  3356 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 15:25:11.253  1431  3356 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 15:25:11.263  4780  7736 D Bluetoothsap: onBluetoothStateChange: up=false
,08-25 15:25:11.263  4780  7736 D Bluetoothsap: Unbinding service...
,08-25 15:25:11.263  4780  4797 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 15:25:11.263  1459  1479 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 15:25:11.263  1459  1479 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 15:25:11.263  4780  4788 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 15:25:11.263  1681  1703 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 15:25:11.263  1681  1703 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 15:25:11.263  1182  3294 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 15:25:11.263  1182  3294 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 15:25:11.263  4780  7736 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 15:25:11.263  4780  7736 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 15:25:11.263  1445  1460 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 15:25:11.263  1445  1460 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 15:25:11.263  1751  2292 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 15:25:11.263  1751  2292 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 15:25:11.273  7215  7232 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 15:25:11.273  7215  7232 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 15:25:11.273  4780  4797 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-25 15:25:11.273  3215  3230 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 15:25:11.273  3215  3230 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 15:25:11.273  3215  3227 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 15:25:11.273  4780  7736 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 15:25:11.273  1019  1049 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 15:25:11.273  1019  1049 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 15:25:11.273  1019  1049 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 15:25:11.273  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:25:11.283  1019  1019 I InputMethodManagerService: [BT Setting State] State =10
,08-25 15:25:11.283  1019  1019 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-25 15:25:11.283  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-25 15:25:11.283  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:25:11.283  1182  1182 D BluetoothTile:  getBluetoothState : 10
,08-25 15:25:11.293  1019  3856 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 15:25:11.293  1019  1487 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-25 15:25:11.293  1879  1879 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-25 15:25:11.293  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-25 15:25:11.293  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:11.293  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:11.303  4780  4780 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:25:11.303  4780  4780 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 15:25:11.303  1019  4325 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-25 15:25:11.303  1019  4325 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 15:25:11.303  1019  4325 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:11.303  1019  4325 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:11.303  1019  4325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 15:25:11.313  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 15:25:11.313  4780  4780 D DockEventReceiver: finishStartingService: stopping service
,08-25 15:25:11.313  4780  4780 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 15:25:11.313  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:25:11.313  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-25 15:25:12.233   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 15:25:12.273  1019  1485 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-25 15:25:12.273  1019  1485 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
08-25 15:25:12.273  1019  1485 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-25 15:25:12.273  1019  1485 D BatteryService: stay LED for charging,
08-25 15:25:12.273  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-25 15:25:12.273  1019  1019 I MotionRecognitionService: Plugged
08-25 15:25:12.273  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,08-25 15:25:12.273  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-25 15:25:12.273  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-25 15:25:12.283  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,08-25 15:25:12.283  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-25 15:25:12.303  1182  1182 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-25 15:25:12.303  1182  1182 D SViewCoverView: level :100 plugged : 2
,08-25 15:25:12.303  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-25 15:25:12.303  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-25 15:25:12.303  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-25 15:25:13.233   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 15:25:13.913  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop,
08-25 15:25:13.913  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:25:14.243   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 15:25:14.253   288   288 E SMD     : DCD OFF
,08-25 15:25:15.233   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-25 15:25:16.453  1019  1099 V AlarmManager: waitForAlarm result :4
,08-25 15:25:16.453   278  1003 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 15:25:16.453   278  1003 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-25 15:25:16.473  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:16.473  1019  1045 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 15:25:16.473  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-25 15:25:16.923  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 15:25:16.923  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@26cf2346 added. We now have 6 listener(s)
,08-25 15:25:16.923  6896  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:25:16.923  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 15:25:16.923  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31158907 added. We now have 7 listener(s)
,08-25 15:25:16.923  6896  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:25:16.923  6896  7047 I System.out: IsBluetoothEnabled
,08-25 15:25:16.923  6896  7047 D BluetoothAdapter: disable()
,08-25 15:25:16.923  1019  1308 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-25 15:25:16.933  6896  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:16.933  6896  7047 D BluetoothAdapter: enable()
,08-25 15:25:16.933  1019  1490 W ActivityManager: Permission Denial: getCurrentUser() from pid=6896, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-25 15:25:16.933  1019  1490 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-25 15:25:16.933  1019  1490 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6896, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-25 15:25:16.933  1019  1490 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 15:25:16.933  1019  1490 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-25 15:25:16.933  1019  1490 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-25 15:25:16.933  1019  1490 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-25 15:25:16.933  1019  1490 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-25 15:25:16.933  1019  1490 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 15:25:16.933  1019  1490 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 15:25:16.943  1019  1490 D SettingsProvider: name = bluetooth_on
,08-25 15:25:16.943  1019  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 15:25:16.943  1019  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 15:25:16.953  1019  1049 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-25 15:25:16.953  3215  3295 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-25 15:25:16.953  3215  3295 D BluetoothAdapterProperties: Setting state to 11
,08-25 15:25:16.953  3215  3295 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 15:25:16.963  3215  3295 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 15:25:16.963  3215  3295 D BluetoothAdapterService: updateAdapterState state is 11,
,08-25 15:25:16.963  3215  3295 D BluetoothAdapterService: Autoconnection is available 
,08-25 15:25:16.963  3215  3295 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-25 15:25:16.963  3215  3295 D BtConfig.SecureMode: isSecureModeOn:false
,08-25 15:25:16.963  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-25 15:25:16.963  3215  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-25 15:25:16.963  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-25 15:25:16.963  3215  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-25 15:25:16.963  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-25 15:25:16.963  3215  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
,08-25 15:25:16.963  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 15:25:16.963  3215  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-25 15:25:16.963  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-25 15:25:16.963  3215  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-25 15:25:16.963  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-25 15:25:16.963  3215  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
,08-25 15:25:16.963  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService,
08-25 15:25:16.963  3215  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-25 15:25:16.963  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 15:25:16.963  3215  3295 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
,08-25 15:25:16.963  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 15:25:16.963  3215  3295 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 15:25:16.963  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-25 15:25:16.963  3215  3295 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService,
08-25 15:25:16.963  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-25 15:25:16.963  1019  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-25 15:25:16.963  3215  3295 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService,
08-25 15:25:16.973  1019  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-25 15:25:16.963  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 15:25:16.963  3215  3295 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-25 15:25:16.963  3215  3295 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-25 15:25:16.963  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-25 15:25:16.963  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-25 15:25:16.963  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-25 15:25:16.973  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:16.973  1019  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 15:25:16.973  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:16.973  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-25 15:25:16.973  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-25 15:25:16.973  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-25 15:25:16.973  3215  3215 D HeadsetService: Received start request. Starting profile...
08-25 15:25:16.973  3215  3215 D HeadsetService: start()
08-25 15:25:16.973  3215  3215 D HeadsetStateMachine: make
,08-25 15:25:16.973  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:25:16.973  1019  1019 I InputMethodManagerService: [BT Setting State] State =11
,08-25 15:25:16.983  3215  3215 E HeadsetStateMachine: # of Max HF connection is 2
,08-25 15:25:16.983  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-25 15:25:16.983  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:25:16.983  1182  1182 D BluetoothTile:  getBluetoothState : 11
,08-25 15:25:16.983  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
08-25 15:25:16.993  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-25 15:25:16.993  1019  1491 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 15:25:16.993  1019  1487 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-25 15:25:16.993  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-25 15:25:16.993  1879  1879 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-25 15:25:16.993  4780  4780 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:25:16.993  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:16.993  1019  1308 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 15:25:16.993  1019  1308 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 15:25:17.003  1019  1308 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:17.003  1019  1308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.003  1019  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.003  1019  4326 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-25 15:25:17.003  1019  4326 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-25 15:25:17.003  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-25 15:25:17.003  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 15:25:17.003  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-25 15:25:17.003  1019  4326 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:17.003  1019  4326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.003  1019  4326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-25 15:25:17.003  1019  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 15:25:17.013  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 15:25:17.013  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:17.013  1019  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.013  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.013  1019  4325 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-25 15:25:17.013  1019  4325 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-25 15:25:17.013  1019  4325 W ActivityManager: userId = 0, bbcId = -10000,
08-25 15:25:17.013  1019  4325 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-25 15:25:17.013  1019  4325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom,
08-25 15:25:17.013  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-25 15:25:17.013  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService,
08-25 15:25:17.013  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-25 15:25:17.013  3215  3215 I bluedroid: get_profile_interface handsfree
08-25 15:25:17.023  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 15:25:17.023  1019  1081 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 15:25:17.023  1019  1081 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-25 15:25:17.023  1019  1081 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:17.023  1019  1081 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.023  1019  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.033  3215  3215 E DualScoManager: Dual Sco Manager already instantiated
08-25 15:25:17.033  3215  3215 I DualScoManager: Set HeadsetServiceHelper
08-25 15:25:17.033  3215  3215 D BluetoothAtMessage: createCMTIContentObservers
,08-25 15:25:17.033  1019  3774 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-25 15:25:17.033  1019  3774 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 15:25:17.033  1019  3774 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 15:25:17.033  1019  3774 D SettingsProvider: selectionArgs: false
08-25 15:25:17.033  1019  3774 D SettingsProvider: selectionArgs: 1002
08-25 15:25:17.033  1019  3774 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 15:25:17.033  1019  3774 D SettingsProvider: ret = -1
08-25 15:25:17.033  3215  7758 D HeadsetStateMachine: Enter Disconnected: -2
,08-25 15:25:17.033  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-25 15:25:17.033  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-25 15:25:17.033  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-25 15:25:17.033  3215  3215 D HeadsetService: mStartError = false
08-25 15:25:17.033  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
,08-25 15:25:17.033  3215  3215 D A2dpService: Received start request. Starting profile...
08-25 15:25:17.033  3215  3215 D A2dpService: start()
08-25 15:25:17.033  3215  3215 I bluedroid: get_profile_interface avrcp
,08-25 15:25:17.033  1019  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 15:25:17.033  1019  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 15:25:17.033  4780  4780 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 15:25:17.033  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:17.033  1019  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.033  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.043  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-25 15:25:17.043  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 15:25:17.043  3215  3295 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-25 15:25:17.043  3215  3215 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 15:25:17.043  3215  3215 D Avrcp   : Initialize Media Controller
08-25 15:25:17.043  3215  3215 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-25 15:25:17.043  3215  3215 E Avrcp   : getActiveSessions
08-25 15:25:17.043  3215  3215 D Avrcp   : pick active media Controller
08-25 15:25:17.043  3215  3215 D Avrcp   : Get the active Media Controller 
,08-25 15:25:17.043  1019  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:25:17.043  3215  7758 D HeadsetStateMachine: Clear mHeadsetBrsf
08-25 15:25:17.043  3215  7758 D HeadsetStateMachine: map size, before remove : 0
08-25 15:25:17.043  3215  7758 D HeadsetStateMachine: map size, after remove: 0
,08-25 15:25:17.043  1019  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 15:25:17.043  1019  1492 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:17.043  1019  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 15:25:17.043  1019  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.053  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-25 15:25:17.053  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 15:25:17.053  3215  3295 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-25 15:25:17.053  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:25:17.053  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-25 15:25:17.053  3215  3215 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-25 15:25:17.053  3215  7759 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-25 15:25:17.053  1019  4326 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:25:17.053  1019  4326 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 15:25:17.053  3215  3215 D A2dpStateMachine: make
08-25 15:25:17.053  1019  4326 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:17.053  1019  4326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.053  1019  4326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.063  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 15:25:17.063  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 15:25:17.063  3215  3215 I bluedroid: get_profile_interface a2dp
08-25 15:25:17.063  3215  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-25 15:25:17.063  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-25 15:25:17.063  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-25 15:25:17.063  3215  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-25 15:25:17.063  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-25 15:25:17.063  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-25 15:25:17.063  3215  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-25 15:25:17.063  3215  3295 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-25 15:25:17.063  3215  3295 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-25 15:25:17.063  3215  3295 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-25 15:25:17.063  3215  7761 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-25 15:25:17.063  3215  3295 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 15:25:17.063  3215  3215 E bt-btif : warning : media task started media_task_refcnt 1 
,08-25 15:25:17.063  3215  3215 D A2dpService: mStartError = false
08-25 15:25:17.063  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
,08-25 15:25:17.063  3215  3215 D HeadsetStateMachine: Try to query the phonestate on bind
,08-25 15:25:17.063  3215  7760 D A2dpStateMachine: Enter Disconnected: -2
08-25 15:25:17.063  1431  3356 I Telecom : BluetoothPhoneService: queryPhoneState
,08-25 15:25:17.063  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-25 15:25:17.063  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-25 15:25:17.063  1431  3356 I Telecom : BluetoothPhoneService: Result of Message : true
08-25 15:25:17.063  3215  3215 D HeadsetStateMachine: Proxy object connected
,08-25 15:25:17.063  3215  3215 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-25 15:25:17.063  3215  7758 D HeadsetStateMachine: Disconnected process message: 11
08-25 15:25:17.063  3215  3215 D HidService: Received start request. Starting profile...
,08-25 15:25:17.063  3215  3215 D HidService: start()
08-25 15:25:17.063  3215  3215 I bluedroid: get_profile_interface hidhost
,08-25 15:25:17.063  3215  3215 D HidService: setHidService(): set to: null
08-25 15:25:17.063  3215  3215 D HidService: mStartError = false
08-25 15:25:17.063  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
08-25 15:25:17.063  3215  3215 D HeadsetPhoneState: sendDeviceDataStateChanged
08-25 15:25:17.063  3215  3215 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-25 15:25:17.063  3215  3215 D HealthService: Received start request. Starting profile...
08-25 15:25:17.063  3215  3215 D HealthService: start()
,08-25 15:25:17.063  3215  7758 D HeadsetStateMachine: Disconnected process message: 18
,08-25 15:25:17.073  3215  3215 I bluedroid: get_profile_interface health
,08-25 15:25:17.073  3215  3215 D HealthService: mStartError = false
08-25 15:25:17.073  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
,08-25 15:25:17.073  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-25 15:25:17.073  3215  3215 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-25 15:25:17.073  3215  7758 D HeadsetStateMachine: Disconnected process message: 10
08-25 15:25:17.073  3215  7758 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 15:25:17.073  3215  7758 D HeadsetStateMachine: Disconnected process message: 11
,08-25 15:25:17.073  3215  3215 D PanService: Received start request. Starting profile...
08-25 15:25:17.073  3215  3215 D PanService: start()
08-25 15:25:17.073  3215  3215 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 15:25:17.073  3215  3215 I bluedroid: get_profile_interface pan
08-25 15:25:17.073  3215  3215 D PanService: mStartError = false
08-25 15:25:17.073  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
,08-25 15:25:17.073  3215  3215 D BluetoothMapService: Received start request. Starting profile...
08-25 15:25:17.073  3215  3215 D BluetoothMapService: start()
,08-25 15:25:17.073  3215  3215 D BluetoothMapService: mStartError = false
,08-25 15:25:17.073  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
,08-25 15:25:17.073  3215  3215 D SapService: Received start request. Starting profile...
08-25 15:25:17.073  3215  3215 D SapService: start()
08-25 15:25:17.073  3215  3215 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-25 15:25:17.073  3215  3215 I bluedroid: get_profile_interface sap
08-25 15:25:17.073  3215  3215 D SapService: mStartError = false
08-25 15:25:17.073  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
,08-25 15:25:17.073  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-25 15:25:17.083  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-25 15:25:17.083  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-25 15:25:17.083  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-25 15:25:17.093  3215  7759 D BluetoothMediaBrowser: no now playing list
08-25 15:25:17.093  3215  7759 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-25 15:25:17.093  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-25 15:25:17.093  3215  3215 E BluetoothAdapterService(897486933): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-25 15:25:17.093  3215  3295 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-25 15:25:17.093  3215  3295 I bluedroid: enable
,08-25 15:25:17.103  3215  3298 E bt-btif : Calling BTA_HhEnable
,08-25 15:25:17.103  3215  3298 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-25 15:25:17.103  3215  3298 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-25 15:25:17.103  3215  3298 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-25 15:25:17.103  3215  3298 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-25 15:25:17.103  3215  3298 E BluetoothServiceJni: populateRssiValuesNative
08-25 15:25:17.103  3215  3298 I bluedroid: getModelRssiValues
,08-25 15:25:17.103  3215  3298 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-25 15:25:17.103  3215  3298 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-25 15:25:17.113  1019  1019 D SettingsProvider: name = bluetooth_name
,08-25 15:25:17.113  3215  3298 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-25 15:25:17.113  3215  3298 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-25 15:25:17.113  3215  3298 D BluetoothAdapterProperties: Scan Mode:20
08-25 15:25:17.113  3215  3298 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 15:25:17.113  3215  3298 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-25 15:25:17.113  3215  3298 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-25 15:25:17.113  3215  3298 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-25 15:25:17.113  3215  3298 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-25 15:25:17.113  3215  3298 E bt-btif : JVenable fails
,08-25 15:25:17.113  3215  3298 D bte_conf: Device ID record 1 : primary
08-25 15:25:17.113  3215  3298 D bte_conf:   vendorId            = 0075
08-25 15:25:17.113  3215  3298 D bte_conf:   vendorIdSource      = 0001
08-25 15:25:17.113  3215  3298 D bte_conf:   product             = 0100
08-25 15:25:17.113  3215  3298 D bte_conf:   version             = 0200
08-25 15:25:17.113  3215  3298 D bte_conf:   clientExecutableURL = 
08-25 15:25:17.113  3215  3298 D bte_conf:   serviceDescription  = 
08-25 15:25:17.113  3215  3298 D bte_conf:   documentationURL    = 
08-25 15:25:17.113  3215  3298 D bte_conf: bte_load_did_conf no section named DID2.
08-25 15:25:17.113  3215  3298 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-25 15:25:17.113  3215  3298 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 15:25:17.123  3215  3295 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-25 15:25:17.123  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:17.123  3215  3295 D BluetoothAdapterProperties: ScanMode =  20
08-25 15:25:17.123  3215  3295 D BluetoothAdapterProperties: State =  11
,08-25 15:25:17.123  1019  1487 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-25 15:25:17.123  3215  3295 D BluetoothAdapterProperties: Setting state to 12
,08-25 15:25:17.123  3215  3295 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-25 15:25:17.123  3215  3298 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-25 15:25:17.123  3215  3298 D BluetoothAdapterProperties: Scan Mode:21
08-25 15:25:17.123  3215  3298 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 15:25:17.123  1019  4325 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-25 15:25:17.123  1019  4325 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 15:25:17.123  1019  4325 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 15:25:17.123  1019  4325 D SettingsProvider: selectionArgs: false
08-25 15:25:17.123  1019  4325 D SettingsProvider: selectionArgs: 1002
,08-25 15:25:17.123  1019  4325 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 15:25:17.123  1019  4325 D SettingsProvider: ret = -1
,08-25 15:25:17.123  3215  3295 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 15:25:17.123  3215  3295 D BluetoothAdapterService: updateAdapterState state is 12
,08-25 15:25:17.133  1019  3856 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:25:17.133  1019  3856 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 15:25:17.133  1019  3856 W ActivityManager: userId = 0, bbcId = -10000,
08-25 15:25:17.133  1019  3856 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.133  1019  3856 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.133  6896  6908 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 15:25:17.133  6896  6908 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 15:25:17.133  3215  3295 D BluetoothAdapterService: Autoconnection is available 
08-25 15:25:17.133  3215  3295 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-25 15:25:17.133  3215  3295 D BluetoothAdapterService: starting service from this receiver
,08-25 15:25:17.143  1019  4325 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:25:17.143  1019  4325 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-25 15:25:17.143  1431  1449 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 15:25:17.143  1431  1449 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 15:25:17.143  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:17.143  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:17.143  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:17.143  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:25:17.143  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:17.143  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:17.143  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:17.143  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:25:17.143  4780  7736 D Bluetoothsap: onBluetoothStateChange: up=true
08-25 15:25:17.143  4780  7736 D Bluetoothsap: Binding service...
,08-25 15:25:17.143  6896  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:25:17.143  1019  4325 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:17.143  1019  4325 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.143  1019  4325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.153  3215  3215 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-25 15:25:17.153  3215  3215 I BluetoothPbapService: Handler(): got msg=1
,08-25 15:25:17.153  3215  3295 I BluetoothAdapterState: Entering On State from state = 11
08-25 15:25:17.153  1019  1032 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-25 15:25:17.153  4780  7736 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-25 15:25:17.163  3215  7766 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-25 15:25:17.173  3215  7766 D BluetoothSocket: bindListen(): myUserId = 0
,08-25 15:25:17.173  3215  7766 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 15:25:17.173  3215  7766 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-25 15:25:17.173  3215  7766 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 15:25:17.173  3215  7766 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 15:25:17.173  3215  7766 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c824769
08-25 15:25:17.173  3215  7766 D BluetoothSocket: channel: 19
08-25 15:25:17.173  3215  7766 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-25 15:25:17.253   288   288 E SMD     : DCD OFF
,08-25 15:25:17.303  1019  1049 I art     : Explicit concurrent mark sweep GC freed 62232(3MB) AllocSpace objects, 7(113KB) LOS objects, 33% free, 22MB/34MB, paused 2.355ms total 151.099ms
08-25 15:25:17.303  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-25 15:25:17.303  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 15:25:17.303  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:17.303  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.303  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.303  4780  7736 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-25 15:25:17.303  4780  4788 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 15:25:17.313  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-25 15:25:17.313  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 15:25:17.313  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:17.313  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.313  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.313  4780  4780 D Bluetoothsap: BluetoothSAP Proxy object connected
08-25 15:25:17.313  4780  4780 D SapProfile: Bluetooth service connected
08-25 15:25:17.313  4780  4780 D Bluetoothsap: getConnectedDevices()
,08-25 15:25:17.313  1431  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 15:25:17.313  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 15:25:17.313  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 15:25:17.313  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:17.313  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.313  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.313  4780  4780 D BluetoothMap: Proxy object connected
08-25 15:25:17.313  1431  1457 E BluetoothHeadset: BluetoothHeadset service is binded
08-25 15:25:17.313  4780  4780 D MapProfile: Bluetooth service connected
08-25 15:25:17.313  4780  4780 D BluetoothMap: getConnectedDevices()
,08-25 15:25:17.323  1459  2494 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 15:25:17.323  1459  2494 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 15:25:17.323  4780  4788 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 15:25:17.323  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-25 15:25:17.323  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 15:25:17.323  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:17.323  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.323  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.323  1681  4466 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 15:25:17.323  1681  4466 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 15:25:17.323  1182  3294 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 15:25:17.323  1182  3294 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 15:25:17.323  4780  4797 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 15:25:17.323  4780  4797 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 15:25:17.323  4780  4780 D BluetoothPbap: Proxy object connected
08-25 15:25:17.323  4780  4780 D PbapServerProfile: Bluetooth service connected
08-25 15:25:17.323  1445  1460 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 15:25:17.323  1445  1460 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 15:25:17.323  1751  1759 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 15:25:17.323  1751  1759 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 15:25:17.323  1019  1049 D BluetoothPan: Binding service...
,08-25 15:25:17.323  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-25 15:25:17.323  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0,
,08-25 15:25:17.333  1431  3356 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 15:25:17.333  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 15:25:17.333  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 15:25:17.333  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 15:25:17.333  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:17.333  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.333  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.333  1431  3356 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 15:25:17.333  1459  2494 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 15:25:17.333  1019  1049 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 15:25:17.333  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 15:25:17.333  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:17.333  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.333  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.333  1459  2494 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 15:25:17.333  7215  7237 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 15:25:17.343  7215  7237 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 15:25:17.343  4780  4797 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 15:25:17.343  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-25 15:25:17.343  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 15:25:17.343  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:17.343  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.343  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.343  3215  3381 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 15:25:17.343  3215  3381 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 15:25:17.343  3215  3230 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 15:25:17.343  4780  4780 D BluetoothInputDevice: Proxy object connected
08-25 15:25:17.343  4780  4780 D HidProfile: Bluetooth service connected
08-25 15:25:17.343  3215  3230 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 15:25:17.343  1019  1049 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-25 15:25:17.343  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 15:25:17.343  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:17.343  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.343  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.343  3215  3215 D BluetoothA2dp: Proxy object connected
08-25 15:25:17.343  3215  3215 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-25 15:25:17.343  4780  4788 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 15:25:17.353  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 15:25:17.353  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-25 15:25:17.353  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:17.353  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.353  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.353  4780  4788 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 15:25:17.353  4780  4780 D HeadsetProfile: Bluetooth service connected
08-25 15:25:17.353  1019  1049 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 15:25:17.353  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 15:25:17.353  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-25 15:25:17.353  1019  1049 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 15:25:17.353  4780  4797 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 15:25:17.353  4780  4797 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 15:25:17.353  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-25 15:25:17.353  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 15:25:17.353  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:17.353  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.353  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.353  1019  1049 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 15:25:17.353  1019  1049 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-25 15:25:17.353  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-25 15:25:17.353  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-25 15:25:17.353  1019  1019 D BluetoothA2dp: Proxy object connected
,08-25 15:25:17.353  1431  1449 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 15:25:17.353  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 15:25:17.363  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 15:25:17.363  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:17.363  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.363  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.363  1431  1449 E BluetoothHeadset: BluetoothHeadset service is binded
08-25 15:25:17.363  4780  7767 D BluetoothPan: Binding service...
08-25 15:25:17.363  4780  4780 D BluetoothA2dp: Proxy object connected
08-25 15:25:17.363  4780  4780 D A2dpProfile: Bluetooth service connected
,08-25 15:25:17.363  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-25 15:25:17.363  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 15:25:17.363  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:17.363  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.363  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.363  1019  1049 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 15:25:17.363  1019  1049 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 15:25:17.363  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-25 15:25:17.363  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-25 15:25:17.363  4780  4780 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 15:25:17.363  4780  4780 D PanProfile: Bluetooth service connected
,08-25 15:25:17.363  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:25:17.363  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
08-25 15:25:17.363  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-25 15:25:17.373  1431  1431 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@36fe0be9, true
,08-25 15:25:17.373  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,08-25 15:25:17.373  1431  1431 D BluetoothHeadset: registerMessageListener
,08-25 15:25:17.373  1879  1879 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 15:25:17.373  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-25 15:25:17.373  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:25:17.373  1182  1182 D BluetoothTile:  getBluetoothState : 12
,08-25 15:25:17.383  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 15:25:17.383  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:17.383  3215  3227 D HeadsetService: registerMessageListener
,08-25 15:25:17.383  3215  3227 D HeadsetService: registerMessageListener
,08-25 15:25:17.383  3215  7758 D HeadsetStateMachine: Disconnected process message: 70
08-25 15:25:17.383  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-25 15:25:17.383  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-25 15:25:17.383  3215  7758 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@38d422fa
,08-25 15:25:17.383  1019  1032 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ),
,08-25 15:25:17.383  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-25 15:25:17.383  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-25 15:25:17.383  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-25 15:25:17.383  1019  1485 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-25 15:25:17.393  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 15:25:17.393  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-25 15:25:17.393  4780  4780 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:25:17.393  3215  7768 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-25 15:25:17.393  1182  1722 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 15:25:17.393  4780  4780 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-25 15:25:17.393  4780  4780 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-25 15:25:17.393  4780  4780 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-25 15:25:17.393  4780  4780 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-25 15:25:17.393  3215  7768 D BluetoothSocket: bindListen(): myUserId = 0
08-25 15:25:17.393  3215  7768 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 15:25:17.393  3215  7758 D HeadsetStateMachine: Disconnected process message: 9
08-25 15:25:17.393  3215  7758 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-25 15:25:17.393  3215  7768 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-25 15:25:17.393  3215  7768 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 15:25:17.393  3215  7768 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 15:25:17.393  3215  7768 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c5740ab
,08-25 15:25:17.403   283  1629 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-25 15:25:17.403   283  1629 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-25 15:25:17.403   283  1629 V voice   : voice_set_parameters: exit with code(-2)
08-25 15:25:17.403   283  1629 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-25 15:25:17.403   283  1629 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-25 15:25:17.403   283  1629 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-25 15:25:17.403   283  1629 V audio_hw_primary: adev_set_parameters: exit
08-25 15:25:17.403  3215  7768 D BluetoothSocket: channel: 5
08-25 15:25:17.403  3215  7758 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-25 15:25:17.403  4780  4780 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 15:25:17.403  1019  1368 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-25 15:25:17.403  1019  1368 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 15:25:17.403  1019  1368 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:17.403  1019  1368 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.403  1019  1368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 15:25:17.413  1681  1681 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 15:25:17.423  4780  4780 D DockEventReceiver: finishStartingService: stopping service
,08-25 15:25:17.423  4780  4780 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 15:25:17.423  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 15:25:17.423  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-25 15:25:17.433  3215  3215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@357e9055
,08-25 15:25:17.433  3215  3215 D BtConfig.SecureMode: isSecureModeOn:false
,08-25 15:25:17.433  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 15:25:17.433  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-25 15:25:17.433  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:17.433  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:17.433  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 15:25:17.443  1019  3856 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-25 15:25:17.453  3215  7773 D BluetoothSocket: bindListen(): myUserId = 0
,08-25 15:25:17.453  3215  7773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 15:25:17.453  3215  7773 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[87]}
08-25 15:25:17.453  3215  7773 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 15:25:17.453  3215  7773 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 15:25:17.453  3215  7773 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f473c87
,08-25 15:25:17.453  3215  7773 D BluetoothSocket: channel: 12
08-25 15:25:17.453  3215  7773 I BtOppRfcommListener: Accept thread started.
,08-25 15:25:17.963  6896  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:17.963  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:17.963  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:17.963  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 15:25:17.963  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:17.963  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:17.963  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:17.963  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 15:25:17.963  6896  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:25:17.963  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:25:17.963  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3855aa34 added. We now have 8 listener(s)
08-25 15:25:17.963  6896  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:25:17.973  1019  1081 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-25 15:25:17.973  1019  1081 D WifiService: setWifiEnabled: false pid=6896, uid=10170,
08-25 15:25:17.973  1019  1081 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 15:25:17.973  1019  1081 D SecContentProvider2: mCursor = null
08-25 15:25:17.973  1019  1081 D SettingsProvider: name = wifi_on,
,08-25 15:25:17.973  6896  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:17.973  1019  3856 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-25 15:25:17.973  1019  3856 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 15:25:17.973  1019  3856 D SecContentProvider2: mCursor = null
,08-25 15:25:17.983  1019  3856 D WifiService: setWifiEnabled: true pid=6896, uid=10170
,08-25 15:25:17.983  1019  3856 W ActivityManager: Permission Denial: getCurrentUser() from pid=6896, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-25 15:25:17.983  1019  3856 W WifiService: Failed getting userId using ActivityManagerNative
08-25 15:25:17.983  1019  3856 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6896, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-25 15:25:17.983  1019  3856 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 15:25:17.983  1019  3856 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-25 15:25:17.983  1019  3856 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-25 15:25:17.983  1019  3856 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-25 15:25:17.983  1019  3856 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-25 15:25:17.983  1019  3856 D SettingsProvider: name = wifi_on
,08-25 15:25:17.993  1019  1130 E WifiHW  : ##################### set firmware type 0 #####################
,08-25 15:25:18.303  1019  1047 D Tethering: interfaceAdded wlan0
,08-25 15:25:18.313  1019  1133 E Tethering: No numeric data
,08-25 15:25:18.313  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-25 15:25:18.313  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:25:18.323  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 15:25:18.323  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 15:25:18.323  1019  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 15:25:18.323  1019  1133 D Tethering: clearTetheredNotification()
,08-25 15:25:18.323  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:18.323  1019  1127 V NetworkStats: performPollLocked() took 8ms
,08-25 15:25:18.323  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 15:25:18.323  1182  1182 D HotspotTile: updateTetherState():false, false
,08-25 15:25:18.323  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
08-25 15:25:18.323  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-25 15:25:18.333  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 15:25:18.333  1019  1133 D Tethering: InitialState.processMessage what=4
,08-25 15:25:18.333  1019  1047 D Tethering: interfaceAdded p2p0
,08-25 15:25:18.333  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:18.333  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:18.333  1019  1133 E Tethering: No numeric data
,08-25 15:25:18.333  1019  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-25 15:25:18.343  1019  1133 D Tethering: clearTetheredNotification()
,08-25 15:25:18.343  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit,
08-25 15:25:18.343  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
08-25 15:25:18.343  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 15:25:18.343  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 15:25:18.343  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 15:25:18.343  1182  1182 D HotspotTile: updateTetherState():false, false
08-25 15:25:18.343   278  1008 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-25 15:25:18.343  1019  1047 D Tethering: p2p0 is not a tetherable iface, ignoring
08-25 15:25:18.343   278  1008 D SoftapController: Softap fwReload - Ok
,08-25 15:25:18.343  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false,
08-25 15:25:18.353  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 15:25:18.343  1019  1047 D Tethering: interfaceStatusChanged p2p0, false,
08-25 15:25:18.353  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:18.353  1019  1127 V NetworkStats: performPollLocked() took 9ms
,08-25 15:25:18.353   278  1008 D CommandListener: Setting iface cfg
08-25 15:25:18.353   278  1008 D CommandListener: Trying to bring down wlan0
08-25 15:25:18.353  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:18.353  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:25:18.353   278  1008 D CommandListener: Clearing all IP addresses on wlan0
,08-25 15:25:18.363  1019  1130 E WifiHW  : supplicant_name : p2p_supplicant
,08-25 15:25:18.403  7786  7786 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-25 15:25:18.403  7786  7786 I wpa_supplicant: Successfully initialized wpa_supplicant
08-25 15:25:18.403  7786  7786 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-25 15:25:18.413  7786  7786 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-25 15:25:18.413   362   362 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7786
08-25 15:25:18.413   362   362 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-25 15:25:18.413  7786  7786 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-25 15:25:18.413  7786  7786 I wpa_supplicant: ssSupport state is = 1
08-25 15:25:18.413  7786  7786 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-25 15:25:18.413  7786  7786 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-25 15:25:18.413   362   362 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7786
08-25 15:25:18.413   362   362 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-25 15:25:18.463  1019  1130 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-25 15:25:18.483  4780  4780 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 15:25:18.483  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-25 15:25:18.483  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:25:18.483  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 15:25:18.483  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:18.483  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-25 15:25:18.483  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:18.483  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:18.483  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 15:25:18.483  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-25 15:25:18.483  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-25 15:25:18.483  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 15:25:18.483  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-25 15:25:18.483  1019  1487 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 15:25:18.483  1182  1182 D HotspotTile: onReceive : 2, 0
08-25 15:25:18.483  1019  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 15:25:18.493  1019  1487 W ActivityManager: userId = 0, bbcId = -10000,
08-25 15:25:18.493  1019  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:18.493  1019  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 15:25:18.493  1630  1630 I Hs20UtilService: Starting #19
08-25 15:25:18.493  1630  1651 I Hs20UtilService: Message received 5011
,08-25 15:25:18.493  7111  7111 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 15:25:18.493  7111  7111 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 15:25:18.493  7111  7111 D SecurityLogAgent: StateMachine : Current State = 1
08-25 15:25:18.493  7111  7111 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 15:25:18.573   362   362 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-25 15:25:18.573  7786  7786 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-25 15:25:18.623  7786  7786 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-25 15:25:18.623  7786  7786 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-25 15:25:18.633  7786  7786 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-25 15:25:18.633   362   362 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7786
,08-25 15:25:18.633   362   362 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-25 15:25:18.633  7786  7786 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-25 15:25:18.633  7786  7786 I wpa_supplicant: ssSupport state is = 1
08-25 15:25:18.633  7786  7786 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-25 15:25:18.633  7786  7786 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 15:25:18.633  7786  7786 E wpa_supplicant: SIM READ ERROR
08-25 15:25:18.633  7786  7786 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 15:25:18.633  7786  7786 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 15:25:18.633  7786  7786 E wpa_supplicant: SIM READ ERROR
08-25 15:25:18.633  7786  7786 I wpa_supplicant: Blacklist: Clear (all) ,
08-25 15:25:18.633  7786  7786 I wpa_supplicant: wpa_default_ap_write_once
08-25 15:25:18.633  7786  7786 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-25 15:25:18.633  7786  7786 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 15:25:18.633  7786  7786 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-25 15:25:18.633  7786  7786 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-25 15:25:18.633  7786  7786 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-25 15:25:18.633  7786  7786 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-25 15:25:18.633  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 15:25:18.633  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-25 15:25:18.633  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 15:25:18.723  7786  7786 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-25 15:25:18.873  7786  7786 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-25 15:25:18.873  7786  7786 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-25 15:25:18.883  7786  7786 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-25 15:25:18.883   362   362 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7786
08-25 15:25:18.883   362   362 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-25 15:25:18.883  7786  7786 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-25 15:25:18.883  7786  7786 I wpa_supplicant: ssSupport state is = 1
08-25 15:25:18.883  7786  7786 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-25 15:25:18.893  7786  7786 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-25 15:25:18.903  7786  7786 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-25 15:25:18.903   362   362 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7786
08-25 15:25:18.903   362   362 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
,08-25 15:25:18.903  7786  7786 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-25 15:25:18.903  7786  7786 I wpa_supplicant: ssSupport state is = 1
08-25 15:25:18.903  7786  7786 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-25 15:25:18.903  7786  7786 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-25 15:25:18.903  7786  7786 E wpa_supplicant: SIM READ ERROR,
08-25 15:25:18.903  7786  7786 I wpa_supplicant: wpa_default_ap_write_once
08-25 15:25:18.903  7786  7786 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
,08-25 15:25:18.903  7786  7786 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-25 15:25:18.913  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false,
08-25 15:25:18.913  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 15:25:18.913  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-25 15:25:18.913  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false,
08-25 15:25:18.913  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 15:25:18.913  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,08-25 15:25:18.953  7786  7786 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-25 15:25:18.953  7786  7786 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-25 15:25:19.103  7786  7786 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-25 15:25:19.103  7786  7786 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-25 15:25:19.103  7786  7786 I wpa_supplicant: Skip scan - bUseNetwork false
,08-25 15:25:19.113  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-25 15:25:19.113  1019  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-25 15:25:19.113  7786  7786 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-25 15:25:19.113  7786  7786 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 15:25:19.113  7786  7786 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-25 15:25:19.113  7786  7786 E wpa_supplicant: SIM READ ERROR
08-25 15:25:19.113  7786  7786 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 15:25:19.143  7786  7786 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-25 15:25:19.153  7786  7786 I wpa_supplicant: Skip scan - bUseNetwork false
,08-25 15:25:19.153  4780  4780 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 15:25:19.163  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-25 15:25:19.163  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:25:19.163  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 15:25:19.163  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:19.163  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:19.163  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:19.163  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:19.163  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 15:25:19.163  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-25 15:25:19.163  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-25 15:25:19.163  1182  1722 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-25 15:25:19.163  1182  1182 D HotspotTile: onReceive : 3, 0
08-25 15:25:19.163  1019  3856 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 15:25:19.163  1019  3856 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 15:25:19.163  1019  1130 D WifiConfigStore: Loading config and enabling all networks 
,08-25 15:25:19.163  1019  3856 W ActivityManager: userId = 0, bbcId = -10000
,08-25 15:25:19.163  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:19.163  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:19.163  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:19.163  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:19.163  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:19.163  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:19.163  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:19.163  6896  6896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:25:19.173  1019  3856 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:19.173  6896  6896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:25:19.173  1019  3856 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 15:25:19.173  1019  1130 E WifiConfigStore: Not a HS20
,08-25 15:25:19.173  7111  7111 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-25 15:25:19.173  7111  7111 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 15:25:19.173  7111  7111 D SecurityLogAgent: StateMachine : Current State = 1
08-25 15:25:19.173  7111  7111 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 15:25:19.173  1630  1630 I Hs20UtilService: Starting #20
,08-25 15:25:19.173  1630  1651 I Hs20UtilService: Message received 5011
,08-25 15:25:19.183  1019  1130 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-25 15:25:19.183  1019  1130 D WifiNative-wlan0: callSECApiBoolean - ID [13],
08-25 15:25:19.183  7786  7786 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
,08-25 15:25:19.183  7786  7786 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-25 15:25:19.183  7786  7786 I wpa_supplicant: reset timer : RESET_TIMER 0
08-25 15:25:19.183  7786  7786 I wpa_supplicant: P2P: Current p2p state = IDLE
08-25 15:25:19.183  7786  7786 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-25 15:25:19.183  7786  7786 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-25 15:25:19.183  7786  7786 I wpa_supplicant: First Scan Start,
08-25 15:25:19.183  7786  7786 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-25 15:25:19.183  1019  1130 D WifiNative-wlan0: Setting external_sim to 1
08-25 15:25:19.183  1019  1130 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 15:25:19.183  1019  1130 I WifiNative-HAL: startHal,
08-25 15:25:19.183  1019  1130 E wifi    : getStaticLongField sWifiHalHandle 0x9f49c88c
08-25 15:25:19.183  1019  1130 I WifiNative-HAL: Could not start hal
08-25 15:25:19.183  7288  7288 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 15:25:19.183  1019  1130 E WifiNative-wlan0: do suspend true
,08-25 15:25:19.193  1019  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-25 15:25:19.193  1019  1129 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-25 15:25:19.193  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 3
,08-25 15:25:19.193   278  1008 D CommandListener: Setting iface cfg
08-25 15:25:19.193   278  1008 D CommandListener: Trying to bring up p2p0
08-25 15:25:19.193  1019  1129 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 15:25:19.193  1019  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-25 15:25:19.193  1019  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-25 15:25:19.193  1019  1130 E WifiNative-wlan0: invaild command id : 215
,08-25 15:25:19.193  1019  1129 D WifiP2pService: P2pEnablingState
08-25 15:25:19.193  1019  1153 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:25:19.193  1019  1153 I WifiNative-HAL: startHal
08-25 15:25:19.193  1019  1153 E wifi    : getStaticLongField sWifiHalHandle 0x9e45c9bc
08-25 15:25:19.193  1019  1153 I WifiNative-HAL: Could not start hal
08-25 15:25:19.193  1019  1153 E WifiScanningService: could not start HAL
,08-25 15:25:19.193  1019  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-25 15:25:19.193  1019  1129 D WifiP2pService: P2pEnablingState{ what=147457 }
08-25 15:25:19.193  1019  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-25 15:25:19.193  1019  1130 E WifiNative-wlan0: invaild command id : 215
,08-25 15:25:19.193  1019  1019 D RttService: SCAN_AVAILABLE : 3
08-25 15:25:19.193  1019  1154 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 15:25:19.193  1019  1129 D WifiP2pService: P2p socket connection successful
,08-25 15:25:19.193  7786  7786 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-25 15:25:19.193  7786  7786 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-25 15:25:19.193  1019  1129 D WifiP2pService: P2pEnabledState
,08-25 15:25:19.193  7786  7786 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-25 15:25:19.193  1019  1130 E WifiStateMachine: Failed to set frequency band 0
,08-25 15:25:19.193  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 15:25:19.193  1019  1130 D SecContentProvider2: mCursor = null
,08-25 15:25:19.203  1019  1129 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-25 15:25:19.203  1019  1132 E ConnectivityService: updateNetworkInfo()
,08-25 15:25:19.203  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-25 15:25:19.203  1019  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-25 15:25:19.203  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 15:25:19.203  1019  1050 D WifiDisplayController: disconnect
08-25 15:25:19.203  1019  1050 D WifiDisplayController: updateConnection
08-25 15:25:19.203  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 15:25:19.203  1019  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-25 15:25:19.203  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 15:25:19.203  1019  1130 D SecContentProvider2: mCursor = null
,08-25 15:25:19.203  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-25 15:25:19.203  1019  1368 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-25 15:25:19.203  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-25 15:25:19.203  1019  1129 D WifiNative-p2p0: p2pGetDeviceAddress
08-25 15:25:19.203  1019  1129 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-25 15:25:19.203  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 15:25:19.203  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
08-25 15:25:19.203  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 15:25:19.203  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-25 15:25:19.213  4780  4780 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-25 15:25:19.213  4780  4780 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 15:25:19.213  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 15:25:19.213  1019  1129 D WifiP2pService: DeviceAddress: 0a:75:42
,08-25 15:25:19.213  1019  1050 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-25 15:25:19.213  1019  1050 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-25 15:25:19.213  1019  1050 D WifiDisplayController:  primary type: 10-0050F204-5
08-25 15:25:19.213  1019  1050 D WifiDisplayController:  secondary type: null
08-25 15:25:19.213  1019  1050 D WifiDisplayController:  wps: 0
08-25 15:25:19.213  1019  1050 D WifiDisplayController:  grpcapab: 0
08-25 15:25:19.213  1019  1050 D WifiDisplayController:  devcapab: 0
08-25 15:25:19.213  1019  1050 D WifiDisplayController:  status: 3
08-25 15:25:19.213  1019  1050 D WifiDisplayController:  wfdInfo: null
08-25 15:25:19.213  1019  1050 D WifiDisplayController:  groupownerAddress: null
08-25 15:25:19.213  1019  1050 D WifiDisplayController:  GOdeviceName: null
08-25 15:25:19.213  1019  1050 D WifiDisplayController:  interfaceAddress: 
08-25 15:25:19.213  1019  1050 D WifiDisplayController:  SConnectInfo : null
,08-25 15:25:19.213  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 15:25:19.213  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 15:25:19.213  4780  4780 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 15:25:19.213  4780  4873 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 15:25:19.223  7669  7669 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 15:25:19.223  7669  7669 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-25 15:25:19.223  7669  7669 D FileShare-Client: Outbound.stopDelayTimer - 
,08-25 15:25:19.223  7273  7273 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 15:25:19.233  1019  1129 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-25 15:25:19.233  1019  1129 D WifiP2pService: InactiveState
,08-25 15:25:19.233  1019  1129 D WifiP2pService: InactiveState{ what=143376 }
,08-25 15:25:19.233  1019  1129 D WifiP2pService: P2pEnabledState{ what=143376 }
08-25 15:25:19.233  7786  7786 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-25 15:25:19.233  1019  1129 D WifiP2pService: InactiveState{ what=143376 }
08-25 15:25:19.233  1019  1129 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-25 15:25:19.323  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false,
08-25 15:25:19.323  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 15:25:19.323  1019  1047 D Tethering: interfaceStatusChanged p2p0, false,
,08-25 15:25:19.923  1019  3351 D SSRM:n  : SIOP:: AP = 320
,08-25 15:25:20.003  6896  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 15:25:20.003  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:20.003  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:20.003  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:20.003  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:20.003  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:20.003  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:20.003  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:25:20.003  6896  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:25:20.013  6896  7047 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-25 15:25:20.013  6896  7047 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-25 15:25:20.013  6896  7047 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9d0e14b Bundle[{}]
,08-25 15:25:20.013  6896  7047 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 15:25:20.013  6896  7047 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-25 15:25:20.013  6896  7047 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-25 15:25:20.013  6896  7047 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-25 15:25:20.013  6896  7047 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-25 15:25:20.023  6896  7047 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 15:25:20.023  6896  7047 I System.out: Running OutgoingSocketThread
,08-25 15:25:20.023  6896  7795 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1380)
,08-25 15:25:20.033  6896  7795 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47547
08-25 15:25:20.033  6896  7795 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-25 15:25:20.253   288   288 E SMD     : DCD OFF,
,08-25 15:25:20.463  7786  7786 I wpa_supplicant: nl80211: Received scan results (31 BSSes),
08-25 15:25:20.463  7786  7786 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-25 15:25:20.463  7786  7786 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-25 15:25:20.463  7786  7786 I wpa_supplicant: Trying to associate with  'G700'
08-25 15:25:20.463  7786  7786 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-25 15:25:20.463  7786  7786 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-25 15:25:20.463  1019  7792 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-25 15:25:20.473  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 15:25:20.473  1019  1130 D SecContentProvider2: mCursor = null
,08-25 15:25:20.573  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 15:25:20.573  7786  7786 E wpa_supplicant: Cmd 35605 not handled
,08-25 15:25:20.573  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-25 15:25:20.573  7786  7786 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-25 15:25:20.573  7786  7786 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-25 15:25:20.573  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 15:25:20.573  7786  7786 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-25 15:25:20.573  7786  7786 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030,
08-25 15:25:20.573  7786  7786 I wpa_supplicant: Associated with F4.99.3E
,08-25 15:25:20.573  7786  7786 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
,08-25 15:25:20.573  7786  7786 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE,
08-25 15:25:20.573  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 15:25:20.573  7786  7786 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-25 15:25:20.573  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 15:25:20.573  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 15:25:20.573  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-25 15:25:20.573  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-25 15:25:20.573  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 15:25:20.573  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
08-25 15:25:20.573  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, true
08-25 15:25:20.573  1019  1047 D Tethering: interfaceStatusChanged wlan0, true
,08-25 15:25:20.583  1019  1133 E Tethering: No numeric data
,08-25 15:25:20.583  1019  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-25 15:25:20.583  1019  1133 D Tethering: clearTetheredNotification()
,08-25 15:25:20.583  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-25 15:25:20.583  1019  1130 D SecContentProvider2: mCursor = null,
,08-25 15:25:20.583  7786  7786 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-25 15:25:20.583  7786  7786 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-25 15:25:20.583  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:20.583  1019  1127 V NetworkStats: performPollLocked(flags=0x1),
08-25 15:25:20.583  7786  7786 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-25 15:25:20.583  7786  7786 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-25 15:25:20.583  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 15:25:20.583  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 15:25:20.583  7786  7786 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 15:25:20.593  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 15:25:20.593  7786  7786 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-25 15:25:20.593  1182  1182 D HotspotTile: updateTetherState():false, false
08-25 15:25:20.593  7786  7786 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-25 15:25:20.593  1019  1127 V NetworkStats: performPollLocked() took 8ms
08-25 15:25:20.593  7786  7786 I wpa_supplicant: Blacklist: Clear (temp) 
08-25 15:25:20.593  7786  7786 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-25 15:25:20.593  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 15:25:20.593  1019  1130 D SecContentProvider2: mCursor = null
08-25 15:25:20.593  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:20.593  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, true
,08-25 15:25:20.593  1019  1047 D Tethering: interfaceStatusChanged wlan0, true
08-25 15:25:20.593  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-25 15:25:20.593  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:20.593  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:25:20.603  1019  1130 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-25 15:25:20.613  1019  1130 E WifiConfigStore: setLastSelectedConfiguration -1
,08-25 15:25:20.613  1019  1130 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-25 15:25:20.613  1019  1132 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-25 15:25:20.613  1019  1132 E ConnectivityService: updateNetworkInfo()
,08-25 15:25:20.613  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-25 15:25:20.613  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-25 15:25:20.613  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:25:20.613  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 15:25:20.613  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:20.613  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:20.613  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:20.613  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:20.623  1019  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-25 15:25:20.623  1019  1368 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 15:25:20.623  1019  1368 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
,08-25 15:25:20.623  1019  1368 W ActivityManager: userId = 0, bbcId = -10000,
08-25 15:25:20.623  1019  1368 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 15:25:20.623  1019  1368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 15:25:20.633  1630  1630 I Hs20UtilService: Starting #21
,08-25 15:25:20.633  1019  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 15:25:20.633  1630  1651 I Hs20UtilService: Message received 5007
,08-25 15:25:20.633  4780  4780 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 15:25:20.633  4780  4780 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 15:25:20.633  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 15:25:20.633  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 15:25:20.633  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 15:25:20.633  4780  4780 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 15:25:20.633  4780  4873 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 15:25:20.643   278  1008 D CommandListener: Setting iface cfg
,08-25 15:25:20.653  1019  1130 E WifiStateMachine: Start Dhcp Watchdog 3
,08-25 15:25:20.653  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 15:25:20.653  1019  1130 D SecContentProvider2: mCursor = null
,08-25 15:25:20.663  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-25 15:25:20.663  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 15:25:20.663  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-25 15:25:20.663  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:20.663  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:20.663  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:20.663  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:20.663  1019  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 15:25:20.663  1019  1130 D SecContentProvider2: mCursor = null
,08-25 15:25:20.673  1019  1130 E WifiNative-wlan0: do suspend false
,08-25 15:25:20.673  1019  1129 D WifiP2pService: InactiveState{ what=143375 }
,08-25 15:25:20.673  1019  1129 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-25 15:25:20.883  7798  7798 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-25 15:25:20.893  7798  7798 I dhcpcd  : version 5.5.6 starting
,08-25 15:25:20.893  7798  7798 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-25 15:25:20.943  7798  7798 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-25 15:25:20.943  7798  7798 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-25 15:25:20.943  7798  7798 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-25 15:25:20.943  7798  7798 I dhcpcd  : bssid match
08-25 15:25:20.943  7798  7798 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-25 15:25:21.033  7798  7798 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-25 15:25:21.033  6896  7047 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1381)
,08-25 15:25:21.033  6896  7047 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1381)
,08-25 15:25:21.033  6896  7047 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1386)
,08-25 15:25:21.033  6896  7047 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-25 15:25:21.033  6896  7047 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1387)
,08-25 15:25:21.033  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 15:25:21.033  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e8d805d added. We now have 2 listener(s)
,08-25 15:25:21.043  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
08-25 15:25:21.043  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:25:21.043  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:25:21.043  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:25:21.043  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@144a2dd2 added. We now have 9 listener(s)
08-25 15:25:21.043  6896  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:25:21.043  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 15:25:21.043  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 15:25:21.053  6896  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-25 15:25:21.053  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:21.053  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:21.053  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-25 15:25:21.053  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:21.053  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:21.053  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:21.053  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:25:21.053  6896  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 15:25:21.053  6896  7047 D io.jxcore.node.ConnectivityMonitor: start: OK,
,08-25 15:25:21.053  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-25 15:25:21.053  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-25 15:25:21.063  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:25:21.063  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28bd35a0 added. We now have 3 listener(s)
,08-25 15:25:21.063  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
08-25 15:25:21.063  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 15:25:21.063  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:25:21.063  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:25:21.063  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18a6c559 added. We now have 10 listener(s)
,08-25 15:25:21.063  6896  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:25:21.063  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 15:25:21.063  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 15:25:21.063  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:21.063  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:21.063  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:21.063  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 15:25:21.063  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:25:21.063  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e8d805d removed from the list
08-25 15:25:21.063  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 15:25:21.063  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@144a2dd2 removed from the list
08-25 15:25:21.063  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:21.063  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:21.063  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 15:25:21.063  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:21.063  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:21.063  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:21.063  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 15:25:21.063  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@144a2dd2 not in the list
08-25 15:25:21.063  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-25 15:25:21.063  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:21.063  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:21.063  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:21.063  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:21.063  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18a6c559 removed from the list
,08-25 15:25:21.063  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:21.063  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:21.063  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:21.063  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:25:21.063  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28bd35a0 removed from the list
,08-25 15:25:21.073  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:25:21.073  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af9551e added. We now have 2 listener(s)
,08-25 15:25:21.073  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
08-25 15:25:21.073  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 15:25:21.073  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 15:25:21.073  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:25:21.073  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@174c91ff added. We now have 9 listener(s)
08-25 15:25:21.073  6896  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:25:21.073  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,08-25 15:25:21.083  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-25 15:25:21.083  6896  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:25:21.083  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:21.083  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:21.083  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:21.083  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:21.083  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:21.083  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:21.083  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:25:21.083  6896  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:25:21.083  6896  7047 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 15:25:21.083  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:25:21.083  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13755e15 added. We now have 3 listener(s)
,08-25 15:25:21.093  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:21.093  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:21.093  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-25 15:25:21.093  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 15:25:21.093  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 15:25:21.093  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 15:25:21.093  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24e1a52a added. We now have 10 listener(s)
08-25 15:25:21.093  6896  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:25:21.093  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 15:25:21.093  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 15:25:21.093  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 15:25:21.093  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-25 15:25:21.093  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 15:25:21.103  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 15:25:21.113  7798  7798 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,08-25 15:25:21.113  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 15:25:21.113  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 15:25:21.123  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 15:25:21.123  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 15:25:21.123  6896  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 15:25:21.123  3215  7240 D BtGatt.GattService: registerClient() - UUID=dd550179-99b7-48b2-9455-2b69e0a6113f
,08-25 15:25:21.163  3215  3298 D BtGatt.GattService: onClientRegistered() - UUID=dd550179-99b7-48b2-9455-2b69e0a6113f, clientIf=6
,08-25 15:25:21.163  6896  6904 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-25 15:25:21.163  3215  3227 D BtGatt.GattService: start scan with filters
,08-25 15:25:21.173  3215  3355 D BtGatt.ScanManager: handling starting scan
08-25 15:25:21.173  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 15:25:21.173  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 15:25:21.173  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 15:25:21.173  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 15:25:21.173  3215  3298 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-25 15:25:21.173  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 15:25:21.173  3215  3355 D BtGatt.ScanManager: allow scan with filters
08-25 15:25:21.173  3215  3355 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-25 15:25:21.173  3215  3355 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
08-25 15:25:21.173  3215  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-25 15:25:21.173  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 15:25:21.173  3215  3355 D BtGatt.ScanManager: Starting BLE batch scan
08-25 15:25:21.173  3215  3355 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-25 15:25:21.173  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 15:25:21.173  6896  6896 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 15:25:21.183  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 15:25:21.183  3215  3298 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-25 15:25:21.183  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:25:21.183  3215  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-25 15:25:21.183  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 15:25:21.193  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 15:25:21.193  6896  7047 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation,
08-25 15:25:21.193  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:21.193  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 15:25:21.193  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:21.193  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 15:25:21.193  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 15:25:21.193  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 15:25:21.193  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 15:25:21.193  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 15:25:21.193  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 15:25:21.193  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 15:25:21.203  3215  3230 D BtGatt.GattService: stopScan() - queue size =1,
,08-25 15:25:21.203  3215  3227 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 15:25:21.203  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-25 15:25:21.203  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 15:25:21.203  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 15:25:21.203  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 15:25:21.203  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 15:25:21.203  3215  3355 D BtGatt.ScanManager: filter size is 1
08-25 15:25:21.203  3215  3355 D BtGatt.ScanManager: delete FilterIndex - 6
08-25 15:25:21.213  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,08-25 15:25:21.213  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 15:25:21.213  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 15:25:21.213  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 15:25:21.213  3215  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-25 15:25:21.213  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 15:25:21.213  3215  3355 D BtGatt.ScanManager: stopping BLe Batch
,08-25 15:25:21.213  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,08-25 15:25:21.213  3215  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-25 15:25:21.213  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 15:25:21.213  3215  3355 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 15:25:21.213  6896  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 15:25:21.213  6896  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 15:25:21.213  6896  6896 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 15:25:21.213  3215  3298 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-25 15:25:21.223  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:25:21.223  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:21.223  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:21.223  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:21.223  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:21.223  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:21.223  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:25:21.223  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:25:21.223  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af9551e removed from the list
08-25 15:25:21.223  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:21.223  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@174c91ff removed from the list
08-25 15:25:21.223  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:21.223  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:25:21.223  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:21.223  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:25:21.233  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 15:25:21.233  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:21.233  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:21.233  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@174c91ff not in the list
08-25 15:25:21.233  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:21.233  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-25 15:25:21.233  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:21.233  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:21.233  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:21.233  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24e1a52a removed from the list
08-25 15:25:21.233  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-25 15:25:21.233  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:21.233  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:21.233  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:25:21.233  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13755e15 removed from the list
,08-25 15:25:21.233  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:25:21.233  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@254ce9f6 added. We now have 2 listener(s)
,08-25 15:25:21.243  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
08-25 15:25:21.243  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:25:21.243  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 15:25:21.243  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:25:21.243  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b4cc1f7 added. We now have 9 listener(s)
08-25 15:25:21.243  6896  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-25 15:25:21.243  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 15:25:21.243  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-25 15:25:21.253  6896  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-25 15:25:21.253  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:21.253  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:21.253  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:21.253  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:21.253  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:21.253  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:21.253  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:25:21.253  6896  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-25 15:25:21.253  6896  7047 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 15:25:21.253  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:25:21.253  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f543acd added. We now have 3 listener(s)
,08-25 15:25:21.263  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-25 15:25:21.263  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:25:21.263  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:25:21.263  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 15:25:21.263  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2855af82 added. We now have 10 listener(s)
,08-25 15:25:21.263  6896  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:25:21.263  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 15:25:21.263  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 15:25:21.263  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:25:21.263  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 15:25:21.263  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-25 15:25:21.263  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:25:21.263  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 15:25:21.263  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:21.263  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 15:25:21.283  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
08-25 15:25:21.283  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 15:25:21.283  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 15:25:21.283  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 15:25:21.283  6896  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 15:25:21.293  3215  3381 D BtGatt.GattService: registerClient() - UUID=57af11b9-d25c-4d4c-8d13-ae7795cdb2d9,
,08-25 15:25:21.333  3215  3298 D BtGatt.GattService: onClientRegistered() - UUID=57af11b9-d25c-4d4c-8d13-ae7795cdb2d9, clientIf=6
08-25 15:25:21.333  6896  6904 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-25 15:25:21.333  3215  3227 D BtGatt.GattService: start scan with filters
08-25 15:25:21.333  3215  3355 D BtGatt.ScanManager: handling starting scan
,08-25 15:25:21.333  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 15:25:21.333  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 15:25:21.333  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 15:25:21.333  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-25 15:25:21.333  3215  3298 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-25 15:25:21.333  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 15:25:21.343  3215  3355 D BtGatt.ScanManager: allow scan with filters
08-25 15:25:21.343  3215  3355 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-25 15:25:21.343  3215  3355 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,08-25 15:25:21.343  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-25 15:25:21.343  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 15:25:21.343  6896  6896 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 15:25:21.343  3215  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-25 15:25:21.343  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 15:25:21.343  3215  3355 D BtGatt.ScanManager: Starting BLE batch scan
08-25 15:25:21.343  3215  3355 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 15:25:21.343  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-25 15:25:21.343  3215  3298 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-25 15:25:21.343  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:25:21.343  3215  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-25 15:25:21.343  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:25:21.343  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:25:21.343  6896  7047 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-25 15:25:21.343  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 15:25:21.343  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:21.343  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:21.343  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:21.343  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:21.343  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 15:25:21.343  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:25:21.343  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@254ce9f6 removed from the list
08-25 15:25:21.343  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:21.343  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b4cc1f7 removed from the list
08-25 15:25:21.343  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:21.343  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:25:21.353  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:21.353  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 15:25:21.353  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:21.353  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 15:25:21.353  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 15:25:21.353  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:21.353  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:21.353  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b4cc1f7 not in the list
08-25 15:25:21.353  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 15:25:21.353  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 15:25:21.353  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 15:25:21.353  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 15:25:21.353  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 15:25:21.353  3215  3352 D BtGatt.GattService: stopScan() - queue size =1
08-25 15:25:21.353  3215  3355 D BtGatt.ScanManager: filter size is 1
08-25 15:25:21.353  3215  3355 D BtGatt.ScanManager: delete FilterIndex - 7
08-25 15:25:21.353  3215  3381 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 15:25:21.353  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 15:25:21.353  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 15:25:21.353  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 15:25:21.353  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 15:25:21.353  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 15:25:21.353  3215  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-25 15:25:21.353  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 15:25:21.353  3215  3355 D BtGatt.ScanManager: stopping BLe Batch
,08-25 15:25:21.353  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 15:25:21.363  3215  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-25 15:25:21.363  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:25:21.363  3215  3355 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 15:25:21.363  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 15:25:21.363  3215  3298 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-25 15:25:21.363  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 15:25:21.363  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 15:25:21.363  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 15:25:21.363  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:25:21.363  6896  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 15:25:21.363  6896  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 15:25:21.363  6896  6896 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 15:25:21.363  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:21.363  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:21.363  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 15:25:21.363  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2855af82 removed from the list
08-25 15:25:21.363  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 15:25:21.363  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:21.373  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:21.373  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 15:25:21.373  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f543acd removed from the list
,08-25 15:25:21.373  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 15:25:21.373  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f3341ce added. We now have 2 listener(s)
,08-25 15:25:21.373  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-25 15:25:21.373  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 15:25:21.373  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:25:21.373  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 15:25:21.373  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a33f8ef added. We now have 9 listener(s)
08-25 15:25:21.373  6896  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:25:21.373  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 15:25:21.383  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 15:25:21.383  6896  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-25 15:25:21.383  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:21.383  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:21.383  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:21.383  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:21.383  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:21.383  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:21.383  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:25:21.383  6896  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-25 15:25:21.383  6896  7047 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 15:25:21.383  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:25:21.383  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c2af685 added. We now have 3 listener(s)
,08-25 15:25:21.383  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:21.383  6896  6896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 15:25:21.383  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-25 15:25:21.383  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 15:25:21.383  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:25:21.383  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:25:21.383  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@545acda added. We now have 10 listener(s)
,08-25 15:25:21.383  6896  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 15:25:21.383  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:25:21.383  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 15:25:21.393  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-25 15:25:21.393  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 15:25:21.393  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 15:25:21.393  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 15:25:21.393  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 15:25:21.393  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 15:25:21.403  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 15:25:21.403  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 15:25:21.403  6896  7047 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 15:25:21.403  3215  3230 D BtGatt.GattService: registerClient() - UUID=aa2e8048-3584-44d4-9d2f-a2b480b41baf
,08-25 15:25:21.443  3215  3298 D BtGatt.GattService: onClientRegistered() - UUID=aa2e8048-3584-44d4-9d2f-a2b480b41baf, clientIf=6
,08-25 15:25:21.443  6896  6904 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-25 15:25:21.443  3215  7240 D BtGatt.GattService: start scan with filters
,08-25 15:25:21.443  3215  3355 D BtGatt.ScanManager: handling starting scan
,08-25 15:25:21.453  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 15:25:21.453  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 15:25:21.453  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 15:25:21.453  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 15:25:21.453  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 15:25:21.453  6896  6896 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 15:25:21.453  3215  3298 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-25 15:25:21.453  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 15:25:21.453  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 15:25:21.453  3215  3355 D BtGatt.ScanManager: allow scan with filters
,08-25 15:25:21.453  3215  3355 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-25 15:25:21.453  3215  3355 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,08-25 15:25:21.463  3215  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-25 15:25:21.463  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 15:25:21.463  3215  3355 D BtGatt.ScanManager: Starting BLE batch scan
,08-25 15:25:21.463  3215  3355 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 15:25:21.463  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 15:25:21.463  3215  3298 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-25 15:25:21.463  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:25:21.463  3215  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-25 15:25:21.463  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 15:25:21.473  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 15:25:21.473  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:21.473  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 15:25:21.473  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 15:25:21.473  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:21.473  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 15:25:21.473  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:25:21.473  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f3341ce removed from the list
,08-25 15:25:21.473  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:21.473  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a33f8ef removed from the list
08-25 15:25:21.473  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:21.473  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 15:25:21.473  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-25 15:25:21.473  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 15:25:21.473  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:21.473  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 15:25:21.473  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 15:25:21.473  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:21.473  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:21.473  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a33f8ef not in the list
08-25 15:25:21.473  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 15:25:21.473  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 15:25:21.473  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 15:25:21.473  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 15:25:21.473  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 15:25:21.483  3215  3352 D BtGatt.GattService: stopScan() - queue size =1
,08-25 15:25:21.483  3215  3381 D BtGatt.GattService: unregisterClient() - clientIf=6,
08-25 15:25:21.483  3215  3355 D BtGatt.ScanManager: filter size is 1
08-25 15:25:21.483  3215  3355 D BtGatt.ScanManager: delete FilterIndex - 8
,08-25 15:25:21.483  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 15:25:21.483  3215  3298 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-25 15:25:21.483  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 15:25:21.483  3215  3355 D BtGatt.ScanManager: stopping BLe Batch
,08-25 15:25:21.483  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 15:25:21.483  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 15:25:21.483  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 15:25:21.483  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 15:25:21.483  3215  3298 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-25 15:25:21.483  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 15:25:21.483  3215  3355 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 15:25:21.483  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 15:25:21.483  3215  3298 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-25 15:25:21.483  3215  3298 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 15:25:21.493  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 15:25:21.493  6896  7047 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 15:25:21.493  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 15:25:21.493  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:25:21.493  1019  1130 E WifiNative-wlan0: do suspend true
,08-25 15:25:21.493  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:21.493  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:21.493  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:21.493  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@545acda removed from the list
08-25 15:25:21.493  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:21.493  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:21.493  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:21.493  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:25:21.493  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c2af685 removed from the list
,08-25 15:25:21.493  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:25:21.493  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e1bca6 added. We now have 2 listener(s)
,08-25 15:25:21.493  6896  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 15:25:21.493  6896  6896 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 15:25:21.493  6896  6896 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 15:25:21.493  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-25 15:25:21.493  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:25:21.493  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:25:21.503  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 15:25:21.503  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3afc16e7 added. We now have 9 listener(s)
08-25 15:25:21.503  6896  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:25:21.503  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 15:25:21.503  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 15:25:21.503  6896  7047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 15:25:21.503  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 15:25:21.503  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 15:25:21.503  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 15:25:21.503  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 15:25:21.503  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 15:25:21.503  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 15:25:21.503  6896  7047 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 15:25:21.503  6896  7047 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 15:25:21.513  6896  7047 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 15:25:21.513  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 15:25:21.513  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3736713d added. We now have 3 listener(s)
,08-25 15:25:21.513  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-25 15:25:21.513  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 15:25:21.513  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 15:25:21.513  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 15:25:21.513  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2adcfd32 added. We now have 10 listener(s)
08-25 15:25:21.513  6896  7047 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 15:25:21.513  6896  7047 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 15:25:21.513  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 15:25:21.513  6896  7047 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 15:25:21.513  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:21.513  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:21.513  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 15:25:21.513  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:25:21.513  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39e1bca6 removed from the list
,08-25 15:25:21.513  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:21.513  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3afc16e7 removed from the list
08-25 15:25:21.513  6896  7047 D io.jxcore.node.ConnectivityMonitor: stop
08-25 15:25:21.513  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 15:25:21.523  1019  1129 D WifiP2pService: InactiveState{ what=143375 }
,08-25 15:25:21.523  1019  1129 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-25 15:25:21.523  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:21.523  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:21.523  1019  1130 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK,
08-25 15:25:21.523  1019  1130 E WifiStateMachine: VerifyingLinkState enter
,08-25 15:25:21.523  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 15:25:21.523  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:21.523  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-25 15:25:21.523  6896  7047 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3afc16e7 not in the list
08-25 15:25:21.523  1019  1132 D ConnectivityService: Adding iface wlan0 to network 504
,08-25 15:25:21.523  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:21.523  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:21.523  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 15:25:21.533  1019  1045 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{1c65f655 u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{2edae03f 6896 com.test.thalitest/10170/u0 remote:432f45e}: filter unregistered
08-25 15:25:21.523  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 15:25:21.523  6896  7047 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 15:25:21.523  6896  7047 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2adcfd32 removed from the list,
08-25 15:25:21.523  6896  7047 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 15:25:21.523  6896  7047 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 15:25:21.523  6896  7047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 15:25:21.523  6896  7047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 15:25:21.523  6896  7047 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3736713d removed from the list
,08-25 15:25:21.523  1019  1132 E ConnectivityService: updateNetworkInfo()
08-25 15:25:21.523  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 15:25:21.523  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 15:25:21.523  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-25 15:25:21.523  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 15:25:21.523  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-25 15:25:21.523  1019  1132 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-25 15:25:21.523  6896  7047 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 15:25:21.533  1019  1045 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{335f86a u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{2edae03f 6896 com.test.thalitest/10170/u0 remote:432f45e}: filter unregistered
,08-25 15:25:21.533  6896  7830 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1394, name: My test thread name)
,08-25 15:25:21.533  6896  7830 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1394, thread name: My test thread name)
,08-25 15:25:21.543  6896  7830 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1394, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 15:25:21.543  1019  1132 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-25 15:25:21.543  1019  1132 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-25 15:25:21.543  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-25 15:25:21.543  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:25:21.543  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 15:25:21.553  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:21.553  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:21.553  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:21.553  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:21.553  1019  1147 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-25 15:25:21.553  1019  1132 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
08-25 15:25:21.553  1019  1147 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-25 15:25:21.553  1019  1147 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-25 15:25:21.553  6896  7832 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1396, name: My test thread name)
08-25 15:25:21.553  6896  7832 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1396, thread name: My test thread name)
08-25 15:25:21.553  6896  7832 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1396, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 15:25:21.553  1019  1147 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-25 15:25:21.553  1019  1132 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 15:25:21.553  1019  1147 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-25 15:25:21.553  1019  1132 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
,08-25 15:25:21.553  1019  1132 D ConnectivityService: LTETest block dns file not exists
,08-25 15:25:21.553  6896  7047 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-25 15:25:21.553  6896  7047 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-25 15:25:21.553  6896  7047 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-25 15:25:21.553  6896  7047 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-25 15:25:21.553  6896  7047 D com.test.thalitest.ThaliTestRunner: Total duration: 23347 ms
,08-25 15:25:21.553  6896  7047 I jxcore-log: Total number of executed tests:  80,
08-25 15:25:21.553  6896  7047 I jxcore-log: 
,08-25 15:25:21.553  6896  7047 I jxcore-log: Number of passed tests:  80
08-25 15:25:21.553  6896  7047 I jxcore-log: 
08-25 15:25:21.563  1019  1132 V NetworkStats: updateIfacesLocked()
08-25 15:25:21.553  6896  7047 I jxcore-log: Number of failed tests:  0
08-25 15:25:21.553  6896  7047 I jxcore-log: 
08-25 15:25:21.563  1019  1132 V NetworkStats: performPollLocked(flags=0x1)
08-25 15:25:21.563  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:21.563  1019  1485 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 15:25:21.563  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 15:25:21.563  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-25 15:25:21.563  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 15:25:21.563  6896  7047 I jxcore-log: Number of ignored tests:  0
08-25 15:25:21.563  6896  7047 I jxcore-log: 
08-25 15:25:21.563  6896  7047 I jxcore-log: Total duration:  23347
08-25 15:25:21.563  6896  7047 I jxcore-log: 
08-25 15:25:21.563  6896  7047 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 15:25:21.563  6896  7047 I jxcore-log: 
,08-25 15:25:21.563  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:21.563  1019  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:21.563  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-25 15:25:21.563  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 15:25:21.563  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:25:21.563  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 15:25:21.563  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:21.563  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:21.563  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:21.563  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:21.563  1019  1130 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-25 15:25:21.573  1630  1630 I Hs20UtilService: Starting #22
08-25 15:25:21.573  6896  6906 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@a16839c, channel: -1, state: CLOSED
08-25 15:25:21.573  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:21.573  1019  1132 V NetworkStats: performPollLocked() took 13ms
08-25 15:25:21.573  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:21.573  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:21.573  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:21.573  6896  7047 I jxcore-log: 
08-25 15:25:21.573  1019  1132 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-25 15:25:21.573  4780  4780 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-25 15:25:21.573  4780  4780 I NearbySettings: MountReceiver.onReceive - Keep current state
08-25 15:25:21.573  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:21.573  6896  7047 I jxcore-log: 
08-25 15:25:21.583  1630  1651 I Hs20UtilService: Message received 5007
08-25 15:25:21.583  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:21.583  6896  7047 I jxcore-log: 
08-25 15:25:21.583  1019  1132 E ConnectivityService: updateNetworkInfo()
08-25 15:25:21.583  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:21.583  6896  7047 I jxcore-log: 
08-25 15:25:21.583  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:21.583  6896  7047 I jxcore-log: 
,08-25 15:25:21.583  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:21.583  6896  7047 I jxcore-log: 
08-25 15:25:21.583  1019  1132 E ConnectivityService: updateNetworkInfo()
,08-25 15:25:21.593  1019  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 15:25:21.593  6896  6896 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-25 15:25:21.593  1019  1132 V NetworkStats: updateIfacesLocked()
08-25 15:25:21.593  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:21.593  1019  1132 V NetworkStats: performPollLocked(flags=0x1)
08-25 15:25:21.593  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-25 15:25:21.593  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 15:25:21.593  1019  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 15:25:21.593  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 15:25:21.593  6896  7047 I jxcore-log: 
08-25 15:25:21.593  1019  1132 V NetworkStats: performPollLocked() took 3ms
08-25 15:25:21.593  1019  1132 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:21.593  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 15:25:21.593  6896  7047 I jxcore-log: 
,08-25 15:25:21.593  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 15:25:21.593  6896  7047 I jxcore-log: 
,08-25 15:25:21.593  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 15:25:21.593  6896  7047 I jxcore-log: 
,08-25 15:25:21.593  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 15:25:21.593  6896  7047 I jxcore-log: 
,08-25 15:25:21.593  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 15:25:21.593  6896  7047 I jxcore-log: 
,08-25 15:25:21.593  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 15:25:21.593  6896  7047 I jxcore-log: 
,08-25 15:25:21.603  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 15:25:21.603  6896  7047 I jxcore-log: 
,08-25 15:25:21.603  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-25 15:25:21.603  6896  7047 I jxcore-log: 
08-25 15:25:21.603  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 15:25:21.603  6896  7047 I jxcore-log: 
,08-25 15:25:21.603  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 15:25:21.603  6896  7047 I jxcore-log: 
,08-25 15:25:21.603  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-25 15:25:21.603  6896  7047 I jxcore-log: 
,08-25 15:25:21.603  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 15:25:21.603  6896  7047 I jxcore-log: 
08-25 15:25:21.603  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-25 15:25:21.603  1019  1019 I WifiTrafficPoller: mBoosterFLAG : 0
08-25 15:25:21.603  1019  1019 I WifiTrafficPoller: current booster mode : FullMode
08-25 15:25:21.603  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 15:25:21.603  6896  7047 I jxcore-log: 
08-25 15:25:21.603  1019  1130 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 15:25:21.603  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 15:25:21.603  6896  7047 I jxcore-log: 
,08-25 15:25:21.603  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 15:25:21.603  6896  7047 I jxcore-log: 
08-25 15:25:21.603  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 15:25:21.603  6896  7047 I jxcore-log: 
08-25 15:25:21.603  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 15:25:21.603  6896  7047 I jxcore-log: 
,08-25 15:25:21.603  1019  1130 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 15:25:21.603  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-25 15:25:21.603  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 15:25:21.603  6896  7047 I jxcore-log: 
,08-25 15:25:21.603  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:25:21.603  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-25 15:25:21.613  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 15:25:21.613  6896  7047 I jxcore-log: 
08-25 15:25:21.613  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:21.613  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:21.613  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:21.613  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:21.613  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 15:25:21.613  6896  7047 I jxcore-log: 
,08-25 15:25:21.613  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:25:21.613  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-25 15:25:21.613  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:21.613  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:21.613  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:21.613  1019  1132 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-25 15:25:21.613  1019  7796 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:25:21.613  1019  1132 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-25 15:25:21.613  1019  7796 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-25 15:25:21.613  1019  7796 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 15:25:21.613  1019  7796 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-25 15:25:21.613  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:21.613  1019  1491 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 15:25:21.623  1019  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 15:25:21.623  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:21.623  1019  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:21.623  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 15:25:21.623  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:25:21.623  1019  7796 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-25 15:25:21.623  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:21.623  1630  1630 I Hs20UtilService: Starting #23
,08-25 15:25:21.623  1019  1132 D ConnectivityService:    accepting network in place of null
08-25 15:25:21.623  1019  1130 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-25 15:25:21.623  1630  1651 I Hs20UtilService: Message received 5007
08-25 15:25:21.623  1019  1129 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-25 15:25:21.623  1459  1459 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-25 15:25:21.623  1459  1459 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-25 15:25:21.623  4780  4780 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 15:25:21.633  1019  1132 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 15:25:21.633  1019  1132 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-25 15:25:21.633   278  1003 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 15:25:21.633   278  1003 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-25 15:25:21.633  1019  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-25 15:25:21.633  4780  4780 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 15:25:21.633  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-25 15:25:21.633  1019  1132 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-25 15:25:21.633  1019  1019 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-25 15:25:21.633  1019  1127 V NetworkStats: updateIfacesLocked()
08-25 15:25:21.633  1019  1133 D Tethering: MasterInitialState.processMessage what=3
08-25 15:25:21.633  1019  1127 V NetworkStats: performPollLocked(flags=0x1)
08-25 15:25:21.633  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:25:21.633  1019  1132 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-25 15:25:21.633  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 15:25:21.633  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 15:25:21.633  1019  1128 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-25 15:25:21.633  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 15:25:21.633  1182  1182 D StatusBar.NetworkController: EthernetConnected: false
08-25 15:25:21.633  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-25 15:25:21.633  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-25 15:25:21.633  1182  1182 D StatusBar.NetworkController: updateDataNetType()
08-25 15:25:21.633  1019  1049 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-25 15:25:21.633  4780  4780 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-25 15:25:21.633  4780  4780 I NearbySettings: MountReceiver.onReceive - Keep current state
08-25 15:25:21.633  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:21.633  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:21.633  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:21.643  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:21.643  1182  1708 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-25 15:25:21.643  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-25 15:25:21.643  1182  1182 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-25 15:25:21.643  1182  1182 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-25 15:25:21.643  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-25 15:25:21.643  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-25 15:25:21.643  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-25 15:25:21.643  1019  1127 V NetworkStats: performPollLocked() took 7ms
08-25 15:25:21.643  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:21.643  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:25:21.643  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-25 15:25:21.643  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:21.643  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:21.643  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:21.643  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:21.643  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:21.643  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:25:21.653  1019  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 15:25:21.653  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 15:25:21.653  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-25 15:25:21.653  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 15:25:21.653  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 15:25:21.653  1630  1630 I Hs20UtilService: Starting #24
08-25 15:25:21.653  1630  1651 I Hs20UtilService: Message received 5007
,08-25 15:25:21.663  4780  4780 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 15:25:21.663  4780  4780 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-25 15:25:21.673  1019  3774 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-25 15:25:21.673  1019  1308 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,08-25 15:25:21.673  1019  1308 D SecContentProvider2: mCursor = null
,08-25 15:25:21.673  1019  4326 D SecContentProvider2: uri = 15 selection = getToastGravity
08-25 15:25:21.673  1019  4326 D SecContentProvider2: mCursor = null
,08-25 15:25:21.673  1019  4324 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,08-25 15:25:21.673  1019  4324 D SecContentProvider2: mCursor = null
,08-25 15:25:21.673  1019  1368 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset,
08-25 15:25:21.673  1019  1368 D SecContentProvider2: mCursor = null
08-25 15:25:21.683  1019  4325 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-25 15:25:21.683  1019  4325 D SecContentProvider2: mCursor = null
08-25 15:25:21.683  1019  1031 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-25 15:25:21.683  1019  1031 D SecContentProvider2: mCursor = null
,08-25 15:25:21.713   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-25 15:25:21.723  6896  6896 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 15:25:21.723  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 15:25:21.723  6896  7047 I jxcore-log: 
,08-25 15:25:21.723  1019  7796 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-25 15:25:21.733  1019  3774 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019
,08-25 15:25:21.733  1182  1182 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-25 15:25:21.793  1019  7796 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 13:25:21 GMT], X-Android-Received-Millis=[1472131521810], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472131521772]}
,08-25 15:25:21.793  1019  7796 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 15:25:21.793  1019  7796 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-25 15:25:21.793  1019  1132 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-25 15:25:21.793  1019  1132 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-25 15:25:21.793  1019  1132 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-25 15:25:21.793  1019  1132 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-25 15:25:21.793  1019  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-25 15:25:21.803  1182  1708 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-25 15:25:21.803  1182  1182 D StatusBar.NetworkController: EthernetConnected: false
,08-25 15:25:21.803  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-25 15:25:21.803  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-25 15:25:21.803  1182  1182 D StatusBar.NetworkController: updateDataNetType()
,08-25 15:25:21.803  1182  1182 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-25 15:25:21.803  1182  1182 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-25 15:25:21.803  1182  1182 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-25 15:25:21.803  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-25 15:25:21.803  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-25 15:25:21.803  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-25 15:25:21.803  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 15:25:21.803  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-25 15:25:21.803  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:21.803  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:21.803  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 15:25:21.803  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 15:25:21.843  7836  7836 D AndroidRuntime: ,
08-25 15:25:21.843  7836  7836 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-25 15:25:21.843  7836  7836 D AndroidRuntime: CheckJNI is OFF,
08-25 15:25:21.843  7836  7836 D AndroidRuntime: readGMSProperty: start,
08-25 15:25:21.843  7836  7836 D AndroidRuntime: readGMSProperty: already setted!!
08-25 15:25:21.843  7836  7836 D AndroidRuntime: propertySet: couldn't set property (it is from app),
08-25 15:25:21.843  7836  7836 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-25 15:25:21.843  7836  7836 D AndroidRuntime: readGMSProperty: end,
08-25 15:25:21.843  7836  7836 D AndroidRuntime: addProductProperty: start
,08-25 15:25:21.863  6896  6896 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-25 15:25:21.863  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 15:25:21.863  6896  7047 I jxcore-log: ,
,08-25 15:25:21.983  7836  7836 E AffinityControl: AffinityControl: registerfunction enter
,08-25 15:25:21.993  6896  6896 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-25 15:25:21.993  6896  7047 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 15:25:21.993  6896  7047 I jxcore-log: ,
,08-25 15:25:22.013  7836  7836 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-25 15:25:22.033  1019  1487 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-25 15:25:22.033  1019  1487 D PackageManager: START PACKAGE DELETE: observer{135174199}
08-25 15:25:22.033  1019  1487 D PackageManager: pkg{<packageName>}
08-25 15:25:22.033  1019  1487 D PackageManager: user{0}
08-25 15:25:22.033  1019  1487 D PackageManager: caller{2000}
08-25 15:25:22.033  1019  1487 D PackageManager: flags{2}
08-25 15:25:22.033  1019  1487 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
08-25 15:25:22.033  1019  1487 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-25 15:25:22.033  1019  1487 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-25 15:25:22.033  1019  1487 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-25 15:25:22.033  1019  1059 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
08-25 15:25:22.033  1019  1059 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-25 15:25:22.033  1019  1059 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-25 15:25:22.033  1019  1059 D ApplicationPolicy: getApplicationUninstallationEnabled
08-25 15:25:22.033  1019  1059 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-25 15:25:22.033  1019  1059 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-25 15:25:22.043  1019  1045 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg,
,08-25 15:25:22.043  1019  1045 I ActivityManager: Killing 6896:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-25 15:25:22.043  1019  1045 I ActivityManager:   Force finishing activity ActivityRecord{f66aad0 u0 com.test.thalitest/.MainActivity t163},
,08-25 15:25:22.053  1019  1045 D InputDispatcher: Focus left window: 6896
,08-25 15:25:22.053   258   440 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-25 15:25:22.053   258   434 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-25 15:25:22.083  1019  1045 D InputDispatcher: Focused application released
,08-25 15:25:22.083  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-25 15:25:22.083  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-25 15:25:22.133  1019  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:25:22.263  1019  1045 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-25 15:25:22.263  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:22.263  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:22.263  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:22.263  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:22.263  1019  1044 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:25:22.283  1019  1045 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7847 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-25 15:25:22.283  1019  1059 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-25 15:25:22.293  7847  7847 E Zygote  : MountEmulatedStorage()
,08-25 15:25:22.293  7847  7847 I libpersona: KNOX_SDCARD checking this for 1000
08-25 15:25:22.293  7847  7847 E Zygote  : v2
08-25 15:25:22.293  7847  7847 I libpersona: KNOX_SDCARD not a persona
,08-25 15:25:22.293  7847  7847 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-25 15:25:22.303  1019  1059 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
08-25 15:25:22.303  7847  7847 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:25:22.303  7847  7847 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 15:25:22.313   304   304 I art     : Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 614us total 31.538ms
,08-25 15:25:22.333   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 17.103ms
,08-25 15:25:22.343  2832  2832 I art     : Explicit concurrent mark sweep GC freed 16591(990KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 799us total 43.720ms
08-25 15:25:22.343  1019  1485 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-25 15:25:22.343  1019  1485 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-25 15:25:22.343  1019  1485 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-25 15:25:22.343  1019  1485 D BatteryService: stay LED for charging
08-25 15:25:22.343  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-25 15:25:22.353   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 18.238ms
,08-25 15:25:22.363  7847  7847 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-25 15:25:22.363  7847  7847 D ActivityThread: Added TimaKeyStore provider
,08-25 15:25:22.373  1019  1102 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 15:25:22.383  1879  1879 E SamsungIME: mOCRHelper is null
,08-25 15:25:22.383  1751  1999 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-25 15:25:22.403  1019  1127 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-25 15:25:22.403  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:22.403  1019  1127 V NetworkStats: performPollLocked(flags=0x3)
,08-25 15:25:22.403  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 15:25:22.403  1019  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 15:25:22.403  1019  1127 V NetworkStats: performPollLocked() took 4ms
08-25 15:25:22.403  1019  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:25:22.403  1019  1044 D EnterpriseDeviceManagerService: Package has changed for user 0
,08-25 15:25:22.413  1019  1044 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-25 15:25:22.423  1019  1044 W TextServicesManagerService: no available spell checker services found
,08-25 15:25:22.453  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 15:25:22.453  1019  1019 D RCPManagerService: PackageReceiver onReceive()
,08-25 15:25:22.463  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-25 15:25:22.463  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-25 15:25:22.463  1019  1019 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-25 15:25:22.463  1019  1019 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-25 15:25:22.463  1445  1445 D PersonaManager: isKioskContainerExistOnDevice
,08-25 15:25:22.463  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 15:25:22.463  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-25 15:25:22.463  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-25 15:25:22.463  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-25 15:25:22.463  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-25 15:25:22.473  7847  7847 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-25 15:25:22.473  7847  7847 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-25 15:25:22.473  7847  7847 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-25 15:25:22.483  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 15:25:22.483  1019  1019 I OTPFW   : ProvisionData::getAllEntries Enter
,08-25 15:25:22.483  1019  1019 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-25 15:25:22.483  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 15:25:22.483  3215  3215 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-25 15:25:22.483  3215  7758 D HeadsetStateMachine: Disconnected process message: 10
,08-25 15:25:22.493  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 15:25:22.493  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 15:25:22.493  1445  1445 D RegisteredServicesCache: empty dynamic service
,08-25 15:25:22.493  1182  1182 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-25 15:25:22.493  1182  1182 D SViewCoverView: level :100 plugged : 2
,08-25 15:25:22.493  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-25 15:25:22.493  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-25 15:25:22.503  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-25 15:25:22.503  7847  7847 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-25 15:25:22.503  7847  7847 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-25 15:25:22.503  7847  7847 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-25 15:25:22.503  7847  7847 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-25 15:25:22.503  1019  1368 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-25 15:25:22.503  1019  1368 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
,08-25 15:25:22.523  1019  1368 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-25 15:25:22.523  1019  1368 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-25 15:25:22.523  1019  1368 I ActivityManager: Killing 7348:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-25 15:25:22.533  1445  1445 D RegisteredComponentCache: Collect Tech packages for Knox
,08-25 15:25:22.533  1445  1445 D PersonaManager: isKioskContainerExistOnDevice
,08-25 15:25:22.543  1019  1492 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin,
08-25 15:25:22.543  1019  1492 D SecContentProvider2: mCursor = null
,08-25 15:25:22.553  1019  1059 I art     : Explicit concurrent mark sweep GC freed 68416(4MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/34MB, paused 11.523ms total 232.643ms
,08-25 15:25:22.583  1019  1044 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-25 15:25:22.603  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 15:25:22.603  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 15:25:22.613  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 15:25:22.633  1019  1044 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-25 15:25:22.633  1019  1044 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 15:25:22.633  1019  1044 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-25 15:25:22.633  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-25 15:25:22.633  1019  1132 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-25 15:25:22.643  1019  1059 D PackageManager: delete codoeFile: 
,08-25 15:25:22.653  1019  1059 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-25 15:25:22.653  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 15:25:22.653  1019  1059 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-25 15:25:22.653  1019  1059 D PackageManager: result of delete: 1{135174199}
,08-25 15:25:22.653  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 15:25:22.663  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-25 15:25:22.663  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-25 15:25:22.663  7836  7836 D AndroidRuntime: Shutting down VM
,08-25 15:25:22.663  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 15:25:22.663  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 15:25:22.673  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-25 15:25:22.673  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-25 15:25:22.673  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-25 15:25:22.673  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 15:25:22.673  1019  1044 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-25 15:25:22.683  1019  1044 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-25 15:25:22.683  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-25 15:25:22.683  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-25 15:25:22.683  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-25 15:25:22.683  1019  1019 V EnterpriseBillingPolicy: uID is 10170
08-25 15:25:22.683  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
08-25 15:25:22.683  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-25 15:25:22.683  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-25 15:25:22.683  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-25 15:25:22.683  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-25 15:25:22.683  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-25 15:25:22.683  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-25 15:25:22.683  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-25 15:25:22.693  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-25 15:25:22.693  1019  1164 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
08-25 15:25:22.693  1019  1019 V EnterpriseBillingPolicy: uID is 10170
08-25 15:25:22.693  1019  3351 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-25 15:25:22.693  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
08-25 15:25:22.693  1019  1019 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
08-25 15:25:22.693  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-25 15:25:22.693  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-25 15:25:22.693  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-25 15:25:22.693  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-25 15:25:22.693  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-25 15:25:22.693  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-25 15:25:22.753  1019  1019 I MotionRecognitionService: Plugged
,08-25 15:25:22.753  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,08-25 15:25:22.763  1019  1019 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-25 15:25:22.763  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:22.763  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:22.763  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:22.763  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:22.783  7865  7865 E Zygote  : MountEmulatedStorage(),
08-25 15:25:22.783  7865  7865 E Zygote  : v2
08-25 15:25:22.783  7865  7865 I libpersona: KNOX_SDCARD checking this for 10001
08-25 15:25:22.783  7865  7865 I libpersona: KNOX_SDCARD not a persona
,08-25 15:25:22.783  7865  7865 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:25:22.783  7865  7865 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 15:25:22.783  1019  1019 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7865 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 15:25:22.783  7865  7865 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-25 15:25:22.813  7865  7865 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:25:22.813  7865  7865 D ActivityThread: Added TimaKeyStore provider
,08-25 15:25:22.863  1019  1490 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-25 15:25:22.863  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:22.863  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:22.863  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:22.863  1019  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:22.883  7836  7836 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,08-25 15:25:22.883  7882  7882 E Zygote  : MountEmulatedStorage(),
08-25 15:25:22.883  7882  7882 I libpersona: KNOX_SDCARD checking this for 1000
08-25 15:25:22.883  7882  7882 E Zygote  : v2
08-25 15:25:22.883  7882  7882 I libpersona: KNOX_SDCARD not a persona
08-25 15:25:22.883  7882  7882 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 15:25:22.893  1019  1490 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7882 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-25 15:25:22.893  1019  1490 I ActivityManager: Killing 7363:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-25 15:25:22.893  7882  7882 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 15:25:22.903  7882  7882 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-25 15:25:22.903  1019  1059 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-25 15:25:22.903  1019  1059 D PackageManager: userId{-1}
08-25 15:25:22.903  1019  1059 D PackageManager: andCode{true}
,08-25 15:25:22.913  1019  1059 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-25 15:25:22.913  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:22.913  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:22.913  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 15:25:22.913  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 15:25:22.933  1019  1059 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7894 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-25 15:25:22.933  7894  7894 E Zygote  : MountEmulatedStorage()
,08-25 15:25:22.933  7894  7894 E Zygote  : v2
08-25 15:25:22.933  7894  7894 I libpersona: KNOX_SDCARD checking this for 10003
08-25 15:25:22.933  7894  7894 I libpersona: KNOX_SDCARD not a persona,
,08-25 15:25:22.943  7894  7894 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 15:25:22.943  7894  7894 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 15:25:22.943  7894  7894 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 15:25:22.943  7882  7882 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 15:25:22.943  7882  7882 D ActivityThread: Added TimaKeyStore provider
,08-25 15:25:22.973  7894  7894 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 15:25:22.973  7894  7894 D ActivityThread: Added TimaKeyStore provider
,08-25 15:25:23.003  7882  7882 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-25 15:25:23.013  7882  7882 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,08-25 15:25:23.013  7882  7882 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:25:23.013  7882  7882 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 15:25:23.013  7882  7882 E SQLit,eOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:25:23.013  7882  7882 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-25 15:25:23.023  7882  7882 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
,08-25 15:25:23.023  7882  7882 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,08-25 15:25:23.023  7882  7882 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:25:23.023  7882  7882 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-25 15:25:23.023  7882  7882 E, SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:25:23.023  7882  7882 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-25 15:25:23.023  7882  7882 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
,08-25 15:25:23.023  1019  1081 I ActivityManager: Killing 7405:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-25 15:25:23.033  7882  7882 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,08-25 15:25:23.033  7882  7882 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 15:25:23.033  7882  7882 E SQLit,eOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-25 15:25:23.033  7882  7882 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
08-25 15:25:23.033  7882  7882 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,08-25 15:25:23.033  7882  7882 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:25:23.033  7882  7882 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-25 15:25:23.033  7882  7882 E, SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:25:23.033  7882  7882 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 15:25:23.043  7882  7882 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
,08-25 15:25:23.043  7882  7882 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,08-25 15:25:23.043  7882  7882 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:25:23.043  7882  7882 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 15:25:23.043  7882  7882 E SQLit,eOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:25:23.043  7882  7882 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-25 15:25:23.043  7882  7882 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
,08-25 15:25:23.053  7882  7882 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,08-25 15:25:23.053  7882  7882 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 15:25:23.053  7882  7882 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
08-25 15:25:23.053  78,82  7882 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1,399)
08-25 15:25:23.053  7882  7882 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:25:23.053  7882  7882 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 15:25:23.053  7882  7882 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
08-25 15:25:23.063  7882  7882 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:25:23.063  7882  7882 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 15:25:23.063  7882  7882 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 15:25:23.063  7882  7882 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode

```
